+++
date    = 2022-08-24
title   = "A Surprisingly Simple Lua Compiler (extended version)"

[extra]
authors = "Hugo Musso Gualandi, Roberto Ierusalimschy"
where   = "Science of Computer Programming"
doi     = "10.1016/j.cola.2022.101151"
+++
Dynamically-typed programming languages are often implemented
using interpreters, which offer several advantages in terms of portability
and flexibility of the implementation. However, as a language
matures and its programs get bigger, programmers may seek compilers,
to avoid the interpretation overhead.

In this study, we present LuaAOT, a simple ahead-of-time compiler
for Lua derived from the reference Lua interpreter. We describe
two alternative compilation strategies. The first one exemplifies an
old idea of using partial evaluation to produce a compiler based
on an existing interpreter. Its contribution is to apply this idea to
a well-established programming language. We show that with a
quite modest effort it is possible to implement an efficient compiler
that covers the entirety of Lua, including coroutines and tail calls.
The whole implementation required less than 500 lines of new code.
For this effort, we reduced the running time of our benchmarks
from 20% to 60%.

The second compilation strategy is based on function “outlining”,
where each bytecode is implemented by a small subroutine. This
strategy reduces executable sizes and compilation times, at the
cost of not speeding up the running times as much as the first
compilation method.

Note: This is an extended version of [a previous paper](@/publications/2021-LuaAOT.md).
