Function (sometimes also called mappings or transformations, according to Rosen 2.3)

Definition (Video 2):
A function is a mapping from a set A to a set B such that each element of A is mapped to exactly one element of B, denoted as f: A → B.

Note 1 (Video 2): Each element in set A must be mapped to one element in set B. If there is an element in A that cannot be mapped to an element in B, then this is not a function.
Example: In the video, each family member should have one favorite kind of bakery. If one person does not have any favorite bakery, then this person cannot be mapped to the set of bakeries, and therefore the mapping is not a function.

Note 2 (Video 2): However, one element in B can correspond to more than one element in A.
Example: If two people have the same favorite bakery, this still constitutes a function.

Note 3 (Self-reflection): The set B should cover the range. It is still a function even if some elements of B do not match with any elements of A. This may seem “unequal,” because each element of A must map to some element of B, but the reverse is not required.
Analogy: To memorize this, we can think of set A as women and set B as men. In patriarchy, a woman is considered “complete” only if she marries a man. Each woman must have exactly one man. A man, however, can have more than one woman—or none. Men with no partners are still in set B but not in the range, like “leftover men” or incels.

Note 4 (Rosen 2.3): Related concepts: domain, codomain, image, preimage, and range.

If f is a function from A to B, A is the domain of f and B is the codomain of f.

If f(a) = b, then b is the image of a and a is a preimage of b.

The range, or image, of f is the set of all images of elements of A.

If f is a function from A to B, we say that f maps A to B.

Bijection (one-to-one correspondence, not just one-to-one): “Perfect match”

Definition: A function is a bijection if it is both one-to-one and onto.

Reflection: In a bijection, there are no missing elements—every element in A and B has a match. There is no repetition—each pair of (a, b) is unique, with no overlap.

One-to-one (injunction)

Definition 1 (Video 2): A function is one-to-one if every element in A maps to a different element in B.

Definition 2 (Rosen 2.3):
∀a∀b (f(a) = f(b) → a = b),
or equivalently ∀a∀b (a ≠ b → f(a) ≠ f(b)).

Reflection: Suppose f(x) = y. This can be better understood through graphs. If we draw a horizontal line (y = k, where k is a constant), then the intersection of y = k and y = f(x) identifies only one x. (Since this is discrete math, the graph of f(x) may consist of individual points rather than a continuous curve.)

Onto (surjection)

Definition 1 (Video 2): A function is onto if every element in B has some element in A that maps to it.

Definition 2 (Rosen 2.3): ∀y∃x (f(x) = y). For every y, there exists an x such that f(x) = y.
“A function f from A to B is onto, or a surjection, if and only if for every element b ∈ B there is an element a ∈ A with f(a) = b.”

Reflection: The key point of an onto function is existence. For every y in the codomain, you can find at least one x that maps to it. One is enough, but there can be more.
Analogy: Using the men–women analogy again, an onto function is like “men’s paradise”: every man in set B can find at least one woman from set A. If he finds exactly one woman, that’s a perfect marriage, i.e., a bijection. If he finds more than one, it is still onto.
