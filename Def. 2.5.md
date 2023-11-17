*Complete lattice*
A complete lattice $(X, \sqsubseteq, \sqcup, \sqcap, \bot, \top)$ is a poset such that :
1. $\forall A \subseteq X : \sqcup \ A \ exists$;
2. $\forall A \subseteq X \ : \sqcap \ A \ exists$;
3. X has a least element $\bot$;
4. X has a great element $\top$;
Naturally, a complete lattice is both lattice and a CPO. Less obviously, to get a complete lattice, either Def. 2.5.1 or Def.2.5.2 is sufficient, as each one implies the other. Indeed, assuming that $\forall A \subseteq X \ : \ \sqcup \ A \ exists$,  then $\forall B \subseteq X \ : \sqcap C \ = \sqcup \{ x \in X\ | \ \forall a \in B: \ x \sqsubseteq a \}$ also exists : we can reduce glb to a lub, which always exists (the converse naturally holds). 
Moreover, both imply 2.5.3 and 2.5.4. Indeed we have: $\bot \ = \ \sqcup \emptyset \ = \ \sqcap X$ and $\top \ = \ \sqcap \emptyset \ = \ \sqcup X$. 