+++
date  = 2024-09-30
title = "Converting Combinatory Logic to and from Concatenative Calculus"

[extra]
authors = "Daniel Kiyoshi Hashimoto, Hugo Musso Gualandi"
where   = "Brazilian Symposium on Programming Languages"
doi     = "10.5753/sblp.2024.3460"
pdf     = "2024-converting-concatenative.pdf"
+++
Combinatory logic and its combinators BCKWI are a foundation for tacit
(point-free) programming. But what does each letter mean? Informally, B stands
for composing, C for swapping, K for discarding, W for duplicating and I is the
identity function. However, B does more than that: depending on where it appears
in the expression, it can also call functions or defer values for later. To help
tell these purposes apart, we relate combinatory logic to the concatenative
calculus of Kerby, which features separate primitives for the different facets
of B.

We provide translations from combinatory logic to concatenative
calculus and vice versa. In both directions we
have contributions. From concatenative to combinatory, we
show that first-order stack programs map to regular combinators,
and which patterns of combinators higher-order
stack programs map to. From combinatory to concatenative,
we extend an algorithm of Kerby to make it compatible with
a call-by-value evaluation order, in addition to call-by-name.

To enforce a strong association between the two worlds,
our translations are simulations. That is, one evaluation step
in the original program is simulated by zero or more evaluation
steps in the translated program.
