# Papers on Compiler Optimizations: Analysis and Transformations (1952-1994)

> [!NOTE]
> This repository is updated periodically. Contributions are welcome!

This repository curates a _chronologically_ sorted list of influential papers on compiler optimization, from the seminal works of 1952 through the advanced techniques of 1994. It's an essential resource for students, researchers, and engineers seeking to understand the foundational and critical advancements in compiler design, analysis, and optimization techniques.
The paper list is provided in two convenient formats:
- a PDF document ([papers.pdf](./papers.pdf)); a compiled $\LaTeX$ table with full bibliographic references for each paper,
- a markdown table; an easily browsed, embedded table in this `README` file. 

<details>
<summary>The $\LaTeX$ folder and its contents</summary>

The [latex folder](./latex/) contains the source files used to generate the PDF:
- the main latex document ([papers.tex](./latex/papers.tex)) that compiles the list of papers into the PDF document ([papers.pdf](./papers.pdf)), and
- a [BibTeX file](./latex/local.bib) with all bibliographic entries ready for citation purpose.
</details>

# Table of Papers

**Key for Columns**

Sources :
- A: [Advanced Compiler Design and Implementation](https://dl.acm.org/doi/10.5555/286076)
- D: [Compilers: Principles, Techniques, and Tools](https://dl.acm.org/doi/10.5555/1177220)
- E: [Engineering a Compiler](https://dl.acm.org/doi/book/10.5555/1526330)
- M: Modern Compiler Implementation in [C](https://dl.acm.org/doi/10.5555/550932)/[Java](https://dl.acm.org/doi/10.5555/599718)/[ML](https://dl.acm.org/doi/10.5555/993972)
- O: [Optimizing Compilers for Modern Architectures: A Dependence-Based Approach](https://dl.acm.org/doi/10.5555/502981) 
- S: [Compiler transformations for high-performance computing](https://dl.acm.org/doi/10.1145/197405.197406) - a 1994 survey paper

Type:
- C: Conference
- J: Journal
- W: Workshop

| Paper Title | Venue Type | Venue Name | Type | Year | Sources |
|---|---|---|---|---|---|
| [The problem of simplifying truth functions](https://doi.org/10.1080/00029890.1952.11988183) | T&F | AMM | J | 1952 | O |
| [Minimization of Boolean functions](https://doi.org/10.1002/j.1538-7305.1956.tb03835.x) | Bell Labs | Bell System Tech. J. | J | 1956 | O |
| [An algorithm for translating Boolean expressions](https://doi.org/10.1145/321105.321116) | ACM | JACM | J | 1962 | S |
| [High speed compilation of efficient object code](https://doi.org/10.1145/365474.365489) | ACM | CACM | J | 1965 | D |
| [Peephole optimization](https://doi.org/10.1145/364995.365000) | ACM | CACM | J | 1965 | E |
| [Index Register Allocation](https://doi.org/10.1145/321312.321317) | ACM | JACM | J | 1966 | E |
| [Analysis of Programs for Parallel Processing](https://doi.org/10.1109/PGEC.1966.264565) | IEEE | TC (TEC) | J | 1966 | O |
| [Program optimization](https://doi.org/10.1145/68182.68200) | - | PP | C | 1966 | A, D, E, M, O, S |
| [Object code optimization](https://doi.org/10.1145/362835.362838) | ACM | CACM | J | 1969 | A, D, E |
| [Local optimizations](https://doi.org/10.1145/390013.808470) | ACM | PLDI (SCO) | C | 1970 | E |
| [Detection and parallel execution of independent instructions](https://doi.org/10.1109/TC.1970.222795) | IEEE | TCO | J | 1970 | S |
| [Global common subexpression elimination](https://doi.org/10.1145/800028.808480) | ACM | PLDI (SCO) | C | 1970 | D, E, M |
| [The Generation of Optimal Code for Arithmetic Expressions](https://doi.org/10.1145/321607.321620) | ACM | JACM | J | 1970 | D, E, M |
| [Control flow analysis](https://doi.org/10.1145/390013.808479) | ACM | PLDI (SCO) | C | 1970 | D, E |
| A Basis for Program Optimization | IFIP | NH | C | 1971 | A, D, E, M, O, S |
| A catalogue of optimizing transformations | - | PH | C | 1972 | A, D, E, M, O, S |
| [Flow graph reducibility](https://doi.org/10.1145/800152.804919) | ACM | STOC | C | 1972 | D |
| [Use-definition chains with applications](https://doi.org/https://doi.org/10.1016/0096-0551(78)90009-7) | Elsevier | COLA (COMLAN) | C | 1972 | E |
| A global flow analysis algorithm | T&F | JCM | J | 1972 | E |
| [Safety of code motion](https://doi.org/10.1080/00207167208803056) | T&F | JCM | J | 1972 | O |
| [On the Number of Operations Simultaneously Executable in Fortran-Like Programs and Their Resulting Speedup](https://doi.org/10.1109/T-C.1972.223501) | IEEE | TCO | J | 1972 | D, O |
| [Testing flow graph reducibility](https://doi.org/10.1145/800125.804040) | ACM | STOC | C | 1973 | A |
| [A unified approach to global program optimization](https://doi.org/10.1145/512927.512945) | ACM | POPL | C | 1973 | A, D, E, M, O, S |
| Fast algorithms for the elimination of common subexpressions | Springer | Acta Inf. | J | 1973 | A, D, E, O |
| [Register allocation via usage counts](https://doi.org/10.1145/361179.361204) | ACM | CACM | J | 1974 | A |
| [Analysis of structured programs](https://doi.org/10.1145/800125.804055) | ACM | STOC | C | 1974 | D |
| [Characterizations of Reducible Flow Graphs](https://doi.org/10.1145/321832.321835) | ACM | JACM | J | 1974 | D, E |
| [The parallel execution of DO loops](https://doi.org/10.1145/360827.360844) | ACM | CACM | J | 1974 | D, O |
| [Interprocedural Data Flow Analysis](https://doi.org/10.1145/567446.567455) | - | IFIP | J | 1974 | D, O |
| Time and parallel processor bounds for linear recurrence systems | IEEE | TCO | J | 1975 | S |
| [A simple algorithm for global data flow analysis problems](https://doi.org/10.1137/0204038) | SIAM | SICOMP | J | 1975 | A, E, O |
| [A program data flow analysis procedure](https://doi.org/10.1145/360018.360025) | ACM | CACM | J | 1976 | A |
| [Recursion analysis for compiler optimization](https://doi.org/10.1145/360349.360355) | ACM | CACM | J | 1976 | O |
| [Optimal Code Generation for Expression Trees](https://doi.org/10.1145/321958.321970) | ACM | JACM | J | 1976 | A, D, E |
| [A Fast and Usually Linear Algorithm for Global Flow Analysis](https://doi.org/10.1145/321921.321939) | ACM | JACM | J | 1976 | E, O |
| [Code generation for expressions with common subexpressions](https://doi.org/10.1145/321958.321970) | ACM | POPL | C | 1976 | E, S |
| [Global data flow analysis and iterative algorithms](https://doi.org/10.1145/321921.321939) | ACM | JACM | J | 1976 | E, O |
| [On Live-Dead Analysis for Global Data Flow Problems](https://doi.org/10.1145/322017.322027) | ACM | JACM | J | 1977 | A |
| [Symbolic evaluation and the global value graph](https://doi.org/10.1145/512950.512961) | ACM | POPL | C | 1977 | A |
| [High-level data flow analysis](https://doi.org/10.1145/359842.359849) | ACM | CACM | J | 1977 | A |
| [Abstract interpretation](https://doi.org/10.1145/512950.512973) | ACM | POPL | C | 1977 | D |
| [An algorithm for reduction of operator strength](https://doi.org/10.1145/359863.359888) | ACM | CACM | J | 1977 | E |
| A transformation system for developing recursive programs | ACM | JACM | J | 1977 | S |
| [Arithmetic shifting considered harmful](https://doi.org/10.1145/956641.956647) | ACM | SIGPLAN Notices | J | 1977 | S |
| [Monotone data flow analysis frameworks](https://doi.org/10.1145/359842.359849) | Springer | Acta Inf. | J | 1977 | A, D, E, O |
| Program Improvement by Source-to-Source Transformation | ACM | CACM | J | 1977 | D, O |
| [An analysis of inline substitution for a structured programming language](https://doi.org/10.1145/359810.359830) | ACM | CACM | J | 1977 | M, S |
| [A new method for compiler code generation](https://doi.org/10.1145/512760.512785) | ACM | POPL | C | 1978 | D |
| [A practical interprocedural data flow analysis algorithm](https://doi.org/10.1145/359588.359596) | ACM | CACM | J | 1978 | A, D, E, O |
| [Data Flow Analysis for Procedural Languages](https://doi.org/10.1145/322123.322135) | ACM | JACM | J | 1979 | A |
| [Constructing the Call Graph of a Program](https://doi.org/10.1109/TSE.1979.234183) | IEEE | TSE | J | 1979 | O |
| [Data flow languages](https://doi.org/10.1145/322123.322135) | IEEE | MARK | W | 1979 | S |
| Time and parallel processor bounds for Fortran-like loops | IEEE | TCO | J | 1979 | S |
| [Unrolling loops in Fortran](https://doi.org/10.1002/spe.4380090807) | Wiley | SPE | J | 1979 | S |
| [A fast algorithm for finding dominators in a flowgraph](https://doi.org/10.1145/357062.357071) | ACM | TOPLAS | J | 1979 | A, E, M, O |
| An efficient way to find the side effects of procedural calls and the aliases of variables | ACM | POPL | C | 1979 | A, D, E, S |
| [Global optimization by suppression of partial redundancies](https://doi.org/10.1145/359060.359069) | ACM | CAMC | J | 1979 | A, D, E, O, S |
| Predicting the effects of optimization on a procedure body | ACM | PLDI (SCC) | C | 1979 | E, S |
| [Structural analysis: A new approach to flow analysis in optimizing compilers](https://doi.org/10.1016/0096-0551(80)90007-7) | Elsevier | COLA (COMLAN) | C | 1980 | A |
| [The design and application of a retargetable peephole optimizer](https://doi.org/10.1145/357094.357098) | ACM | TOPLAS | J | 1980 | E |
| [Data flow supercomputers](https://doi.org/10.1145/567446.567455) | IEEE | Computer | J | 1980 | S |
| High-speed multiprocessors and compilation techniques | IEEE | TCO | J | 1980 | S |
| [Interprocedural data flow analysis in the presence of pointers, procedure variables, and label variables](https://doi.org/10.1145/567446.567455)  | ACM | POPL | C | 1980 | A, E, O |
| [Deciding Linear Inequalities by Computing Loop Residues](https://doi.org/10.1145/322276.322288) | ACM | JACM | J | 1981 | D |
| [A precise inter-procedural data flow algorithm](https://doi.org/10.1145/567532.567556) | ACM | POPL | C | 1981 | O, S |
| [Register allocation via coloring](https://doi.org/10.1016/0096-0551(81)90025-5) | Elsevier | COLA (COMLAN) | C | 1981 | A, D, E, O, S |
| [Reduction of operator strength](https://doi.org/10.1145/359863.359888) | NJ | Program flow analysis | J | 1981 | A, E, S |
| [Dependence graphs and compiler optimizatlons](https://doi.org/10.1145/567532.567555) | ACM | POPL | C | 1981 | O, S |
| [On the performance enhancement of paging systems through program analysis and transformations](https://doi.org/10.1109/TC.1981.1675803) | IEEE | TCO | J | 1981 | D, S |
| [Optimizing delayed branches](https://doi.org/10.1145/1014194.800941) | ACM | MICRO | W | 1982 | D |
| A composite hoisting-strength reduction transformation for global program optimization part i | T&F | JCM | J | 1982 | E |
| [Optimization of range checking](https://doi.org/10.1145/800230.806986) | ACM | PLDI (SCC) | C | 1982 | E |
| [Register allocation and spilling via graph coloring](https://doi.org/10.1145/800230.806981) | ACM | PLDI | C | 1982 | A, D, E, M, O, S |
| [Experience with the SETL optimizer](https://doi.org/10.1145/69624.357194) | ACM | TOPLAS | J | 1983 | S |
| [Postpass Code Optimization of Pipeline Constraints](https://doi.org/10.1145/2166.357217) | ACM | TOPLAS | J | 1983 | A, E |
| [Conversion of control dependence to data dependence](https://doi.org/10.1145/567067.567085) | ACM | POPL | C | 1983 | O, S |
| [Register allocation and exhaustive peephole optimization](https://doi.org/10.1145/364995.365000) | Wiley | SPE | J | 1984 | E |
| [Automatic generation of peephole optimizations](https://doi.org/10.1145/364995.365000) | Springer | CC | C | 1984 | E |
| Analysis of interprocedural side effects in a parallel programming environment | Springer | ICSP | C | 1984 | O |
| Polyvariant mixed computation for analyzer programs | Springer | Acta Inf. | J | 1984 | O |
| [Stream processing](https://doi.org/10.1145/800055.802021) | ACM | LFP | C | 1984 | O |
| [A hierarchical basis for reordering transformations](https://doi.org/10.1145/800017.800539) | ACM | POPL | C | 1984 | O |
| [Register allocation by priority-based coloring](https://doi.org/10.1145/502949.502896) | ACM | PLDI (SCC) | C | 1984 | A, E, O |
| Automatic loop interchange | ACM | PLDI (SCC) | C | 1984 | O, S |
| Efficient computation of flow insensitive interprocedural summary information | ACM | PLDI (SCC) | C | 1984 | A, O |
| [On linearizing parallel code](https://doi.org/10.1145/318593.318636) | ACM | POPL | C | 1985 | O |
| Distributed execution of functional programs using serial combinators | IEEE | TCO | J | 1985 | S |
| Strictness analysis-a practical approach | Springer | FPCA | C | 1985 | S |
| [A linear algorithm for finding dominators in flow graphs and related problems](https://doi.org/10.1145/22145.22166) | ACM | STOC | C | 1985 | E, M, O |
| Efficient instruction scheduling for a pipelined architecture | ACM | PLDI (SCC) | C | 1986 | A |
| [Efficient symbolic analysis of programs](https://doi.org/https://doi.org/10.1016/0022-0000(86)90031-0) | ACM | JCSS | J | 1986 | A |
| [Graph-Based Algorithms for Boolean Function Manipulation](https://doi.org/10.1109/TC.1986.1676819) | IEEE | TC | J | 1986 | D |
| Loops skewing: The wavefront method revisited | Springer | JPP | J | 1986 | O |
| Highly concurrent scalar processing | ACM | CAN | J | 1986 | O |
| Multiplication by integer constants | Wiley | SPE | J | 1986 | S |
| [Global register allocation at link time](https://doi.org/10.1145/12276.13338) | ACM | PLDI | C | 1986 | A, E |
| [Interprocedural constant propagation](https://doi.org/10.1145/176454.176526) | ACM | PLDI | C | 1986 | A, D, E, O, S |
| [Interprocedural optimization: eliminating unnecessary recompilation](https://doi.org/10.1145/12276.13317) | ACM | CC | C | 1986 | A, E, O |
| Interprocedural dependence analysis and parallelization | ACM | PLDI | C | 1986 | O, S |
| [Effectiveness of a machine-level, global optimizer](https://doi.org/10.1145/12276.13321)  | ACM | PLDI (SCC) | C | 1986 | A, E |
| [Direct parallelization of call statements](https://doi.org/10.1145/13310.13329) | ACM | PLDI (SCC) | C | 1986 | O, S |
| Code motion of control structures in high-level languages | ACM | POPL | C | 1986 | E, M |
| [Automatic inference and fast interpretation of peephole optimization rules](https://doi.org/10.1145/364995.365000) | Wiley | SPE | J | 1987 | E |
| [Compiler Algorithms for Synchronization](https://doi.org/10.1109/TC.1987.5009499) | IEEE | TCO | J | 1987 | O |
| [Automatic decomposition of scientific programs for parallel execution](https://doi.org/10.1145/41625.41631) | ACM | POPL | C | 1987 | O |
| [Guided Self-Scheduling: A Practical Scheduling Scheme for Parallel Supercomputers](https://doi.org/10.1109/TC.1987.5009495) | IEEE | TCO | J | 1987 | S |
| Loop coalescing: A compiler transformation for parallel machines | ACM | ICPP | C | 1987 | S |
| Strategies for cache and local memory management by global program transformation | Springer | ICS | C | 1987 | S |
| The program dependence graph and its use in optimization | ACM | TOPLAS | J | 1987 | A, E, M, O |
| [Automatic translation of Fortran programs to vector form](https://doi.org/10.1145/41625.41631) | ACM | TOPLAS | J | 1987 | D, O, S |
| [An efficient approach to data flow analysis in a multiple pass global optimizer](https://doi.org/10.1145/960116.54006) | ACM | PLDI | C | 1988 | A |
| [A solution to a problem with Morel and Renvoise's ``Global optimization by suppression of partial redundancies''](https://doi.org/10.1145/359060.359069) | ACM | TOPLAS | J | 1988 | E |
| [Efficient computation of flow-insensitive interprocedural summary information—a correction](https://doi.org/10.1145/960116.54006) | ACM | SIGPLAN Notices | J | 1988 | O |
| [Dependence of multi-dimensional array references](https://doi.org/10.1145/55364.55405) | ACM | ICS | C | 1988 | O |
| [The importance of direct dependences for automatic parallelization](https://doi.org/10.1145/55364.55404) | ACM | ICS | C | 1988 | O |
| [Introducing symbolic problem solving techniques in the dependence testing phases of a vectorizer](https://doi.org/10.1145/55364.55403) | ACM | ICS | C | 1988 | O |
| [Generating sequential code from parallel code](https://doi.org/10.1145/55364.55421) | ACM | SC | C | 1988 | O |
| Advanced loop optimizations for parallel computers | ACM | ICS | C | 1988 | S |
| An introduction to a formal theory of dependence analysis | Springer | JSC | J | 1988 | S |
| [Analysis of interprocedural side effects in a parallel programming environment](https://doi.org/10.1145/62116.62125) | ACM | ICS | C | 1988 | S |
| Array expansion | ACM | ICS | C | 1988 | S |
| [Loop quantization: A generalized loop unwinding technique](https://doi.org/https://doi.org/10.1016/0743-7315(88)90013-5) | ACM | JPDC | J | 1988 | S |
| Supernode partitioning | ACM | PLDI | C | 1988 | S |
| A fast algorithm for code movement optimisation | ACM | PLDI | C | 1988 | A, E |
| Compiling programs for distributed-memory multiprocessors | Elsevier | JSC | J | 1988 | O, S |
| Optimal loop parallelization | ACM | PLDI | C | 1988 | A, E, M, S |
| [Software pipelining: an effective scheduling technique for VLIW machines](https://doi.org/10.1145/960116.54022) | ACM | PLDI | C | 1988 | D, E |
| The program summary graph and flow-sensitive interprocedual data flow analysis | ACM | PLDI | C | 1988 | A, O |
| A framework for determining useful parallelism | ACM | ICS | C | 1988 | O, S |
| An overview of the PTRAN analysis system for multiprocessing | Elsevier | JPDC | J | 1988 | D, S |
| [Efficient interprocedural analysis for program parallelization and restructuring](https://doi.org/10.1145/62116.62125) | ACM | PPoPP (PPEALS) | C | 1988 | O, S |
| Compiling issues for supercomputers | ACM/IEEE | SC | C | 1988 | O, S |
| Minimizing register usage penalty at procedure calls | ACM | PLDI | C | 1988 | A, S |
| Estimating interlock and improving balance for pipelined architectures | Elsevier | JPDC | J | 1988 | O, S |
| [Global value numbers and redundant computations](https://doi.org/10.1145/73560.73562) | ACM | POPL | C | 1988 | E, O |
| [Perfect pipelining: A new loop parallelization technique](https://doi.org/10.1145/960116.54022) | Springer | ESOP | C | 1988 | A, S |
| Code scheduling and register allocation in large basic blocks | ACM | SC | C | 1988 | A, E |
| [Interprocedural side-effect analysis in linear time](https://doi.org/10.1145/62116.62125) | ACM | PLDI | C | 1988 | A, E, O |
| Unified management of registers and cache using liveness and cache bypass | ACM | PLDI | C | 1989 | A |
| A new algorithm for composite hoisting and strength reduction optimisation | T&F | JCM | J | 1989 | E |
| [Program optimization for instruction caches](https://doi.org/10.1145/68182.68200) | ACM | ASPLOS | C | 1989 | A |
| [Dependence analysis for pointer variables](https://doi.org/10.1145/73141.74821) | ACM | PLDI | C | 1989 | E |
| [The program dependence graph and vectorization](https://doi.org/10.1145/75277.75278) | ACM | POPL | C | 1989 | O |
| [Achieving high instruction cache performance with an optimizing compiler](https://doi.org/10.1145/68182.68200) | ACM | ISCA | C | 1989 | S |
| Evaluating the performance of four snooping cache coherency protocols | IEEE | ICSA | C | 1989 | S |
| Scans as primitive parallel operations | IEEE | TCO | J | 1989 | S |
| [Code generation using tree matching and dynamic programming](https://doi.org/10.1145/69558.75700) | ACM | TOPLAS | J | 1989 | A, D, E, M |
| [Register allocation via clique separators](https://doi.org/10.1145/73141.74842) | ACM | PLDI | C | 1989 | A, E |
| [Fast interprocedual alias analysis](https://doi.org/10.1145/75277.75282) | ACM | POPL | C | 1989 | A, E, O, S |
| [Coloring heuristics for register allocation](https://doi.org/10.1145/73141.74843) | ACM | PLDI | C | 1989 | A, E, O |
| [More iteration space tiling](https://doi.org/10.1145/76263.76337) | ACM/IEEE | SC | C | 1989 | A, S |
| [Data dependence analysis on multi-dimensional array references](https://doi.org/10.1145/318789.318813) | ACM | ICS | C | 1989 | O, S |
| [Spill code minimization techniques for optimizing compliers](https://doi.org/10.1145/73141.74841) | ACM | PLDI | C | 1989 | A, E |
| Customization: Optimizing compiler technology for SELF, a dynamically-typed OOP language  | ACM | PLDI | C | 1989 | O, S |
| An efficient method of computing static single assignment form | ACM | POPL | C | 1989 | A, O |
| [An approach to ordering optimizing transformations](https://doi.org/10.1145/99163.99179) | ACM | PPoPP | C | 1990 | A |
| [Register allocation across procedure and module boundaries](https://doi.org/10.1145/93548.93551) | ACM | PLDI | C | 1990 | A |
| [Region Scheduling: An Approach for Detecting and Redistributing Parallelism](https://doi.org/10.1109/32.54294) | IEEE | TSE | J | 1990 | E |
| [Constructing the procedure call multigraph](https://doi.org/10.1109/32.54302) | IEEE | TSE | J | 1990 | O |
| On the perfect accuracy of an approximate subscript analysis test | ACM | CAN | J | 1990 | O |
| Structured dataflow analysis for arrays and its use in an optimizing compiler | Wiley | Software: Practice and Experience | J | 1990 | O |
| Compilation of Haskell array comprehensions for scientific computing | ACM | PLDI | C | 1990 | S |
| [How to read floating point numbers accurately](https://doi.org/10.1145/93548.93557) | ACM | PLDI | C | 1990 | S |
| [How to print floating-point numbers accurately](https://doi.org/10.1145/93548.93559) | ACM | PLDI | C | 1990 | S |
| [Profile guided code positioning](https://doi.org/10.1145/93548.93550) | ACM | PLDI | C | 1990 | S |
| Updating distributed variables in local computations | Wiley | SPE | J | 1990 | S |
| [An interval-based approach to exhaustive and incremental interprocedural data-flow analysis](https://doi.org/10.1145/78969.78963) | ACM | TOPLAS | J | 1990 | E, O |
| [The priority-based coloring approach to register allocation](https://doi.org/10.1145/93548.93552) | ACM | TOPLAS | J | 1990 | A, D, E, S |
| [Improving register allocation for subscripted variables](https://doi.org/10.1145/93548.93551) | ACM | PLDI | C | 1990 | A, E, M, O, S |
| [Analysis of pointers and structures](https://doi.org/10.1145/93542.93585) | ACM | PLDI | C | 1990 | A, E |
| Loop distribution with arbitrary control flow | ACM | PLDI | C | 1990 | O, S |
| [Graph coloring register allocation for processors with multi-register operands](https://doi.org/10.1145/93548.93552) | ACM | PLDI | C | 1990 | A, E |
| Register allocation via hierarchical graph coloring | ACM | PLDI | C | 1991 | A |
| [Circular scheduling: a new technique to perform software pipelining](https://doi.org/10.1145/113445.113464) | ACM | PLDI | C | 1991 | A |
| [Efficient DAG construction and heuristic calculation for instruction scheduling](https://doi.org/10.1145/123465.123482) | ACM | MICRO | W | 1991 | E |
| A composite algorithm for strength reduction and code movement optimization | Springer | ACIS | J | 1991 | E |
| [Efficiently computing static single assignment form and the control dependence graph](https://doi.org/10.1145/115372.115320) | ACM | TOPLAS | J | 1991 | M |
| [Software prefetching](https://doi.org/10.1145/106972.106979) | ACM | ASPLOS | C | 1991 | O |
| [Compiling global name-space parallel loops for distributed execution](https://doi.org/10.1109/71.97901) | IEEE | TPDS | J | 1991 | O |
| An implementation of interprocedural bounded regular section analysis | ACM | TPDS | J | 1991 | O |
| Limits of instruction-level parallelism | ACM | ASPLOS | C | 1991 | S |
| [Uniform techniques for loop optimization](https://doi.org/10.1145/109025.109077) | ACM | ICS | C | 1991 | S |
| [A data locality optimizing](https://doi.org/10.1145/113446.113449) | ACM | PLDI | C | 1991 | A, D, M, O |
| [Constant propagation with conditional branches](https://doi.org/10.1145/115372.115386) | ACM | TOPLAS | J | 1991 | A, E, M, O, S |
| [Efficient and exact data dependence analysis](https://doi.org/10.1145/113446.113447) | ACM | PLDI | C | 1991 | A, D, O |
| [Efficiently computing static single assignment](https://doi.org/10.1145/115372.115320) | ACM | TOPLAS | J | 1991 | A, D, E, O |
| [Global instruction scheduling for superscalar machines](https://doi.org/10.1145/113446.113466) | ACM | PLDI | C | 1991 | A, D, E |
| [Practical adaption of the global optimization algorithm of Morel and Renvoise](https://doi.org/10.1145/106972.106981) | ACM | TOPLAS | J | 1991 | A, E |
| [The cache performance and optimizations of blocked algorithms](https://doi.org/10.1145/106972.106981) | ACM | ASPLOS | C | 1991 | A, D |
| [A loop transformation theory and an algorithm to maximize parallelism](https://doi.org/10.1145/109025.109077) | IEEE | TPDS | J | 1991 | O, S |
| Dataflow analysis of array and scalar references | Springer | JPP | J | 1991 | A, S |
| [Optimization of array accesses by collective loop transformations](https://doi.org/10.1145/109025.109077) | ACM | SC | C | 1991 | D, O |
| Interprocedural transformations for parallel code generation | ACM/IEEE | SC | C | 1991 | O, S |
| [Practical dependence testing](https://doi.org/10.1145/113446.113468) | ACM | PLDI | C | 1991 | A, O |
| Procedure merging with instruction caches | ACM | PLDI | C | 1991 | A, S |
| An experiment with inline substitution | Wiley | SPE | J | 1991 | E, S |
| Integrating scalar optimization and parallelization | Springer | LCPC | C | 1992 | A |
| [Sharlit—a tool for building optimizers](https://doi.org/10.1145/143103.143120) | ACM | PLDI | C | 1992 | A |
| How to analyze large programs efficiently and informatively | ACM | PLDI | C | 1992 | A |
| Compiler code transformations for superscalar-based high performance systems | IEEE | SC | C | 1992 | A |
| [Engineering a simple, efficient code-generator generator](https://doi.org/10.1145/151640.151642)  | ACM | TOPLAS (LOPLAS) | J | 1992 | D |
| Some efficient solutions to the affine scheduling problem. I. One-dimensional time | Elsevier | JPP | J | 1992 | D |
| [Avoiding unconditional jumps by code replication](https://doi.org/10.1145/143095.143144) | ACM | PLDI | C | 1992 | E |
| [Rematerialization](https://doi.org/10.1145/143103.143143) | ACM | PLDI | C | 1992 | E |
| Coloring register pairs | ACM | TOPLAS (LOPLAS) | J | 1992 | E |
| Optimizing for parallelism and data locality | ACM | SC | C | 1992 | O |
| Maximizing loop parallelism and improving data locality via loop fusion and distribution | ACM | LCPC | W | 1992 | O |
| [Beyond induction variables](https://doi.org/10.1145/143103.143131) | ACM | PLDI | C | 1992 | O |
| [Efficient call graph analysis](https://doi.org/10.1145/151640.151643) | ACM | TOPLAS (LOPLAS) | J | 1992 | O |
| [A safe approximate algorithm for interprocedural aliasing](https://doi.org/10.1145/143095.143137) | ACM | PLDI | C | 1992 | O |
| [Relaxing SIMD control flow constraints using loop transformations](https://doi.org/10.1145/143103.143133) | ACM | PLDI | C | 1992 | S |
| [Unexpected side effects of inline substitution: a case study](https://doi.org/10.1145/130616.130619) | ACM | TOPLAS (LOPLAS) | J | 1992 | S |
| [Eliminating false positives using the omega test](https://doi.org/10.1145/143103.143129) | ACM | PLDI | C | 1992 | A, D, O |
| [Lazy code motion](https://doi.org/10.1145/143103.143136) | ACM | PLDI | C | 1992 | A, D, E |
| [Software support for speculative loads](https://doi.org/10.1145/143365.143484) | ACM | ASPLOS | C | 1992 | A, E |
| [A practical algorithm for exact array dependence analysis](https://doi.org/10.1145/135226.135233) | ACM | CACM | J | 1992 | O, S |
| [Array privatization for parallel execution of loops](https://doi.org/10.1145/143369.143426) | ACM | ICS | C | 1992 | O, S |
| [The power test for data dependence](https://doi.org/10.1145/143103.143129) | IEEE | TCO | J | 1992 | A, S |
| Eliminating branches using a superoptimizer and the GNU C compiler | ACM | PLDI | C | 1992 | E, S |
| [Design and evaluation of a compiler algorithm for prefetching](https://doi.org/10.1145/143371.143488) | ACM | ASPLOS | C | 1992 | D, O |
| [Dependence-based program analysis](https://doi.org/10.1145/155090.155098) | ACM | PLDI | C | 1993 | A |
| [A variation of Knoop, R{"u}thing, and Steffen's lazy code motion](https://doi.org/10.1145/143103.143136)  | ACM | PLDI | C | 1993 | E |
| Lazy strength reduction | C&H | JPL | J | 1993 | A, E |
| Collective loop fusion for array contraction | Springer | LCPC | C | 1993 | O |
| [Interprocedural constant propagation: an empirical study](https://doi.org/10.1145/176454.176526) | ACM | TOPLAS (LOPLAS) | J | 1993 | O |
| Symbolic analysis: A basis for parallelization, optimization, and scheduling of programs  | Springer | LCPC | W | 1993 | O |
| [Array-data flow analysis and its use in array privatization](https://doi.org/10.1145/158511.158515) | ACM | POPL | C | 1993 | S |
| [Automatic array alignment in data-parallel programs](https://doi.org/10.1145/158511.158515) | ACM | POPL | C | 1993 | S |
| Global optimizations for parallelism and locality on scalable parallel machines | ACM | PLDI | C | 1993 | S |
| [Instruction-Level Parallel Processing: History, Overview, and Perspective](https://doi.org/10.1007/978-1-4615-3200-2_3)  | Springer | JSC | J | 1993 | S |
| A practical system for intermodule code optimization at link-time | C&H | JPL | J | 1993 | A |
| Loop-level parallelism in numeric and symbolic programs | IEEE | TPDS | J | 1993 | S |
| [Orchestrating interactions among parallel computations](https://doi.org/10.1145/173262.155100) | ACM | PLDI | C | 1993 | S |
| The superblock: an effective technique for VLIW and superscalar compilation | Springer | JSC | J | 1993 | S |
| [Optimizing array bound checks using flow analysis](https://doi.org/10.1145/176454.176507) | ACM | PLDI | C | 1993 | A, E |
| [Register allocation with instruction scheduling](https://doi.org/10.1145/173262.155114) | ACM | PLDI | C | 1993 | A, E |
| A methodology for procedure cloning | Elsevier | COLA (COMLAN) | J | 1993 | A, O, S |
| Efficient flow-sensitive interprocedural computation of pointer-induced aliases and side effects | ACM | POPL | C | 1993 | E, O, S |
| [Automatic array privatization](https://doi.org/10.1145/158511.158515) | Springer | LCPC | W | 1993 | O, S |
| Interprocedural modification side effect analysis with pointer aliasing | ACM | PLDI | C | 1993 | M, S |
| Branch prediction for free | ACM | PLDI | C | 1993 | A, M |
| [Link-time optimization of address calculation on a 64-bit architecture](https://doi.org/10.1145/178243.178248) | ACM | PLDI | C | 1994 | A |
| Effective partial redundancy elimination | ACM | PLDI | C | 1994 | A |
| Partial dead code elimination | ACM | PLDI | C | 1994 | A |
| [A general data dependence test for dynamic, pointer-based data structures](https://doi.org/10.1145/178243.178262)  | ACM | PLDI | C | 1994 | A |
| Instruction scheduling over regions: A framework for scheduling across basic blocks | Springer | CC | C | 1994 | A |
| [Value dependence graphs: representation without taxation](https://doi.org/10.1145/174675.177907) | ACM | POPL | C | 1994 | A |
| [Zero-cost range splitting](https://doi.org/10.1145/773473.178420) | ACM | PLDI | C | 1994 | E |
| [Reducing branch costs via branch alignment](https://doi.org/10.1145/381792.195553) | ACM | OSR | J | 1994 | E |
| [Improving the ratio of memory operations to floating-point operations in loops](https://doi.org/10.1145/197320.197366) | ACM | TOPLAS | J | 1994 | M |
| [Optimizing multi-method dispatch using compressed dispatch tables](https://doi.org/10.1145/191081.191117) | ACM | OOPSLA | C | 1994 | M |
| [Improving the accuracy of static branch prediction using branch correlation](https://doi.org/10.1145/381792.195549) | ACM | ASPLOS | C | 1994 | M |
| [A compiler framework for restructuring data declarations to enhance cache and TLB effectiveness](https://dl.acm.org/citation.cfm?id=782188) | IEEE | CASCON | C | 1994 | S |
| [False sharing and spatial locality in multiprocessor caches](https://doi.org/10.1109/12.286299) | IEEE | TCO | J | 1994 | S |
| Reassociation and strength reduction | ACM | SCO | C | 1994 | S |
| The alignment-distribution graph | Springer | LCPC | W | 1994 | S |
| [Improvements to graph coloring register allocation](https://doi.org/10.1145/177492.177575) | ACM | TOPLAS | J | 1994 | A, E, M |
| [Context-sensitive interprocedural points-to analysis in the presence of function pointers](https://doi.org/10.1145/178243.178264) | ACM | PLDI | C | 1994 | D, E |
| [Interprocedural may-alias analysis for pointers: beyond k-limiting](https://doi.org/10.1145/178243.178263) | ACM | PLDI | C | 1994 | A, E |
| [Scalar replacement in the presence of conditional control flow](https://doi.org/10.1002/spe.4380240104) | Wiley | SPE | J | 1994 | E, O |
<!-- | Corpus-based static branch prediction | ACM | PLDI | C | 1995 | A |
| [Resource-Constrained Software Pipelining](https://doi.org/10.1109/71.476167) | IEEE | TPDS | J | 1995 | A |
| [Elimination of redundant array subscript range checks](https://doi.org/10.1145/223428.207160) | ACM | PLDI | C | 1995 | A |
| [Improving balanced scheduling with compiler optimizations that increase instruction-level parallelism](https://doi.org/10.1145/223428.207132) | ACM | PLDI | C | 1995 | A |
| [Accurate static branch prediction by value range propagation](https://doi.org/10.1145/207110.207117) | ACM | PLDI | C | 1995 | A |
| [Tile size selection using cache organization and data layout](https://doi.org/10.1145/207110.207162) | ACM | PLDI | C | 1995 | E |
| [Combining analyses, combining optimizations](https://doi.org/10.1145/201059.201061)  | ACM | TOPLAS | J | 1995 | E |
| [Global code motion/global value numbering](https://doi.org/10.1145/207110.207154) | ACM | PLDI | C | 1995 | E |
| [A linear time algorithm for placing φ-nodes](https://doi.org/10.1145/199448.199464) | ACM | POPL | C | 1995 | O |
| [Points-to analysis in linear time](https://doi.org/10.1145/237721.237727) | ACM | POPL | C | 1996 | D |
| Aggressive loop unrolling in a retargetable, optimizing compiler  | Springer | CC | C | 1996 | E |
| [Iterated register coalescing](https://doi.org/10.1145/229542.229546) | ACM | TOPLAS | J | 1996 | E, M |
| [Improving data locality with loop transformations](https://doi.org/10.1145/233561.233564) | ACM | TOPLAS | J | 1996 | E, O |
| [Maximizing parallelism and minimizing synchronization with affine transforms](https://doi.org/10.1145/263699.263719) | ACM | POPL | C | 1997 | D |
| [Fast and accurate flow-insensitive points-to analysiS](https://doi.org/10.1145/263699.263703) | ACM | PLDI | C | 1997 | E |
| Register promotion in C programs | ACM | PLDI | C | 1997 | E |
| [Efficient procedure mapping using cache line coloring](https://doi.org/10.1145/258916.258931) | ACM | PLDI | C | 1997 | E |
| [Spill code minimization via interference region spilling](https://doi.org/10.1145/258916.258941) | ACM | PLDI | C | 1997 | E |
| Aggressive inlining | ACM | PLDI | C | 1997 | E |
| [Optimal weighted loop fusion for parallel programs](https://doi.org/10.1145/258492.258520) | ACM | SPAA | C | 1997 | O |
| [Near-optimal intraprocedural branch alignment](https://doi.org/10.1145/258915.258932) | ACM | PLDI | C | 1997 | E, M |
| [Value numbering](https://doi.org/10.1145/207110.207154) | Wiley | SPE | J | 1997 | A, E |
| [A new algorithm for scalar register promotion based on SSA form](https://doi.org/10.1145/277650.277656) | ACM | PLDI | C | 1998 | E |
| [Register promotion by sparse partial redundancy elimination of loads and stores](https://doi.org/10.1145/277650.277659) | ACM | PLDI | C | 1998 | E |
| [Cost-optimal code motion](https://doi.org/10.1145/295656.295664) | ACM | TOPLAS | J | 1998 | E |
| International Conference on Compiler Construction | Springer | CC | C | 1998 | E |
| [Complete removal of redundant expressions](https://doi.org/10.1145/277652.277653) | ACM | PLDI | C | 1998 | E |
| [Using integer sets for data-parallel program analysis and optimization](https://doi.org/10.1145/277652.277721) | ACM | PLDI | C | 1998 | O |
| [Bidirectional data flow analysis: myths and reality](https://doi.org/10.1145/606666.606676) | ACM | SIGPLAN Notices | J | 1999 | A |
| [An affine partitioning algorithm to maximize parallelism and minimize communication](https://doi.org/10.1145/305138.305197) | ACM | SC | C | 1999 | D |
| [Interprocedural pointer alias analysis](https://doi.org/10.1145/325478.325519) | ACM | TOPLAS | J | 1999 | E |
| [Dominators in linear time](https://doi.org/10.1137/0128054) | SIAM | SICOMP | J | 1999 | E |
| [Scalable context-sensitive flow analysis using instantiation constraints](https://doi.org/10.1145/358438.349332) | ACM | PLDI | C | 2000 | D |
| Unification-based pointer analysis with directional assignments | ACM | PLDI | C | 2000 | E |
| [Fast greedy weighted fusion](https://doi.org/10.1145/335231.335244) | ACM | ICS | C | 2000 | O |
| [Blocking and array contraction across arbitrarily nested loops using affine partitioning](https://doi.org/10.1145/568014.379586) | ACM | PPoPP | C | 2001 | D |
| [Ultra-fast Aliasing Analysis using CLA: A Million Lines of C Code in a Second](https://doi.org/10.1145/381694.378855) | ACM | PLDI | C | 2001 | D |
| [A simple, fast dominance algorithm](https://doi.org/10.1002/spe.381)  | Wiley | SPE | J | 2001 | E, O |
| [Operator Strength Reduction](https://doi.org/10.1145/504083.504090) | ACM | TOPLAS | J | 2001 | A, E |
| [Symbolic pointer analysis](https://doi.org/10.1145/996893.996860) | IEEE | ICCAD | C | 2002 | D |
| [Cloning-based context-sensitive pointer alias analysis using binary decision diagrams](https://doi.org/10.1145/996841.996859) | ACM | PLDI | C | 2004 | D |
| [Symbolic pointer analysis Revisited](https://doi.org/10.1145/996893.996860) | ACM | PLDI | C | 2004 | D |
| [A generalized algorithm for graph-coloring register allocation](https://doi.org/10.1145/996893.996875) | ACM | PLDI | C | 2004 | E |
| [Optimistic register coalescing](https://doi.org/10.1145/1011508.1011512) | ACM | TOPLAS | J | 2004 | E |
| [Context-sensitive program analysis as database queries](https://doi.org/10.1145/1065167.1065169) | ACM | PODS | C | 2005 | D |
| [Improving software security with a C pointer analysis](https://doi.org/10.1145/1062455.1062520) | IEEE | ICSE | C | 2005 | D |
| [Register allocation via coloring of chordal graphs](https://doi.org/10.1007/11575467_20) | Springer | APLAS | C | 2005 | E |
| [Polynomial time graph coloring register allocation](https://doi.org/10.1145/1064978.1065003) | ACM | PLDI | C | 2005 | E |
| [Optimal register allocation for SSA-form programs in polynomial time](https://doi.org/10.1016/j.ipl.2006.01.008) | Elsevier | IPL | J | 2006 | E | -->