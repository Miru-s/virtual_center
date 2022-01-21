Algorithms Documents 
=====================

.. contents:: **Table of Contents**

*Vanilla Policy Gradient
    *:ref:'Background <bg>'
       
    *Documentation
        
    *References
       

.. _bg:
Background
____________________

The key idea underlying policy gradients is to push up the probabilities of actions that lead to higher return, and push down the probabilities of actions that lead to lower return, until you arrive at the optimal policy.

**Quick Facts**
*VPG is an on-policy algorithm.
*VPG can be used for environments with either discrete or continuous action spaces.
*The Spinning Up implementation of VPG supports parallelization with MPI.
