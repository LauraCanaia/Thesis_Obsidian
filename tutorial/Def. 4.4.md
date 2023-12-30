[[Tutorial on Abstract Interpretation.pdf]]
*Narrowing*
Definition similar to [[Def. 2.17]]
A binary operator $\triangle : D^{\#} \times D^{\#} \rightarrow D^{\#}$ is a narrowing operator in an abstract domain $D^{\#}$ if:
1. $\forall X^{\#}, Y^{\#} \in D^{\#} : X^{\#} \sqcap ^{\#} Y^{\#} \sqsubseteq ^{\#} X^{\#} \triangle Y^{\#} \sqsubseteq ^{\#} X^{\#}$;
2. for any sequence $(Y^{\# ^{i}})_{i \in \mathbb{N}}$ in $D^{\#}$, the sequence $(Z^{\# ^{i}})_{i \in \mathbb{N}}$ computed as $Z^{\# 0} = Y^{\# 0}$, $Z^{\# i+1} = Z^{\# i} \triangle Y^{\# i+1}$ stabilizes in finite time : $\exists k \geq 0 : Z^{\# k+1} = Z^{\# k}$. 