### sheaf on modules (Spanier)
$\Gamma$ is a [[presheaf]] of modules on [[topological-space]] X:
- $\mathscr{U}$ is a collection of [[open-set|open sets]] on X
- compatible $\mathscr{U}$ family of $\Gamma$ is an indexed family $\{\gamma_{U} \in \Gamma(U)\}_{U\in \mathscr{U}}$ s.t. 
  - $\gamma_{U}|U\cap U^{\prime}=\gamma_{U^{\prime}}|U\cap U^{\prime}$
  - $U, U^{\prime}\in \mathscr{U}$
- section? $\gamma$ evaluated over different subsets $U, U^{\prime}\subset B$ equal on $\cap$

presheaf $\Gamma$ is a sheaf if given collection $\mathscr{U}$ of open subsets on X with $V = \cup_{U\in \mathscr{U}}U$
1. given $\gamma \in \Gamma(V)$ s.t $\gamma|U = 0$ for $U\in \mathscr{U}$, then $\gamma=0$
2. given compatible $\mathscr{U}$ family $\{\gamma_U\}_{U\in\mathscr{U}}$, there is an element $\gamma \in \Gamma(V)$ s.t. $\gamma|U=\gamma_U$ for all $U \in \mathscr{U}$ 
3. follows from 1 that every $\gamma$ in 2. is unique

