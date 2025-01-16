

### Definition
A finite automaton is a 5-tuple $(Q,\Sigma,\delta, q_{0},F)$
1. $Q$ is a finite set called the **states**
2. $\Sigma$ is a finite set called the **alphabet**
3. $\delta:Q\times \Sigma\to Q$ is the **transition function**
4. $q_{0}\in Q$ in the **start state**
5. $F\subseteq Q$ is the **set of accept states**

### Operations
Union: $A\cup B$
Concatenation: $A\circ B$
Star:


### Language
The set of string with only the $\epsilon$ empty string 
$\Sigma^0=\{\epsilon\}$ 

The set of string with only one character
$\Sigma^1=\{a, b, c, \dots\}$ 

The infinite set of finite sets of string with i length
$\Sigma^*=\bigcup_{i=0}^\infty \Sigma^i$

### Definition of Language
A language $S$ is $S\subseteq \Sigma^*$
A language that can be recognized by finite automaton is **Regular Language**
