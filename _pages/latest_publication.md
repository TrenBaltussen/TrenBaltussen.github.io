**Title:** Policy Iteration over Terminal Cost Functions: From LQR to MPC<br>
**Authors:** Tren Baltussen, Nathan P. Lawrence, Alexander Katriniok, Ali Mesbah, Maurice Heemels<br>
**Date:** 2026-11-02<br>
Preprint available on [ArXiv](https://arxiv.org/abs/2611.03401)  

**Abstract:**  
 Policy iteration is a classical method for successively improving control policies in optimal control and reinforcement learning. In this paper, we propose a policy iteration framework that refines receding-horizon control (RHC) and model predictive control (MPC) policies online by iteratively updating the terminal cost. We first develop the framework for the linear quadratic regulator (LQR) problem. We show that the Riccati map is a contraction in the Thompson metric on an explicitly constructed invariant order interval. Using this property, we prove convergence of approximate policy iteration for finite-horizon RHC, where the terminal cost is given by an approximate value function. From an initial terminal cost, we then construct a robust invariant order interval within which the RHC policy is refined online. We extend the analysis to constrained MPC and present a constructive algorithm for safely updating the terminal ingredients, which guarantees recursive feasibility and asymptotic stability of the closed loop throughout the iterations. These results connect classical Riccati theory with approximate policy iteration and provide a principled pathway toward learning MPC terminal ingredients. A numerical example illustrates the proposed method. 
 
