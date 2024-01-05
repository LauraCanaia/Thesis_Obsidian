[[survey temporal logic.pdf]]
Is an extension of [[Computational Tree Logic (CTL)]]  by adding properties of linear temporal logic.
Is a logic which unifies [[Computational Tree Logic (CTL)]] and [[Linear Temporal Logic (LTL)]].

*CTL \* [P]* is a way to say that CTL* can be applied also to path operators, so we can see if some property is satisfied at a certain point in the path we want to observe.

Properties over path expressed below :
- $\forall \square p$ : *safety property* : p is true at all states of each path;
- $\forall \diamondsuit p$ : *liveness property* : p is true at some state of each path;
- $\exists \diamondsuit p$ : *possibility property* : p is true at some state of some path.

This logic can be used in specification of some more complex properties, which cannot be expressed either UB and CTL:
- $\square \diamondsuit p \rightarrow \square \diamondsuit q$  : *fairness property*;
- $\diamondsuit \square p \rightarrow \square \diamondsuit q$ : *justice property*;
- $\exists ((pUq) \lor \square p)$ : *weak until property*.
