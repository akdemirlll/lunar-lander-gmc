# Lunar Lander
---
## Usage
---
Run `land.py` to land on Moon!

Run `sga_train.py` to train a new agent.

## Agents
---

Gradient Monte Carlo, Semi Gradient and Episodic Semi Gradient agents can be found in `agent.py`.

### Gradient Monte Carlo (GMC)
A GMC [[1]] agent implementation for solving Lunar Landing task.

Gradient Monte Carlo algorithm works on the basis of SGD, sampling states and rewards from an environment using provided policy and updating a differentiable value-approximation function at the end of sequence.

Weight update is performed separately for each state-action tuple, rather than accumulating the gradient over all sequence.

## References
---

[1]: url "Sutton, R. S., Barto, A. G.  (20181019). Reinforcement Learning: An Introduction."

1. "Sutton, R. S., Barto, A. G.  (20181019). Reinforcement Learning: An Introduction."
