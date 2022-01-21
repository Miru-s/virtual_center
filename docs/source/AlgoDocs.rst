Algorithms Documents 
=====================

.. contents:: **Table of Contents**

*Vanilla Policy Gradient
    *Background
        *Quick Facts
        *Key Equations
        *Exploration vs. Exploitation
        *Pseudocode
    *Documentation
        *Documentation: PyTorch Version
        *Saved Model Contents: PyTorch Version
        *Documentation: Tensorflow Version
        *Saved Model Contents: Tensorflow Version
    *References
        *Relevant Papers
        *Why These Papers?
        *Other Public Implementations

Background
____________________

The key idea underlying policy gradients is to push up the probabilities of actions that lead to higher return, and push down the probabilities of actions that lead to lower return, until you arrive at the optimal policy.

**Quick Facts**
*VPG is an on-policy algorithm.
*VPG can be used for environments with either discrete or continuous action spaces.
*The Spinning Up implementation of VPG supports parallelization with MPI.