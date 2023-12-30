[[Tutorial on Abstract Interpretation.pdf]]
*Galois connection properties*
Given a Galois connection we have :
1. $\gamma \circ \alpha \circ \gamma = \gamma$ and $\alpha \circ \gamma \circ \alpha = \alpha$;
2. $\alpha \circ \gamma$ and $\gamma \circ \alpha$ are idempotent;
3. $\forall c \in C : \alpha(c) = \sqcap \{ a \ | \ c \leq \gamma(a)\}$;
4. $\forall a \in A : \gamma(a) = \lor \{ c \ | \ \alpha(c) \sqsubseteq a\}$;
5. $\alpha$ maps concrete lubs to abstract lubs : $\forall X \subseteq C : \ if \lor X$ exists then $\alpha(\lor X) = \sqcup \{\alpha(x) \ | \ x \in X\}$;
6. $\gamma$  maps concrete glbs to abstract glbs : $\forall X \subseteq A : \ if \sqcap X$ exists, then $\gamma(\sqcap X) = \land \{\gamma(x) \ | \ x \in X\}$;
Note that $\gamma \circ \alpha$ is extensive ([[Th. 2.3]]) and that the relationships are sound ([[Def. 2.11]]).
