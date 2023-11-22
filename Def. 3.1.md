*Abstract domain*
An abstract domain is given by :
- a set $D^{\#}$ of computer representable abstract values;
- an effective partial order $\sqsubseteq^{\#}$ on $D^{\#}$;
- a monotonic concretization function $\gamma : D^{\#} \rightarrow D$;
- a smallest element $\bot^{\#}\in  D^{\#}$ and a largest element $\top^{\#}\in D^{\#}$ that represent respectively $\emptyset$ and $\epsilon$;
- (optionally) a Galois connection [[Def. 2.12]]
- a sound effective abstraction of assignments and atomic conditions ![[Pasted image 20231122182655.png]]
- sound and effective abstractions of set union $\cup$ and set intersection $\cap$ ![[Pasted image 20231122182814.png]]
- a widening operator $\bigtriangledown$ [[Def. 2.17]]