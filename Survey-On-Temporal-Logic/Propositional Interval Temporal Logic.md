[[survey temporal logic.pdf]], [[Interval temporal logic]]
The syntax of this kind of logic is constructed from the following : the set of propositional variables, the truth values, the classical operators and a set of temporal operators defined for each logic.

*The logic HS*
relatively expressive propositional interval temporal logic that has enough expressive power to distinguish different temporal structures that are formally shown as follows :
- $length0 \equiv [B]\bot$ 
- $length1 \equiv \langle B\rangle \top [length0]$ 
- $dense \equiv \neg length1$
- $discrete \equiv length0 \lor length1 \lor (\langle B \rangle length1 \land \langle E \rangle length1)$
see [[Temporal structure]] for Dedekind completeness.

*The logic CDT*
Is one of the most expressive propositional interval logic over linear orderings and includes the modal operators C, D and T.
Specification of the intervals this logic can specify :
$(length1 \ C \ \top) \land (\top \ C \ length1)$

*The logic PNL*
Deeply explained in the paper

