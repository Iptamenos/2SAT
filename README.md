# 2-SAT
An algorithm that given a set of CNF (conjuctive normal form) clauses using n=3 variables with 2 variables per clause (2-Satisfiability), outputs a solution (if it exists), which is an assignment for the truth variables that satisfies all the given CNF clauses. Written in Python.

*CNF clause example: (x1 + x2') * (x1 + x3) * (x2 + x3') * (x1' + x2') * (x1 + x2)*

*A: a set of satisfiable assignment of truth variables for the given CNF clause: x1 = True, x2 = False, x3 = False*

Note that the algorithm is guaranteed to find a solution, if it exists, in:

**n_variables<sup>2</sup> * (1 + 4 * sqrt(2 / 3)) = 3<sup>2</sup> * (1 + 4 * sqrt(2 / 3)) ~= 38** iterations.


**See *Sheldon Ross: Introduction to Probability Models* book, page 241**

https://www.academia.edu/7013149/Introduction_to_Probability_Models_-_Sheldon_M-1._Ross
