This project implements the iterative deepening branch-and-bound algorithm for the restricted container relocation
problem with distinct priorities in Tanaka & Takii (2016). The algorithm is improved by several dominance rules
originally described in Tanake & Mizuno (2018), which have been slightly modified based on the lexicographic dominance
principle to guarantee mutual consistency.

This project is written in C99.

References:

- Tanaka, S. & Takii, K. (2016). A faster branch-and-bound algorithm for the block relocation problem. *IEEE
  Transactions on Automation Science and Engineering*, 13(1), 181-190.
- Tanaka, S. & Mizuno, F. (2018). An exact algorithm for the unrestricted block relocation problem. *Computers &
  Operations Research*, 95, 12-31.
