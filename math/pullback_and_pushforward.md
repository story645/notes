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

# on [[sheaf|sheaves]]
* $F: X \rightarrow set$
* $G: \rightarrow set$

morphism: $X \xrightarrow{f} Y$
pushforward: $F(X) \xrightarrow{f_*} (f_*F)(Y)$
pullback: $(f^*G)(X) \xrightarrow{f^*} G(Y)$ 

## by [[function-types|function type]]
* point $\{p\}$
* codomains: $I = [0,1],\{p\} \subset I$ 
* domain for sections $s$ on $\{p\}$ : $I$
* domain for sections $t$ on $I$: $I^2$
### injective (inclusion $\iota$)
* $F: \{p\} \rightarrow \{s: p \rightarrow a \mid p \in \{p\}, a\in I\}$
* $G: I \rightarrow \{t:q\rightarrow (b,c) \mid q,b,c \in I\}$ 

morphism: $\{p\} \xrightarrow{f} \{q\} \in I \mid p\mapsto q$

pushforward (skyscraper sheaf)
$\{s: p \rightarrow a \mid p \in \{p\}, a\in I\} \xrightarrow{f_*} \begin{cases} f^{-1}[q] \in \{p\} & \{s: f^{-1}[q] \rightarrow a \mid a\in I\}\\ f^{-1}[q]\not\in \{p\} & 0 \end{cases}$

pullback ([[stalk]] on q) 
$\{t: f(p)\rightarrow (b,c) \mid b,c \in I\} \xrightarrow{f^*}\{t:q\rightarrow (b,c) \mid b,c \in I\}$ for $p,q$ s.t. $f(p) \in q$

### surjective ($\xi$)
* $F: I \rightarrow \{s: p \rightarrow (a,b) \mid p,a,b \in I\}$ 
* $G: \{q\} \rightarrow \{t: q \rightarrow c \mid q \in \{c\}, x\in I\}$
 
morphism: $I \xrightarrow{f} \{q\}$
pushforward (delayed evaluation) s(q)-> s(p)
$\{s: p \rightarrow (a, b) \mid p, a, b \in I\}  \xrightarrow{f_*}  \{s: f^{-1}[q] \rightarrow (a,b) \mid a,b \in I\}, f^{-1}[q]=I$

pullback (copy constant function over interval, t(p)->t(q))
$\{t: f(p) \rightarrow c \mid p, c\in I\} \xrightarrow{f^*}\{t: q \rightarrow c \mid q \in \{q\}, c\in I\}$ s.t. $f(p) \in \{q\}$

![](figures/pushpull.png)

### Hom equivalance  $Hom_{\mathcal{O}(X)}(f^*G,F) = Hom_{\mathcal{O}(Y)}(G, f_*F)$
![](figures/hom_equiv.png)
* $F: x \rightarrow \{s: x \rightarrow set\}$
* $G: y \rightarrow \{t: y \rightarrow set\}$
* $f: X \rightarrow Y$
* $f_*F: f^{-1}(y) \rightarrow \{s: f^{-1}(y) \rightarrow set\}$
* $f^*G:  f(x) \rightarrow \{t: f(x) \rightarrow set\}$
  
#### constraints
* $f(x) \subset Y$
* $f^{-1}(y) \in X$

#### HomS
* $Hom_{\mathcal{O}(X)}(f^*G,F) \ni \varphi_x: \{t: f(x) \rightarrow set\} \rightarrow \{s: x \rightarrow set\}$
* $Hom_{\mathcal{O}(Y)}(G, f_*F) \ni \varphi_y: \{t: y \rightarrow set\} \rightarrow \{s: f^{-1}(y) \rightarrow set\}$

#### associativity of $\varphi$ components
$\varphi_{x,y}: t \rightarrow s$
$\varphi_x = f^* \circ (t \rightarrow s) = f^*\circ \varphi_{x,y}$
$\varphi_y = (t \rightarrow s) \circ f_* = \varphi_{x,y} \circ f_*$
$\varphi_x \circ f_* = f^* \circ \varphi_y$
$(f^*\circ \varphi_{x,y}) \circ f_* = f^* \circ (\varphi_{x,y} \circ f_*)$ 

#### currying
pushforward to Y: $f_* \circ (t \rightarrow s) = (f^* \circ t)\rightarrow s$
pullback to X: $(t \rightarrow s) \circ f_* = t \rightarrow (f_* \circ s)$
