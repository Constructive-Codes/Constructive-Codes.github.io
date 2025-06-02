---
layout: home
list_title: ' '
---

![equidistant](equidistant.png){: style="float: left; margin-right: 1em;" width="250"}
## Let's see if we can use code generation to construct novel solutions to interesting problems.
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
**May 29, 2025**: New results using [CPro1](https://github.com/Constructive-Codes/CPro1) with reasoning models:<br><br>
Rosin, C.D. (May 2025) "Using Reasoning Models to Generate Search Heuristics that Solve Open Instances of Combinatorial Design Problems." [https://arxiv.org/pdf/2505.23881](https://arxiv.org/pdf/2505.23881)<br><br>
Running CPro1 with reasoning model o3-mini-high on 4 combinatorial problems from Feb. 2025 publications, CPro1 resolves open instances for 3 of them.  CPro1 also finds new Deletion Codes, and solves additional open instances of the Handbook of Combinatorial Designs problems from January 2025 (below).

**Jan. 29, 2025**: The [Handbook of Combinatorial Designs](https://www.taylorfrancis.com/books/edit/10.1201/9781420010541/handbook-combinatorial-designs-jeffrey-dinitz-charles-colbourn) is an extensive catalog of different types of combinatorial designs: [Balanced Incomplete Block Designs](https://en.wikipedia.org/wiki/Block_design), [Costas Arrays](https://en.wikipedia.org/wiki/Costas_array), [Weighing Matrices](https://en.wikipedia.org/wiki/Weighing_matrix), etc.  For many of these, it lists open instances of the *existence problem*: given a set of parameters describing the design, does a solution exist with these parameters that meets the constraints required by this type of combinatorial design?  These are beautiful problems, with simple constraints and instances that are described by just a few numbers (e.g. size).

The protocol [CPro1](https://github.com/Constructive-Codes/CPro1) uses an LLM to generate code that attempts to construct solutions to instances of combinatorial design existence problems.  For each problem, it generates and tunes 1000 candidate programs -- enough to experiment with a variety of techniques and variations.  Testing it on 16 different types of combinatorial designs from the Handbook, it is able to resolve small open instances for 6 of them.

Rosin, C.D. (Jan. 2025) "Using Code Generation to Solve Open Instances of Combinatorial Design Problems." [https://arxiv.org/abs/2501.17725](https://arxiv.org/abs/2501.17725)<br><br>
On GitHub: [Code and Result Files](https://github.com/Constructive-Codes/CPro1)
<br>





