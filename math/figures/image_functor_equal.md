* $\xi^{*}\mathcal{O}_{(K,E)} \approx \xi^{-1}\mathcal{O}_{(K,E)}$
* $Hom_{\mathcal{O}(S)}(\xi^{-1}\mathcal{O}_{(K,E)}, \mathcal{O}_{(S,H)}) = 
Hom_{\mathcal{O}(K)}(\mathcal{O}_{(K,E)}, \xi_*\mathcal{O}_{(S,H)})$

[usually not isomorphisms](https://en.wikipedia.org/wiki/Inverse_image_functor):
* $\mathcal{O}_{(K,E)}\rightarrow \xi_*\xi^*\mathcal{O}_{(K,E)}$ push (pull)
*  $\xi^*\xi_*\mathcal{O}_{(S,H)} \rightarrow \mathcal{O}_{(S,H)}$ pull (push)
*  push over K, pull over S


# Sections of sheaves
surjective map $\xi: S \rightarrow K,\; \xi(s) = k$ 

## graphic 
* $D \hookrightarrow H \xrightarrow{\pi} S$
* $\{W\} \in S$
* $\mathcal{O}_{(S,H)}: \mathcal{S}^{op} \rightarrow Set$
* $\mathcal{O}_{(S,H)}: W \mapsto \Gamma(W, H|_W)$
* $\Gamma(W, H|_W) \ni \rho: W \rightarrow H|_W$
* $\rho(s) = d,\; s \in W, d \in D_s$
    * example: $d = \{x,y,r,g,b\}$ 
## data 
* $F \hookrightarrow E \xrightarrow{\pi} K$
* $\{U\} \in K$
* $\mathcal{O}_{(K,E)}: \mathcal{K}^{op} \rightarrow Set$ 
* $\mathcal{O}_{(K,E)}: U \mapsto \Gamma(U, E|_U)$
* $\Gamma(U, E|_U) \ni \tau: U \rightarrow E|_U$
* $\tau(k) = r, \; k \in U, r \in F_k$ (Butler)
  * typed & named field:value pairs (Spivak): 
  * $r = \{field_1:value, field_2:value, ...,field_n:value\}$ 
## pushed forward graphic
* $\xi_*D \hookrightarrow \xi_*H \xrightarrow{\pi} K$
* $\xi_*\mathcal{O}_{(S,H)}: U \mapsto \Gamma(U, \xi_* H|_U)$
* $\Gamma(U, \xi_* H|_U) \ni \xi_*\rho: U \rightarrow \xi_*H|_U$ 
* $\xi_*\rho(k) = \rho(\xi^{-1}(k)) = d \in D_{s}$ for all $s \in \xi^{-1}(k)$
  * $\{\rho(s)\;for\;s\;in\;\xi^{-1}(k)\}$ <- whole glyph
  
## pulled back data 
* $\xi^*F \hookrightarrow \xi^*E \xrightarrow{\pi} S$
* $\xi^*\mathcal{O}_{(K,H)}: W \mapsto \Gamma(W, \xi^*E|_W)$
* $\Gamma(W, \xi^*E|_W) \ni \xi^*\tau: W \rightarrow \xi^*E|_W$
* $\xi^*\tau(s) = \tau(\xi(s)) = r \in F_{k}, \xi(s)=s$ # graphic region collapses to one record r


# Artist
* naturally isomorphic: $[\mathcal{O}_{S, \xi^*E}, \mathcal{O}_{S,H}] \cong [\mathcal{O}_{K, E}, \mathcal{O}_{K,\xi_* H}]$

## $A_S \in Hom_{S}(\mathcal{O}_{S, \xi^*E}, \mathcal{O}_{S,H})$
  * $A_S \in [\mathcal{O}_{S, \xi^*E}, \mathcal{O}_{S,H}]$
  * 
  *  $A_S \in Nat(\mathcal{O}_{S, \xi^*E}, \mathcal{O}_{S,H})$
  * $A_S: \xi^{*}\mathcal{O}_{(K,E)} \mapsto \mathcal{O}_{(S,H)}$ 
  * $A_S(\xi^*\tau) = A_s (\tau ( \xi(s))) = \rho(s)$

## $A_K \in Hom_{\mathcal{O}(K)}(\mathcal{O}_{(K,E)}, \xi_*\mathcal{O}_{(S,H)})$
  * $A_K (\tau) = \xi_*\rho = \rho|_{\xi^{-1}(k)}$

## $A \in Hom_{\mathcal{O}(K), \mathcal{O}(S)}(\mathcal{O}(K,E), \mathcal{O}(S,H))$
* $A: \tau \mapsto \rho$, $A(\tau(k)) = \rho|_{\xi^{-1}(k)}$
* $\xi^{-1}(k) \subset S$, $\rho|_{\xi^{-1}(k)}: \xi^{-1}{k} \rightarrow H|_{\xi^{-1}(k)}$