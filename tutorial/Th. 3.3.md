[[Tutorial on Abstract Interpretation.pdf]]
*Termination and soundness*
$\forall p \in stat, \ I^{\#} \in D^{\#}: if \ I \subseteq \gamma(I^{\#})$ , then the limit $(X_i^{\#})_{i\in L}$ of iteration (example) is reached in finite time and is a sound abstraction of the limit $(X_i)_{i \in L}$ of iteration (example), i.e., $\forall i \in L:X_i \subseteq \gamma(X_I^{\#})$.