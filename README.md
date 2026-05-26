# CartPole Environment - OpenAI Gymnasium
 
## Overview
 
CartPole is a classic control problem from OpenAI's Gymnasium library. The task involves balancing a pole on top of a moving cart. The agent must learn to move the cart left and right to keep the pole upright.
 
## Problem Description
 
### Objective
Keep a pole balanced on a cart by applying force to move the cart left or right. The episode ends when:
- The pole falls over (angle exceeds ±12°)
- The cart moves too far from center (position exceeds ±2.4 units)
- The episode reaches 500 steps (success)
### Physical System
The CartPole system consists of:
- **Cart**: A moving platform on a frictionless track
- **Pole**: A 1.0 meter long rod attached to the cart via a hinge
- **Goal**: Balance the pole upright while keeping the cart centered
