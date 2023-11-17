*Sound and exact operator abstraction*
Given a concretization $\gamma$ from an abstract domain (A, $\sqsubseteq$) to a concrete domain (C, $\le$) , a concrete operator $f : C \rightarrow C$,  and an abstract operator $g : A \rightarrow A$ :
1. $g$ is a sound abstraction of $f \\ if\forall a \in A: f(\gamma(a)) \le \gamma(g(a))$;
2. $g$ is an exact abstraction of $f \\ if f \circ \gamma = \gamma \circ g$.
An exact abstraction is always sound. For a sound abstraction to be exact, the concrete image of any abstract-representable element must also be abstract-representable (e.g., the image of an interval is an interval), which is quite rare. 
When we have a Galois connection, we can additionally transport the notion of best abstraction to operators.