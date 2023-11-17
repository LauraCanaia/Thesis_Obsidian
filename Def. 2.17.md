*Widening*
A binary operator $\bigtriangledown : \ A \ \times \ A \rightarrow A$ is a widening operator in abstract domain $(A, \sqsubseteq)$ if :
1. it computes upper bounds : $\forall x,y \in A : x \sqsubseteq x \bigtriangledown y \ and \ y \sqsubseteq x\bigtriangledown y$ ;
2. and it enforces convergence : for any sequence $(y^i)_{i \in \mathbb{N}}$ in A, the sequence $(x^i)_{i \in \mathbb{N}}$ computed as $x^0 \overset{\operatorname{def}}{=} y^0, \ x^{i+1} \overset{\operatorname{def}}{=} x^i \bigtriangledown y^{i+1}$  stabilizes in finite time : $\exists k \geq 0 : x^{k+1} = x^k$ 