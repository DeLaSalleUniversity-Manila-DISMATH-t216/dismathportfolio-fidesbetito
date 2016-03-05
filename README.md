# dismathportfolio-fidesbetito
dismathportfolio-fidesbetito created by Classroom for GitHub

___

### Week 1:

* We were introduced to a new subject called, DISCRETE MATHEMATICS or DISMATH.
* This subject soon proved to be really challenging if it was not taken seriously when studying.
* I've learned that DISMATH deals with mathematical truth **only**.

* I learned about logical connectives as presented in the table:

##### LOGICAL CONNECTIVES TABLE
| *Logical Symbol*  |  *Logical Operator* | *Logical Expression* | *Shorthand* | *Formula* | 
| :-----: |:-------:|:--------:| :-------: | :-----: |
| ¬ | Negation | val(¬p) = 1 - val(p) | not | ¬p |
| ∧ | Conjunction | val(p ∧ q) = min(val(p), val(q)) | and | p ∧ q |
| v | Disjunction | val(p v q) = max(val(p), val(q)) | or | p v q |
| ⊕ | Exclusive Disjunction | if val(p)  not equal val(q) = 1 , otherwise  0 | xor |  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if val(p)  ≤ val(q) = 1 , otherwise  0 | if, then | p → q ≡  ¬p v q |
| ↔ | Biconditional | if val(p) equals val(q) = 1 , otherwise  0 | iff |  p ↔ q ≡ (p → q) ∧ (q → p) |

* I learned how to test the verification of a statement by using TRUTH TABLES.

* I learned about IMPLICATION which gets confusing as more complicated expressions were presented.

* Lastly, I learned about PROPOSITIONAL LOGIC such as:
    - inverse of p→q which is ¬p → ¬q
    - converse of p→q which is q → p
    - contrapositive of p→q which is ¬q → ¬p

___

### Week 2:

* In this week, we were introduced to a new set of laws in mathematics called **LOGICAL EQUIVALENCES**:

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

* Using logic, we were able to conclude that Superman does not exist!

* We were also able to prove that **p → q ≡ ¬p ∨ q** using a Truth Table and Logical Equivalences. 

* **Predicate Logic**, much like in the English language, is not only concerned with its relation to logic but also with their internal structure in terms of subject and predicate.
* **Propositional Logic** deals with propositions, _subject and predicate_, as a whole.
* **Quantifiers** indicate the generality of the open sentence in which a variable occurs.
    - Existential Quantifier - "there exists" - if and only if P(x) is true for at least one value of x in the domain.
    - Universal Quantifier - "then exists" - many mathematical statements assert that a property is true for all values of a variable in a particular domain.

___

### Week 3:

* The terminologies for **Rules of Inference** were introduced:
    - _Argument_ is a series of statements that end with a conclusion.
    - _Valid_ is the conclusion which must follow from the truth of the preceding statements or premises of the argument.
    - _Fallacy_ is the common form of incorrect reasoning which leads to invalid arguments. 

* The tools that can be used to prove statements are:
    - Truth table
    - Logical Equivalences
    - Quantifiers
    - Rules of Inference
 
##### RULES OF INFERENCE TABLE   
|  **TYPE**  |  **RULE OF INFERENCE**  |  **TAUTOLOGY**  |
| -------: | :--------------: | :--------- |
|  _Modus Ponens_  |  p, p → q ∴ q  |  (p ∧ (p → q)) → q  |
|  _Modus Tollens_  |  ¬q, p → q ∴ ¬p |  (¬q ∧ (p → q)) → ¬p  |
|  _Hypothetical Syllogism_  |  p → q, q → r ∴ p → r  |  ((p → q) ∧ (q → r)) → (p → r)  |
|  _Disjunctive Syllogism_  |  p ∨ q, ¬p ∴ q  |  ((p ∨ q) ∧ ¬p) → q  |
|  _Addition_  |  p ∴ p ∨ q  |  p → p ∨ q  |
|  _Simplification_  |  p ∧ q ∴ p  |  (p ∧ q) → p  |
|  _Conjunction_  |  p, q ∴ p ∧ q  |  ((p) ∧ (q)) → (p ∧ q)  |
|  _Resolution_  |  p ∨ q, ¬p ∨ r ∴ q ∨ r  |  ((p ∨ q) ∧ (¬p ∨ r)) → q ∨ r  |

