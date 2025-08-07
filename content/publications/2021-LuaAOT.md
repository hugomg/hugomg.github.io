+++
date  = 2021-10-05
title = "A Surprisingly Simple Lua Compiler"

[extra]
authors = "Hugo Musso Gualandi, Roberto Ierusalimschy"
where   = "Brazilian Symposium on Programming Languages"
doi     = "10.1145/3475061.3475077"
pdf     = "2021-LuaAOT.pdf"
+++
Dynamically-typed programming languages are often implemented
using interpreters, which offer several advantages in terms of portability
and flexibility of the implementation. However, as a language
matures and its programs get bigger, programmers may seek compilers,
to avoid the interpretation overhead.

In this study, we present LuaAOT, a simple ahead-of-time compiler for Lua.
The compiler is derived from the Lua interpreter and
it exemplifies an old idea of using partial evaluation to produce a
compiler based on an existing interpreter. Our contribution is to
apply this idea to a well-established programming language. We
show that with a quite modest effort it is possible to implement an
efficient compiler that covers the entirety of Lua, including coroutines and tail calls.
The whole implementation required less than
500 lines of new code. For this effort, we reduced the running time
of our benchmarks from 20% to 60%.

Note: An [extended version](@/publications/2022-LuaAOT-ext.md) is also available.
