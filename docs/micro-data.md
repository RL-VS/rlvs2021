# Micro-data policy search

## Abstract

Most policy search algorithms require thousands of training episodes to find an effective policy, which is often infeasible when experiments takes time or are expensive (for instance, with physical robot or with an aerodynamics simulator). This class focuses on the extreme other end of the spectrum: how can an algorithm adapt a policy with only a handful of trials (a dozen) and a few minutes? By analogy with the word "big-data", we refer to this challenge as "micro-data reinforcement learning". We will describe two main strategies: (1) leverage prior knowledge on the policy structure (e.g., dynamic movement primitives), on the policy parameters (e.g., demonstrations), or on the dynamics (e.g., simulators), and (2) create data-driven surrogate models of the expected reward (e.g., Bayesian optimization) or the dynamical model (e.g., model-based policy search), so that the policy optimizer queries the model instead of the real system. Most of the examples will be about robotic systems, but the principle apply to any other expensive setup.

## Speakers

[Jean-Baptiste Mouret](jean-baptiste-mouret.md)  
[Konstantinos Chatzilygeroudis](konstantinos-chatzilygeroudis.md)

## Class material

[Video recording](https://us02web.zoom.us/rec/share/JbQjBBmjyShfeFlTzRrmzNIaudpXFm7zxqzyW5ShweyIXObRoddeCbQHVQu3HHk.o4MmIY1XbxKTfasR?startTime=1617883414000)  

Slides:

1. [Introduction](class-material/micro-data/0_light-virtual_school_micro_data-intro-conclusion.pdf)
2. [Priors on policy structures](class-material/micro-data/1_light-virtual_school_micro_data-policies.pdf)
3. [Bayesian Optimization](class-material/micro-data/2_light-virtual_school_bo.pdf)
4. [Model based policy search](class-material/micro-data/3_light-virtual_school_micro_data-model_based.pdf)

Demos:

- On [Bayesian Optimization](class-material/micro-data/bo_tutorial.zip) ([colab link](https://colab.research.google.com/github/jbmouret/bo_tutorial/blob/main/bo.ipynb)) ([original repo](https://github.com/jbmouret/bo_tutorial)).
- On [policy search priors](class-material/micro-data/ps_tutorial.zip) ([original repo](https://github.com/costashatz/ps_tutorial)).

Readings:  
[A survey on policy search algorithms for learning robot controllers in a handful of trials](https://arxiv.org/abs/1807.02303)



