# Polynomial Semantics of Dependent Type Theory

**Authors:** Lukas Buchschmid (TU Darmstadt), Eric Finster (University of Birmingham)  
**Status:** Under Review  

## Abstract
We propose a new algebraic semantics for dependently typed algebraic theories
inspired by the theory of polynomial functors. We first introduce a notion of
dependent polynomial, where operation symbols can have non-trivial
dependencies in their arities. Dependent polynomials can be viewed spans in a
certain presheaf category and inherit a natural notion of composition. Monoids
for this composition are called dependent polynomial monads, and
represent our axiomatization of a collection of dependently typed terms closed
under substitution.

An advantage of this perspective is that our dependent polynomial monads come
with a natural notion of bimodule and the category of dependent polynomials and
their bimodules enjoys many nice structural features which follow from general
theory. Our dependent polynomial monads lack, however, a means of substituting
terms in types. We introduce the notion of a substitution structure to
account for this difference. A dependent polynomial monad equipped with a
well-behaved substitution structure is called a polynomial theory, and we
show that polynomial theories are equivalent to the B-systems of Voevodsky.

## Note on the Current Draft
The PDF provided here is the original preprint submitted for review. During the peer-review process, a few minor errors were identified (specifically regarding Construction 4.2 and Lemma 5.31). These do not affect the main equivalence result and will be corrected in the final camera-ready version.

