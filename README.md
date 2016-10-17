# dismathportfolio-fidesbetito
dismathportfolio-fidesbetito created by Classroom for GitHub

___

### Week 1:

* We were introduced to DISCRETE MATHEMATICS.
* I've learned that DISMATH deals with mathematical truth **only**.
* I learned about logical connectives and how to use them as presented in the table:

##### LOGICAL CONNECTIVES TABLE
| *Logical Symbol*  |  *Logical Operator* | *Logical Expression* | *Shorthand* | *Formula* | 
| :-----: |:-------:|:--------:| :-------: | :-----: |
| ¬ | Negation | val(¬p) = 1 - val(p) | not | ¬p |
| ∧ | Conjunction | val(p ∧ q) = min(val(p), val(q)) | and | p ∧ q |
| v | Disjunction | val(p v q) = max(val(p), val(q)) | or | p v q |
| ⊕ | Exclusive Disjunction | if val(p)  not equal val(q) = 1 , otherwise  0 | xor |  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if val(p)  ≤ val(q) = 1 , otherwise  0 | if, then | p → q ≡  ¬p v q |
| ↔ | Biconditional | if val(p) equals val(q) = 1 , otherwise  0 | iff |  p ↔ q ≡ (p → q) ∧ (q → p) |

* I learned about statement verification using TRUTH TABLES.

* I learned about IMPLICATION which can get confusing if not understood correctly.

* Lastly, I learned about PROPOSITIONAL LOGIC:
    - inverse of p→q which is ¬p → ¬q
    - converse of p→q which is q → p
    - contrapositive of p→q which is ¬q → ¬p
        NOTE: Converse and Contrapositive have the same truth table.

___

### Week 2:

* New terms were discussed:
    1. Tautology - always true
    2. Contradiction - always false
    3. Contingency - sometimes true, sometimes false

* *Question:* How can we prove that a propositional formula is a tautology?
    - Truth Table
    - Equivalence
    
* We were introduced to **LOGICAL EQUIVALENCES**:

##### LOGICAL EQUIVALENCES AND PROOF BY TRUTH TABLE
|  **LAW**  |  **EQUIVALENCE**  |
| :------: | :-----------------------------: |
|  _Identity Laws_  |  p ∨ F ≡ T  <br>  p ∧ F ≡ T  |
|  _Domination Laws_  |  p ∨ T ≡ T  <br>  p ∧ F ≡ F  |
|  _Negation Laws_  |  p ∨ ¬p ≡ T  <br>  p ∧ ¬p ≡ F  |
|  _Double Negation Law_  |  ¬(¬p) ≡ p  |
|  _Idempotent Laws_  |  p ∨ p ≡ p  <br>  p ∧ p ≡ p  |
| _Distributive Laws_  |  p ∨ (q ∧ r) ≡ (p ∨ q) ∧ (p ∨ r)  <br>  p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (p ∧ r)  |
|  _Commutative Laws_  |  p ∨ q ≡ q ∨ p  <br>  p ∧ q ≡ q ∧ p  |
|  _Associative Laws_  |  (p ∨ q) ∨ r ≡ p ∨ (q ∨ r)  <br>  (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)  |
|  _De Morgan's Laws_  |  ¬(p ∧ q) ≡ ¬p ∨ ¬q  <br>  ¬(p ∨ q) ≡ ¬p ∧ ¬q  |
|  _Absorption Laws_  |  p ∨ (p ∧ q) ≡ p  <br>  p ∧ (p ∨ q) ≡ p  |

* Formula is:</br>
    - Satisfiable: <u>there exists</u> a row where formula evaluates to true</br>
    - Unsatisfiable: all rows evaluates to false</br>
    - Contingent: there is a row evaluating to true; there is a row evaluating to false</br>
    - Valid: true <u>for all</u> rows</br>
        </br>*Note:* the terms above can be used beyond propositional logic 

___

### Week 4:

* We did more practice on logical equivalences
* We translated English statements to logical expressions
* We were introduced to **FIRST-ORDER LOGIC**
    > allows representation of more complex facts and making more sophisticated inferences
   > *Predicate Logic*
    

___

### Week 4:

* After reviewing First-Order Logic, we moved on to **Quantifiers**:</br>
    1. Universal Quantifier: "Ɐ" - <u>all</u> objects</br>
    2. Existential Quantifier: "Ǝ" - <u>some</u> objects

* We were told to review basic algebra terms as it is useful in this subject.

* **Direct Proof** was also introduced in order to prove the FOL.
    > p → q

* We also practiced on the translation of English text to *Quantified Formula*
___

### Week 5:

* We started the week by discussing the **Rules of Inference:**
