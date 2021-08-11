### metacategory
[[metagraphs]]+ (Mac Lane) 
- identity (operation): each object $a$ is assigned an arrow $id_a=1_a:a\rightarrow a$
- composition (operation): each pair of arrows $<g,f>$ with dom $g$=cod $f$ is assigned an arrow $g\circ f$
    - $g \circ f$: dom $f \rightarrow$ cod $g$
    - output of f is input to g
- associativity (axiom): for $a \xrightarrow{f} b \xrightarrow{g} c \xrightarrow{k}d$
    - $k\circ(g\circ f) = (k\circ g) \circ f)$ 
- unit law (axiom): for all arrows $f: a \rightarrow b$ and $g: b\rightarrow c$
    - $1_b \circ f: f$ and $g \circ 1_b: g$
    - b\c $\#1 \circ \#2$-output of #2 is input to #1