### presheaf of R-modules (Spanier)
- $\Gamma$ of [[R-module|R modules]] on [[topological-space]] X
- [[contravariant-functors|contravariant functor]] from [[categories|category]] of [[open-set|open sets]] U of X 
- inclusion maps $U \subset V$ to the category R s.t. $\Gamma(\varnothing)=0$
  
$\Gamma$ assigns 
- open subset $U \subset X$:  an R module $\Gamma(U)$
- inclusion map $U \subset V$: [[homomorphism-types|homomorphic]] restriction map $\rho_{UV}: \Gamma(V) \rightarrow \Gamma(U)$
  - $\rho_{UU} = 1_{\Gamma(U)}$ 
  - $\rho_{UW} = \rho_{UV}\circ \rho_{VW}: \Gamma(W)\rightarrow \Gamma(U)$, $U\subset V\subset W$
  
- presheaf generalizes the concept of global space of [[section|sections]]
- presheaf does not have to be on R-modules:
  - input open set -> output is space of sections
  
  Notes:
  $\Gamma$ of the tangent bundle says this section arises out of the section maps coming from the base and fiber space,

  what if someone just gave you sections? -> is a vector space?

  Higher order function:
    computer function, something that returns something -
      ex: infinite f(R)-> R^N, ex type(2)->int
    sheaf: input is open set, function returns section of bundle over open set
  can look at it as abstract data type, removes the structure