* We also started with the **METHODS OF PROOF**.
    - Why study methods of proof?
        1. Software - debug a program beyond a doubt
        2. Hardware - useful in debug before pre-production hardware

* **DIRECT PROOF**
    - In a conditional statement where _p implies q_, assume that _p_ is true and use definitions and previously proven theorems to show that _q_ must also be true.
    - Steps:
        1. Assume _p_ is true
        2. Show that _q_ is also true
    - Example: We must prove that: If **n** is an odd integer, then **n<sup>2</sup>** is odd.

___

### Week 4:

* We continue with Methods of Proof

* **PROOF BY CONTRAPOSITION**
    - Also known as _Indirect Proof_
    - We take _¬q_ as hypothesis, and using definitions, and previously proven theorems, we show that _¬p_ must follow.
    - Steps:
        1. Assume _¬q_ is true
        2. Show that  _¬p_ is also true
    - Example: Prove that if **n** is an integer and **3n+2** is odd, then **n** is odd.

* **VACUOUS AND TRIVIAL PROOF**
    - _Vacuous Proof_
        - Show that _p_ is false, because _p → q_ must be true when _p_ is false.
        - ¬p → (p → q)
    - _Trivial Proof_
        - Show that _q_ is true, it follows that _p → q_ must also be true.
        - q → (p → q)
    
    - Two exercises were solved in this topic:
        - If there are **30** students in this course this semester, then **6<sup>2</sup> = 36**.
            - TRIVIAL
        - If **6** is a prime number, then **6<sup>2</sup>=30**.
            - VACUOUS
        
* **PROOF BY CONTRADICTION**
    - Show that assuming ¬p is true leads to contradiction.
    - ¬p ≡ T
    - Steps:
        1. Assume that the premise is not true
        2. Show that (a.) will end up in a contradiction
    - Example: Prove that **√2** is irrational by giving a proof by contradiction.

* **RATIONAL NUMBER**
    - If _r_ is rational, _r_ can be written as _p/q_ where _q ≠ 0_ and where _p_ and _q_ have no common factors other than +1 and -1.
    - Steps:
        1. Assume that the premise is true
        2. Show that (a.) ends up in contradiction
    - Example: Give a proof by contradiction of the theorem "If **3n+2** is odd, then **n** is odd."
        - This example almost took up the whole class time because of how confused we got about the problem!

* **NEGATION OF IMPLICATION**
    - The negation of the statement "If _p_ is true, then _q_ is true" is the statement "There is at least one case where _p_ is true and _q_ is false."

* **CONTRADICTIONS AND IMPLICATIONS**
    - "If _p_ is true, then _q_ is true" must be proved using contradiction.
    - Steps:
        - Assume that _p_ is true and _q_ is false
        - Derive a contradiction
        - Conclude that if _p_ is true, then _q_ must be as well

* **PROOF BY EQUIVALENCE (Biconditionals)**
    - To prove a theorem that is a biconditional statement, _p ↔ q_, we show that _p → q_ and _q → p_ are both true.
    - Example: If **n** is an integer, **n** is even if and only if **n<sup>2</sup>** is even.
        - We are given this: _r → s_
            - We must show that both _r_ and _s_ are even.

___

### Week 5:

- For week 5, we only had one meeting due to the cancellation of classes last Monday in celebration of Chinese New year.
- For the only class we had this week, we solved more problems:
    - If _n_ is a positive integer, then _n_ is odd if and only if _n<sup>2</sup>_ is odd.
    - For any natural number _n_, _n_ is even if and only if _n<sup>2</sup>_ is even.
    - Show that these statements about the integer _n_ are equivalent:
        - P1: _n_ is even
        - P2: _n-1_ is odd
        - P2: _n<sup>2</sup>_ is even
    - Prove or disprove the following theorem: 
        - Every positive integer is the sum os the squares of two integers
    
