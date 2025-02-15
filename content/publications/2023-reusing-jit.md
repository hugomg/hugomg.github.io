+++
date  = 2023-10-16
title = "Reusing Just-in-Time Compiled Code"

[extra]
authors = "Meetesh Kalpesh Mehta, Sebastián Krynski, Hugo Musso Gualandi, Manas Thakur, Jan Vitek"
where   = "OOPSLA"
doi     = "10.1145/3622839"
+++
Most code is executed more than once. If not entire programs then libraries remain unchanged from one run
to the next. Just-in-time compilers expend considerable eﬀort gathering insights about code they compiled
many times, and often end up generating the same binary over and over again. We explore how to reuse
compiled code across runs of diﬀerent programs to reduce warm-up costs of dynamic languages. We propose
to use speculative contextual dispatch to select versions of functions from an oﬀ-line curated code repository.
That repository is a persistent database of previously compiled functions indexed by the context under which
they were compiled. The repository is curated to remove redundant code and to optimize dispatch. We assess
practicality by extending Ř, a compiler for the R language, and evaluating its performance. Our results suggest
that the approach improves warmup times while preserving peak performance.
