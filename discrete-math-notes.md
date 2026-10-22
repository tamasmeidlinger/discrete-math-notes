# Propositional Logic

## Logical operators

| Operator | Symbol | LaTeX | Meaning |
|---|---|---|---|
| NOT | $\neg$ | `\neg` | Negation |
| AND | $\land$ | `\land` | Conjunction |
| OR | $\lor$ | `\lor` | Disjunction |
| XOR | $\oplus$ | `\oplus` | Exclusive OR |
| Implication | $\rightarrow$ | `\rightarrow` | If...then |
| Reverse implication | $\leftarrow$ | `\leftarrow` | Is implied by |
| Biconditional | $\leftrightarrow$ | `\leftrightarrow` | If and only if |
| Universal quantifier | $\forall$ | `\forall` | For all |
| Existential quantifier | $\exists$ | `\exists` | There exists |
| Unique existence | $\exists!$ | `\exists!` | There exists exactly one |
| Equivalent | $\equiv$ | `\equiv` | Logically equivalent |
| Not equivalent | $\not\equiv$ | `\not\equiv` | Not logically equivalent |


## Logical Classification

- **Tautology** — A statement that is always true, regardless of the truth values of its variables.
- **Contradiction** — A statement that is always false, regardless of the truth values of its variables.
- **Contingency** — A statement that is sometimes true and sometimes false, depending on the truth values of its variables.

## Order of precedence of logical operations

1. $\neg$
2. $\land$
3. $\lor$
4. $\rightarrow$
5. $\leftrightarrow$

No consensus on $\oplus$

# Logical Equivalences

Two propositions p, q are logically equivalent $(p \equiv q)$ if $p \leftrightarrow q$ is a tautology

## Idempotent law 1

![Idempotent law 1](images/idempotent-law-1.png)

## Absorption law 1

![Absorption law 1](images/absorption-law-1.png)

## Distributive laws

![Distributive laws](images/distributive-laws.png)

## De Morgans's laws

![De Morgan's Laws](images/de-morgans-laws.png)

## Absorption law 2

![Absorption law 2](images/absorption-law-2.png)

## Contraposition

![Contraposition](images/contraposition.png)

## Or Formulation

![Or Formulation](images/or-formulation.png)

## And Formulation

![And Formulation](images/and-formulation.png)

# Open Proposition

An open proposition (propositional function, predicate) is a statement in which one (or more) variables occur

## Quantifiers

![Universal Quantifier](images/universal-quantifier.png)

![Existential Quantifier](images/existential-quantifier.png)

![Uniqueness Quantifier](images/uniqueness-quantifier.png)

## Quantifiers with finite domains

![Quantifiers with finite domains](images/q-with-finite-domains.png)

![Quantification over finite domains](images/q-over-finite-domains.png)

## Quantifiers with restricted domains

![Quantifiers with restricted domains](images/q-with-restricted-domains.png)

## Negating quantifiers

![Negating quantifiers](images/de-morgan-quantifiers.png)

## Nested quantifiers

![Nested quantifiers](images/nested-quantifiers.png)

### Order of nested quantifiers

![Order of nested quantifiers](images/order-of-nested-q.png)

### Negating nested quantifiers

![Negating nested quantifiers](images/negating-nested-q.png)

# Proofs

## Definition of proof

![Definition of proof](images/definition-of-proof.png)

## Prove p AND q

![How to prove p and q](images/prove-p-and-q.png)

## Prove p OR q

![How to prove p or q](images/prove-p-or-q.png)

## Even and Odd numbers

![Even and odd numbers](images/even-odd.png)

## Prove p IMPLIES q

### Direct

![Direct proof](images/prove-p-impl-q-direct.png)

### Contraposition

![By Contraposition](images/prove-p-impl-q-contrap.png)

### Contradiction

![Pigeonhole principle](images/prove-p-impl-q-contrad.png)

![By contradiction](images/prove-p-impl-q-contrad-2.png)

## Prove p EQUIVALENT q

![Direct, double implication](images/prove-p-equiv-q.png)

## Proofs to be continued

Continue with proofs here

# Sets

## Quick reference

| Set Relation / Operation | Symbol | Meaning | Example |
|---|---|---|---|
| Subset | A ⊆ B | Every element of A is also in B. | A = {1, 2}, B = {1, 2, 3} |
| Proper Subset | A ⊊ B | A is a subset of B, but A is not equal to B. | A = {1, 2}, B = {1, 2, 3} |
| Equality of Sets | A = B | Both sets contain exactly the same elements. | A = {1, 2, 3}, B = {3, 2, 1} |
| Disjoint Sets | A ∩ B = ∅ | The sets have no elements in common. | A = {1, 2}, B = {3, 4} |
| Overlapping Sets | A ∩ B ≠ ∅ | The sets have at least one element in common. | A = {1, 2, 3}, B = {3, 4, 5} |
| Union | A ∪ B | All elements in A or B, without duplicates. | A = {1, 2}, B = {2, 3}; A ∪ B = {1, 2, 3} |
| Intersection | A ∩ B | Elements common to both sets. | A = {1, 2, 3}, B = {3, 4}; A ∩ B = {3} |
| Set Difference | A − B | Elements in A that are not in B. | A = {1, 2, 3}, B = {3, 4}; A − B = {1, 2} |
| Empty Set | ∅ | A set containing no elements. | A = ∅ |
| Universal Set | U | The set containing all elements under consideration. | U = {1, 2, 3, 4, 5} |

## Basics

### Definition

![Definition of Set](images/sets-definition.png)

### Set Builder Notation

![Set builder Notation](images/set-builder-notation.png)

### Venn Diagrams

![Venn Diagrams](images/venn-diagrams.png)

### Cardinality

![Cardinality](images/cardinality-sets.png)

### Equality, Subset, Superset

![Equality, Subset, Superset](images/eq-subset-superset.png)

### Power Set

![Power Set](images/power-set.png)

## Set Operators

### Union

![Union](images/union.png)

### Intersection

![Intersection](images/intersection.png)

### Difference

![Difference](images/difference.png)

### Complement

![Complement](images/complement.png)

## Set Identities

![Set Identities](images/set-identities.png)

## Tuple

![Tuple definition](images/tuple-definition.png)

![Cartesion Product](images/cartesian-product.png)

# Expected Learning Outcome

![Expected Learning Outcome](images/expected-learning-outcome.png)
