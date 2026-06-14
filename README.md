# RL Algorithm Comparison Notebooks

Runnable Colab companions to my Reinforcement Learning notes. Each is self-contained,
CPU-runnable on free Colab, and compares algorithms head-to-head with identical
nets/seeds so only the algorithm changes.

| Notebook | Compares | Env |
|---|---|---|
| 01 | REINFORCE → A2C → PPO (on-policy) | CartPole-v1 |
| 02 | DDPG → TD3 → SAC (off-policy continuous) | Pendulum-v1 |
| 03 | DQN vs PPO (value-based vs policy-based) | CartPole-v1 |
| 04 | GRPO group-relative advantage (toy, no LLM/gym) | contextual bandit |

Open any notebook in Colab via: `colab.research.google.com/github/<user>/<repo>/blob/main/<file>.ipynb`
