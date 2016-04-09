# dismathportfolio-trishadevera
dismathportfolio-trishadevera created by Classroom for GitHub

# DISMATH PORTFOLIO

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
The lesson on proof by equivalence was continued and biconditional statements were given as examples. Mathematical Induction was also introduced. The first step was the basis step, which is to show  that P(1) or P(0) is true. The second step is using direct proof, which is don by assuming that P(k) is true and showing that P(k+1) is true. Recursion was also introduced. The steps done for recursion consists of the basis step, which is specifying the value of a function at zero, and the recursive step, which is giving a rule for finding its value at an integer from its values at smaller integers. Examples were given and one of them is this: Given f(0)=3 and a function rule f(n+1)=2f(n)+3, find f(1), f(2), and f(3). The answers were obtained by substituting f(0)=3 to to n and obtaining f(1) and using the answer to get f(2) and so on. Another topic introduced in this week was recursive algorithm. It is similar to recursion but integrated to a program. Program correctness and partial correctness were also discussed. There were both programs used to confirm that the final assertion is valid. Power series was also included in this week's lessons. It was based on geometric series but the equation is f(x)=1/(1-x)

# Week 7
This week, Introduction to Set Theory was the lesson. I learned about the definition of set, which is an unordered collection of distinct objects. This means that the order of elements in a set does not matter as long as they are the same elements. I also learned about set bulder notation which is definition for set that uses symbols. I learned that a union of two sets A and B (A U B) is all the elements of A and B combined and their intersection (A∩B) is the element/s which is/are common to A and B. Power Set was also introduced and it is the set of all subsets. To get the cardinality of subsets in a set is given by: 2^n, where n is the number of elements. 

# Week 8
The lesson for this week was about the function. I learned that there are three elements in a function which are known as the domain, codomain, and range. Domain is/are given values in a function. Codomain can also be given values but can also be values which are assigned or paired to the domain. Range are actually occuring/assigned values for the domain. I also leanrend that there are different types of function. The first one is the One-to-One function (Injective). It is a function that never assign the same value to two different domain elements. Ex. (a,b), (c,d), (e,f). The next type is the onto function which has equal range and codomain. Ex. (1,3),  (2,4), (2,5). The next type is the One-to-One correspondence (Bijection). It is a function that is both one-to-one and onto. Ex. (5,6), (7,8), (9,10). (NOTE: Not all one-to-one is onto and not all onto is one-to-one.) Furthermore, I learned that y=√x is not a function because it gives two domain for just one range but y=sqrt (x) in programming is a function because it is limited to positive integers. Another lesson discussed in this week was about the Algorithm which is a finite set of precise instructions for performing a computation that is similar to programming.

# Week 9
In this week, one of the topics was about Binary Search Algorithm. It is a search for a certain location of a value from a list of elements arranged in ascending order. One of the ways to write its algorithm is this:

Procedure: Binary Search(
Input: x-searched element
       {a1, a2, ..., ai, ..., an}
Output: location, loc)
i=1;
j=n;

while(i<j){
  mid=[(i+j)/2]
  if(x>amid)
    i=mid+1;
  else
    j=mid;
    }
if x=a, then loc=i
else loc=-1

The algorithm means that the first thing to do is compare the first (i) and last element (j). While the first element is less than the last, the assignment for middle term is the sum of the first and last element divided by 2 which is covered by the while loop. Still included in the while loop is the if-else statement which suggests that if the element searched (x) is greater than the current middle term, "i" will be updated, the comparison will go on, and mid will also be updated but when x is greater than the current middle term,j will be updated. The termination will be done when process stop satisfying the while loop. 

Another lesson in this week was about the sorting algorithm. The first kind is called the bubble sort and the second one is the insertion sort. I also learned about greedy algorithm and growth of functions. Greedy Algorithm can be used to compute the minimum number of coins that can be used to attain certain amount of money. 

# Week 10
The continuation for the lesson on Growth of Functions was continued this week. I learned about Big-O, Big-Omega, and Big-Theta Notations. A big-o of a certain function means that is is an upper bound of another function. For example, the statement "x^2+2x+1 is O(x^2)" states that the function x^2 is an upper bound of x^2+2x+1. This can be proven by providing witnesses "c" and "k" such that f(x)=x^2+2x+1 <= C[g(x)=x^2] whenever x>k. On the other hand, Big-Omega (Ω) is the reverse of Big-O, which means that f(x) >= Cg(x) whenever x>k. Big Theta is the combination of the two first notations. A certain function f(x) is θ[g(x)] when there are witnesses c and k such that f(x) is both O[g(x)] and Ω[g(x)]. 

The next lesson was about Algorithm Time Complexity which is denoted by the table below                                               
| Complexity  |   Terminology  |
|:-----------:|:--------------:|
| (1) | Constant  complexity  |
| (log n) | Logarithmic complexity |
| (n) | Linear complexity |
| (n log n) | Linearithmic complexity |
| (n^b) | Polynomial complexity |
| (b^n), where b > 1 | Exponential complexity |
| (n!) | Factorial complexity |

