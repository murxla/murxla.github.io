---
layout: default
---

{%- assign gh = site.github.public_repositories |where: "name", "bitwuzla" |first -%}

# About Murxla

Murxla is a modular and highly extensible, model-based API Fuzzer for SMT
solvers.

Its name is derived from the German (rather informal) word *Murks*, which can
be translated as "screw-up". Murxla is a tool to find *Murks*es (bugs) in SMT
solvers via API fuzzing.


# News

- Murxla is now available on [GitHub]({{ gh.html_url }})

