+++
date  = 2020-01-15
title = "Pallene: A companion language for Lua (extended version)"

[extra]
authors = "Hugo Musso Gualandi, Roberto Ierusalimschy"
where   = "Science of Computer Programming"
doi     = "10.1016/j.scico.2020.102393"
pdf     = "2020-Pallene-ext.pdf"
+++
The simplicity and flexibility of dynamic languages make them popular for prototyping and scripting, but
the lack of compile-time type information makes it challenging to generate efficient executable code.
Inspired by ideas from scripting, just-in-time compilers, and optional type systems, we have developed
Pallene, a typed companion language to the Lua scripting language, intended for writing lower-level libraries
and extension modules. It plays the role of a system language in the scripting paradigm, but one that
has been explicitly designed to interoperate with Lua. Pallene is designed to be efficient, to interoperate
seamlessly with Lua (even sharing its runtime), and to be familiar to Lua programmers. It should also be
simple, easy to understand, and easy to implement, so it can be as portable as maintainable as Lua itself.
In this paper, we discuss the rationale for Pallene’s design and present a description of its syntax, type
system, and semantics. We also compare the performance of Pallene extension modules against pure Lua
(both interpreted and JIT-compiled), against C extension modules (operating with Lua data structures),
and also against programs fully written in C, which provide a familiar baseline. The results corroborate our
hypothesis that Pallene has the potential to be a low-level counterpart to Lua. The performance of Lua
extension modules written in Pallene can be better than that of equivalent modules written in C and it is
competitive with the performance from a JIT compiler, despite the vastly simpler implementation.
This is a revised and extended version of a [SBLP 2018 paper](@/publications/2018-Pallene.md) with a similar title.
