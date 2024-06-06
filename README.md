# Synthetic 3D Environment Navigation using NeRF-Enhanced Reinforcement Learning

This is an academic research project website.

## Abstract
This project explores the simulation of humanoid agents navigating within photorealistic, synthetic 3D environments using a combination of Neural Radiance Fields (NeRF) and Reinforcement Learning (RL). We first capture a real-world scene using multiple high-resolution images and utilize NeRF to reconstruct the environment as a continuous function, enabling novel viewpoint generation. To facilitate agent interaction, we extract a mesh representation from the NeRF volume and integrate it into a physics simulator. A humanoid agent is then trained using Proximal Policy Optimization (PPO) with a reward structure encouraging forward movement and obstacle avoidance. However, this approach results in unnatural gait patterns. To address this, we incorporate imitation learning, to mimic natural human locomotion. Finally, we generate a unified video by overlaying the agent's movement within the physics engine onto a video rendered from the NeRF representation, showcasing the agent's navigation in a photorealistic and visually appealing manner. Our approach demonstrates the effectiveness of combining Neural Radiance Fields and Reinforcement Learning for creating interactive and realistic virtual environments for embodied AI agents.

## Acknowledgments
This page was built using the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template) page.



