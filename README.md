# Reinforcement Learning Cheatsheet

Some important concepts and algorithms in RL, all summarized in one place. PDF file is also available [here](https://alexandrethm.github.io/assets/pdf/rl-cheatsheet.pdf).

## Contents

1. **Bandits**: settings, exploration-exploitation, UCB, Thompson Sampling
1. **RL Framework**: Markov Decision Process, Markov Property, Bellman Equations
1. **Dynamic Programming**: Policy Evaluation, Policy Iteration, Value Iteration
1. **Value-Based**
   1. **Tabular environments**: Tabular Q-learning, SARSA, TD-learning, eligibility traces
   1. **Approximate Q-learning**: DQN, prioritized experience replay, Double DQN, Rainbow, DRQN
1. **Policy Gradients**
   1. **On-Policy**: REINFORCE, Actor-Critic (with compatible functions, GAE), A2C/A3C, TRPO, PPO
   1. **Off-Policy**: Policy gradient theorem, ACER, importance sampling
   1. **Continuous Action Spaces**: DDPG, Q-Prop

## References

- [Reinforcement Learning and advanced Deep Learning (RLD)](https://dac.lip6.fr/master/rladl/), Sorbonne University course, by Sylvain Lamprier
- [Spinning Up in Deep RL](https://spinningup.openai.com/en/latest/index.html), Open AI
- [UCL Course on RL](https://www.davidsilver.uk/teaching/), David Silver's Lecture

## Contributing
Contributions are welcome !
If you find any typo or error, feel free to raise an issue. 

If you would like to contribute to the code and make changes directly (e.g. adding algorithms, adding a new section, etc), you should start by cloning the repository.

```
git clone https://github.com/alexandrethm/rl-cheatsheet.git
```

### Work locally
Since all the sources and figures are included in the repo, you can make modifications and build the document locally. For this, you should have a full TeX distribution (if not, you can install it [here](https://www.latex-project.org/get/)), and you can then edit the LateX files with any IDE (e.g. Visual Studio Code).

### Work on Overleaf
If you'd rather avoid installing LateX, you can also use [Overleaf](https://www.overleaf.com/). For this, you need to compress the `rl-cheatsheet` folder and upload it to Overleaf (`New Project -> Upload Project`).
