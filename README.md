# Robot-Dressing-Support-System

This project explores using reinforcement learning to automate robot assistance for activities of daily living like feeding and dressing. The goal is to develop policies that can control robotic manipulators to safely interact with humans and assist them with essential tasks.

## Approaches

- Simulated feeding task with Sawyer robot using Proximal Policy Optimization (PPO) and Soft Actor Critic (SAC) algorithms

- Simulated dressing task with Jaco robot using deep RL 

- Tested on physics-based Assistive Gym framework for human-robot interaction

## Environments

- Feeding: Bowl, spoon, spheres (food), table, human model

- Dressing: Hospital gown, wheelchair-mounted Jaco arm, human model 

## Implementation

- Vectorized environments and trained policies with TensorFlow and Gym 

- Evaluated on test episodes and compared performance metrics like rewards

- Rendered simulations to visualize learned assistive behaviors

## Results

- PPO and SAC successfully learned feeding policies with positive rewards  

- SAC (off-policy RL) more stable and data efficient than PPO

- Dressing simulation feasibility but very slow training convergence

## Discussion

- Significant challenges remain in training for complex human-robot tasks

- Better reward functions and simulation environments could improve learning

- Alternatively, modular pipeline with vision, control, imitation learning may be better suited

## Simulation

Packages Required - Assistive Gym, stablebaselines3, os, multiprocessing, numpngw, IPython.display
The code has been adapted for google Colab

Trained model can be found in "In" subfolder
Outputs can be found in the "Out" subfolder
The python notebook can be found in the "Code" subfolder

Please contact me at spauly@umd.edu, if facing any issues with the code.

## References

[1] Erickson et al., Assistive Gym  
[2] Park et al., Active Robot-Assisted Feeding
