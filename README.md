# DDP_Two_Joint_Arm
Design a policy to simulate a simplified, two-joint arm that can reach and track a moving target.

## DDP
I develop a deep deterministic policy gradient to learn to control a two-joint arm. The arm's state dynamics are described by a differential equation $a = M(q) \ddot{q} + \Gamma(q, \dot{q}){q}$, where $a$ is the action, $q$ is the configuration vector containing the shoulder and elbow angles in that order, $\dot{q}$ and $\ddot{q}$ are the velocity and acceleration, and $\psi_1, \psi_2, \psi_3$ are constants. 
