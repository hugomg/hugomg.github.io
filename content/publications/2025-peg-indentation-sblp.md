+++
date  = 2025-08-11
title = "Indentation-Sensitive Parsers for Free-Form Languages"

[extra]
authors = "Sérgio Queiroz de Medeiros, Hugo Musso Gualandi"
where = "Brazilian Symposium on Programming Languages"
doi   = "?"
+++
Consistent source code indentation is crucial for code readability, even in
free-form languages that are oblivious to whitespace. However, as in a free-form
language programmers can format the code as they desire, this may lead to
mismatched indentation styles. Automatic code formatters address this problem by
rewriting code to a standard layout, however they impose a specific style and
only work for syntactically valid code.

We describe an extension of Parsing Expression Grammars (PEGs) that can model
indentation information and we show that it can be used to specify different
indentation styles. A parser based on such extension can check for indentation
inconsistencies and inform the developer about them. To evaluate our approach,
we also implemented a full parser for the Lua programming language and used it
to parse a well-known Lua codebase. We observed that 98% of source code lines
were well-indented according to our specification.
