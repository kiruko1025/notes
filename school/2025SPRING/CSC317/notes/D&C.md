### Recursive case 
When sub problem large enough and similar then solve recursively
### Recurrence $T(n)$ 
A equation or Inequality that describes a function in terms of its value on smaller inputs

### Solving Recurrence
Usually ignore boundary, floor, and ceiling 

#### substitution method
1. Guess the form
2. Use induction to find constant $c$  and prove works
3. Extend boundary for small $n$ if necessary   
4. add or subtract constant $d$ to make it work if needed 
	$e$.$g$. Guess $T(n)=O(n)$ prove $T(n)\leq cn$ by substitution (need to prove the exact form) 
	 
#### recursive tree method
#### master method