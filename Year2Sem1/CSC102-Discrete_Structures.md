1. [[#Sets|Sets]]
	1. [[#Sets#Counting Principles, Classes of Sets|Counting Principles, Classes of Sets]]
		1. [[#Counting Principles, Classes of Sets#Counting|Counting]]
		2. [[#Counting Principles, Classes of Sets#Inclusion-Exclusion Principle|Inclusion-Exclusion Principle]]
	2. [[#Sets#Classes of Sets|Classes of Sets]]
	3. [[#Sets#Power Sets|Power Sets]]
	4. [[#Sets#Partitions|Partitions]]
2. [[#Logic|Logic]]
	1. [[#Logic#Proposition & Truth Value|Proposition & Truth Value]]
		1. [[#Proposition & Truth Value#Proposition|Proposition]]
			1. [[#Proposition#Negation (NOT)|Negation (NOT)]]
			2. [[#Proposition#Connective (AND)|Connective (AND)]]
			3. [[#Proposition#Disjunction (OR)|Disjunction (OR)]]
			4. [[#Proposition#Conditional (IF)|Conditional (IF)]]
			5. [[#Proposition#Biconditional ()|Biconditional ()]]
	2. [[#Logic#Quantifiers|Quantifiers]]
	3. [[#Logic#Basic Logical Operators|Basic Logical Operators]]
		1. [[#Basic Logical Operators#precedence of logical operators|precedence of logical operators]]
		2. [[#Basic Logical Operators#Logic and Bit operations|Logic and Bit operations]]
			1. [[#Logic and Bit operations#XOR|XOR]]
		3. [[#Basic Logical Operators#Propositional Equivalences|Propositional Equivalences]]
			1. [[#Propositional Equivalences#tautology|tautology]]
			2. [[#Propositional Equivalences#contradiction|contradiction]]
			3. [[#Propositional Equivalences#contingency|contingency]]
		4. [[#Basic Logical Operators#Logical equivalences|Logical equivalences]]
	4. [[#Logic#Applications of Propositional Logic|Applications of Propositional Logic]]
		1. [[#Applications of Propositional Logic#System specifications|System specifications]]
	5. [[#Logic#Argument|Argument]]
3. [[#Proofs|Proofs]]
	1. [[#Proofs#Direct proof|Direct proof]]
4. [[#Relations|Relations]]
5. [[#Functions and Combinatorics|Functions and Combinatorics]]
	1. [[#Functions and Combinatorics#Functions|Functions]]
		1. [[#Jargon]]
		2. [[#Representing functions]]
		3. [[#Simple Mathematical Function]]

# Sets
## Counting Principles, Classes of Sets
- **Finite Set**: Countable Set
- **Infinite Set**: Not Countable
	- **Countably infinite**: Infinite but can be arranged as a sequence (has a pattern e.g., {2, 4, 8, 64…})
### Counting 
Notation 

(🫠)
### Inclusion-Exclusion Principle

Say, $A, B$ and $C$ are finite sets, the $A\cup B \cup C$   is finite 
## Classes of Sets
## Power Sets

## Partitions
- $S$ isnt empty
- Partition of $S$ has subsets(?) that have no overlapping elements


# Logic
##  Proposition & Truth Value
### Proposition 
**Declarative sentences** that are (explicitly) either true **OR** false but not both

We use letters to denote **propositional variables** (var that)

#### Negation (NOT)
- let  $p$ = proposition 
-  negation of p, denoted by $\lnot p$ /~$p$
- proposition $\lnot p$ = not p

| P   | ~P  |
| --- | --- |
| T   | F   |



#### Connective (AND)
- conjunction of p and q denoted by proposition p $\land$ q
- both are true

| P   | Q   | P^Q |
| --- | --- | --- |
| T   | T   | T   |
| F   | F   | F   |
| T   | F   | F   |
| F   | T   | F   |

#### Disjunction (OR)

- True if **either** p or q are true. If(P = 0 && Q == 0){False}
- denoted by $p \lor q$ 
#### Conditional (IF)
P -> q is false if p = 1 & q = 0. True otherwise
- denoted by $p \implies q$ 

#### Biconditional ()
If p and q have the same truth values = true 
- denoted by $p \iff q$ 
- e.g.,

| $p$ | $q$ | $p \iff q$ |
| --- | --- | ---------- |
| T   | T   | T          |
| F   | F   | T          |
| T   | F   | F          |
| F   | T   | F          |
## Quantifiers 
Used to express the extent or the scope
## Basic Logical Operators
### precedence of logical operators
### Logic and Bit operations


#### XOR
Either one is 1, not both
### Propositional Equivalences
#### tautology
Always true
#### contradiction
Always false
#### contingency
!(Tautology || contradiction)

|     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- |
|     |     |     |     |     |     |     |
|     |     |     |     |     |     |     |
|     |     |     |     |     |     |     |
|     |     |     |     |     |     |     |
### Logical equivalences

## Applications of Propositional Logic
- by SW/HW specs
- circuits
### System specifications
TL-ing natural language to logical expressions
${\text{FullFS}} \implies \lnot \text{ReplySendable}$ 

## Argument
Series if premises that prove a conclusion 

$$\frac{p\land{q}}{\therefore{p}}$$
# Proofs
## Direct proof
- a
# Relations
Ah, relations; a foundational concept in discrete math and compsci. A relation _establishes a meaningful connection between elements of two sets_ 

# Functions and Combinatorics
## Functions

**Formal Def**: A function (or mapping) $f$ from set $A$ (domain) to a set $B$ (codomain), denoted as $$f: A \to B$$ is a rule that assigns to each element $x$ in $A$ is exactly one element $y$ in $B$ 

In other words, _it's a rule that takes an input from $A$ to exactly one output in $B$_. Remember exponential, square root, logarithmic and trigonometric? Those are functions

### Jargon
- **Domain**: all possible input
- **Codomain**: all possible output
- **Range**: subset of codomain that has _actual output you can get_
- **Image**: the output you get from an input
- **Pre-Image**: The input you need to get that output
### Representing functions
- Ordered pairs: $F$ = {(1,2), (2,3), (3,4)}
- Arrow diagram: Where element in $A$ points to $B$ e.g., $1 \to B, 2 \to A, 3 \to C$ 
- Table of values: good 'ol tables where

| $x$ | ~~y~~ $f(x)$ |
| --- | ------------ |
| 1   | 2            |
| 2   | 4            |
| 3   | 6            |
- Graph: y'know Cartesian Plane, ain't drawing that

### Simple Mathematical Function