* **MATHEMATICAL INDUCTION**
    - We are given a sequence of propositions that we would like to prove.
    - The sequence:
        - _P(1) P(2) P(3) P(k) P(k+1)_
    - Steps:
        1. Basis step: _P(1)_ is shown to be true
        2. Do the inductive step:
            "If _P(k+1)_ is true whenever _P(k)_ is true, then _P_ is true for all positive integer."
    - Example: Prove _P(n) = 1 + 2 + 3 + ... + n = n(n+1)/2_
___

### Week 6:

* **SUMMATION**
    - The notation for sum of _a<sub>m</sub>, a<sub>m+1</sub>, ..., a<sub>n</sub>_ is _∑<sup>a</sup><sub>i=m </sub>a<sub>i</sub>_ where _i_ is the index of summation.
    - Example: ∑<sup>a</sup><sub>i=m </sub> = 1 + 2 + 3 + ... + n
    - We also proved the theorem: The sum of the first n powers of two is _2<sup>n</sup>-1_.

* **RECURSIVE/INDUCTIVE DEFINITION**
    - Basis step: Specify the value of the function at zero
    - Recursive step: Give a rule for finding its value at an integer from its values at smaller integers
    - Example: Find _f(1), f(2), f(3), f(4)_ of the following recursive function.

* **RECURSIVE ALGORITHMS**
    - It solves a problem by reducing it to an instance of the same problem with smaller input.
        - Recall: <u>Algorithm</u> - finite set of precise instructions for performing a computation/solving a problem.
    - Examples:
        - What is the recursive algorithm _n!_?
        - Give a recursive algorithm for computing _a<sup>n</sup>_, where _a_ is a nonzero real number and _n_ is a nonnegative integer.

* **PROGRAM CORRECTNESS**
    - We need a proof to show that the program always gives the correct output.
        - PROGRAM VERIFICATION
            - Proof of correctness of programs
            - Uses the rules of inference and various proof techniques including mathematical induction
            - It is said to be correct if it produces the correct output for every possible input:
                1. Show that the correct answer is obtained if the program terminates (Partial Correctness)
                2. Show that the program always terminates
        - PARTIAL CORRECTNESS
            - Two propositions are used to specify what it means for a program to produce the correct output:
                1. Initial Assertion - _p_ - gives the properties that the input values must have
                2. Final Assertion - _q_ - gives the properties that the output of the program should have, if the program did what it was told

* **HOARE TRIPLE**
    - p{s}q
    - A program, _S_, is said to be partially correct with respect to the initial assertion _p_ and the final assertion _q_ if whenever _p_ is true for the input values of _S_ and _S_ terminates, then _q_ is true for the output values of _S_.
    - Example: Given the initial assertion _p: x=1_ and the final assertion _q: z=3_, show the partial correctness of the program segment: </br> y = 2 </br> z = x + y

* **RULES OF INFERENCE**
    - CONDITIONAL STATEMENTS </br>
        (p ∧ _condition_) {S} q </br>
        (p ∧ _¬condition_) → q </br>
        ∴ p {**if** _condition_ **then** _S_} q
        - Example: Verify that the following program segment is correct with respect to the initial assertion _T_ and the final assertion _y ≥ x_. </br>
            **if** _x>y_ **then** </br>
            _y=x_
    - IF-ELSE STATEMENT </br>
        (p ∧ _condition_) {S<sub>1</sub>} q </br>
        (p ∧ _¬condition_) {S<sub>2</sub>} q </br>
        ∴ p {*if* _condition_ *then* _S<sub>1</sub>_ *else* _S<sub>2</sub>_} q
        - Example: **if** _x<0_ **then** </br> _abs= -x_ </br> **else** </br> _abs = x_

* **POWER SERIES**
    - ∑<sup>∞</sup><sub>n = 0</sub> a<sub>n</sub>x<sup>n</sup> </br>
        where _a<sub>0</sub>, a<sub>1</sub>, a<sub>2</sub>, ..._ is a given sequence of constants, and _x_ is a real variable.
    - Examples:
        - 1 + r + r<sup>2</sup> + r<sup>3</sup> + ... = 1/(1-r)
        - Represent as power series: 1/(1+x)
        - Find the corresponding function: 1 - x<sup>2</sup> + x<sup>4</sup> - x<sup>6</sup> + ... 

