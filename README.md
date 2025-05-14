# TurtlebotRL-CLM

# 🤖 TurtleBot3 com Aprendizado por Reforço para Saída de Labirintos

## 1. Contexto e Motivação

O TurtleBot3 é uma plataforma móvel de baixo custo, amplamente adotada em pesquisa e ensino de robótica móvel graças à sua modularidade e ao suporte ao ROS, que permitem ciclos rápidos de desenvolvimento. Neste projeto, exploramos técnicas de aprendizado por reforço (RL) para treinar um agente capaz de encontrar a saída de um labirinto sem dispor de um mapa prévio. A cada episódio de simulação, o robô recebe recompensas por aproximar-se da saída e penalidades por colisões, ajustando gradualmente sua política de navegação.

## 2. Ambiente de Simulação

Para o treinamento, utilizaremos o Gazebo integrado ao ROS para modelar labirintos de diferentes formatos e complexidades. O TurtleBot3 será equipado com dados de LIDAR e odometria emulado, tomando ações discretas (avançar, girar) e aprendendo, via DQN ou variantes, a maximizar a recompensa cumulativa até escapar do ambiente.

## 3. Cenário de Aplicação: Exploração de Ambientes Inexplorados

Robôs treinados para “resolver labirintos” podem ser empregados em missões de exploração onde o terreno é desconhecido ou inacessível a humanos, como:

- Cavernas e minas profundas, mapeando passagens estreitas com SLAM incremental.
- Superfícies planetárias, avançando autonomamente e retransmitindo dados científicos para bases remotas.

Neste contexto, a capacidade de sair de labirintos sem mapa prévio torna-se fundamental para garantir autonomia e segurança em cenários reais de exploração.


## 📚 Referências 
ALIIREZAEI. *turtlebot3_rl*. GitHub. Disponível em: https://github.com/AliiRezaei/turtlebot3_rl. Acesso em: 14 maio 2025.

REINIS. Using Turtlebot in Deep Reinforcement Learning. *Medium*, 2022. Disponível em: https://medium.com/@reinis_86651/using-turtlebot-in-deep-reinforcement-learning-4749946e1c15. Acesso em: 14 maio 2025.

BHCTSNTRK. *mantis_ddqn_navigation*. GitHub. Disponível em: https://github.com/bhctsntrk/mantis_ddqn_navigation. Acesso em: 14 maio 2025.

MIKEOGEZI. *turtlebot3_rl*. GitHub. Disponível em: https://github.com/mikeogezi/turtlebot3_rl. Acesso em: 14 maio 2025.
