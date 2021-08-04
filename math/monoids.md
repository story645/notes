monoid (S+M, pg. 2)
- [[groups|group]] w/o inverses (semi group w/ identity)
symmetric monoidal category (Spivak & Fong, Riehl)
- data $(V, \otimes, *)$ 
  - category V
  - monoidal product: $\otimes:V\ times V \rightarrow V$ (bifunctor)
  - unit object: $* \in V$ 
  - natural isomorphisms:
    - symmetry: $v \otimes w \underset{\gamma}{\cong} w \otimes v$
    - associativity: $u \otimes (v \otimes w) \underset{\alpha}{\cong} = (u \otimes v) \otimes w$
    - unit (identity): $* \otimes v \underset{\lambda}{\cong} v \underset{p}{\cong} v \otimes *$   

monoidal category: symmetric monoidal category w/o symmetry

Monoid object $(M, \mu, \eta)$ in a symmetric monoidal category $(C, I, \otimes)$ $((V, \otimes, *))$ is 
- object $M \in C$ w/ morphisms 
  - $\mu: M \otimes M \rightarrow M$ 
  - $\eta: I \rightarrow M$ 
- s.t 
  - $\mu \circ (\mu \otimes id) = \mu \circ (id \otimes \mu)$
  - $\mu \circ (\eta \otimes id) = id = \mu \circ (id \otimes \eta)$