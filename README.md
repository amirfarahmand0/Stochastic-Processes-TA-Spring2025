# Stochastic-Processes-TA-Spring2025
Repository for Stochastic Processes TA course (Spring 2025). Contains lecture notes, assignments, solutions, project guidelines, and resources for students and teaching assistants.


## First Project 
- Markov Reward Process
  - <S , P , R, $\gamma$ >
  - E[R_{t+1} | S_{t} = s]$
  - $G_t = \sum_i^t R_i$
  - $ \vec{v} = E[G_t|S_t = s]$
  - Use FSA to compute $v(s)$ (Analytically) - Bellman
  - Large n computationally expensive -> Value iteration
- Markov Decision Process - frozen lake in gym
  - Defenition : <S, A , P, R, $\gamma$ >
  - Policy $\pi(a|s)$
  - $v_{\pi}(s)$ state-value function or simply value fanction
  - Derieve Bellman for $v_{\pi}$
  - without direct solution, find optimal value function $v^*$ (using value iteration)
  - Derive a deterministic policy using converged value function 
