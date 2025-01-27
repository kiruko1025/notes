### Non-deterministic Turing Machine
Connect $S\circ T$ by $\epsilon$  
A non-deterministic finite automaton is a 5-tuple $(Q,\Sigma,\delta, q_{0},F)$
1. $Q$ is a finite set called the **states**
2. $\Sigma$ is a finite set called the **alphabet**
3. $\delta:Q\times \Sigma_{\epsilon}\to P(Q)$ is the **transition function**
4. $q_{0}\in Q$ in the **start state**
5. $F\subseteq Q$ is the **set of accept states**

The power set of $Q$: $P(Q)=\{ \emptyset,\{ q_{1} \},\dots \{ q_{1},q_{2} \},\dots \{ q_{1},q_{2},q_{3},q_{4}  \}\}$ 
