[[Tutorial on Abstract Interpretation.pdf]]
*Abstract value domain*
An abstract domain of values is given by :
- a set $B^{\#}$ of computer-representable abstract values;
- an effective partial order $\sqsubseteq^{\#}_{b}$ on $B^{\#}$;
- a monotonic concretization function $\gamma_b : B^{\#} \rightarrow P(I)$;
- a smallest $\bot^{\#}_{b}$ and a largest element $\top^{\#}_{b}\in B^{\#}$ that represent respectively $\emptyset$ and $I$;
- (optionally) a Galois connection $(P(I), \ \subseteq) \leftrightarrow (B^{\#}, \sqsubseteq^{\#}_b)$   [[Def. 2.12]];
- a sound and effective abstraction of constants and non-deterministic intervals of unary operators and binary operators;
- a sound and effective abstraction of set union $\cup$ and set intersection $\cap$;
- a widening operator $\bigtriangledown_b$ [[Def. 2.17]];