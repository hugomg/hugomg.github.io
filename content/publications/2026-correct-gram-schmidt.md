+++
date = 2026-09-10
title = "Correct by Construction Gram-Schmidt Process"

[extra]
authors = "João Victor Lopez Pereira, Daniel Kiyoshi Hashimoto, Hugo Musso Gualandi, João Paixão"
where = "Brazilian Symposium on Programming Languages (SBLP)"
doi = "10.5753/sblp.2026.28541"
pdf = "2026-correct-gram-schmidt.pdf"
+++
The programming languages community has developed proof techniques for reasoning about correctness and equivalence of stream programs in a concise and precise way whilst not worrying about indexes. These ideas can be applied to areas, such as linear algebra, where indexes are the gold-standard. We showcase this through the lens of the Gram-Schmidt process for producing an orthonormal basis, which is an online algorithm that can be succinctly implemented as a purely functional stream program. Our first contribution is a specification of orthogonalization as a Galois Connection. Our second contribution is a correct-by-construction derivation of the classical Gram-Schmidt algorithm directly from its specification. Our third contribution is an induction-free proof that the more numerically stable modified Gram-Schmidt algorithm is equivalent to its classical counterpart. All of our proofs are index-free, in the sense that we do not use indexes to refer to vectors in a basis nor to elements in a vector.
