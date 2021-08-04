### nerve (Spanier)
- [[set]] X 
- collection $\mathscr{W}=\{W\}$ of subsets of X
- nerve $K(\mathscr{W})$ is the [[simplicial-complex]] whose simplicies are finite non-empty subsets of of $mathscr{W}$ with non-empty intersection, 
- vertices of $K(\mathscr{W})$ are non-empty elements of $\mathscr{W}$

Hatcher:
- [[open-cover]] $\mathcal{U} = \{U_{\alpha}\}$ of a given space $X$
- nerve $N(\mathcal{U})$ is associated [[simplicial-complex]
- vertex $v_{\alpha}$ for each $U_{\alpha}$
- set $k+1$ vertices spans a $k$-simplex, 
- $k+1$ corresponding $U_{\alpha}$ w/ nonempty intersection

cover $\mathcal{V}=\{V_{\beta}\}$ is a refinement of $\mathcal{U}$, so each $V_{\beta}\subset U_{\alpha}$, then these inclusions induce a simplicial map $N(\mathcal{V})\rightarrow N(\mathcal{U})$ that is  well-defined up to [[homotopy]]
