# Regret bounds of model-based reinforcement learning

## Abstract

We discuss some recent results on model-based methods for online reinforcement learning (RL). The goal of online RL is to adaptively explore an unknown environment and learn to act with provable regret bounds. In particular, we focus on finite-horizon episodic RL where the unknown transition law belongs to a generic family of models. We propose a model-based "value-targeted regression" RL algorithm that is based on the optimism principle: In each episode, the set of models that are "consistent" with the data collected is constructed. The criterion of consistency is based on the total squared error that the model incurs on the task of predicting values as determined by the last value estimate along with the transitions. The next value function is then chosen by solving the optimistic planning problem with the constructed set of models. We derive a bound on the regret, for an arbitrary family of transition models, using the notion of the so-called Eluder dimension proposed by Russo & Van Roy (2014).

## Speakers  
[Mengdi Wang](mengdi-wang.md)  


## Class material
[Slides](class-material/regret_bounds_model_based_rl/RLVS-Wang-modelRL.pdf)

[Video](https://us02web.zoom.us/rec/play/pYPCiE95k7RGRbLWXSgQ-kWUMGpdopDPntSwl7ehxu7YkkwywQUd6fdjiFMD6yZdJh2zDRm-WM9LG6Kv.QyOobcsChamMszxF?startTime=1617287469000&_x_zm_rtaid=bEWCP9bZQcqdgw2uo6bNZQ.1617351700726.be5ebfbe27a7cf6a6a07cc5f95a28017&_x_zm_rhtaid=842)


