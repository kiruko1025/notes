
### Definitions 
Algorithms
	deterministic
	correctness proved by induction

Efficient Algorithm
	Time complexity is a polynomial $T(n)=O(n^k)$ 

Hard problem
	have no known polynomial-time algorithms

Optimal Algorithms
	when time complexity of algorithm same as lower bound of the problem

 
### Loop Invariant
Initialization - must be true before first iteration
Maintenance - still true after iteration
Termination - can tell the answer is right by some property

 
### Model of Computation
- Specification on what operation is $O(1)$
- Word-RAM


## Growth of Functions
![[Pasted image 20250119020311.webp]]

Asymptotic Lower Bound $\Omega(g(n))$ 
	$f(n)\geq c(g(n))$ 
	best case scenario
	 Gives lower bound with in a constant factor

Asymptotic upper Bound on a problem $O(g(n))$ 
	$f(n)\leq c(g(n))$ 
	worst case scenario
	Gives upper bound with in a constant factor

Asymptotic tight Bound $\Theta(g(n))$ 
	When $O(g(n))=\Omega(g(n))$, $\Theta(g(n))$  
	$\Theta(g(n))$ = $\{ f(n): \text{there exist positive constans } c_{1}, c_{2}, n_{0} \text{ such that }0\leq c_{1}g(n)\leq f(n)\leq c_{2}g(n)\text{ for all }n\geq n_{0} \}$   
	$\Theta$ bounds a function by constant factor
	Must be asymptotically positive (always positive for large n)

Non asymptotic tight upper bound $o(g(n))$  
	$f<c(g(n))$ 
	$e$.$g$.  $2n=o(n^{2})$  $2n^{2}\neq o(n^{2})$ 

Non asymptotic tight lower bound $\omega(g(n))$
	$f(n)\in \omega g(n)\iff g(n)\in o(g(n))$
	 

