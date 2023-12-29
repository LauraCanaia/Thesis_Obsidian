An action $a_R$ is responsible for the behavior B of interest in a given execution $\iff$ $a_R$ is free to make choices, and such a choice is the first one that guarantees the occurrence of B in the execution.   

*Definition that comes from the forest fire's example*
An event $e$ is a cause of another occurrence of another event $e'$ $\iff$ were $e$ not to occur, $e'$ would not happen.
SEM can be used to determine which program point is responsible of what, but in misses the 3 properties to determine responsibility.
The 3 properties to determine responsibility are:
1. The temporal order of event/actions should be taken into account;
2.  The responsible entity is free to make choices;
3.  It is necessary to explicitly specify "whose to cognizance" when analyzing the responsibility.

*Informal definition of responsibility given by the article*
_To the cognizance of an observer, an action $a_R$ is responsible for the behavior $\mathcal B$ of interest in a given execution if and only if, according to the observer's observation, $a_R$ is free to make choices, and such a choice is the first one that guarantees the occurrence of $\mathcal B$ in that execution._  