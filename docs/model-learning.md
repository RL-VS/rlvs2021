# Leveraging model-learning for extreme generalization

## Abstract

Early RL was almost completely focused on learning a policy, sometimes via a value function, for a fixed reward function.   If the reward function is really fixed and if the agent really needs a quick reaction in all world states, that's the right strategy.  But those conditions don't always hold.  "Goal-conditioned" RL attempts to relax the first condition by allowing the reward function to be, in essence, part of the state.   That addresses the first problem but makes the second one much worse!  Now we are have to find a quick reaction to all state-goal pairs.  I will extol the virtues of learning models instead, with a focus on models that generalize extremely aggressively via factoring and quantification, and argue informally that such models can be learned with relatively less computation and data, and can be acquired incrementally without interference.  "Compilation" methods can still be used to make reactions fast for very common cases while retaining the ability to deliberate to solve unusual or difficult problems.   Depending on time and interest, I might also talk about the substantial partial observability that arises in long-term household robot problems, discuss some of our approaches to it, and encourage participants to help think of others. 

## Speaker

[Leslie Kaelbling](leslie-kaelbling.md)

## Class material
[Video](https://us02web.zoom.us/rec/play/_tOCAibc1Vl5f-Wwo5kS7tNU83GcjbCAZYpng3p3c0NraZ3FMHl-JShL6FefuaEkDtyTS-JLYgMp3ffz.tX07bsh2m4rDzO1I?startTime=1617975918000&_x_zm_rtaid=ymYVeH5TS-yFo43GnN8WBA.1618294478147.5eaefc2413c244edb1d881fa39ddc8c2&_x_zm_rhtaid=167)   
[Slides](class-material/model-learning/RLVS_21.pdf)   

Readings:

- [Blog post](https://lis.csail.mit.edu/the-engineering-science-of-embodied-intelligence/)
- [General survey on task and motion planning](https://arxiv.org/abs/2010.01083)
- [Learning models of skills to add to a planner](https://arxiv.org/abs/2006.06444)
- [Learning search control for TAMP problems](http://people.csail.mit.edu/beomjoon/publications/kim-corl19.pdf)
- [Hierarchical planning and execution in belief space](https://lis.csail.mit.edu/pubs/tlp/IJRRBelFinal.pdf)


