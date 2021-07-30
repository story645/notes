### Functor (covariant, pushforward): (Bradley, Fong & Spivak)
- specifying functor from [[categories|category]] C to category D $\mathcal{F}: \mathcal{C}\rightarrow \mathcal{D}$
    - object $F(X)$ of the category D for each object X in C
        - every object $c \in Ob(\mathcal{C})$ has a corresponding object $F(c) \in Ob(\mathcal{D})$
    - morphism $Fhf:FX \rightarrow FY$ for every [[category-homomorphisms|morphism]] $f:X\rightarrow Y$
        - for every morphism $f: c_1 \rightarrow c_2$, there's a morphism $F(f): F(c_1) \rightarrow F(c_2)$
- must satisfy properties:
  - identity: 
      - $F id_x = id_{FX}$, for every $c\in Ob(\mathcal{C})$
      - $F(id_c) = id_{F(c)}$
  - composition: 
      - $(Fg)(Ff) = F(gf)$ for any morphism $f: X\rightarrow Y$, $g: Y\rightarrow Z$
      - given $c_1, c_2, c_3 \in Ob(\mathcal{C})$, morphisms $f \in \mathcal{C}(c_1, c_2), g \in mathcal{C}(c2, c3)$
          - $F(g\circ f) = F(g) \circ F(f)$ holds in $\mathcal{D}$
            