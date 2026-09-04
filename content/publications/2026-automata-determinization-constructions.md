+++
date = 2026-09-10
title = "Two Induction-Free Constructions For Finite Automata Determinization"

[extra]
authors = "Matheus do Ó, Hugo Musso Gualandi"
where = "Brazilian Symposium on Programming Languages"
#doi =
pdf = "2026-automata-determinization-constructions.pdf"
+++
The standard algorithm to determinize a finite automaton is the subset construction, however its description and the proof of correctness are usually presented separately. We derive the subset construction from the specification of a deterministic automaton by expressing the language recognized by the automaton as a fixed point of a function. We do this in two ways, one based on the right languages of the states, and the other based on the left languages. The derivation based on right languages resembles a derivation made by Kozen using matrix techniques and Kleene algebra. The derivation based on left languages, on the other hand, uses non-linear functions and has no matrix analogue. Our proofs are induction-free and instead we rely on the uniqueness of fixed-points. In summary, we highlight that an algebraic model of an automaton allows an elegant derivations of the subset construction and highlight the duality between the left and right languages of an automaton.
