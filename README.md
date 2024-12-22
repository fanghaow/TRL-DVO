# TRL-DVO: A Transformer-Based RL Approach for Capturing Dynamic Target with a Magnetic Soft Microgripper in Cluttered Environments

This repository contains the TRL-DVO (Transformer-based Reinforcement Learning with Deterministic VO) framework, designed to train and deploy a mobile magnetic microgripper for navigation tasks in complex environments. The robot is trained to navigate toward both static and dynamic goals while effectively avoiding obstacles, making it suitable for challenging scenarios.

## Key Features
* **Transformer-based Reinforcement Learning**: Utilizes advanced transformer architectures to process spatial and temporal data for effective decision-making.
* **Dynamic and Static Goal Navigation**: Capable of adapting to both stationary and moving targets.
* **Simulation and Real-world Testing**: Supports training and evaluation both in simulation and on physical robots.

## Demonstrations
Here are 4 demos showing our control policy for navigating in the simulation and real world.

* Simulation for reaching static goal 

<p align="center">
  <img src="demo/static_sim.gif" alt="simulation_static" title="simulation_static" img width=55% />
</p>

* Simulation for reaching dynamic goal 

<p align="center">
  <img src="demo/dynamic_sim.gif" alt="simulation_dynamic" title="simulation_dynamic" img width=55% />
</p>

* Real for reaching static goal 

<p align="center">
  <img src="demo/static_real.gif" alt="real_static" title="real_static" img width=100%/>
</p>

* Real for reaching dynamic goal 

<p align="center">
  <img src="demo/dynamic_real.gif" alt="real_dynamic" title="real_dynamic" img width=100% />
</p>

## What's Next
* **Code Release**: Full implementation of TRL-DVO for training and testing reinforcement learning policies in both simulated and real-world setups.
* **Detailed Documentation**: Step-by-step guides for setup, training, and deployment.
* **Extended Results**: Comprehensive benchmarks and additional experiments showcasing the model's performance.

Stay tuned for updates as we finalize our codebase and results!

<!-- More results and implementation details will be coming soon ...  -->