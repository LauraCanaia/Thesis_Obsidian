[[survey temporal logic.pdf]]
Introduced after [[Linear Temporal Logic (LTL)]].
Was introduced (over discrete time models) with X(next) and U(until) operators. PTL is decidable, and it provides a sound and complete axiomatization.
Several examples of properties of programs expressible by means of temporal logics can be found. 
Important properties can be expressed in PTL as follows :
- $p \rightarrow \square q$ : q holds at all states after p holds.
- $\square((\neg q)\lor(\neg p))$ : p and q cannot hold at the same time.
- $p \rightarrow \diamondsuit q$ : q holds at some time after p holds.
- $\square \diamondsuit p \rightarrow \diamondsuit q$ : if p repeatedly holds, q holds after some time.
- $\square p \rightarrow \diamondsuit q$ : if p always holds, q holds after some time.