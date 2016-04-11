# dismathportfolio-JerichoL
dismathportfolio-JerichoL created by Classroom for GitHub

# Week 1
- I was introduced to a really interesting but rather weeeiiirrddd topic based on mathematics called Discrete Mathermatics (DISMATH)
- I understood what the basics of Discrete Mathematics was all about; **Proof**, **Proposition**, **Logical Deduction**, and **Axioms**
- That there are several *truths* as dependent to its beholder: **Legal Truth**, **Authorative Truth**, **Scientific Truth**, **Probable Truth**, and **Philosophical Truth**. But sadly we wouldn't tackle these types of truth which I wanted to know.
- **LOGICAL CONNECTIVES:**

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |
## Week 2:
- I learned about a new topic in DISMATH called **Logical Equivalences**.
- The different kinds of laws used in Logical Equivalences were introduced.
- These laws are: 

|         Name        |                           Equivalence                                 |
|:-------------------:|:--------------------------------------------------------------------: |
|    Identity laws    |                      p ∧ T ≡ p <br> p v F ≡ p                         |
|   Domination laws   |                       p v T ≡ T <br> p ∧ F ≡ F                        |
|    Negation laws    |                     p v ¬p ≡ T <br> p ∧ ¬p ≡ F                        |
| Double negation law |                            ¬(¬p) ≡ p                                  |
|   Idempotent laws   |                       p v p ≡ p <br> p ∧ p ≡ p                        |
|   Commutative laws  |                   p v q ≡ q v p <br> p ∧ q ≡ q ∧ p                    |
|   Associative laws  |       (p v q) v r ≡ p v (q v r) <br> (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)        |
|  Distributive laws  | p v (q ∧ r) ≡ (p v q) ∧ (p v r) <br>  p ∧(q v r) ≡ (p ∧ q) v (p ∧ r)  |
|   De Morgan's laws  |              ¬(p ∧ q) ≡ ¬p v ¬q <br> ¬(p v q) ≡ ¬p ∧ ¬q               |
|   Absorption laws   |                 p v (p ∧ q) ≡ p <br> p ∧ (p v q) ≡ p                  |

- I've also learned about **Propositional Logic** and **Quantifiers**. 
- Propositional Logic deals with proposition as a whole. (Subject + Predicate).
- Quantifiers indicates the generality of an open sentence in which a variable occurs.
- Quantifiers have two classifications, one being Existential Quantifiers (∃x) which means "There exist" and the other being Universal Quantifiers (∀x) which means "For all".

## Week 3:
- During this week, I was introduced to a topic called **Rules of Inference**.
- The Rules of Inferences are:

|          Name          |   Rules of Inference       |            Tautology           |
|:---------------------: |:-------------------------:|:-----------------------------:|
|      Modus Ponens      |       p<br>p→q<br>∴q      |        (p ∧ (p → q)) → q       |
|      Modus Tollens     |     ¬q<br>p→q<br>∴ ¬p     |       (¬q ∧ (p → q)) → ¬p      |
| Hypothetical Syllogism |     p→q<br>q→r<br>∴p→r    |  ((p → q) ∧ (q → r)) → (p → r) |
|  Disjunctive Syllogism |      p∨q<br>¬p<br>∴q      |       ((p ∨ q) ∧ ¬p) → q       |
|        Addition        |       p<br>∴p ∨ q         |           p → (p ∨ q)          |
|      Simplication      |       p ∧ q<br>∴p         |           (p ∧ q) → p          |
|       Conjunction      |      p<br>q<br>∴p ∧ q     |      ((p) ∧ (q)) → (p ∧ q)     |
|       Resolution       | p ∨ q<br>¬p ∨ r<br>∴q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |

- We used the different rules of inferences to solve problems such as our homework wherein we have to prove "*Superman doesn't exist!*".
- Our professor also discussed about the different **Methods of Proof** starting with **Direct Proof**.
  - To use this method, first assume that P is true then show that Q is also true.
  - P → Q

## Week 4:
- The second method of proof is **Contraposition** or the **Indirect Proof**.
    - First assume ¬Q is true then show that ¬P must also be true.
    - ¬Q → ¬P
- The third method of proof is **Vacuous Proof**.
  - Show that P is false, because P → Q must be true when p is false.
  - ¬P → (P → Q)
- The fourth method is **Trivial Proof**.
  - Show that Q is true, it follows that P → Q must also be true.
  - Q → (P → Q)
- The fifth method is **Proof by Contradiction**.
  - Assume that the premise is not true, then show that the premise will end up in a contradiction.
- I learned about the definition of a rational number which is {a/b | a, b ∈ ℤ, b≠0, a & b have no common factors other than ±1}.

## Week 5
- The sixth method was introduced which is **Proof by Equivalence** (Biconditionals).
  - (P ↔ Q) ↔ [(P → Q) ∧ (Q → P)]
  - Show that P → Q and Q → P are both true.
- A new lesson was introduced which is **Mathematical Induction**.
  - There are two steps in applying Mathematical Induction.
    - Basis
      - Show that P(1) or P(0) to be true
    - Direct Proof
      - Asumme P(k) ≡ T
      - Show P(k+1) ≡ T
## Week 6:
- Program Correctness
- Recursive Algorithms
- Summation

