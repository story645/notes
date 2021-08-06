### cw complex (Hatcher)
CW complex is a space X constructed in the following way
1. start w/ discrete set $X_0$, 0-cells of X
2. inductively from the [[simplicial-complex|n-skeleton]] $X^n$ from $X^{n-1}$ by attaching n cells $e^{n}_{\alpha}$ via maps $\phi_{\alpha}:S^{n-1}\rightarrow X^{n-1}$  
3. 

$e^{n}$: n-cell, [[homeomorphism|hoemeomorphic]] to the open n-disk $D^{n}-\partial D^{n}$ 
    - $S^{n}$ unit sphere in $\mathbb{R}^{n+1}$, all points distance = 1 from origin
    - $D^{n}$ unit disk or ball in $\mathbb{R}^{n}$, all points distance $\leq 1$ from origin
    - $\partial D^{n}$ the boundary of the n-disk

Any topological space can be approximated by a CW complex that is unique up to [[homotopy]]. CW complexes are built in stages, from adjoining cells of a given dimension. Advantage over simplicial complex is usually fewer cells. 
