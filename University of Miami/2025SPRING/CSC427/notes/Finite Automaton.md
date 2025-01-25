
### Definition
A finite automaton is a 5-tuple $(Q,\Sigma,\delta, q_{0},F)$
1. $Q$ is a finite set called the **states**
2. $\Sigma$ is a finite set called the **alphabet**
3. $\delta:Q\times \Sigma\to Q$ is the **transition function**
4. $q_{0}\in Q$ in the **start state**
5. $F\subseteq Q$ is the **set of accept states**

### Operations
Union: $A\cup B=\{ x|x \in A\cup x \in B \}$
Concatenation: $A\circ B=\{ xy| x \in A \cap y \in B \}$
Star: $A^{*}=\{ x_{1},x_{2},\dots x_{k}|k\geq 0\cap y \in B\}$ 

### Language
The set of string with only the $\epsilon$ empty string 
$\Sigma^0=\{\epsilon\}$ 

The set of string with only one character
$\Sigma^1=\{a, b, c, \dots\}$ 

The infinite set of finite sets of string with i length
$\Sigma^*=\bigcup_{i=0}^\infty \Sigma^i$


### Definition of Language
A language $S$ is $S\subseteq \Sigma^*$
A language $S$ that can be recognized by finite automaton $M$ is **Regular Language**
$M$ can decide  if $\sigma \in \Sigma^*$ when $\sigma \in S$ 
$\emptyset$ is regular
$\Sigma^{*}$ is regular
counting mod $n$ is regular
if $S\text{ and} T$ are regular  $U=S\cup T$ is 

Singleton sets are regular:
$S_{s=w}=\{ w \}$ 
$S\subseteq \Sigma^{*}|S|<\infty$ 

### Combine two machines
$S'=S_{1}\cup S_{2}$ 
$Q'=Q_{1}\times Q_{2}$
$q_{0}'=(q_{0}1,q_{0}2)$ 
$F'=(F_{1}\times Q_{2})\cup(Q_{1}\times F_{2})$ 
$S'((q_{1},q_{2}),\sigma)=((q_{1},\sigma),(q_{2},\sigma))$ 
