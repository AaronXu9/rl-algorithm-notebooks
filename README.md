# RL Algorithm Comparison Notebooks

Runnable Colab companions to my Reinforcement Learning notes. Each is self-contained,
CPU-runnable on free Colab, and compares algorithms head-to-head with identical
nets/seeds so only the thing under study changes.

| Notebook | Compares | Env |
|---|---|---|
| 01 | REINFORCE → A2C → PPO (on-policy) | CartPole-v1 |
| 02 | DDPG → TD3 → SAC (off-policy continuous) | Pendulum-v1 |
| 03 | DQN vs PPO (value-based vs policy-based) | CartPole-v1 |
| 04 | GRPO group-relative advantage (toy, no LLM/gym) | contextual bandit |
| 05 | GAE-λ bias/variance dial (λ sweep, PPO) | CartPole-v1 |
| 06 | MCTS + AlphaZero (self-play, PUCT) | Tic-Tac-Toe |
| 07 | Offline RL: BC vs CQL vs IQL (+naive) | CartPole-v1 (fixed dataset) |
| 08 | GFlowNet vs PPO vs MCMC (diversity / modes) | hypergrid |
| 09 | Exploration: ε-greedy vs count/RND/ICM (sparse reward) | four-rooms gridworld |
| 10 | Control as inference: soft vs hard Q-learning (Boltzmann policy, α sweep) | 5×5 gridworld (tabular) |

Open any notebook in Colab via: `colab.research.google.com/github/<user>/<repo>/blob/main/<file>.ipynb`
