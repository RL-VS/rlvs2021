# Regret bounds of model-based reinforcement learning

## Abstract

We discuss some recent results on model-based methods for online reinforcement learning (RL). The goal of online RL is to adaptively explore an unknown environment and learn to act with provable regret bounds. In particular, we focus on finite-horizon episodic RL where the unknown transition law belongs to a generic family of models. We propose a model-based "value-targeted regression" RL algorithm that is based on the optimism principle: In each episode, the set of models that are "consistent" with the data collected is constructed. The criterion of consistency is based on the total squared error that the model incurs on the task of predicting values as determined by the last value estimate along with the transitions. The next value function is then chosen by solving the optimistic planning problem with the constructed set of models. We derive a bound on the regret, for an arbitrary family of transition models, using the notion of the so-called Eluder dimension proposed by Russo & Van Roy (2014).

## Speakers  
[Mengdi Wang](mengdi-wang.md)  


## Class material
[Slides](class-material/regret_bounds_model_based_rl/RLVS-Wang-modelRL.pdf)

<iframe width="560" height="315" src="https://www.youtube.com/embed/t3zQhltzSmc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
