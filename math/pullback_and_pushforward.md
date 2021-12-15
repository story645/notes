# pullback
- precomposition of a function 
  - f(y(x)) = g(x)
- acts on the argument
- [[category-limit]]
    - $P = X \times_{Z} Y $
- product is pullback w/ z= [[category-terminal]]

![wikepedia](figures/pullback.png)\

# pullback bundle
- Given a bundle p:E→Xp \colon E \to X, and a morphism f:Y→Xf \colon Y \to X, then the pullback bundle f *E→Yf^\ast E \to Y is (if it exists) simply the pullback of pp along ff, regarded as a bundle over YY. [nlab]
# pushforward/pushout 
- post composition of a function
- acts on the return
- [[category-colimit]]
  - $P = X \sqcup_{Z} Y$
- coproduct is pushout from [[category-initial]]
![wikipedia](figures/pushout.png)

### on [[sheaf|sheaves]]
* $F: X \rightarrow set$
* $G: \rightarrow set$

morphism: $X \xrightarrow{f} Y$
pushforward: $F(X) \xrightarrow{f_*} (f_*F)(Y)$
pullback: $(f^*G)(X) \xrightarrow{f^*} G(Y)$ 

### by [[function-types|function type]]
* point $\{p\}$
* codomains: I = [0,1], $\{p\} \subset I$ 
* domain for sections s on {p} : I
* domain for sections t on I: $I^2$
#### injective (inclusion function $\iota$)
* $F: \{p\} \rightarrow \{s: p \rightarrow x \mid p \in \{p\}, x\in I\}$
* $G: I \rightarrow \{t:q\rightarrow (x,y) \mid q,x,y \in I\}$ 

morphism: $\{p\} \xrightarrow{f} [0,1]$
pushforward (skyscraper sheaf)
$\{s: p \rightarrow x \mid p \in \{p\}, x\in I\} \xrightarrow{f_*} \begin{cases} q \in \{p\} & \{s:q\rightarrow x \mid x\in I\}\\ q\not\in \{p\} & 0 \end{cases}$
pullback ([[stalk]])
$\{t: p\rightarrow (x,y) \mid x,y \in I\} \xrightarrow{f^*}\{t:q\rightarrow (x,y) \mid x,y \in I\}$ for $p,q$ s.t. $f(p) \in q$

