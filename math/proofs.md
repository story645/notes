classical mathemathical texts:
* start w/ definitions and axioms, then produce statements, then proofs from your statements
    - axioms are information that is taken for granted
        - reasonable axioms are self-evidently true
            ex: there is a thing we call point, and between two points there is a thing called line (Euclid's geometry)
            ex: set of axioms to describe what it means for something to be a vector space
        - if we have an object for which the axioms are true then we have an object
        - properties/traits/constraints of a thing
            - groups and monoids are structures w/ multiplication map and identity, conditions operations meets determines membership
            - sets of axioms declare the interface for objects in math
                - how we can interact with things and what needs to exist for interaction to be valid
        - establish rules of doing a particular types of mathematics
    - definitions are statements that create new constructs
        - give a name to something
            - ex: define an object line w/ the set of axioms/properties needed for it to be line
            - variable assigment for mathematical writing
    - statements are claims that can have a truth value
        - ex: the intersection of 2 open sets in a topology is a topology (axiom and statement)
        - ex: collection of open intervals on the real line intersect on an open interval
            - statement, has a truth value
            - not an axiom b/c not clear beyond any additional explanation (would likely need a proof)
* proposition, theorem, lemma
    - statements followed by proof of statements
    - distinctions are in how they are meant to be used (generally blurred)
        - many famous lemmas really have statute of theorem
    - theorem: generally a proven claim that can be reused in other works
        - akin to a user facing function in a software library
    - proposition and lemmas
        - less important than theorems
            - more like private functions
    - proposition: value neutral proven claim
    - lemma: more technical proposition
        - typically used to package up parts of a proof into a reusable box
        - common way to refactor a proof is to extract the repeated structures into a lemma
         - akin to utility functions for housekeeping
* proof
    - sequence of statements, where each statement is either:
        - an implication "if then" or an equivalence "if and only if then"
        - serve to setup a chain of implications
    - ex: if v is a vector space, then v has a dimension
        - if v is a vector space: definition of a vector space which would include axioms of a vector space
            - prove w/ a sequence of steps where each step is clearly and obviously true
                - here have to show what it is about a vector space that means there has to be a dimension
    - any axiom that is pulled in by the premises, you can call on to take a step that is clearly true
    - any other theorem/statement/propostion/lemma that has been proven true can be used as step in the proof
        - akin to calling a function
    - proof tends to occupy a similar role in mathematical statements as functions bodys in programming
        - akin to an essay  - what's being proven is the topic sentence, steps are supporting sentences
        - logic proofs: start w/ implication, then stack together propositions to prove implication
* proof structures
    - proof by contradiction: start w/ assuming thing is false, then show how that's impossible cause leads to contradiction
    - proof by induction: axiomitize the natrual numbers
        - natural numbers has a lowest numbers + every number has one larger
        - proof that a parameterized statement holds for all numbers by mapping into start + next step
        - used for recursion b/c same (dual) structure
    - pigeonhole principal: often gets packaged inside relatively fundemental results where usually folks use the intermediate results
        - ex: map from a higher dimensional space to a lower dimensional space can't be linear and 1 to 1 (injective)
            - once proven, claim that can't be linear and 1 to 1" becomes the proposition/lemma/theorem that gets used

* constructive vs non-constructive
    * proof by construction: $new_number = \product(primes) + 1$
        - says finite list of primes is not finite
        - claim only primes are 3 and 5, (3*5 + 1) = 16
            - status of 16 is unknown currently, makes proof non-constructive
            - creating a thing that has properties that contradict our assertion
            - not creating what we asserted was there
    * many non-constructive proofs are proof by contradiction,
    * core of intiutionist logic: don't allow the removal of a double negation (modal logic)
    * classical logic -> true or false, prove not false $\implies$ true
        * mathematical philosophers don't like it b/c
    * non-constructive proofs don't help you with computation
        - claiming a thing exists but up to you to find it
        - starting w/ algorithms and explicit construction
            - constructivist logic, nothing exists w/o an algorithm to create it
            -