___

**QUIZ 1**

___

### Week 7:

* **INTRODUCTION TO SET THEORY**
    - A _set_ is an unordered collection of distinct objects, which may be anything (including other sets).
        - {a,b,c,d,e}
        </br>    ↳ *Set Notation:* curly braces with commas separating out the elements 
* **Empty Set**
</br>   ↳ { } = ∅
    - no elements
    * **Set Builder Notation**
    </br>    ↳ {x | some property x satisfies}
* **Venn Diagrams**
    - A 
        </br>![Screenshot](https://github.com/DeLaSalleUniversity-Manila-DISMATH-t216/dismathportfolio-fidesbetito/blob/master/Screen.Shot.2016-03-05.at.19.55.55.png)
    - B
        </br>![Screenshot](https://github.com/DeLaSalleUniversity-Manila-DISMATH-t216/dismathportfolio-fidesbetito/blob/master/Screen.Shot.2016-03-05.at.19.56.06.png)
    - UNION
        - A ⋃ B ≡ (x ∈ A) ∧ (x ∈ B)
        </br>![Screenshot](https://github.com/DeLaSalleUniversity-Manila-DISMATH-t216/dismathportfolio-fidesbetito/blob/master/Screen.Shot.2016-03-05.at.19.56.24.png)
    - INTERSECTION
        - A ⋂ B ≡ (x ∈ A) ∨ (x ∈ B)
        </br>![Screenshot](https://github.com/DeLaSalleUniversity-Manila-DISMATH-t216/dismathportfolio-fidesbetito/blob/master/Screen.Shot.2016-03-05.at.19.56.51.png)
    - DIFFERENCE
        - A - B
        </br>![Screenshot](https://github.com/DeLaSalleUniversity-Manila-DISMATH-t216/dismathportfolio-fidesbetito/blob/master/Screen.Shot.2016-03-05.at.19.57.20.png)
    - DIFFERENCE
        - A \ B ≡ (x ∈ A) ∧ (x ∉ B)
        </br>![Screenshot](https://github.com/DeLaSalleUniversity-Manila-DISMATH-t216/dismathportfolio-fidesbetito/blob/master/Screen.Shot.2016-03-05.at.19.57.33.png)
    - SYMMETRIC DIFFERENCE
        - A ∆ B ≡ {x | (x ∈ A) ∧ (x ∉ B) ∨ (x ∈ B) ∧ (x ∉ A)}
        </br>![Screenshot](https://github.com/DeLaSalleUniversity-Manila-DISMATH-t216/dismathportfolio-fidesbetito/blob/master/Screen.Shot.2016-03-05.at.19.57.48.png)

* **SET IDENTITIES**
    - Very similar to logical equivalences
|  **LAW**  |  **EQUIVALENCE**  |
| :------: | :-----------------------------: |
|  _Identity Laws_  |  A ∩ U ≡ A  <br>  A ∪ ∅ ≡ A  |
|  _Domination Laws_  |  A ∪ U ≡ U  <br>  A ∩ ∅ ≡ ∅  |
|  _Idempotent Laws_  |  A ∪ A ≡ A  <br>  A ∩ A ≡ A  |
|  _Complementation Law_  |  (A¯) ≡ A  |
|  _Double Negation Law_  |  ¬(¬p) ≡ p  |
| _Distributive Laws_  |  p ∨ (q ∧ r) ≡ (p ∨ q) ∧ (p ∨ r)  <br>  p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (p ∧ r)  |
|  _Commutative Laws_  |  p ∨ q ≡ q ∨ p  <br>  p ∧ q ≡ q ∧ p  |
|  _Associative Laws_  |  (p ∨ q) ∨ r ≡ p ∨ (q ∨ r)  <br>  (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)  |
|  _De Morgan's Laws_  |  ¬(p ∧ q) ≡ ¬p ∨ ¬q  <br>  ¬(p ∨ q) ≡ ¬p ∧ ¬q  |
|  _Absorption Laws_  |  p ∨ (p ∧ q) ≡ p  <br>  p ∧ (p ∨ q) ≡ p  |
