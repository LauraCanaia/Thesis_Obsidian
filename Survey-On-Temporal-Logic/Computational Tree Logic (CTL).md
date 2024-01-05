[[survey temporal logic.pdf]]
CTL is a point-based branching time logic (references in [[Temporal structure]], [[Point structure]], [[Branching Time Logic (BTL)]]).
CTL allows quantification over paths.
Some quantification formulas are given below :
- $\exists \diamondsuit (p \land \neg q)$ : There exists a state where p holds but q does not hold;
- $\forall \square (p \rightarrow \forall \diamondsuit q)$ : whenever p holds, eventually q holds;
- $\forall \square (\exists \diamondsuit p)$ : at all paths p holds after some time.