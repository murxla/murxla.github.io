---
layout: default
---

{%- assign gh = site.github.public_repositories |where: "name", "bitwuzla" |first -%}

# About Murxla

Murxla is a modular and highly extensible, model-based API Fuzzer for SMT
solvers.

Murxla randomly generates valid sequences of solver API calls based on a
customizable API model, with full support for the semantics and features of
SMT-LIB. It is solver-agnostic but extensible to allow for solver-specific
testing and supports option fuzzing, cross-checking with other solvers,
translation to [SMT-LIB](http://smt-lib.org), and SMT-LIB input fuzzing.

Its name is derived from the German (rather informal) word *Murks*, which can
be translated as "screw-up". Murxla is a tool to find *Murks*es (bugs) in SMT
solvers via API fuzzing.


# News

- Murxla is now available on [GitHub]({{ gh.html_url }})