## Week 8:
I learned that:
- An empty set is not equal to a set containing an empty set.
- A power set contains all subsets of a set. (no. of subsets= 2^n where n is the number of elements of a set)
- Identities also exist in sets.

## Week 9:
- I learned that:
  - There are 3 types of functions.
    - One-to-one function (Injective)
      - For every x,y such that (x!=y --> f(x)!=f(y))
    - Onto Function (Surjective)
      - For every y, there's an x such that (f(x)=y)
    - Bijective Function
      - If and only if it is BOTH injective & surjective.
- Also this week, I learned different types of algorithm:
  - Finding the Minimum/Maximum
  - Linear Search Algorithm
  - Binary Search Algorithm

## Week 10:
- More types of algorithm:
  - Bubble Sort Algorithm
  - Insertion Sort Algorithm
  - Greedy Change Algorithm
- I learned about Growth of Functions.
  - Big-O Notation.
  - Big-Omega Notation.
  - Big-Theta Notation.

## Week 12:
- I learned about graph theory
  - graphs
  - vertex and degree of a vertex
  - Handshaking theorem
  - Simple graphs Kn
  - Euler Circuit and Path
  - Hamilton Circuit and Path
  - Matrices of graphs
  - Isomorphism of graphs
  - Planar Graphs
  - Euler's formula

## Week 13:
- <b> COLORED GRAPHS </b>
 - A coloring of a simple graph is the assignment of a color to each vertex of the graph so that no two adjacent vertices are assigned the same color.
 - The chromatic number of a graph is the least number of colors needed for a coloring of this graph.
 - The best algorithms known for finding the chromatic number of a graph have exponential worst-case time complexity
 
<b> FOUR COLOR THEOREM </b>
- The chromatic number of planar graph is no greater than four. (ONLY APPLIES TO PLANAR GRAPHS)
- non-planar graphs can have a larger number

<b> TREES </b>
- A <b> TREE </b> is a connected undirected graph with no simple circuits.
- a data structure that emulates a hierarchichal tree structure with a set of linked nodes.
- WHY STUDY TREES?
  - used to construct efficient algorithms for locating items in a list
  - used in algorithms, such as Huffman coding, that construct efficient codes saving costs in data transmission and storage
  - used to study games such as checkers and chess and can help determine winning strategies for playing these games
  - used to model procedures carried out using a sequence of decisions
  
- THEOREM: An undirected graph is a treee if and only if there is a unique simple path between any two of its vertices.
- <b> ROOTED TREE </b>
 - a tree in which one vertex has been designated as the root and every edge is directed away from the root

- <b> LEAVES </b>
 - nodes who don't have children
- <b> INTERNAL NODES </b>
 - those who have children
 
- <b> M-ARY TREE </b>
 - A rooted tree is called an m-ary tree if every internal vertex has no more than m children.
 - The tree is called a full m-ary tree if every internal vertex has exactly m children.
 
<b> ORDERED ROOTED TREE </b>
 - a rooted tree where the children of each internal vertex are ordered
 
- PROPERTIES OF TREES </b>
 - A tree with n vertices has n-1 edges
 - A full m-ary tree with i internal vertices contains n = mi + 1 vertices
 - A full m-ary tree with 
  - (i) n vertices has i = (n-1)/m internal vertices and l = [(m-1) n + 1]/m leaves,
  - (ii) i internal vertices has n = mi + 1 vertices and l = (m-1)i + 1 leaves,
  - (iii) l leaves has n = (ml - 1)/(m-1) vertices and i = (l-1)/(m-1) internal vertices
  
- <b> MODELING COMPUTATION </b> 
 - Structures in models of computaion:
    1. Grammars
    2. Finite-State Machines
    3. Turing Machines
    
- <b> GRAMMARS </b> 
 - FORMAL LANGUAGES
 - Why not English or Tagalog or any other language?
    - There are various meanings in a language. It is not definite or could have multiple meanings. (VAGUE LANGUAGE)
 - Grammars are extremely important in the construction and theory of compilers.
 - A SOURCE CODE cannot do everything by itself.
 
 - SYNTAX - The syntax of a language is extremely complicated 
 - APLHABET - a finite set of symbols
 - VOCABULARY (V) - is a finite, nonempty set of elements called <i> symbols </i>
 - WORD (or sentece) over V
 
- <b> AUTOMATA THEORY </b>
 - studies the laws of computation
 - lexical analyzers
 
- <b> FINITE-STATE MACHINE </b>
 - consists of a finite set S of states, a finite input alphabet I, a finite output alphabet O, a transitiom function f that assigns to each state and input pair a new state, an output function g that assigns to each state and input pair an output, and an initial state s0.
 - example
   - ![alt text](https://github.com/DeLaSalleUniversity-Manila-DISMATH-t216/dismathportfolio-Isabel-del-Castillo/blob/master/vending%20machine.png)
 
- <b> FINITE-MACHINES (NO OUTPUT) </b>
 - A finite-state automaton M = (S, I, f, s0, F ) consists of a finite set S of states, a finite input alphabet I, a transition function f that assigns a next state to every pair of state and input (so that f : S × I → S), an initial or start state s0, and a subset F of S consisting of final (or accepting states).

- <b> TURING MACHINES </b> [ T =(S,I,f,s0)]
 - consists of a finite set S of states, an alphabet I containing the blank symbol B, a partial function f from S × I to S × I × {R, L}, and a starting state s0.
 

 


 
