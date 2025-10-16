# Papers on Compiler Optimizations: Analysis and Transformations (1952-1994)

> [!NOTE]
> This repository is updated periodically.
> The papers up to 1994 should be almost complete. The following years will arrive soon, incrementally.
> **Contributions are welcome!**

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

| Paper Title | Authors | Venue Type | Venue Name | Type | Year | Sources |
|---|---|---|---|---|---|---|
| [The problem of simplifying truth functions](https://doi.org/10.1080/00029890.1952.11988183) | Quine W. | T&F | AMM | J | 1952 | O |
| [Minimization of Boolean functions](https://doi.org/10.1002/j.1538-7305.1956.tb03835.x) | McCluskey E. | Bell Labs | Bell System Tech. J. | J | 1956 | O |
| [An algorithm for translating Boolean expressions](https://doi.org/10.1145/321119.321121) | Arden B., Galler B., Graham R. | ACM | JACM | J | 1962 | S |
| [High speed compilation of efficient object code](https://doi.org/10.1145/365474.365489) | Gear C. | ACM | CACM | J | 1965 | D |
| [Peephole optimization](https://doi.org/10.1145/364995.365000) | McKeeman W. | ACM | CACM | J | 1965 | E |
| [Index Register Allocation](https://doi.org/10.1145/321312.321317) | Horwitz L., Karp R., Miller R., Winograd S. | ACM | JACM | J | 1966 | E |
| [Analysis of Programs for Parallel Processing](https://doi.org/10.1109/PGEC.1966.264565) | Bernstein A. | IEEE | TC (TEC) | J | 1966 | O |
| [Program optimization](https://doi.org/10.1145/68182.68200) |  | - | PP | C | 1966 | A, D, E, M, O, S |
| [Object code optimization](https://doi.org/10.1145/362835.362838) | Lowry E., Medlock C. | ACM | CACM | J | 1969 | A, D, E |
| [Local optimizations](https://doi.org/10.1145/390013.808484) | Bagwell Jr J. | ACM | PLDI (SCO) | C | 1970 | E |
| [Detection and parallel execution of independent instructions](https://doi.org/10.1109/T-C.1970.222795) | Tjaden G., Flynn M. | IEEE | TCO | J | 1970 | S |
| [Global common subexpression elimination](https://doi.org/10.1145/800028.808480) | Cocke J. | ACM | PLDI (SCO) | C | 1970 | D, E, M |
| [The Generation of Optimal Code for Arithmetic Expressions](https://doi.org/10.1145/321607.321620) | Sethi R., Ullman J. | ACM | JACM | J | 1970 | D, E, M |
| [Control flow analysis](https://doi.org/10.1145/390013.808479) | Allen F. | ACM | PLDI (SCO) | C | 1970 | D, E |
| A Basis for Program Optimization |  | IFIP | NH | C | 1971 | A, D, E, M, O, S |
| A catalogue of optimizing transformations | Frances E. Allen J. | - | PH | C | 1972 | A, D, E, M, O, S |
| [Flow graph reducibility](https://doi.org/10.1145/800152.804919) | Hecht M., Ullman J. | ACM | STOC | C | 1972 | D |
| [Use-definition chains with applications](https://doi.org/https://doi.org/10.1016/0096-0551(78)90009-7) |  | Elsevier | COLA (COMLAN) | C | 1972 | E |
| A global flow analysis algorithm | Kennedy K. | T&F | JCM | J | 1972 | E |
| [Safety of code motion](https://doi.org/10.1080/00207167208803056) |  | T&F | JCM | J | 1972 | O |
| [On the Number of Operations Simultaneously Executable in Fortran-Like Programs and Their Resulting Speedup](https://doi.org/10.1109/T-C.1972.223501) | Kuck D., Muraoka Y. | IEEE | TCO | J | 1972 | D, O |
| [Testing flow graph reducibility](https://doi.org/10.1145/800125.804040) | Tarjan R. | ACM | STOC | C | 1973 | A |
| [A unified approach to global program optimization](https://doi.org/10.1145/512927.512945) | Kildall G. | ACM | POPL | C | 1973 | A, D, E, M, O, S |
| Fast algorithms for the elimination of common subexpressions | Ullman J. | Springer | Acta Inf. | J | 1973 | A, D, E, O |
| [Interprocedural Analysis and the Information derived by it](https://doi.org/10.1007/BF00264216) | Allen F. | Springer | Prog. Meth. | J | 1974 | - |
| [Register allocation via usage counts](https://doi.org/10.1145/361179.361201) | Freiburghouse R. | ACM | CACM | J | 1974 | A |
| [Analysis of structured programs](https://doi.org/10.1145/800125.804055) | Kosaraju S. | ACM | STOC | C | 1974 | D |
| [Characterizations of Reducible Flow Graphs](https://doi.org/10.1145/321832.321835) | Hecht M., Ullman J. | ACM | JACM | J | 1974 | D, E |
| [The parallel execution of DO loops](https://doi.org/10.1145/360827.360844) | Lamport L. | ACM | CACM | J | 1974 | D, O |
| [Interprocedural Data Flow Analysis](https://doi.org/10.1145/567446.567455) |  | - | IFIP | J | 1974 | D, O |
| [Application of lattice algebra to loop optimization](https://doi.org/10.1145/512976.512977) | Fong A., Kam J., Ullman J. | ACM | POPL | C | 1975 | - |
| [Program optimization - theory and practice](https://doi.org/10.1145/390015.808407) | Loveman D., Faneuf R. | ACM | PLDI (SCC) | C | 1975 | - |
| Time and parallel processor bounds for linear recurrence systems | Chen S., Kuck D. | IEEE | TCO | J | 1975 | S |
| [A simple algorithm for global data flow analysis problems](https://doi.org/10.1145/512927.512946) | Hecht M., Ullman J. | SIAM | SICOMP | J | 1975 | A, E, O |
| [Program improvement by source to source transformation](http://dx.doi.org/10.1145/800168.811548) | Loveman D. | ACM | POPL | C | 1976 | - |
| [A program data flow analysis procedure](https://doi.org/10.1145/360018.360025) | Allen F., Cocke J. | ACM | CACM | J | 1976 | A |
| [Recursion analysis for compiler optimization](https://doi.org/10.1145/360336.360341) | Walter K. | ACM | CACM | J | 1976 | O |
| [Optimal Code Generation for Expression Trees](https://doi.org/10.1145/321958.321970) | Aho A., Johnson S. | ACM | JACM | J | 1976 | A, D, E |
| [A Fast and Usually Linear Algorithm for Global Flow Analysis](https://doi.org/10.1145/321921.321939) | Graham S., Wegman M. | ACM | JACM | J | 1976 | E, O |
| [Code generation for expressions with common subexpressions](https://doi.org/10.1145/321992.322001) | Aho A., Johnson S., Ullman J. | ACM | POPL | C | 1976 | E, S |
| [Global data flow analysis and iterative algorithms](https://doi.org/10.1145/321921.321938) | Kam J., Ullman J. | ACM | JACM | J | 1976 | E, O |
| [Compiler Analysis of the Value Ranges for Variables](https://doi.org/10.1109/TSE.1977.231133) | Harrison W. | IEEE | TSE | J | 1977 | - |
| [On Live-Dead Analysis for Global Data Flow Problems](https://doi.org/10.1145/322017.322027) | Kou L. | ACM | JACM | J | 1977 | A |
| [Symbolic evaluation and the global value graph](https://doi.org/10.1145/512950.512961) | Reif J., Lewis H. | ACM | POPL | C | 1977 | A |
| [High-level data flow analysis](https://doi.org/10.1145/359842.359849) | Rosen B. | ACM | CACM | J | 1977 | A |
| [Abstract interpretation](https://doi.org/10.1145/512950.512973) | Cousot P., Cousot R. | ACM | POPL | C | 1977 | D |
| [An algorithm for reduction of operator strength](https://doi.org/10.1145/359863.359888) | Cocke J., Kennedy K. | ACM | CACM | J | 1977 | E |
| A transformation system for developing recursive programs | Burstall R., Darlington J. | ACM | JACM | J | 1977 | S |
| [Arithmetic shifting considered harmful](https://doi.org/10.1145/956641.956647) | Steele G. | ACM | SIGPLAN Notices | J | 1977 | S |
| [Monotone data flow analysis frameworks](https://doi.org/10.1007/BF00290339) | Kam J., Ullman J. | Springer | Acta Inf. | J | 1977 | A, D, E, O |
| Program Improvement by Source-to-Source Transformation | Loveman D. | ACM | CACM | J | 1977 | D, O |
| [An analysis of inline substitution for a structured programming language](https://doi.org/10.1145/359810.359830) | Scheifler R. | ACM | CACM | J | 1977 | M, S |
| [Program optimization using invariants](https://doi.org/10.1109/TSE.1978.233858) |  | IEEE | TSE | J | 1978 | - |
| [A new method for compiler code generation](https://doi.org/10.1145/512760.512785) | Glanville R., Graham S. | ACM | POPL | C | 1978 | D |
| [A practical interprocedural data flow analysis algorithm](https://doi.org/10.1145/359588.359596) | Barth J. | ACM | CACM | J | 1978 | A, D, E, O |
| [Data Flow Analysis for Procedural Languages](https://doi.org/10.1145/322123.322135) | Rosen B. | ACM | JACM | J | 1979 | A |
| [Constructing the Call Graph of a Program](https://doi.org/10.1109/TSE.1979.234183) | Ryder B. | IEEE | TSE | J | 1979 | O |
| [Data flow languages](https://doi.org/10.1109/MARK.1979.8817131) | Ackerman W. | IEEE | MARK | W | 1979 | S |
| Time and parallel processor bounds for Fortran-like loops | Chen S. | IEEE | TCO | J | 1979 | S |
| [Unrolling loops in Fortran](https://doi.org/10.1002/spe.4380090307) | Dongarra J., Hinds A. | Wiley | SPE | J | 1979 | S |
| [A fast algorithm for finding dominators in a flowgraph](https://doi.org/10.1145/357062.357071) | Lengauer T., Tarjan R. | ACM | TOPLAS | J | 1979 | A, E, M, O |
| An efficient way to find the side effects of procedural calls and the aliases of variables | Banning J. | ACM | POPL | C | 1979 | A, D, E, S |
| [Global optimization by suppression of partial redundancies](https://doi.org/10.1145/359060.359069) | Morel E., Renvoise C. | ACM | CAMC | J | 1979 | A, D, E, O, S |
| Predicting the effects of optimization on a procedure body | Ball J. | ACM | PLDI (SCC) | C | 1979 | E, S |
| [Structural analysis: A new approach to flow analysis in optimizing compilers](https://doi.org/10.1016/0096-0551(80)90007-7) | Sharir M. | Elsevier | COLA (COMLAN) | C | 1980 | A |
| [The design and application of a retargetable peephole optimizer](https://doi.org/10.1145/357094.357098) | Davidson J., Fraser C. | ACM | TOPLAS | J | 1980 | E |
| [Data flow supercomputers](https://doi.org/10.1109/MC.1980.1653418) | Dennis J. | IEEE | Computer | J | 1980 | S |
| A composite algorithm for strength reduction and code movement optimization | Dhamdhere D., Isaac J. | Springer | ACIS | J | 1980 | E |
| High-speed multiprocessors and compilation techniques | Padua K. | IEEE | TCO | J | 1980 | S |
| [Interprocedural data flow analysis in the presence of pointers, procedure variables, and label variables](https://doi.org/10.1145/567446.567455) | Weihl W. | ACM | POPL | C | 1980 | A, E, O |
| [Deciding Linear Inequalities by Computing Loop Residues](https://doi.org/10.1145/322276.322288) | Shostak R. | ACM | JACM | J | 1981 | D |
| [A precise inter-procedural data flow algorithm](https://doi.org/10.1145/567532.567556) | Myers E. | ACM | POPL | C | 1981 | O, S |
| [Register allocation via coloring](https://doi.org/10.1016/0096-0551(81)90025-5) | Chaitin G., Auslander M., Chandra A., John H., Martin E M. | Elsevier | COLA (COMLAN) | C | 1981 | A, D, E, O, S |
| [Reduction of operator strength](https://doi.org/10.1145/359863.359888) | Allen F., Cocke J., Kennedy K. | NJ | Program flow analysis | J | 1981 | A, E, S |
| [Dependence graphs and compiler optimizatlons](https://doi.org/10.1145/567532.567555) | Kuck D., Kuhn R., Padua D., Leasure B. | ACM | POPL | C | 1981 | O, S |
| [On the performance enhancement of paging systems through program analysis and transformations](https://doi.org/10.1109/TC.1981.1675792) | Kuck L. | IEEE | TCO | J | 1981 | D, S |
| [Using peephole optimization on intermediate code](https://doi.org/10.1145/357153.357155) | McKeeman W. | ACM | TOPLAS | J | 1982 | - |
| [Optimizing delayed branches](https://doi.org/10.1145/1014194.800941) | Gross T., Hennessy J. | ACM | MICRO | W | 1982 | D |
| A composite hoisting-strength reduction transformation for global program optimization part i | Joshi S., Dhamdhere D. | T&F | JCM | J | 1982 | E |
| [Optimization of range checking](https://doi.org/10.1145/800230.806986) | Markstein V., Cocke J., Markstein P. | ACM | PLDI (SCC) | C | 1982 | E |
| [Register allocation and spilling via graph coloring](https://doi.org/10.1145/872726.806984) | Chaitin G. | ACM | PLDI | C | 1982 | A, D, E, M, O, S |
| [Experience with the SETL optimizer](https://doi.org/10.1145/357195.357197) | Freudenberger S., Schwartz J., Sharir M. | ACM | TOPLAS | J | 1983 | S |
| [Postpass Code Optimization of Pipeline Constraints](https://doi.org/10.1145/2166.357217) | Hennessy J., Gross T. | ACM | TOPLAS | J | 1983 | A, E |
| [Conversion of control dependence to data dependence](https://doi.org/10.1145/567067.567085) | Allen J., Kennedy K., Porterfield C. | ACM | POPL | C | 1983 | O, S |
| [Code selection through object code optimization](https://doi.org/10.1145/1780.1783) | Davidson J., Fraser C. | ACM | TOPLAS | J | 1984 | - |
| [Register allocation and exhaustive peephole optimization](https://doi.org/10.1145/364995.365000) | Davidson J., Fraser C. | Wiley | SPE | J | 1984 | E |
| [Automatic generation of peephole optimizations](https://doi.org/10.1145/364995.365000) | Davidson J., Fraser C. | Springer | CC | C | 1984 | E |
| Analysis of interprocedural side effects in a parallel programming environment | Callahan D., Kennedy K. | Springer | ICSP | C | 1984 | O |
| [Polyvariant mixed computation for analyzer programs](https://doi.org/10.1007/BF00271642) | Bulyonkov M. | Springer | Acta Inf. | J | 1984 | O |
| [Stream processing](https://doi.org/10.1145/800055.802021) | Goldberg A., Paige R. | ACM | LFP | C | 1984 | O |
| [A hierarchical basis for reordering transformations](https://doi.org/10.1145/800017.800539) | Warren J. | ACM | POPL | C | 1984 | O |
| [Register allocation by priority-based coloring](https://doi.org/10.1145/502949.502896) | Chow F., Hennessy J. | ACM | PLDI (SCC) | C | 1984 | A, E, O |
| Automatic loop interchange | Allen J., Kennedy K. | ACM | PLDI (SCC) | C | 1984 | O, S |
| Efficient computation of flow insensitive interprocedural summary information | Cooper K., Kennedy K. | ACM | PLDI (SCC) | C | 1984 | A, O |
| [Program transformations in a denotational setting](https://doi.org/10.1145/3916.3917) | Nielson F. | ACM | TOPLAS | J | 1985 | - |
| [On linearizing parallel code](https://doi.org/10.1145/318593.318636) | Ferrante J., Mace M. | ACM | POPL | C | 1985 | O |
| Distributed execution of functional programs using serial combinators | Hudak P., Goldberg B. | IEEE | TCO | J | 1985 | S |
| Strictness analysis-a practical approach | Clack C., Peyton Jones S. | Springer | FPCA | C | 1985 | S |
| [A linear algorithm for finding dominators in flow graphs and related problems](https://doi.org/10.1145/22145.22166) | Harel D. | ACM | STOC | C | 1985 | E, M, O |
| [Efficient compilation of linear recursive functions into object level loops](https://doi.org/10.1145/12276.13332) | Harrison P., Khoshnevisan H. | ACM | PLDI (SCC) | C | 1985 | - |
| [Advanced compiler optimizations for supercomputers](https://doi.org/10.1145/7902.7904) | Padua D., Wolfe M. | ACM | CACM | J | 1986 | - |
| [The impact of interprocedural analysis and optimization in the Rn programming environment](https://doi.org/10.1145/6465.6489) | Cooper K., Kennedy K., Torczon L. | ACM | TOPLAS (LOPES) | C | 1986 | - |
| Efficient instruction scheduling for a pipelined architecture | Gibbons P., Muchnick S. | ACM | PLDI (SCC) | C | 1986 | A |
| [Efficient symbolic analysis of programs](https://doi.org/https://doi.org/10.1016/0022-0000(86)90031-0) | John H. Reif H. | ACM | JCSS | J | 1986 | A |
| [Graph-Based Algorithms for Boolean Function Manipulation](https://doi.org/10.1109/TC.1986.1676819) | Bryant R. | IEEE | TC | J | 1986 | D |
| [Loops skewing: The wavefront method revisited](https://doi.org/10.1007/BF01407876) | Wolfe M. | Springer | JPP | J | 1986 | O |
| [Highly concurrent scalar processing](https://doi.org/10.1145/17356.17401) | Hsu P., Davidson E. | ACM | CAN | J | 1986 | O |
| [Multiplication by integer constants](https://doi.org/10.1002/spe.4380160704) | Bernstein R. | Wiley | SPE | J | 1986 | S |
| [Global register allocation at link time](https://doi.org/10.1145/12276.13338) | Wall D. | ACM | PLDI | C | 1986 | A, E |
| [Interprocedural constant propagation](https://doi.org/10.1145/176454.176526) | Callahan D., Cooper K., Kennedy K. | ACM | PLDI | C | 1986 | A, D, E, O, S |
| [Interprocedural optimization: eliminating unnecessary recompilation](https://doi.org/10.1145/12276.13317) | Cooper K., Kennedy K., Torczon L. | ACM | CC | C | 1986 | A, E, O |
| Interprocedural dependence analysis and parallelization | Burke M., Cytron R. | ACM | PLDI | C | 1986 | O, S |
| [Effectiveness of a machine-level, global optimizer](https://doi.org/10.1145/12276.13321) | Johnson M., Miller T. | ACM | PLDI (SCC) | C | 1986 | A, E |
| [Direct parallelization of call statements](https://doi.org/10.1145/13310.13329) | Triolet R., Irigoin F., Feautrier P. | ACM | PLDI (SCC) | C | 1986 | O, S |
| Code motion of control structures in high-level languages | Cytron R., Lowry A., Zadeck F. | ACM | POPL | C | 1986 | E, M |
| [Automatic inference and fast interpretation of peephole optimization rules](https://doi.org/10.1145/364995.365000) | Davidson J., Fraser C. | Wiley | SPE | J | 1987 | E |
| [Compiler Algorithms for Synchronization](https://doi.org/10.1109/TC.1987.5009499) | Midkiff S., Padua D. | IEEE | TCO | J | 1987 | O |
| [Automatic decomposition of scientific programs for parallel execution](https://doi.org/10.1145/41625.41631) | Allen r., Callahan D., Kennedy K. | ACM | POPL | C | 1987 | O |
| [Guided Self-Scheduling: A Practical Scheduling Scheme for Parallel Supercomputers](https://doi.org/10.1109/TC.1987.5009495) | Polychronopoulos C., Kuck D. | IEEE | TCO | J | 1987 | S |
| Loop coalescing: A compiler transformation for parallel machines | Polychronopoulos C. | ACM | ICPP | C | 1987 | S |
| Strategies for cache and local memory management by global program transformation | Gannon D., Jalby W., Gallivan K. | Springer | ICS | C | 1987 | S |
| [The program dependence graph and its use in optimization](https://doi.org/10.1145/24039.24041) | Ferrante J., Ottenstein K., Warren J. | ACM | TOPLAS | J | 1987 | A, E, M, O |
| [Automatic translation of Fortran programs to vector form](https://doi.org/10.1145/41625.41631) | Allen R., Kennedy K. | ACM | TOPLAS | J | 1987 | D, O, S |
| [Safety consideration for storage allocation optimizations](https://doi.org/10.1145/53990.53991) | Chase D. | ACM | PLDI | C | 1988 | - |
| [Efficient and correct execution of parallel programs that share memory](https://doi.org/10.1145/42190.42277) | Shasha D., Snir M. | ACM | TOPLAS (LOPES) | C | 1988 | - |
| [On the control dependence in the program dependence graph](https://doi.org/10.1145/322609.322862) | Natour I. | ACM | CSC | C | 1988 | - |
| [Resource requirements of dataflow programs](https://dl.acm.org/doi/10.5555/52400.52417) | Culler D. | ACM | ISCA | C | 1988 | - |
| [Incremental data flow analysis via dominator and attribute update](http://dx.doi.org/10.1145/73560.73584) | Carroll M., Ryder B. | ACM | POPL | C | 1988 | - |
| [An efficient approach to data flow analysis in a multiple pass global optimizer](https://doi.org/10.1145/960116.54006) | Jain S., Thompson C. | ACM | PLDI | C | 1988 | A |
| [A solution to a problem with Morel and Renvoise's ``Global optimization by suppression of partial redundancies''](https://doi.org/10.1145/359060.359069) | Drechsler K., Stadel M. | ACM | TOPLAS | J | 1988 | E |
| [Efficient computation of flow-insensitive interprocedural summary information—a correction](https://doi.org/10.1145/44326.44329) | Cooper K., Kennedy K. | ACM | SIGPLAN Notices | J | 1988 | O |
| [Dependence of multi-dimensional array references](https://doi.org/10.1145/55364.55405) | Wallace D. | ACM | ICS | C | 1988 | O |
| [The importance of direct dependences for automatic parallelization](https://doi.org/10.1145/55364.55404) | Brandes T. | ACM | ICS | C | 1988 | O |
| [Introducing symbolic problem solving techniques in the dependence testing phases of a vectorizer](https://doi.org/10.1145/55364.55403) | Lichnewsky A., Thomasset F. | ACM | ICS | C | 1988 | O |
| [Generating sequential code from parallel code](https://doi.org/10.1145/55364.55421) | Ferrante J., Mace M., Simons B. | ACM | SC | C | 1988 | O |
| [CRegs: a new kind of memory for referencing arrays and pointers](https://doi.org/10.1109/SUPERC.1988.44673) | Dietz H., Chi C. | ACM | ICS | C | 1988 | - |
| Advanced loop optimizations for parallel computers | Polychronopoulos C. | ACM | ICS | C | 1988 | S |
| An introduction to a formal theory of dependence analysis | Banerjee U. | Springer | JSC | J | 1988 | S |
| [Analysis of interprocedural side effects in a parallel programming environment](https://doi.org/10.1016/0743-7315(88)90011-1) | Callahan D., Kennedy K. | ACM | ICS | C | 1988 | S |
| Array expansion | Feautrier P. | ACM | ICS | C | 1988 | S |
| [Loop quantization: A generalized loop unwinding technique](https://doi.org/https://doi.org/10.1016/0743-7315(88)90013-5) |  | ACM | JPDC | J | 1988 | S |
| Supernode partitioning | Irigoin F., Triolet R. | ACM | PLDI | C | 1988 | S |
| [A fast algorithm for code movement optimisation](https://doi.org/10.1145/51607.51621) | Dhamdhere D. | ACM | PLDI | C | 1988 | A, E |
| Compiling programs for distributed-memory multiprocessors | Callahan D., Kennedy K. | Elsevier | JSC | J | 1988 | O, S |
| [Optimal loop parallelization](https://doi.org/10.1145/53990.54021) | Aiken A., Nicolau A. | ACM | PLDI | C | 1988 | A, E, M, S |
| [Software pipelining: an effective scheduling technique for VLIW machines](https://doi.org/10.1145/960116.54022) | Lam M. | ACM | PLDI | C | 1988 | D, E |
| The program summary graph and flow-sensitive interprocedual data flow analysis | Callahan D. | ACM | PLDI | C | 1988 | A, O |
| A framework for determining useful parallelism | Allen F., Burke M., Cytron R., Ferrante, | ACM | ICS | C | 1988 | O, S |
| An overview of the PTRAN analysis system for multiprocessing | Allen F., Burke M., Charles P., Cytron | Elsevier | JPDC | J | 1988 | D, S |
| [Efficient interprocedural analysis for program parallelization and restructuring](https://doi.org/10.1145/62116.62125) | Li Z., Yew P. | ACM | PPoPP (PPEALS) | C | 1988 | O, S |
| Compiling issues for supercomputers | Girkar M., Polychronoupoulos C. | ACM/IEEE | SC | C | 1988 | O, S |
| [Minimizing register usage penalty at procedure calls](https://doi.org/10.1145/73141.74849) | Chow F. | ACM | PLDI | C | 1988 | A, S |
| Estimating interlock and improving balance for pipelined architectures | Callahan D., Cocke J., Kennedy K. | Elsevier | JPDC | J | 1988 | O, S |
| [Global value numbers and redundant computations](https://doi.org/10.1145/73560.73562) | Rosen B., Wegman M., Zadeck F. | ACM | POPL | C | 1988 | E, O |
| [Perfect pipelining: A new loop parallelization technique](https://doi.org/10.1007/3-540-19027-9_15) | Aiken A., Nicolau A. | Springer | ESOP | C | 1988 | A, S |
| Code scheduling and register allocation in large basic blocks | Goodman J., Hsu W. | ACM | SC | C | 1988 | A, E |
| [Interprocedural side-effect analysis in linear time](https://doi.org/10.1145/62116.62125) | Cooper K., Kennedy K. | ACM | PLDI | C | 1988 | A, E, O |
| [A technique for summarizing data access and its use in parallelism enhancing transformations](https://doi.org/10.1145/74818.74822) | Balasundaram V., Kennedy K. | ACM | PLDI | C | 1989 | - |
| [Interprocedural analysis vs. procedure integration](https://doi.org/10.1016/0020-0190(89)90014-8}) | Stephen Richardson M. | Elsevier | IPL | J | 1989 | - |
| Unified management of registers and cache using liveness and cache bypass | Chi C., Dietz H. | ACM | PLDI | C | 1989 | A |
| A new algorithm for composite hoisting and strength reduction optimisation | Dhamdhere D. | T&F | JCM | J | 1989 | E |
| [Interprocedual data flow testing](https://dl.acm.org/doi/10.1145/75309.75327) | Harrold M., Soffa M. | ACM | SEN | C | 1989 | - |
| [Program optimization for instruction caches](https://doi.org/10.1145/68182.68200) | McFarling S. | ACM | ASPLOS | C | 1989 | A |
| [Dependence analysis for pointer variables](https://doi.org/10.1145/73141.74821) | Horwitz S., Pfeiffer P., Reps T. | ACM | PLDI | C | 1989 | E |
| [The program dependence graph and vectorization](https://doi.org/10.1145/75277.75278) | Baxter W., Bauer H. | ACM | POPL | C | 1989 | O |
| [Achieving high instruction cache performance with an optimizing compiler](https://doi.org/10.1109/ISCA.1989.714559) | Hwu W., Chang P. | ACM | ISCA | C | 1989 | S |
| Evaluating the performance of four snooping cache coherency protocols | Eggers S., Katz R. | IEEE | ICSA | C | 1989 | S |
| [Scans as primitive parallel operations](https://doi.org/10.1109/12.42122) | Blelloch G. | IEEE | TCO | J | 1989 | S |
| [Code generation using tree matching and dynamic programming](https://doi.org/10.1145/69558.75700) | Aho A., Ganapathi M., Tjiang S. | ACM | TOPLAS | J | 1989 | A, D, E, M |
| [Register allocation via clique separators](https://doi.org/10.1145/73141.74842) | Gupta R., Soffa M., Steele T. | ACM | PLDI | C | 1989 | A, E |
| [Fast interprocedual alias analysis](https://doi.org/10.1145/75277.75282) | Cooper K., Kennedy K. | ACM | POPL | C | 1989 | A, E, O, S |
| [Coloring heuristics for register allocation](https://doi.org/10.1145/73141.74843) | Briggs P., Cooper K., Kennedy K., Torczon L. | ACM | PLDI | C | 1989 | A, E, O |
| [More iteration space tiling](https://doi.org/10.1145/76263.76337) | Wolfe M. | ACM/IEEE | SC | C | 1989 | A, S |
| [Data dependence analysis on multi-dimensional array references](https://doi.org/10.1145/318789.318813) | Li Z., Yew P., Zhu C. | ACM | ICS | C | 1989 | O, S |
| [Spill code minimization techniques for optimizing compliers](https://doi.org/10.1145/73141.74841) | Bernstein D., Golumbic M., Mansour y., Pinter R., D. K., H. N. | ACM | PLDI | C | 1989 | A, E |
| [Customization: Optimizing compiler technology for SELF, a dynamically-typed OOP language](https://doi.org/10.1145/74818.74831) | Chambers C., Ungar D. | ACM | PLDI | C | 1989 | O, S |
| [An efficient method of computing static single assignment form](https://doi.org/10.1145/75277.75280) | Cytron R., Ferrante J., Rosen B., Wegman, | ACM | POPL | C | 1989 | A, O |
| [The program dependence graph in a software development environment](https://doi.org/10.1007/3-540-52592-0_76) |  | ACM | TOPLAS | J | 1990 | - |
| [Compiler techniques for data partitioning of sequentially iterated parallel loops](https://doi.org/10.1145/79147.79159) | Hudak D., Abraham S. | ACM | SC | C | 1990 | - |
| [Vectorization of tree traversals](https://doi.org/10.1145/77726.255156) |  | Elsevier | JCP | J | 1990 | - |
| [Loop displacement: an approach for transforming and scheduling loops for parallel execution](https://doi.org/10.1109/SUPERC.1990.130046) | Gupta R. | ACM | SC | C | 1990 | - |
| [Experience with interprocedural analysis of array side effects](https://dl.acm.org/doi/10.5555/110382.110626) | Havlak P., Kennedy K. | ACM | SC | C | 1990 | - |
| [An approach to ordering optimizing transformations](https://doi.org/10.1145/99163.99179) | Whitfield D., Soffa M. | ACM | PPoPP | C | 1990 | A |
| [Register allocation across procedure and module boundaries](https://doi.org/10.1145/93548.93551) | Santhanam V., Odnert D. | ACM | PLDI | C | 1990 | A |
| [Region Scheduling: An Approach for Detecting and Redistributing Parallelism](https://doi.org/10.1109/32.54294) | Gupta R., Soffa M. | IEEE | TSE | J | 1990 | E |
| [Constructing the procedure call multigraph](https://doi.org/10.1109/32.54302) | Callahan D., Carle A., Hall M., Kennedy K. | IEEE | TSE | J | 1990 | O |
| [On the perfect accuracy of an approximate subscript analysis test](https://doi.org/10.1145/255129.255158) | Klappholz D., Psarris K., Kong X. | ACM | CAN | J | 1990 | O |
| [Structured dataflow analysis for arrays and its use in an optimizing compiler](https://doi.org/10.1002/spe.4380200203) | Gross T., Steenkiste P. | Wiley | Software: Practice and Experience | J | 1990 | O |
| Compilation of Haskell array comprehensions for scientific computing | Anderson S., Hudak P. | ACM | PLDI | C | 1990 | S |
| [How to read floating point numbers accurately](https://doi.org/10.1145/93548.93557) | Clinger W. | ACM | PLDI | C | 1990 | S |
| [How to print floating-point numbers accurately](https://doi.org/10.1145/93548.93559) | Steele G., White J. | ACM | PLDI | C | 1990 | S |
| [Profile guided code positioning](https://doi.org/10.1145/93548.93550) | Pettis K., Hansen R. | ACM | PLDI | C | 1990 | S |
| Updating distributed variables in local computations | Gerndt M. | Wiley | SPE | J | 1990 | S |
| [An interval-based approach to exhaustive and incremental interprocedural data-flow analysis](https://doi.org/10.1145/78969.78963) | Burke M. | ACM | TOPLAS | J | 1990 | E, O |
| [The priority-based coloring approach to register allocation](https://doi.org/10.1145/88616.88621) | Chow F., Hennessy J. | ACM | TOPLAS | J | 1990 | A, D, E, S |
| [Improving register allocation for subscripted variables](https://doi.org/10.1145/93548.93553) | Callahan D., Carr S., Kennedy K. | ACM | PLDI | C | 1990 | A, E, M, O, S |
| [Analysis of pointers and structures](https://doi.org/10.1145/93542.93585) | Chase D., Wegman M., Zadeck F. | ACM | PLDI | C | 1990 | A, E |
| Loop distribution with arbitrary control flow | Kennedy K., McKinley K. | ACM | PLDI | C | 1990 | O, S |
| [Graph coloring register allocation for processors with multi-register operands](https://doi.org/10.1145/93548.93552) | Nickerson B. | ACM | PLDI | C | 1990 | A, E |
| [A data locality optimizing algorithm](http://dx.doi.org/10.1145/113445.113449) | Wolf M., Lam M. | ACM | PLDI | C | 1991 | - |
| [On optimal parallelization of arbitrary loops](https://doi.org/10.1016/0743-7315(91)90118-S) | Uwe Schwiegelshohn F. | Elsevier | JPDC | J | 1991 | - |
| [On the adequacy of dependence-based representations for programs with heaps](https://doi.org/10.1007/3-540-54415-1_55) | Pfeiffer P., Selke R. | Springer | TACS | C | 1991 | - |
| [Program optimization and parallelization using idioms](http://dx.doi.org/10.1145/99583.99597) | Pinter S., Pinter R. | ACM | POPL | C | 1991 | - |
| [Automatic construction of sparse data flow evaluation graphs](http://dx.doi.org/10.1145/99583.99594) | Choi J., Cytron R., Ferrante J. | ACM | POPL | C | 1991 | - |
| [Compiler optimizations for Fortran D on MIMD distributed-memory machines](https://doi.org/10.1145/125826.125886) | Hiranandani S., Kennedy K., Tseng C. | ACM | SC | C | 1991 | - |
| [Register allocation via hierarchical graph coloring](https://doi.org/10.1145/113446.113462) | Callahan D., Koblenz B. | ACM | PLDI | C | 1991 | A |
| [Circular scheduling: a new technique to perform software pipelining](https://doi.org/10.1145/113445.113464) | Jain S. | ACM | PLDI | C | 1991 | A |
| [Efficient DAG construction and heuristic calculation for instruction scheduling](https://doi.org/10.1145/123465.123482) | Smotherman M., Krishnamurthy S., Aravind P. | ACM | MICRO | W | 1991 | E |
| [Efficiently computing static single assignment form and the control dependence graph](https://doi.org/10.1145/115372.115320) | Cytron R., Ferrante J., Rosen B., Wegman, | ACM | TOPLAS | J | 1991 | M |
| [Software prefetching](https://doi.org/10.1145/106972.106979) | Callahan D., Kennedy K., Porterfield A. | ACM | ASPLOS | C | 1991 | O |
| [Compiling global name-space parallel loops for distributed execution](https://doi.org/10.1109/71.97901) | Koelbel C., Mehrotra P. | IEEE | TPDS | J | 1991 | O |
| An implementation of interprocedural bounded regular section analysis | Havlak P., Kennedy K. | ACM | TPDS | J | 1991 | O |
| Limits of instruction-level parallelism | Wall D. | ACM | ASPLOS | C | 1991 | S |
| [Uniform techniques for loop optimization](https://doi.org/10.1145/109025.109108) | Pugh W. | ACM | ICS | C | 1991 | S |
| [A data locality optimizing](https://doi.org/10.1145/113446.113449) | Wolf M., Lam M. | ACM | PLDI | C | 1991 | A, D, M, O |
| [Constant propagation with conditional branches](https://doi.org/10.1145/103135.103136) | Wegman M., Zadeck F. | ACM | TOPLAS | J | 1991 | A, E, M, O, S |
| [Efficient and exact data dependence analysis](https://doi.org/10.1145/113446.113447) | Maydan D., Hennessy J., Lam M. | ACM | PLDI | C | 1991 | A, D, O |
| [Efficiently computing static single assignment](https://doi.org/10.1145/115372.115320) | Cytron R., Ferrante J., Rosen B., Wegman, | ACM | TOPLAS | J | 1991 | A, D, E, O |
| [Global instruction scheduling for superscalar machines](https://doi.org/10.1145/113446.113466) | Bernstein D., Rodeh M. | ACM | PLDI | C | 1991 | A, D, E |
| [Practical adaption of the global optimization algorithm of Morel and Renvoise](https://doi.org/10.1145/103135.214520) | Dhamdhere D. | ACM | TOPLAS | J | 1991 | A, E |
| [The cache performance and optimizations of blocked algorithms](https://doi.org/10.1145/106972.106981) | Lam M., Rothberg E., Wolf M. | ACM | ASPLOS | C | 1991 | A, D |
| [A loop transformation theory and an algorithm to maximize parallelism](https://doi.org/10.1109/71.97902) | Wolf M., Lam M. | IEEE | TPDS | J | 1991 | O, S |
| [Dataflow analysis of array and scalar references](https://doi.org/10.1007/BF01407931) | Feautrier P. | Springer | JPP | J | 1991 | A, S |
| [Optimization of array accesses by collective loop transformations](https://doi.org/10.1145/109025.109077) | Sarkar V., Gao G. | ACM | SC | C | 1991 | D, O |
| Interprocedural transformations for parallel code generation | Hall M., Kennedy K., McKinley K. | ACM/IEEE | SC | C | 1991 | O, S |
| [Practical dependence testing](https://doi.org/10.1145/113445.113448) | Goff G., Kennedy K., Tseng C. | ACM | PLDI | C | 1991 | A, O |
| [Procedure merging with instruction caches](https://doi.org/10.1145/113446.113452) | McFarling S. | ACM | PLDI | C | 1991 | A, S |
| [An experiment with inline substitution](https://doi.org/10.1002/spe.4380210604) | Cooper K., Hall M., Torczon L. | Wiley | SPE | J | 1991 | E, S |
| [Access normalization: loop restructuring for NUMA compilers](https://doi.org/10.1145/143371.143541) |  | ACM | ASPLOS | C | 1991 | - |
| [Non-unimodular transformations of nested loops](https://doi.org/10.1109/SUPERC.1992.236692) | Ramanujam J. | ACM | SC | C | 1992 | - |
| [A framework for interprocedural data flow analysis in the presence of pointers](https://doi.org/10.1145/143103.143132) |  | ACM | PLDI | C | 1992 | - |
| [A program integration algorithm that accommodates semantics-preserving transformations](https://doi.org/10.1145/131736.131756) | Yang W., Horwitz S., Reps T. | ACM | TOSEM | J | 1992 | - |
| [The transitive closure of control dependence: The iterated join](https://doi.org/10.1145/151333.151337) | Weiss M. | ACM | TOPLAS (LOPLAS) | J | 1992 | - |
| [Abstract description of pointer data structures: an approach for improving the analysis and optimization of imperative programs](https://doi.org/10.1145/151640.151644) | Hummel J., Hendren L., Nicolau A. | ACM | TOPLAS (LOPLAS) | J | 1992 | - |
| [Abstractions for recursive pointer data structures: improving the analysis and transformation of imperative programs](https://doi.org/10.1145/143095.143138) | v. Hanxleden R., Kennedy K. | ACM | PLDI | C | 1992 | - |
| [Generalized dominators and post-dominators](http://dx.doi.org/10.1145/143165.143216) | Gupta R. | ACM | POPL | C | 1992 | - |
| [A comprehensive approach to parallel data flow analysis](https://doi.org/10.1145/143369.143415) | Lee Y., Ryder B. | ACM | ICS | C | 1992 | A |
| Integrating scalar optimization and parallelization | Tjiang S., Wolf M., Lam M., Pieper K. | Springer | LCPC | C | 1992 | A |
| [Sharlit—a tool for building optimizers](https://doi.org/10.1145/143103.143120) | Tjiang S., Hennessy J. | ACM | PLDI | C | 1992 | A |
| [How to analyze large programs efficiently and informatively](https://doi.org/10.1145/143103.143135) | Dhamdhere D., Rosen B., Zadeck F. | ACM | PLDI | C | 1992 | A |
| Compiler code transformations for superscalar-based high performance systems | Mahlke S., Chen W., Gyllenhaal J., Hwu W. | IEEE | SC | C | 1992 | A |
| [Engineering a simple, efficient code-generator generator](https://doi.org/10.1145/151640.151642) | Fraser C., Hanson D., Proebsting T. | ACM | TOPLAS (LOPLAS) | J | 1992 | D |
| Some efficient solutions to the affine scheduling problem. I. One-dimensional time | Feautrier P. | Elsevier | JPP | J | 1992 | D |
| [Avoiding unconditional jumps by code replication](https://doi.org/10.1145/143095.143144) | Mueller F., Whalley D. | ACM | PLDI | C | 1992 | E |
| [Rematerialization](https://doi.org/10.1145/143103.143143) | Briggs P., Cooper K., Torczon L. | ACM | PLDI | C | 1992 | E |
| [Coloring register pairs](https://doi.org/10.1145/143103.143135) | Briggs P., Cooper K., Torczon L. | ACM | TOPLAS (LOPLAS) | J | 1992 | E |
| Optimizing for parallelism and data locality | Kennedy K., McKinley K. | ACM | SC | C | 1992 | O |
| Maximizing loop parallelism and improving data locality via loop fusion and distribution | Kennedy K., McKinley K. | ACM | LCPC | W | 1992 | O |
| [Beyond induction variables](https://doi.org/10.1145/143103.143131) | Wolfe M. | ACM | PLDI | C | 1992 | O |
| [Efficient call graph analysis](https://doi.org/10.1145/151640.151643) | Hall M., Kennedy K. | ACM | TOPLAS (LOPLAS) | J | 1992 | O |
| [A safe approximate algorithm for interprocedural aliasing](https://doi.org/10.1145/143095.143137) | Landi W., Ryder B. | ACM | PLDI | C | 1992 | O |
| [Relaxing SIMD control flow constraints using loop transformations](https://doi.org/10.1145/143103.143133) | v. Hanxleden R., Kennedy K. | ACM | PLDI | C | 1992 | S |
| [Unexpected side effects of inline substitution: a case study](https://doi.org/10.1145/130616.130619) | Cooper K., Hall M., Torczon L. | ACM | TOPLAS (LOPLAS) | J | 1992 | S |
| [Eliminating false positives using the omega test](https://doi.org/10.1145/143103.143129) | Pugh W., Wonnacott D. | ACM | PLDI | C | 1992 | A, D, O |
| [Lazy code motion](https://doi.org/10.1145/143103.143136) | Knoop J., R\"{u}thing O., Steffen B. | ACM | PLDI | C | 1992 | A, D, E |
| [Software support for speculative loads](https://doi.org/10.1145/143365.143484) | Rogers A., Li K. | ACM | ASPLOS | C | 1992 | A, E |
| [A practical algorithm for exact array dependence analysis](https://doi.org/10.1145/135226.135233) | Pugh W. | ACM | CACM | J | 1992 | O, S |
| [Array privatization for parallel execution of loops](https://doi.org/10.1145/143369.143426) | Li Z. | ACM | ICS | C | 1992 | O, S |
| [The power test for data dependence](https://doi.org/10.1109/71.159042) | Wolfe M., Tseng C. | IEEE | TCO | J | 1992 | A, S |
| [Eliminating branches using a superoptimizer and the GNU C compiler](https://doi.org/10.1145/143095.143146) | Granlund T., Kenner R. | ACM | PLDI | C | 1992 | E, S |
| [Design and evaluation of a compiler algorithm for prefetching](https://doi.org/10.1145/143371.143488) | Mowry T., Lam M., Gupta A. | ACM | ASPLOS | C | 1992 | D, O |
| [Data dependence and data-flow analysis of arrays](https://doi.org/10.1007/3-540-57502-2_63) | Maydan D., Amarsinghe S., Lam M. | Springer | LCPC | C | 1992 | - |
| [Advanced compiler optimizations for sparse computations](https://doi.org/10.1145/169627.169765) | Bik A., Wijshoff H. | ACM | SC | C | 1993 | - |
| [Access normalization: loop restructuring for NUMA computers](https://doi.org/10.1145/161541.159766) | Li W., Pingali K. | ACM | TOCS | J | 1993 | - |
| [On the conversion of indirect to direct recursion](https://doi.org/10.1145/176454.176510) | Kaser O., Ramakrishnan C., Pawagi S. | ACM | TOPLAS (LOPLAS) | J | 1993 | - |
| [A practical data flow framework for array reference analysis and its use in optimizations](http://dx.doi.org/10.1145/155090.155097) | Duesterwald E., Gupta R., Soffa M. | ACM | PLDI | C | 1993 | - |
| [Using lifetime predictors to improve memory allocation performance](http://dx.doi.org/10.1145/155090.155108) | Barrett D., Zorn B. | ACM | PLDI | C | 1993 | - |
| [Data flow analysis for parallel programs](https://doi.org/10.1145/170791.170853) | Ito M., Zaafrani A. | ACM | CSC | C | 1993 | - |
| [Dependence-based program analysis](https://doi.org/10.1145/155090.155098) | Johnson R., Pingali K. | ACM | PLDI | C | 1993 | A |
| [A variation of Knoop, Rüthing, and Steffen's lazy code motion](https://doi.org/10.1145/152819.152823) | Knoop J., R\"{u}thing O., Steffen B. | ACM | PLDI | C | 1993 | E |
| [Lazy strength reduction](https://www.clear.rice.edu/comp512/Lectures/Papers/Knoop-LazyStrengthReduction.pdf) | Knoop J. | C&H | JPL | J | 1993 | A, E |
| Collective loop fusion for array contraction | Gao G., Olsen R., Sarkar V., Thekkath R. | Springer | LCPC | C | 1993 | O |
| [Interprocedural constant propagation: an empirical study](https://doi.org/10.1145/176454.176526) | Metzger R., Stroud S. | ACM | TOPLAS (LOPLAS) | J | 1993 | O |
| Symbolic analysis: A basis for parallelization, optimization, and scheduling of programs | Haghighat M., Polychronopoulos C. | Springer | LCPC | W | 1993 | O |
| [Array-data flow analysis and its use in array privatization](https://doi.org/10.1145/158511.158515) | Maydan D., Amarasinghe S., Lam M. | ACM | POPL | C | 1993 | S |
| [Automatic array alignment in data-parallel programs](https://doi.org/10.1145/158511.158517) | Chatterjee S., Gilbert J., Schreiber R. | ACM | POPL | C | 1993 | S |
| Global optimizations for parallelism and locality on scalable parallel machines | Anderson J., Lam M. | ACM | PLDI | C | 1993 | S |
| [Instruction-Level Parallel Processing: History, Overview, and Perspective](https://doi.org/10.1007/978-1-4615-3200-2_3) | Rau B., Fisher J. | Springer | JSC | J | 1993 | S |
| [A practical system for intermodule code optimization at link-time](https://web.stanford.edu/class/cs343/resources/om.pdf) | Srivastava A. | C&H | JPL | J | 1993 | A |
| Loop-level parallelism in numeric and symbolic programs | Larus J. | IEEE | TPDS | J | 1993 | S |
| [Orchestrating interactions among parallel computations](https://doi.org/10.1145/173262.155100) | Graham S., Lucco S., Sharp O. | ACM | PLDI | C | 1993 | S |
| The superblock: an effective technique for VLIW and superscalar compilation | Hwu W., Mahlke S., Chen W., Chang, | Springer | JSC | J | 1993 | S |
| [Optimizing array bound checks using flow analysis](https://doi.org/10.1145/176454.176507) | Gupta R. | ACM | PLDI | C | 1993 | A, E |
| [Register allocation with instruction scheduling](https://doi.org/10.1145/173262.155114) | Pinter S. | ACM | PLDI | C | 1993 | A, E |
| [A methodology for procedure cloning](https://doi.org/10.1016/0096-0551(93)90005-L) | Cooper K., Hall M., Kennedy K. | Elsevier | COLA (COMLAN) | J | 1993 | A, O, S |
| [Efficient flow-sensitive interprocedural computation of pointer-induced aliases and side effects](https://doi.org/10.1145/158511.158639) | Choi J., Burke M., Carini P. | ACM | POPL | C | 1993 | E, O, S |
| [Automatic array privatization](https://dl.acm.org/doi/10.5555/645671.665384) | Tu P., Padua D. | Springer | LCPC | W | 1993 | O, S |
| [Interprocedural modification side effect analysis with pointer aliasing](https://doi.org/10.1145/155090.155102) | Landi W., Ryder B., Zhang S. | ACM | PLDI | C | 1993 | M, S |
| [Branch prediction for free](https://doi.org/10.1145/155090.155119) | Ball T., Larus J. | ACM | PLDI | C | 1993 | A, M |
| [Enabling unimodular transformations](https://doi.org/10.1109/SUPERC.1994.344341) | Sass R., Mutka M. | ACM | SC | C | 1994 | - |
| [Compiler optimizations for improving data locality](https://doi.org/10.1145/195470.195557) | Carr S., McKinley K., Tseng C. | ACM | ASPLOS | C | 1994 | - |
| [The revival transformation](https://doi.org/10.1145/174675.178043) | Feigen L., Klappholz D., Casazza R. | ACM | PLDI | C | 1994 | - |
| [The range test: a dependence test for symbolic, non-linear expressions](https://dl.acm.org/doi/10.5555/602770.602858) | Blume W., Eigenmann R. | ACM | SC | C | 1994 | - |
| [Link-time optimization of address calculation on a 64-bit architecture](https://doi.org/10.1145/178243.178248) | Srivastava A., Wall D. | ACM | PLDI | C | 1994 | A |
| [Effective partial redundancy elimination](https://doi.org/10.1145/178243.178257) | Briggs P., Cooper K. | ACM | PLDI | C | 1994 | A |
| [Partial dead code elimination](https://doi.org/10.1145/773473.178256) | Knoop J., R{\"u}thing O., Steffen B. | ACM | PLDI | C | 1994 | A |
| [A general data dependence test for dynamic, pointer-based data structures](https://doi.org/10.1145/178243.178262) | Hummel J., Hendren L., Nicolau A. | ACM | PLDI | C | 1994 | A |
| Instruction scheduling over regions: A framework for scheduling across basic blocks | Mahadevan U., Ramakrishnan S. | Springer | CC | C | 1994 | A |
| [Value dependence graphs: representation without taxation](https://doi.org/10.1145/174675.177907) | Weise D., Crew R., Ernst M. | ACM | POPL | C | 1994 | A |
| [Zero-cost range splitting](https://doi.org/10.1145/773473.178420) | Kurlander S., Fischer C. | ACM | PLDI | C | 1994 | E |
| [Reducing branch costs via branch alignment](https://doi.org/10.1145/381792.195553) | Calder B., Grunwald D. | ACM | OSR | J | 1994 | E |
| [Improving the ratio of memory operations to floating-point operations in loops](https://doi.org/10.1145/197320.197366) | Carr S., Kennedy K. | ACM | TOPLAS | J | 1994 | M |
| [Optimizing multi-method dispatch using compressed dispatch tables](https://doi.org/10.1145/191081.191117) | Amiel E., Gruber O., Simon E. | ACM | OOPSLA | C | 1994 | M |
| [Improving the accuracy of static branch prediction using branch correlation](https://doi.org/10.1145/381792.195549) | Young C., Smith M. | ACM | ASPLOS | C | 1994 | M |
| [A compiler framework for restructuring data declarations to enhance cache and TLB effectiveness](https://dl.acm.org/citation.cfm?id=782188) | David F. Bacon J., Dz{-}Ching Ju K. | IEEE | CASCON | C | 1994 | S |
| [False sharing and spatial locality in multiprocessor caches](https://doi.org/10.1109/12.286299) | Torrellas J., Lam H., Hennessy J. | IEEE | TCO | J | 1994 | S |
| Reassociation and strength reduction | Markstein P., Markstein V., Zadeck F. | ACM | SCO | C | 1994 | S |
| The alignment-distribution graph | Chatterjee S., Gilbert J., Schreiber R. | Springer | LCPC | W | 1994 | S |
| [Improvements to graph coloring register allocation](https://doi.org/10.1145/177492.177575) | Briggs P., Cooper K., Torczon L. | ACM | TOPLAS | J | 1994 | A, E, M |
| [Context-sensitive interprocedural points-to analysis in the presence of function pointers](https://doi.org/10.1145/178243.178264) | Emami M., Ghiya R., Hendren L. | ACM | PLDI | C | 1994 | D, E |
| [Interprocedural may-alias analysis for pointers: beyond k-limiting](https://doi.org/10.1145/178243.178263) | Deutsch A. | ACM | PLDI | C | 1994 | A, E |
| [Scalar replacement in the presence of conditional control flow](https://doi.org/10.1002/spe.4380240104) | Carr S., Kennedy K. | Wiley | SPE | J | 1994 | E, O |
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
| [Dominators in linear time](https://doi.org/10.1137/S0097539797317263) | SIAM | SICOMP | J | 1999 | E |
| [Scalable context-sensitive flow analysis using instantiation constraints](https://doi.org/10.1145/358438.349332) | ACM | PLDI | C | 2000 | D |
| Unification-based pointer analysis with directional assignments | ACM | PLDI | C | 2000 | E |
| [Fast greedy weighted fusion](https://doi.org/10.1145/335231.335244) | ACM | ICS | C | 2000 | O |
| [Monotonic evolution: an alternative to induction variable substitution for dependence analysis](https://doi.org/10.1145/377792.377809) | ACM | ICS | C | 2001 | D |
| [Blocking and array contraction across arbitrarily nested loops using affine partitioning](https://doi.org/10.1145/568014.379586) | ACM | PPoPP | C | 2001 | D |
| [Ultra-fast Aliasing Analysis using CLA: A Million Lines of C Code in a Second](https://doi.org/10.1145/381694.378855) | ACM | PLDI | C | 2001 | D |
| [A simple, fast dominance algorithm](https://www.cs.tufts.edu/~nr/cs257/archive/keith-cooper/dom14.pdf)  | Wiley | SPE | J | 2001 | E, O |
| [Operator Strength Reduction](https://doi.org/10.1145/504709.504710) | ACM | TOPLAS | J | 2001 | A, E |
| [Symbolic pointer analysis](https://doi.org/10.1145/996893.996860) | IEEE | ICCAD | C | 2002 | D |
| [Cloning-based context-sensitive pointer alias analysis using binary decision diagrams](https://doi.org/10.1145/996841.996859) | ACM | PLDI | C | 2004 | D |
| [Symbolic pointer analysis Revisited](https://doi.org/10.1145/996893.996860) | ACM | PLDI | C | 2004 | D |
| [A generalized algorithm for graph-coloring register allocation](https://doi.org/10.1145/996893.996875) | ACM | PLDI | C | 2004 | E |
| [Optimistic register coalescing](https://doi.org/10.1145/1011508.1011512) | ACM | TOPLAS | J | 2004 | E |
| [Context-sensitive program analysis as database queries](https://doi.org/10.1145/1065167.1065169) | ACM | PODS | C | 2005 | D |
| [Improving software security with a C pointer analysis](https://doi.org/10.1145/1062455.1062520) | IEEE | ICSE | C | 2005 | D |
| [Register allocation via coloring of chordal graphs](https://doi.org/10.1007/11575467_21) | Springer | APLAS | C | 2005 | E |
---------------------| Polynomial time graph coloring register allocation | ACM | PLDI | C | 2005 | E |
| [Optimal register allocation for SSA-form programs in polynomial time](https://doi.org/10.1016/j.ipl.2006.01.008) | Elsevier | IPL | J | 2006 | E | -->
