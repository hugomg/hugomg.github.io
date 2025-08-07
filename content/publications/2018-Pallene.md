+++
date  = 2018-09-20
title = "Pallene: a statically typed companion language for Lua"

[extra]
authors = "Hugo Musso Gualandi, Roberto Ierusalimschy"
where   = "Brazilian Symposium on Programming Languages"
doi     = "10.1145/3264637.3264640"
pdf     = "2018-Pallene.pdf"
+++
The simplicity and flexibility of dynamic languages make
them popular for prototyping and scripting, but the lack of
compile-time type information makes it very challenging to
generate efficient executable code.

Inspired by ideas from scripting, just-in-time compilers,
and optional type systems, we are developing Pallene, a
statically typed companion language to the Lua scripting
language. Pallene is designed to be amenable to standard
ahead-of-time compilation techniques, to interoperate seamlessly
with Lua (even sharing its runtime), and to be familiar
to Lua programmers.

In this paper, we compare the performance of the Pallene
compiler against LuaJIT, a just in time compiler for Lua, and
with C extension modules. The results suggest that Pallene
can achieve similar levels of performance.

Note: An [extended version](@/publications/2020-Pallene-ext.md) is also available.
