[[survey temporal logic.pdf]]
Assume $\langle T, < \rangle$ represent  a temporal structure. In a temporal logic the structure time is *linear* if any two points can be compared.  Namely, if they satisfy the following condition : $\forall x, y \ : \ x < y \lor x=y \lor x>y$.

Another class is the *branching-time structures*, where the underlying temporal structure is branching-like. The structure can be considered a tree. A *tree* is a set of points T ordered by a binary relation < which satisfies the following requirements :
- $\langle T, < \rangle$ is irreflexive;
- $\langle T, < \rangle$ is transitive;
- $\forall t, u, v \in T \ u< t$ and $v < t \rightarrow v, u, = v$ or $u>v$ (i.e. the past of any point is linear);
- $\forall x, y \in T, \exists z \in T$ such that $z < x$ and $z < y$ (i.e. $\langle T, < \rangle$ is connected).

A temporal logic  is *discrete* if each non-final point is followed by a successor point. This can be formulated as follows : $\forall x, y(x<y \rightarrow \exists z (x < z \land \neg\exists w(x<w \land w<z)))$.

A temporal domain is *dense* if, between any 2 distinct points, there is another point. This can be formally denoted $\forall x, y(x<y \rightarrow \exists z(x < z < y))$.

A temporal domain is *bounded above* (*bounded below*)if the temporal domain is bounded in the future (past) time. Similarly, a temporal domain is *unbounded above* (*unbounded below*) if each point has a successor (predecessor) point.

A temporal domain is *Dedekind complete* if all the time point sets (non-empty) are bounded above, and they have a least upper bound.
