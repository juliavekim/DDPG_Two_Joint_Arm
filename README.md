# DDP_Two_Joint_Arm
Design a policy to simulate a simplified, two-joint arm that can reach and track a moving target.

## DDP
I develop a deep deterministic policy gradient to learn to control a two-joint arm. The arm's state dynamics are described by the differential equation $a = M(q) \ddot{q} + \Gamma(q, \dot{q}){q} = \begin{bmatrix} \end{bmatrix}$
