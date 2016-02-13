# dismathportfolio-trishadevera
dismathportfolio-trishadevera created by Classroom for GitHub

# Week 1
In this week, I was introduced to logic and proofs. I learned that a proposition is a statement or a declarative sentence that is either true or false, but not both. I also learned about the different logical connectives such as Negation, Conjunction, Disjunction, Exclusive Or, Conditional, and Biconditional and their corresponding symbol and usage which are shown on the table below:

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |

Furthermore, I also acquired information about how these operators are used in statements. Moreover, truth tables were taught on this same week. I learned that they can be used to prove the equivalence of two or more logical expressions. Also, I was introduced to conditional statements such as converse, contrapositive, and inverse.

# Week 2
This week, I was introduced to the idea og Logical Equivalences. I learned that compound propositions that have the same truth values in all cases are logically equivalent. Furthermore, I learned that logical expressions can be proven, not only by truth values, but also by logical equivalences namely, Identity, Domination, Idempotent, Double negation, Commutative, Associative, Distributive, De Morgan's, Absorption, and Negations laws which are tabulated below:

|                           Equivalence                           |         Name        |
|:-------------------------------------------------------------:  |:-------------------:|
|                      p ∧ T ≡ p <br> p v F ≡ p                   |    Identity laws    |
|                       p v T ≡ T <br> p ∧ F ≡ F                  |   Domination laws   |
|                       p v p ≡ p <br> p ∧ p ≡ p                  |   Idempotent laws   |
|                            ¬(¬p) ≡ p                            | Double negation law |
|                   p v q ≡ q v p <br> p ∧ q ≡ q ∧ p              |   Commutative laws  |
|       (p v q) v r ≡ p v (q v r) <br> (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)  |   Associative laws  |
| p v (q ∧ r) ≡ (p v q) ∧ (p v r) <br>  p ∧(q v r) ≡ (p ∧ q) v (p ∧ r) |  Distributive laws  |
|              ¬(p ∧ q) ≡ ¬p v ¬q <br> ¬(p v q) ≡ ¬p ∧ ¬q          |   De Morgan's laws  |
|                 p v (p ∧ q) ≡ p <br> p ∧ (p v q) ≡ p             |   Absorption laws   |
|                     p v ¬p ≡ T <br> p ∧ ¬p ≡ F                   |    Negation laws    |

I also learned that, sometimes, they are more convenient to use rather than truth tables in terms of proving equivalences. Predicate logic was introduced which gave me an idea about it being similar to the english language of subject and predicate but instead of just looking at the grammar, we would look at the logic of the statement and use the subject and predicate as functions and translate them to equations. I was also introduced to quantifiers such as Universal, meaning a property is true for all values of a variable in a domain, and Existensial, meaning a property is true if and only if P(x) is true for at least one value of x. 
Superman Homework on rules of inference was also learned by the class before the topic was even discussed.

# Week 3
The topics for this week were about the argument, rules of inference, and methods of proof. I learned that an argument, in discrete mathematics, is a sequence of statements which ends with a conclusion. I also learned that it can be classified as valid if the conclusion of an argument follows from the truth of the preceding premises. On the other hand, an argument which is classified as a fallacy has a contradicting premise and conclusion. I learned that to classify an argument as valid or invalid, we could use the rules of inference by applying them to each premise of an argument and arriving at an answer. These rules are can be better understood and shown on the table: 

|   Rule of Inference       |            Tautology           |          Name          |
|:--------------------:     |:------------------------------:|:----------------------:|
|       p<br>p→q<br>∴q      |        (p ∧ (p → q)) → q       |      Modus ponens      |
|     ¬q<br>p→q<br>∴ ¬p     |       (¬q ∧ (p → q)) → ¬p      |      Modus tollens     |
|     p→q<br>q→r<br>∴p→r    |  ((p → q) ∧ (q → r)) → (p → r) | Hypothetical syllogism |
|      p∨q<br>¬p<br>∴q      |       ((p ∨ q) ∧ ¬p) → q       |  Disjunctive syllogism |
|       p<br>∴p ∨ q         |           p → (p ∨ q)          |        Addition        |
|       p ∧ q<br>∴p         |           (p ∧ q) → p          |      Simplication      |
|      p<br>q<br>∴p ∧ q     |      ((p) ∧ (q)) → (p ∧ q)     |       Conjunction      |
| p ∨ q<br>¬p ∨ r<br>∴q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |       Resolution       |

I also learned about the methods of proofs such as direct. A direct proof is a proof wherein one should assume that the antecedent, p, in the conditional statement, p → q, as true and then later on, show that q, which is the consequence, is true. 

# Week 4
In this week, the methods of constructing proofs are continued. Proof by contraposition is done by assuming that ¬q is true and showing that ¬p is also true. Vacuous proof means that ¬p → (p → q) while trivial means that q → (p → q). Another method of proof is the proof by contradiction which is done by assuming that ¬(premise) is true which will be equivalent to p ∧ ¬q and showing that there is a contradiction.

# Week 5
This week, we continued the lesson about contradiction. In class, we proved the statement "√2 is irrational." by contradiction. Also, I learned another example statement which can be proven by contraposition. This statement is "If a^2 is even, thena is also even." Furthermore, there were more examples on proof by contradiction and contraposition. I also learned another form of proof, which is the proof by equivalence. The example conditional statement was r ↔ s, "n is even iff n^2 is even." It was done by proving that r → s, "If n is even, then n^2 is also even." and s → r, "If n^2 is even, then n is also even.". r → s was proved by direct proof and s → r was proved by contraposition. Both of these processes were proofs of r ↔ s.

# Week 6
The lesson on proof by equivalence was continued and biconditional statements were given as examples. Mathematical Induction was also introduced. The first step was the basis step, which is to show  that P(1) or P(0) is true. The second step is using direct proof.
