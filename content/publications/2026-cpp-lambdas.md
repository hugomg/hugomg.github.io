+++
date = 2026-09-10
title = "A Large-Scale Analysis of C++ Lambdas and Their Capture Lists in Opensource Repositories"

[extra]
authors = "Luiz Romário Santana Rios, Hugo Musso Gualandi"
where = "Brazilian Symposium on Programming Languages"
#doi = "?"
pdf = "2026-cpp-lambdas.pdf"
+++
In C++, lambda expressions offer fine control over variable capture: variables can be captured wholesale or individually, and they may be captured by value or by reference. This study is a large-scale analysis of C++ lambda variable capture patterns, aggregating data from over 1600 open-source repositories, since the release of lambdas in C++11. We are the first to measure the frequency of lambda expressions per lines of code, as opposed to total number of lambdas, and are the first to measure the frequency of different variable capture strategies. We confirm that lambda use in C++ is on a growing trend and it is in widespread use: over 70% of projects use lambdas. However, we observed that adoption of lambdas was a slow process; it was only in late 2019 that adoption reached 50%. We also observe substantial variety in variable capture strategies. Out of the repositories that used lambdas, 38.3% favored capturing no variables, 23.5% favored explicit capture, 26.1% favored automatic capture by reference, 8.6% favored capturing only the “this” pointer, and only 3.6% favored automatic capture by value. Overall, implicit capture was twice as popular as explicit capture lists.
