# K & S 
## stages
### data D: 
- TEAM: \mathcal{E}
- the underlying mathematical structure of the data or object being visualized,
  - mathematical types of the individual data points
  - organization of the data points
  - operational context
  - actions (but they don't call it this)
    - linear transforms on the space + properties/ partial orders
    - ordering maps for trees
    - 
### representations R: 
- TEAM: implementation of \mathcal{E} + \mathcal{E}\rightarrow \mathcal{E'}
- concrete representation of the data in a computer,
  - data structure? list or table, vector 
  - computation: samples, 

### visualization V:
- TEAM: how folks view \mathcal{H}
- mathematical description of how humans perceive the visualization.

## mappings
- $r$ data to representation: 
  - TEAM: \mathcal{E}, computation:\mathcal{E} -> \mathcal{E'}
- $v$ representation to visual
  - TEAM: Q\circ\nu
- \alpha data symmetries
  - TEAM: \varphi
- \omega visual symmetries
  - TEAM: ImA_{\varphi}
## principals
1. representation invariance: \alpha=1_D \rightarrow \omega = 1_V
    - how data is encoded shouldn't change the viz
      - ex: numpy array | pandas dataframe -> same line plot
    - visualization should not depend on the specifics of how the underlying data is represented 
    - TEAM: formalism of \mathcal{E}
2. unambigous data depiction: w = 1_V => \alpha = 1_D
   - changing the data should change the viz
    - data and data + 2 don't yield the same plot
   - Ziemkiewicz and Kosara injectivity: every piece of information maps to a single visual element
   - TEAM: xi: S->K (bijective?)
3. visual-data correspondance \alpha \cong \omega
    - match mathematical structure in data with that in visual perception.
    - large changes in data should yield large \varphi
    - visual affordances should match important low-level tasks
    - TEAM: \varphi commutes to ImA_{\varphi}

## notation
* symmetry: group actions; invertible transformations that when applied to each element in a set of things, map back to the same set. 
* affordances: something perceived in the environment to provide the possibility
of action (Gibson, http://cs.brown.edu/courses/cs137/2017/readings/Gibson-AFF.pdf),
