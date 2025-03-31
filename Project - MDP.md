### Mini Project 1

In this project, students will become familiar with the basics of reinforcement learning and implement the **value iteration** algorithm in a **Grid environment**.

- **Markov Reward Process**
  - ⟨ S , P , R, $\gamma$ ⟩
  - $E[R_{t+1} \mid S_t = s]$
  - $G_t = \sum_i^t R_i$
  - $\vec{v}(s) = \mathbb{E}[G_t \mid S_t = s]$
  - Use FSA to compute $v(s)$ analytically (Bellman equation)
  - For large $n$, exact solution becomes computationally expensive → use **value iteration**

- **Markov Decision Process** – *FrozenLake environment in OpenAI Gym*
  - Definition: ⟨ S, A, P, R, $\gamma$ ⟩
  - Policy $\pi(a \mid s)$
  - $v_{\pi}(s)$: state-value function (or simply, value function)
  - Derive the **Bellman equation** for $v_{\pi}$
  - Without direct solution, find optimal value function $v^*$ using **value iteration**
  - Derive a **deterministic policy** using the converged value function

