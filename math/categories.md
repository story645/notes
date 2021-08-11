### categories
- notation (Mac Lane)
    - fx <=> f(x)
    - $g \circ f: X\rightarrow Z$, $x \mapsto g(f(x))$
    - category of all topological spaces:
        - X, Y,Z - topological spaces
        - f, g, h - continuous maps
    - category of all groups
        - X, Y, Z - groups
        - f, g, h - homomorphisms (homomorphic functions)
- category C consists of data:
    - class/collection (aggregate) of objects
    - identity morphism: for every object $X$, identity $id_x:X \rightarrow X$ (Spivak & Fong)
    - for every two objects $X,Y$, set $C(X,Y)$ of morphisms $f:X\rightarrow Y$ (also known as [[hom-sets|$hom_C(X, Y)$]])
    - composition rule for morphisms (composite morphism): if $f:X \rightarrow Y$ and $g:Y \rightarrow Z$ then $gf: X\rightarrow Z$
- data must meet these axioms (conditions):
    - composition is associative: 
        - if $h: X\rightarrow Y$, $g:Y\rightarrow Z$, $f:Z\rightarrow W$ then f(gh) = (fg)h 
        - derived from composition rule
    - unitality: s.t for every $f: X \rightarrow Y$ there exists $f \circ id_x = f = id_y \circ f$
- tradition/philosophy (Riehl)
    - traditionally name a category after its objects (top, etc in Bradley)
    - algebra of morphisms determines the category, morphisms take primacy

opposite category (nlab)
-$C^{op}$ - formally reversing the direction of all it morphisms (while retaining original composition)
    - $C^{op}$ has same objects as $C$, 
    - $f:c\rightarrow y$ in $C^{op}$ is $f:y \rightarrow x$  
### random notes
what are the objects, arrows, and notions of equivalence:
- categories that have a map into set, (everything can be kinda turned into a set)
- if we have an arrow from A to B
- A, B are sets
- arrow is a functor (forgetful functor)
- equivalence
- what is different about arrows between category of sets and category of groups? 
- notion of equivalence:
    - isomorphism: bijection + homomorphism