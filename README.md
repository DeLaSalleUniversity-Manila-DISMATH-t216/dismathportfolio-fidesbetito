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
<center>
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
</center>
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

##### RULES OF INFERENCE TABLE   
|  **TYPE**  |  **RULE OF INFERENCE**  |  **TAUTOLOGY**  |
| -------: | :--------------: | :--------- |
|  _Modus Ponens_  |  p, p → q ∴ q  |  (p ∧ (p → q)) → q  |
|  _Modus Tollens_  |  ¬q, p → q ∴ ¬p |  (¬q ∧ (p → q)) → ¬p  |
|  _Hypothetical Syllogism_  |  p → q, q → r ∴ p → r  |  ((p → q) ∧ (q → r)) → (p → r)  |
|  _Or Elimination_  |  p ∨ q, ¬p ∴ q  |  ((p ∨ q) ∧ ¬p) → q  |
|  _Or Introduction_  |  p ∴ p ∨ q  |  p → p ∨ q  |
|  _And Elimination_  |  p ∧ q ∴ p  |  (p ∧ q) → p  |
|  _And Introduction_  |  p, q ∴ p ∧ q  |  ((p) ∧ (q)) → (p ∧ q)  |
|  _Resolution_  |  p ∨ q, ¬p ∨ r ∴ q ∨ r  |  ((p ∨ q) ∧ (¬p ∨ r)) → q ∨ r  |

* Followed by the **General Strategies for Proving Theorems:**
</br>
    I. **DIRECT PROOF**
    - In a conditional statement where _p implies q_, assume that _p_ is true and use definitions and previously proven theorems to show that _q_ must also be true.
    - Steps:
        1. Assume _p_ is true
        2. Show that _q_ is also true
    - Example: We must prove that: If **n** is an odd integer, then **n<sup>2</sup>** is odd.
</br>
</br>
II. **PROOF BY CONTRAPOSITION**
    - Also known as _Indirect Proof_
    - We take _¬q_ as hypothesis, and using definitions, and previously proven theorems, we show that _¬p_ must follow.
    - Steps:
        1. Assume _¬q_ is true
        2. Show that  _¬p_ is also true
    - Example: Prove that if **n** is an integer and **3n+2** is odd, then **n** is odd.
</br>
</br>
III. **PROOF BY CONTRADICTION**
    - Show that assuming ¬p is true leads to contradiction.
    - ¬p ≡ T
    - Steps:
        1. Assume that the premise is not true
        2. Show that (a.) will end up in a contradiction
    - Example: Prove that **√2** is irrational by giving a proof by contradiction.
</br>
</br>
IV. **CASES**
    - Apply arguments in different cases and combine the results
    - Example: Prove that **|xy|=|x||y|.**
___

(Quiz 1)
___

###WEEK 6:

- The week was started with a seatwork to help increase the scores in the quiz.

#####FUNCTIONS
- A function from a set A to a set B assigns each element of A to exactly <u>one</u> element of B.
- If f maps element a ϵ A to element b ϵ B written as f(a) = b.
- If f(a) = b, b is called image of a; a is in preimage of b.
- <u>Range</u> or "actually occurring values" of f is the set of all images in A. 

* **TYPES OF FUNCTIONS**
    - One - to - one Function (_Injection_)</br>
        ↳ functions that never assign the same value to two different domain elements.
    - Onto Function (_Surjective_)</br>
        ↳ functions have equal range & co-domain.
    - One - to - one Correspondence (_Bijection_)</br>
        ↳ function is both one - to - one and onto.
    - Inverse Functions</br>
        ↳ Bijective function
        ↳ Onto function not an inverse

* **IMAGE**
    - If _f(a) = b_, _b- is the image of _A_.
    - The range of _f_ is the set of all images of elements of _a_.
    
* **COMPOSITION OF FUNCTIONS**
    - Let g: A → B and f: B → C
    - f(g(x))
    - inner function is first to be evaluated
* **CEILING FUNCTION**
    - largest number following a given integer
* **FLOOR FUNCTION**
    - smallest number following a given integer
___

###WEEK 7:

#####ALGORITHMS
↳ a finite set of precise instructions for performing a computation or for solving a problem.
<u>Pseudocode</u>:
    ↳ high - level desciption of an algorithm that uses the structural conventions of a programming language 
    ↳ intended for human reading</br>
    - **Preconditions** - describe valid input</br>
    - **Postconditions** - conditions that the output should satisfy</br>
    - **Generality** - applicable for all problems of the desired form</br>
    - **Finiteness** - produce the desired output</br>
    - **Correctness** - produce the correct output values</br>

* **SEARCHING ALGORITHMS** </br>
    ↳ Problem of locating an algorithm in an ordered list
    - **Binary Search** - comparing the middle values of a list then repeated until the desired output is found.
* **SORTING ALGORITHMS** </br>
    ↳ Problem of assorting elements into increasing order
    - **Bubble Sort** - compares the first two elements then interchanging them if they are in the incorrect order.
    - **Insertion Sort** - compares the second element with the first and inserts it before the first element if it is less. Otherwise, it is inserted after the first element.
* **GREEDY ALGORITHMS** </br>
    ↳ Algorithms that make what seems to be the "best" choice at each step.
    - Greedy coin algorithm
___

###WEEK 8:

#####GROWTH OF FUNCTIONS
* **Big-O Notation**
    - Let _f_ and _g_ be functions from R-R; _f(x)_ is _O(g(x))_ if there are constants _C_ and _k_ such that: </br>
        |f(x)| ≤ C|g(x)| </br>
    whenever _x > k_.
* **Big-Omega and Big-Theta Notation**
    - Big-O Notation does not provide a lowerbound for the size of f(x). </br>
        ↳ **Big-Omega** (Big-Ω) - lower bound </br>
        ↳ **Big-Theta** (Big-Θ) - both upper and lower bound
___

(Quiz 2)
___