Determining the complexity of an algorithm is first done by counting the number of comparisons in the program in terms of "n". Comparisons on each loop are assigned as "n" and the other comparisons are just additions. After determining the number of comparisons, we can now determine the complexity. 
The lessons for this week also include Division and Modulo Operator and Cryptology. Division operator is denoted by the statement  "q=a div d" where a is the dividend, d is the divisor, and q is the quotient. Modulo operator is the statement "r=a mod d" a is the dividend, d is the divisor, and r is the remainder. You can use these two equations to determine the missing element. The last lesson this week, which is Cryptology, is the study of secret messages. The class discussed on of the methods called Caesar Cipher that is made by shifting each letter, three letters forward in the alphabet. Example: The word "MATH" would become "PDWK". However, when the letter is "Z", there would be no letter after it which means we would be using modulo operaor to determine the equivalnt letter of "Z". Since "Z" is the 25th letter, we would add 3 which would be equal to 28 and we could use 28 mod 26=2 to determine the letter. The equivalent Caesar Cipher for "Z" is "C" because, A=0, B=1, C=2.

# Week 11
In this week, our lesson was all about graph theory. The graphs being discussed in this lesson are discrete structures consisting of vertices and edges that connect these vertices such that G=(V,E) where V consists of non-empty set of vertices and E consists of edges. Each edge has either one or two vertices associated with it, called end points. I also learned about the degree of a vertex. It is the number of edges incident with the vertex and a loop in a vertex contributes twice to its degree. 

Another topic discussed is called Handshaking Theorem. If you are given the number of vertices and their degrees respectively, you can get the number of edges by the formula 2e=Σ deg(v), where "e" is the number of edges and Σ deg(v) is the sum of the degrees of the vertices. Subgraph was also part of this week's lessons. It is similar to subset where there are graphs belongin to a bigger graph.

I also learned about paths and circuits. Path is a sequence of edges that begins at a vertex and travels from vertex to vertex along edges of the graph. A circuit is a also a similar to a path it has to go back to the vertex where it started. I learned about the types of circuit and path. Euler circuit is a circuit that travels to every edge of the graph only once. A graph also has an Euler circuit if every node of the graph has even degrees. An Euler path is a path which, like the Euler circuit, passes every edge of the graph only once. It can be determined by having exactly two nodes with odd degrees. Another type of circuit and path is called the Hamilton. A Hamilton circuit is a circuit that passes all the vertices of a graph only once and the Hamilton path is similar to it but it is just a path.

Adjacency matrix was also part of the discussion this week. It is a matrix of the connection between two vertices which totals the number of the connections between two vertices. Another topic was about Isomorphism between graphs. Isomorphism states that if two graphs have the same nodes, same connections, and same adjacency matrix, and form, they are said to be isomorphic. It means that if you could identify the vertices of a graph which are equivalent to the vertices of another graph, then the graphs are isomorphic. I also learned about planar graphs. These are graphs that can be drawn on a plane without the edges intersecting and without deleting of adding nodes or changing the connections. This topic is associated with Kuratowski's theorem which can identify non-planar graphs if they contain a subgraph which is homeomorphic to K3,3 or K3,4 or K5 and many more. The last lesson for this week was about Euler's formula. It is a formula for calculating the regions of a graph, given the number of edges and vertices. The formula is r=e-v+2.

# Week 12
This week, I learned about graph coloring. This topic is about the assignment of a color to each vertx of a graph so that no two adjacent vertices are assigned the same color. I also learned that the chromatic number of a graph is the least number of colors needed to color a graph denoted by x(G). Another lesson discussed is the four color theorem which states that the chromatic number of a planar graph is no greater than four, which means that the maximum chromatic number of a planar graph is four. I also learned about cycles which is a planar 2-D graph that loops back to its starting point by going around the edges. A cycle's with even number of edges has a chromatic number of 2 and the odd number of edges has 3 as its chromatic number. The topic about trees was also discussed. 
I learned that a tree is a connected undirected graph with no simple circuit. A rooted tree is a tree which one vertex has been designated as the root and every edge is directed away from the root. A subtree was also dicussed which is similar to subset and subgraph. I also learned about M-ary tree, which is a tree with every internal vertex has no more than m children. Internal vertices are nodes from a root which has another edge below connected to them, which is called the child/children. A full m-ary tree has internal vertex/vertices that has exactly m children. The edges with no children are called leaves. An ordered rooted tree is a tree with the children of every internal vertex are ordered. The last topic about tree is its properties. I learned that a tree with n vertices has n-1 degrees.

- **Modeling Computation
  - Structures in Models of Computations:
    - Grammars
    - Finite-state machine
    - Turing Machine
- **Language Grammars**
  - *Grammars* 
    - Generate the words of a language and determine whether a word is in a language
    - Important in constructing a sentence and compiling a program
- **Formal Language** 
  - Generated by grammars, provide models for both natural languages (English and the like) and programming language (Java, C++, etc.).
  - Concerned of the syntax and semantics.
- **Automata Theory**
  - Laws of computation.
  - Finite Automation - Simplest model of a computing device.
    - Initial state
    - Final/acceptance state
    - Dead/stuck state
    - Transition
- **Finite-State Machines with Output**: M = (S, I, O, f, g, s<sub>0</sub>) 
  - S: Finite set of states
  - I: Finite input alphabet
  - O: Finite output alphabet
  - f: Transition function
  - g: Output function
  - s<sub>0</sub>: Initial state
  - Ex. A vending machine
