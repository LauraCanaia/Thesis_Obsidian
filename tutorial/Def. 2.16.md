[[Tutorial on Abstract Interpretation.pdf]]
*Best operator abstraction*
Given a Galois connection $(C, \le ) \leftrightharpoons^\alpha_\beta \ (A, \sqsubseteq )$  and a concrete operator $f : C \longrightarrow C$ , the best abstraction of f is given by $\alpha \circ f\circ \gamma$ .

Indeed  note that, the soundness definition, $f(\gamma (a))\le\gamma(g(a))$ from [[Def. 2.15]] can be written equivalently, given the definition of Galois connection ([[Def. 2.5]]), as $\forall a \in A:\alpha(f(\gamma(a))) \sqsubseteq g(a)$ . Hence, a sound abstraction $g$ of $f$ is any operator that is greater than $\alpha \circ f \circ \gamma$ . This means that a $\alpha \circ f \circ \gamma$ is thus the best abstraction, i.e., the smallest sound abstraction, of $f$.