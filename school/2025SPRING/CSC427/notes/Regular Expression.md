$\text{RegExp} X \iff M_{X}$  
$S \subseteq \sum ^{2}$ 
Also recognize same language as finite automata
### Defined recursively a alphabet $\Sigma$ 
1. $a \in \Sigma$ is a $R$.E
2. $\epsilon$ is a $R$.$E$.
3. $\emptyset$ is a $R$.$E$.
4. $(R_{1} \cup R_{2})$ is a $R$.$E$. given both are $R$.$E$.
5. $(R_{1}\circ R_{2})$ is a $R$.$E$. given both are $R$.$E$.
6. $(R^{k})$ 
### $E$.$g$.
$0^{*} 10^{*}$ - some 0, one 1, some 0 
$0^{*}10^{*}10^{*}$ - string with two ones 
$((0 \cup 1)(0 \cup 1))^{*}$ - 0 and multiples of 2 length string 


### Turn FA into $R$.$E$.
Generalized Nondeterministic Finite Automata GNFA
Arrows are labelled with $R$.$E$.
All states have all possible arrows, if no connection put empty set, suppressed for simplicity when drawing
except:
- A unique start state that goes to all other states, without incoming arrows
- A unique accept state with arrow from all other states and no out going states
![[Pasted image 20250205104227.webp]]

GNFA to regular expression by ripping states
![[Pasted image 20250205104428.webp]]
![[Pasted image 20250205105011.webp]]
