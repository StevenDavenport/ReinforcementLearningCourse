# Reinforcement Learning Public Course Roadmap

Goal: theory‑heavy, reality‑grounded, notebook‑first, with examples throughout.

## Knowledge Tree (Conceptual Map)

### A. Why RL matters now (entry layer)
- “Why RL now?” (decision‑making under uncertainty; robotics, healthcare, ops, LLM agents, recommender systems, finance)
- “What RL is *not*” (supervised, unsupervised, causal vs. control)
- The RL loop + vocabulary (state, action, reward, return, policy, value)

### B. Historical foundation (conceptual roots)
- Bellman optimality & dynamic programming
- Early control + MDP formalism
- Sutton & Barto era (TD methods)
- Monte‑Carlo methods vs. TD

### C. Core MDPs and variants (formal layer)
- MDPs: definition + properties
- POMDPs and partial observability
- Semi‑MDPs, options, temporally extended actions
- Average reward vs. discounted reward
- Constrained MDPs & safety

### D. Value‑based methods
- DP methods (policy evaluation, improvement, iteration)
- MC control
- TD(0), TD(λ), eligibility traces
- Q‑learning, SARSA, Expected SARSA
- Function approximation + instability
- DQN and stabilizers (experience replay, target networks)

### E. Policy‑based methods
- REINFORCE & score function estimators
- Baselines + variance reduction
- Actor‑Critic
- TRPO/PPO (why they matter)

### F. Model‑based methods (parallel track)
- Planning with known models
- Learning dynamics models
- Dyna‑style methods
- World models & imagination rollouts
- Model‑based vs. model‑free tradeoffs

### G. Exploration & credit assignment
- ε‑greedy, UCB, Thompson sampling
- Optimism & intrinsic motivation
- Exploration with uncertainty

### H. Deep RL milestones
- Atari DQN (why it mattered)
- A3C and parallelism
- AlphaGo/AlphaZero (search + RL)
- MuZero (model‑based + learned dynamics)
- Modern DRL pitfalls

### I. Practical engineering
- Reward shaping and reward hacking
- Off‑policy vs. on‑policy pipelines
- Replay buffers and data management
- Hyperparameters + reproducibility
- Benchmarking + evaluation metrics

### J. Real‑world applications (threaded across all sections)
- Robotics
- Healthcare decision support
- Operations & scheduling
- Finance / resource allocation
- LLM‑based agents and tool use

### K. Ethics, safety, and societal context
- Alignment & specification gaming
- Fairness & biases in reward design
- Safety constraints & robust RL

## Notebook Sequence (public‑friendly)

1. Why RL matters now (with 3 concrete case studies)
2. RL loop + vocabulary
3. Bellman equations + dynamic programming
4. MDPs + optimality
5. Monte‑Carlo methods
6. TD learning
7. Q‑learning and SARSA
8. Function approximation (linear)
9. DQN (Atari case study)
10. Policy gradients
11. Actor‑Critic
12. PPO (modern baseline)
13. POMDPs + partial observability
14. Model‑based RL (Dyna, planning)
15. World models + MuZero/AlphaZero
16. Exploration strategies
17. Safety + constraints
18. Real‑world project mini‑capstone (choose one domain)

## Standard Notebook Structure (layered for mixed audiences)

- 1‑page story: why this matters + real use case
- Core idea: minimal math + intuition
- Worked example: small MDP or toy environment
- Code path A (beginner): run provided code, change 1–2 knobs
- Code path B (intermediate): implement a key function (e.g., update rule)
- Optional deep dive: full derivation + proofs
- Takeaways + “what to read next”

## Exercise Tiers (repeatable)

- Tier 1: concept checks (5–10 min)
- Tier 2: light coding edits (15–30 min)
- Tier 3: extension/ablation study (30–60 min)
