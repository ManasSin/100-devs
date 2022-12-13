Manas Singh

---
__Differentiate between prepositional and predicate logic__.

Prepositional logic and predicate logic are two types of formal logic, which are systems of representation and rules for making logical arguments.

Prepositional logic is a type of formal logic that deals with propositions, which are statements that can be either true or false. In prepositional logic, these propositions are represented using logical connectives such as "and," "or," and "not," and the truth of a proposition is determined by the truth values of its constituent parts.

Predicate logic, on the other hand, is a type of formal logic that deals with predicates, which are expressions that describe the properties of objects or the relationships between objects. In predicate logic, predicates are combined with variables to form propositions, and the truth of a proposition is determined by the values that are assigned to the variables.

One key difference between prepositional and predicate logic is the level of abstraction. Prepositional logic is a more abstract system, in which propositions are represented using logical connectives and truth values, without any reference to the objects or properties that they describe. Predicate logic, on the other hand, is a more concrete system, in which propositions are formed by combining predicates with variables, and the truth of a proposition depends on the values that are assigned to the variables.

Another difference between the two logics is the way in which they handle quantifiers. In prepositional logic, quantifiers such as "all" and "some" are typically treated as part of the propositional structure, and the truth of a proposition with a quantifier is determined by the truth values of its constituent parts. In predicate logic, on the other hand, quantifiers are treated as separate logical operators, and the truth of a proposition with a quantifier is determined by the values of the variables that are quantified over.


#### Questions

__Explain with an example for knowledge representation used in AI through predicate logic__.

Ans:-
In predicate logic, knowledge is represented using predicates, which are statements that can be either true or false about some objects. For example, the predicate "is a mammal" could be applied to the objects "dog" and "cat", and the resulting statements would be "dog is a mammal" and "cat is a mammal", which are both true.
Here is an example of how knowledge could be represented using predicate logic:

Let's say we have the following predicates:
is a mammal has four legs has fur
We can then apply these predicates to different objects to represent our knowledge about those objects. For example, if we have the objects "dog" and "cat", we can represent the following knowledge using predicate logic:
"dog is a mammal" (true)
"dog has four legs" (true)
"dog has fur" (true)
"cat is a mammal" (true)
"cat has four legs" (true)
"cat has fur" (true)

In this example, we used predicate logic to represent our knowledge about the objects "dog" and "cat" using the predicates "is a mammal", "has four legs", and "has fur". This allows us to reason about the objects in a logical and systematic way, which is useful for many AI applications.

---

__How to write statements in first order logic? Draw truth tables of all the five logical connectives of prepositional logic__.

Ans:-
In first-order logic, statements are written using predicates, variables, and logical connectives. Predicates are statements that can be either true or false about some objects, and are usually written with a letter or symbol followed by a list of variables in parentheses. For example, the predicate "is a mammal" could be written as "M(x)", where "x" is a variable representing the object that the predicate is being applied to.

Variables are placeholders for objects, and are usually written as a single letter. For example, the variable "x" could represent any object that the predicate is being applied to.

Logical connectives are symbols or words that are used to combine predicates or other statements into more complex statements. The most common logical connectives in first-order logic are "and", "or", "not", "if-then", and "if and only if". These connectives are used to create statements such as "if x is a mammal and x has four legs, then x is a dog".

Here are the truth tables for the five logical connectives of prepositional logic:

And:

p q p and q
T T T
T F F
F T F
F F F

Or:

p q p or q
T T T
T F T
F T T
F F F

Not:

p not p
T F
F T

If-then:

p q if p then q
T T T
T F F
F T T
F F T

If and only if:

p q p if and only if q
T T T
T F F
F T F
F F T