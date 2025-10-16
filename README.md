# 📚 `interaction-net-resources`

_Interaction nets_ are a local graph rewriting formalism introduced by Yves Lafont in 1989. A particular interaction net is an undirected graph of **agents** connected through their **principal** & **auxiliary** ports; two agents connected through their principal ports form an **active pair**. By fixing (1) a set of **interaction rules** for reducing active pairs & (2) a suitable reduction strategy, we can evaluate the entire net to a normal form by repeatedly firing appropriate rules, until there are no more active pairs in the net. Since interaction nets were introduced, they have been mainly used for Lévy-optimal implementations of the lambda calculus, yet they constitute a universal model of computation, & can therefore serve as efficient implementations of conventional programming languages. In particular, duplication & erasing are dealt with at a structural level, which allows interaction nets to excel where sharing is a priority.

This is a collection of resources for studying interaction nets & their applications, ranging from introductory materials to advanced papers. Any questions regarding interaction nets will be welcomed in the issues.

For a more concise list, see [`marvinborner/interaction-net-resources`].

[`marvinborner/interaction-net-resources`]: https://github.com/marvinborner/interaction-net-resources

## Projects

 - [BOHM](https://github.com/asperti/BOHM1.1) -- The Bologna Optimal Higher-Order Machine, version 1.1.
 - [PECLR](https://github.com/pis147879/PELCR) -- A parallel environment for optimal lambda calculus reduction.
 - [Optiscope](https://github.com/etiamz/optiscope) -- A Lévy-optimal lambda calculus reducer with a backdoor to C.
 - [Inpla](https://github.com/inpla/inpla) -- A multi-threaded parallel interpreter of interaction nets.
 - [ingpu](https://github.com/euschn/ingpu) -- An experimental GPU-based evaluator for interaction nets.
 - [HVM](https://github.com/HigherOrderCO/HVM) -- A massively parallel functional runtime written in Rust.
 - [Bend](https://github.com/HigherOrderCO/Bend) -- A massively parallel, high-level programming language based on HVM.
 - [Vine](https://github.com/VineLang/vine) -- An experimental programming language based on interaction nets.
 - [inet-forth](https://github.com/xieyuheng/inet-forth) -- An implementation of interaction nets as a Forth-like language.
 - [Linr](http://cl-informatik.uibk.ac.at/users/sgimenez/lin/) -- A lightweight parallel computation server for interaction nets.
 - [GoI-Visualizer](https://koko-m.github.io/GoI-Visualiser/) -- A simulation tool of the dynamic GoI abstract machine.

## Papers

### 1989

 - Lafont, Yves. "Interaction nets." Proceedings of the 17th ACM SIGPLAN-SIGACT symposium on Principles of programming languages. 1989. $${\textbf{\color{lightgreen}introductory}}$$ $${\textbf{\color{gold}popular}}$$ $${\textbf{\color{orange}must read}}$$ $${\textbf{\color{thistle}programming}}$$
   <br>[URL](https://dl.acm.org/doi/pdf/10.1145/96709.96718)
 - Lamping, John. "An algorithm for optimal lambda calculus reduction." Proceedings of the 17th ACM SIGPLAN-SIGACT symposium on Principles of programming languages. 1989. $${\textbf{\color{gold}popular}}$$ $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$
   <br>[URL](https://dl.acm.org/doi/pdf/10.1145/96709.96711)

### 1990

 - Gay, Simon J. "Interaction nets." Diploma in Computer Science in Queens (1991). $${\textbf{\color{lightgreen}introductory}}$$
   <br>[URL](https://www.dcs.gla.ac.uk/~simon/publications/diploma.pdf), [webarchive](http://web.archive.org/web/20250123150222/https://www.dcs.gla.ac.uk/~simon/publications/diploma.pdf)

### 1992

 - Gonthier, Georges, Martín Abadi, and Jean-Jacques Lévy. "The geometry of optimal lambda reduction." Proceedings of the 19th ACM SIGPLAN-SIGACT symposium on Principles of programming languages. 1992. $${\textbf{\color{gold}popular}}$$ $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$
   <br>[URL](https://dl.acm.org/doi/pdf/10.1145/143165.143172)

### 1994

 - Asperti, Andrea, and Cosimo Laneve. "Interaction systems I: The theory of optimal reductions." Mathematical Structures in Computer Science 4.4 (1994): 457-504. $${\textbf{\color{purple}optimality}}$$
   <br>[URL](https://inria.hal.science/inria-00076988/document), [webarchive](http://web.archive.org/web/20251016074422/https://inria.hal.science/inria-00076988/document)

### 1995

 - Mackie, Ian. "The geometry of interaction machine." Proceedings of the 22nd ACM SIGPLAN-SIGACT symposium on Principles of programming languages. 1995. $${\textbf{\color{orchid}λ-calculus}}$$
   <br>[URL](https://dl.acm.org/doi/pdf/10.1145/199448.199483)

### 1996

 - Asperti, Andrea, and Cosimo Laneve. "Interaction Systems II: the practice of optimal reductions." Theoretical Computer Science 159.2 (1996): 191-244. $${\textbf{\color{purple}optimality}}$$
   <br>[URL](https://www.sciencedirect.com/science/article/pii/0304397595000623/pdf?md5=842ebd201d36c01e835ecb2c52014052&pid=1-s2.0-0304397595000623-main.pdf)
 - Lawall, Julia L., and Harry G. Mairson. "Optimality and inefficiency: what isn't a cost model of the lambda calculus?." ACM Sigplan Notices 31.6 (1996): 92-101. $${\textbf{\color{gold}popular}}$$ $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$ $${\textbf{\color{red}efficiency}}$$ $${\textbf{\color{crimson}complexity}}$$
   <br>[URL](https://dl.acm.org/doi/pdf/10.1145/232629.232639)
 - Asperti, Andrea, Cecilia Giovannetti, and Andrea Naletto. "The Bologna optimal higher-order machine." Journal of Functional Programming 6.6 (1996): 763-810. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$ $${\textbf{\color{red}efficiency}}$$ $${\textbf{\color{cyan}implementation}}$$
   <br>[URL](https://scispace.com/pdf/the-bologna-optimal-higher-order-machine-2ty9tlqc1w.pdf), [webarchive](http://web.archive.org/web/20251016074139/https://scispace.com/pdf/the-bologna-optimal-higher-order-machine-2ty9tlqc1w.pdf)
 - Danos, Vincent, and Laurent Regnier. "Reversible, Irreversible and Optimal λ-machines." Electronic Notes in Theoretical Computer Science 3 (1996): 40-60. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$
   <br>[URL](https://www.sciencedirect.com/science/article/pii/S0304397599000493)

### 1997

 - Lafont, Yves. "Interaction combinators." information and computation 137.1 (1997): 69-101. $${\textbf{\color{lightgreen}introductory}}$$ $${\textbf{\color{gold}popular}}$$ $${\textbf{\color{orange}must read}}$$
   <br>[URL](https://www.sciencedirect.com/science/article/pii/S0890540197926432)
 - Asperti, Andrea, and Juliusz Chroboczek. "Safe Operators: Brackets Closed Forever Optimizing Optimal λ-Calculus Implementations: Optimizing Optimal λ-Calculus Implementations." Applicable Algebra in Engineering, Communication and Computing 8.6 (1997): 437-468. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$ $${\textbf{\color{red}efficiency}}$$
   <br>[URL](https://link.springer.com/content/pdf/10.1007/s002000050083.pdf)
 - Asperti, Andrea. "P= NP, up to sharing." (1997). $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$
   <br>[URL](https://www.researchgate.net/publication/2758968_P_NP_up_to_sharing)

### 1998

 - Asperti, Andrea, and Stefano Guerrini. The optimal implementation of functional programming languages. Vol. 45. Cambridge University Press, 1998. $${\textbf{\color{lightgreen}introductory}}$$ $${\textbf{\color{gold}popular}}$$ $${\textbf{\color{orange}must read}}$$ $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$ $${\textbf{\color{red}efficiency}}$$ $${\textbf{\color{crimson}complexity}}$$ $${\textbf{\color{cyan}implementation}}$$ $${\textbf{\color{thistle}programming}}$$
   <br>[URL](https://www.amazon.com/exec/obidos/ASIN/0521621127/acmorg-20)
 - Mackie, Ian. "YALE: Yet another lambda evaluator based on interaction nets." Proceedings of the third ACM SIGPLAN international conference on Functional programming. 1998. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{red}efficiency}}$$
   <br>[URL](https://dl.acm.org/doi/pdf/10.1145/289423.289434)
 - Asperti, Andrea, and Harry G. Mairson. "Parallel beta reduction is not elementary recursive." Proceedings of the 25th ACM SIGPLAN-SIGACT symposium on Principles of programming languages. 1998. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$ $${\textbf{\color{crimson}complexity}}$$
   <br>[URL](https://dl.acm.org/doi/pdf/10.1145/268946.268971)
 - Fernández, Maribel, and Ian Mackie. "Interaction nets and term-rewriting systems." Theoretical Computer Science 190.1 (1998): 3-39.
   <br>[URL](https://www.sciencedirect.com/science/article/pii/S0304397597000820)

### 1999

 - Fernández, Maribel, and Ian Mackie. "A calculus for interaction nets." International Conference on Principles and Practice of Declarative Programming. Berlin, Heidelberg: Springer Berlin Heidelberg, 1999. $${\textbf{\color{orange}must read}}$$
   <br>[URL](https://link.springer.com/chapter/10.1007/10704567_10)

### 2000

 - Pinto, Jorge Sousa. "Sequential and concurrent abstract machines for interaction nets." International Conference on Foundations of Software Science and Computation Structures. Berlin, Heidelberg: Springer Berlin Heidelberg, 2000. $${\textbf{\color{cyan}implementation}}$$
   <br>[URL](https://link.springer.com/content/pdf/10.1007/3-540-46432-8_18.pdf)
 - Asperti, Andrea, Paolo Coppola, and Simone Martini. "(Optimal) duplication is not elementary recursive." Proceedings of the 27th ACM SIGPLAN-SIGACT symposium on Principles of programming languages. 2000. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$ $${\textbf{\color{crimson}complexity}}$$
   <br>[URL](https://dl.acm.org/doi/pdf/10.1145/325694.325707)
 - Pedicini, Marco, and Francesco Quaglia. "A parallel implementation for optimal lambda-calculus reduction." Proceedings of the 2nd ACM SIGPLAN international conference on Principles and practice of declarative programming. 2000. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$ $${\textbf{\color{red}efficiency}}$$ $${\textbf{\color{aquamarine}parallelism}}$$
   <br>[URL](https://dl.acm.org/doi/pdf/10.1145/351268.351270)
 - Mackie, Ian. "Interaction nets for linear logic." Theoretical Computer Science 247.1-2 (2000): 83-140.
   <br>[URL](https://www.sciencedirect.com/science/article/pii/S0304397500001985)
 - Alexiev, Vladimir. Non-deterministic interaction nets. University of Alberta, 2000.
   <br>[URL](https://central.bac-lac.gc.ca/.item?id=NQ46797&op=pdf&app=Library&oclc_number=1006677144), [webarchive](http://web.archive.org/web/20251016073816/https://central.bac-lac.gc.ca/.item?id=NQ46797&op=pdf&app=Library&oclc_number=1006677144)

### 2001

 - Fernández, Maribel, Ian Mackie, and Jorge Sousa Pinto. "Combining interaction nets with externally defined programs." (2001). $${\textbf{\color{thistle}input-output}}$$
   <br>[URL](https://core.ac.uk/download/pdf/55602454.pdf), [webarchive](http://web.archive.org/web/20251016073740/https://core.ac.uk/download/pdf/55602454.pdf)

### 2002

 - Mackie, Ian, and Jorge Sousa Pinto. "Encoding linear logic with interaction combinators." Information and Computation 176.2 (2002): 153-186.
   <br>[URL](https://www.sciencedirect.com/science/article/pii/S0890540102931639)
 - Lippi, Sylvain. "Encoding left reduction in the λ-calculus with interaction nets." Mathematical Structures in Computer Science 12.6 (2002): 797-822. $${\textbf{\color{orchid}λ-calculus}}$$
   <br>[URL](https://doi.org/10.1017/S0960129502003754)
 - Lippi, Sylvain. "in2: A graphical interpreter for interaction nets." International Conference on Rewriting Techniques and Applications. Berlin, Heidelberg: Springer Berlin Heidelberg, 2002. $${\textbf{\color{cyan}implementation}}$$ $${\textbf{\color{thistle}programming}}$$
   <br>[URL](https://link.springer.com/chapter/10.1007/3-540-45610-4_29)
 - Fernández, Maribel, and Ian Mackie. "Call-by-value λ-graph rewriting without rewriting." International Conference on Graph Transformation. Berlin, Heidelberg: Springer Berlin Heidelberg, 2002. $${\textbf{\color{orchid}λ-calculus}}$$
   <br>[URL](https://link.springer.com/chapter/10.1007/3-540-45832-8_8)
 - Fernandez, Maribel, and Lionel Khalil. "Interaction Nets with McCarthy's amb." Electronic Notes in Theoretical Computer Science 68.2 (2002): 51-68.
   <br>[URL](https://www.sciencedirect.com/science/article/pii/S1571066105803639)

### 2003

 - Fernández, Maribel, and Ian Mackie. "Operational equivalence for interaction nets." Theoretical Computer Science 297.1-3 (2003): 157-181.
   <br>[URL](https://www.sciencedirect.com/science/article/pii/S0304397502006370)
 - Pinto, Jorge Sousa. "Weak reduction and garbage collection in interaction nets." Electronic Notes in Theoretical Computer Science 86.4 (2003): 625-640. $${\textbf{\color{purple}optimality}}$$ $${\textbf{\color{red}efficiency}}$$
   <br>[URL](https://doi.org/10.1016/S1571-0661(05)82614-3)
 - Thyer, Michael Jonathan. Lazy specialization. University of York, Department of Computer Science, 2003. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$
   <br>[URL](http://www.thyer.name/phd-thesis/thesis-thyer.pdf), [webarchive](https://web.archive.org/web/20240730045022if_/http://www.thyer.name/phd-thesis/thesis-thyer.pdf)

### 2004

 - Mackie, Ian. "Efficient λ-evaluation with interaction nets." International Conference on Rewriting Techniques and Applications. Berlin, Heidelberg: Springer Berlin Heidelberg, 2004. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{red}efficiency}}$$
   <br>[URL](https://link.springer.com/chapter/10.1007/978-3-540-25979-4_11)
 - van Oostrom, Vincent, Kees-Jan van de Looij, and Marijn Zwitserlood. "Lambdascope: another optimal implementation of the lambda-calculus." Workshop on Algebra and Logic on Programming Systems (ALPS). 2004. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$
   <br>[URL](http://www.javakade.nl/research/pdf/lambdascope.pdf), [webarchive](http://web.archive.org/web/20251016073247/http://www.javakade.nl/research/pdf/lambdascope.pdf)

### 2005

 - Baillot, Patrick, and Kazushige Terui. "A feasible algorithm for typing in elementary affine logic." International Conference on Typed Lambda Calculi and Applications. Berlin, Heidelberg: Springer Berlin Heidelberg, 2005. $${\textbf{\color{red}efficiency}}$$
   <br>[URL](https://arxiv.org/pdf/cs/0412028), [webarchive](http://web.archive.org/web/20251016073124/https://arxiv.org/pdf/cs/0412028)
 - Mackie, Ian. "Towards a programming language for interaction nets." Electronic Notes in Theoretical Computer Science 127.5 (2005): 133-151. $${\textbf{\color{thistle}programming}}$$
   <br>[URL](https://www.sciencedirect.com/science/article/pii/S1571066105050176)
 - Guerrini, Stefano. "Sharing implementations of graph rewriting systems." Electronic Notes in Theoretical Computer Science 127.5 (2005): 113-132. $${\textbf{\color{lightgreen}introductory}}$$ $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$
   <br>[URL](https://www.sciencedirect.com/science/article/pii/S1571066105050164)
 - Sinot, François-Régis. "Call-by-name and call-by-value as token-passing interaction nets." International Conference on Typed Lambda Calculi and Applications. Berlin, Heidelberg: Springer Berlin Heidelberg, 2005. $${\textbf{\color{orchid}λ-calculus}}$$
   <br>[URL](https://link.springer.com/chapter/10.1007/11417170_28)
 - Mackie, Ian. "Encoding strategies in the lambda calculus with interaction nets." Symposium on Implementation and Application of Functional Languages. Berlin, Heidelberg: Springer Berlin Heidelberg, 2005. $${\textbf{\color{orchid}λ-calculus}}$$
   <br>[URL](https://link.springer.com/chapter/10.1007/11964681_2)
 - Sinot, François-Régis. "Call-by-name and call-by-value as token-passing interaction nets." International Conference on Typed Lambda Calculi and Applications. Berlin, Heidelberg: Springer Berlin Heidelberg, 2005. $${\textbf{\color{orchid}λ-calculus}}$$
   <br>[URL](https://link.springer.com/chapter/10.1007/11417170_28)
 - Mackie, Ian, Jorge Sousa Pinto, and Miguel Vilaça. "Functional programming and program transformation with interaction nets." (2005).
   <br>[URL](https://www.researchgate.net/publication/228680206_Functional_programming_and_program_transformation_with_interaction_nets)

### 2006

 - Sinot, François-Régis. Stratégies Efficaces et Modèles d'Implantation pour les Langages Fonctionnels. Diss. Ecole Polytechnique X, 2006. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{red}efficiency}}$$
   <br>[URL](https://pastel.hal.science/pastel-00001952/document), [webarchive](http://web.archive.org/web/20251016103559/https://pastel.hal.science/pastel-00001952/document)
 - Coppola, Paolo, and Simone Martini. "Optimizing optimal reduction: A type inference algorithm for elementary affine logic." ACM Transactions on Computational Logic (TOCL) 7.2 (2006): 219-260. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$ $${\textbf{\color{red}efficiency}}$$
   <br>[URL](https://dl.acm.org/doi/pdf/10.1145/1131313.1131315)
 - Ehrhard, Thomas, and Laurent Regnier. "Differential interaction nets." Theoretical Computer Science 364.2 (2006): 166-195.
   <br>[URL](https://www.sciencedirect.com/science/article/pii/S0304397506005299)
 - Mazza, Damiano. "Interaction nets: Semantics and concurrent extensions." These de doctorat, Université Aix-Marseille II/Universita degli Studi Roma Tre (2006).
   <br>[URL](https://lipn.univ-paris13.fr/~mazza/papers/Thesis-1.0.pdf), [webarchive](http://web.archive.org/web/20251016072951/https://lipn.univ-paris13.fr/~mazza/papers/Thesis-1.0.pdf)
 - Sinot, François-Régis. "Token-passing nets: Call-by-need for free." Electronic Notes in Theoretical Computer Science 135.3 (2006): 129-139.
   <br>[URL](https://www.sciencedirect.com/science/article/pii/S1571066106000934)

### 2007

 - Mazza, Damiano. "A denotational semantics for the symmetric interaction combinators." Mathematical Structures in Computer Science 17.3 (2007): 527-562.
   <br>[URL](https://lipn.univ-paris13.fr/~mazza/papers/CombSem-MSCS.pdf), [webarchive](http://web.archive.org/web/20250930033905/https://lipn.univ-paris13.fr/~mazza/papers/CombSem-MSCS.pdf)
 - Lippi, Sylvain. "The graphical Krivine machine." Higher-order and symbolic computation 20.3 (2007): 295-318. $${\textbf{\color{orchid}λ-calculus}}$$
   <br>[URL](https://link.springer.com/article/10.1007/s10990-007-9011-3)
 - Terui, Kazushige. "Light affine lambda calculus and polynomial time strong normalization." Archive for Mathematical Logic 46.3 (2007): 253-280. $${\textbf{\color{orchid}λ-calculus}}$$
   <br>[URL](https://doi.org/10.1007/s00153-007-0042-6)
 - Cirstea, Horatiu, et al. "From functional programs to interaction nets via the Rewriting Calculus." Electronic Notes in Theoretical Computer Science 174.10 (2007): 39-56.
   <br>[URL](https://doi.org/10.1016/j.entcs.2007.02.046)
 - Zwitserlood, Marijn. End-of-Scope, Locally. 2007. Universiteit Utrecht, Master's thesis. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$
   <br>[URL](http://www.javakade.nl/research/supervised/marijnzwitserlood.pdf), [webarchive](http://web.archive.org/web/20251016104532/http://www.javakade.nl/research/supervised/marijnzwitserlood.pdf)

### 2008

 - Hassan, Abubakar, Ian Mackie, and Shinya Sato. "Interaction nets: programming language design and implementation." Electronic Communications of the EASST 10 (2008). $${\textbf{\color{cyan}implementation}}$$ $${\textbf{\color{thistle}programming}}$$
   <br>[URL](https://www.user.tu-berlin.de/o.runge/tfs/workshops/gtvmt08/Program/paper_38.pdf), [webarchive](http://web.archive.org/web/20241210103945/https://www.user.tu-berlin.de/o.runge/tfs/workshops/gtvmt08/Program/paper_38.pdf)
 - Béchet, Denis, and Sylvain Lippi. "Hard combinators." Electronic Notes in Theoretical Computer Science 203.1 (2008): 31-48.
   <br>[URL](https://www.researchgate.net/publication/222019408_Hard_combinators)
 - Almeida, José Bacelar, Jorge Sousa Pinto, and Miguel Vilaça. "Token-passing nets for functional languages." Electronic Notes in Theoretical Computer Science 204 (2008): 181-198.
   <br>[URL](https://www.sciencedirect.com/science/article/pii/S1571066108001667)
 - Mackie, Ian. "An interaction net implementation of closed reduction." Symposium on Implementation and Application of Functional Languages. Berlin, Heidelberg: Springer Berlin Heidelberg, 2008. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{red}efficiency}}$$
   <br>[URL](https://link.springer.com/chapter/10.1007/978-3-642-24452-0_3)

### 2009

 - Hassan, Abubakar, Ian Mackie, and Shinya Sato. "Compilation of interaction nets." Electronic Notes in Theoretical Computer Science 253.4 (2009): 73-90. $${\textbf{\color{red}efficiency}}$$
   <br>[URL](https://www.sciencedirect.com/science/article/pii/S1571066109004381)
 - Lippi, Sylvain. "Universal Hard Interaction for Clockless Computation: Dem Glücklichen schlägt keine Stunde!." Fundamenta Informaticae 91.2 (2009): 357-394.
   <br>[URL](https://dl.acm.org/doi/abs/10.5555/1549637.1549661)
 - Mackie, Ian, Jorge Sousa Pinto, and Miguel Vilaça. "Iterators, Recursors and Interaction Nets." arXiv preprint arXiv:0910.3321 (2009). $${\textbf{\color{thistle}programming}}$$
   <br>[URL](https://www.researchgate.net/publication/45878966_Iterators_Recursors_and_Interaction_Nets)
 - Fernández, Maribel, et al. "Recursive functions with pattern matching in interaction nets." Electronic Notes in Theoretical Computer Science 253.4 (2009): 55-71. $${\textbf{\color{thistle}programming}}$$
   <br>[URL](https://www.sciencedirect.com/science/article/pii/S157106610900437X)
 - Gimenez, Stéphane. Programmer, calculer et raisonner avec les réseaux de la logique linéaire. Diss. Université Paris-Diderot-Paris VII, 2009.
   <br>[URL](http://cl-informatik.uibk.ac.at/users/sgimenez/thesis-sgimenez.pdf), [webarchive](http://web.archive.org/web/20251016072522/http://cl-informatik.uibk.ac.at/users/sgimenez/thesis-sgimenez.pdf)

### 2010

 - Hassan, Abubakar, Eugen Jiresch, and Shinya Sato. "An implementation of nested pattern matching in interaction nets." arXiv preprint arXiv:1003.4562 (2010). $${\textbf{\color{thistle}programming}}$$
   <br>[URL](https://arxiv.org/pdf/1003.4562), [webarchive](http://web.archive.org/web/20250913110939/https://arxiv.org/pdf/1003.4562)
 - Hassan, Abubakar, Ian Mackie, and Shinya Sato. "A lightweight abstract machine for interaction nets." Electronic Communications of the EASST 29 (2010). $${\textbf{\color{red}efficiency}}$$ $${\textbf{\color{cyan}implementation}}$$
   <br>[URL](https://doi.org/10.14279/tuj.eceasst.29.416)
 - Fernández, Maribel, and Nikolaos Siafakas. "Labelled lambda-calculi with explicit copy and erase." arXiv preprint arXiv:1003.5515 (2010). $${\textbf{\color{orchid}λ-calculus}}$$
   <br>[URL](https://arxiv.org/pdf/1003.5515), [webarchive](http://web.archive.org/web/20251016072419/https://arxiv.org/pdf/1003.5515)

### 2012

 - Guerrini, Stefano, Thomas Leventis, and Marco Solieri. "Deep into optimality–complexity and correctness of sharing implementation of bounded logics." Third International Workshop on Developments in Implicit Complexity. 2012. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$ $${\textbf{\color{crimson}complexity}}$$
   <br>[URL](https://ms.xt3.it/research/DeepIntoOptimality_2012-02-17.pdf), [webarchive](http://web.archive.org/web/20251016072157/https://ms.xt3.it/research/DeepIntoOptimality_2012-02-17.pdf)
 - Jiresch, Eugen Robert Winfried. Extending interaction nets towards the real world. Diss. Technische Universität Wien, 2012. $${\textbf{\color{thistle}input-output}}$$
   <br>[URL](https://repositum.tuwien.at/bitstream/20.500.12708/12949/2/Jiresch%20Eugen%20Robert%20Winfried%20-%202012%20-%20Extending%20interaction%20nets%20towards%20the...pdf), [webarchive](http://web.archive.org/web/20251016072103/https://repositum.tuwien.at/bitstream/20.500.12708/12949/2/Jiresch%20Eugen%20Robert%20Winfried%20-%202012%20-%20Extending%20interaction%20nets%20towards%20the...pdf)

### 2013

 - Gimenez, Stéphane, and Georg Moser. "The structure of interaction." Computer Science Logic 2013 (CSL 2013). Schloss Dagstuhl–Leibniz-Zentrum für Informatik, 2013.
   <br>[URL](http://cl-informatik.uibk.ac.at/users/sgimenez/data/articles/soi.pdf), [webarchive](http://web.archive.org/web/20241204085641/http://cl-informatik.uibk.ac.at/users/sgimenez/data/articles/soi.pdf)
 - Fernández, Maribel, Ian Mackie, and Matthew Walker. "Bigraphical nets." arXiv preprint arXiv:1302.6339 (2013).
   <br>[URL](https://arxiv.org/pdf/1302.6339), [webarchive](http://web.archive.org/web/20251016071851/https://arxiv.org/pdf/1302.6339)
 - Balabonski, Thibaut. "Weak optimality, and the meaning of sharing." ACM SIGPLAN Notices 48.9 (2013): 263-274. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$
   <br>[URL](https://doi.org/10.1145/2544174.2500606)

### 2014

 - Pedicini, Marco, Giulio Pellitta, and Mario Piazza. "Sequential and parallel abstract machines for optimal reduction." Preproceedings of the 15th Symposium on Trends in Functional Programming (TFP2014). 2014. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$ $${\textbf{\color{aquamarine}parallelism}}$$
   <br>[URL](https://www.mat.uniroma3.it/users/pedicini/papers/subTFP2014.pdf), [webarchive](http://web.archive.org/web/20251016071634/https://www.mat.uniroma3.it/users/pedicini/papers/subTFP2014.pdf)

### 2015

 - Kahl, Wolfram. "A simple parallel implementation of interaction nets in Haskell." arXiv preprint arXiv:1504.02603 (2015). $${\textbf{\color{cyan}implementation}}$$ $${\textbf{\color{aquamarine}parallelism}}$$
   <br>[URL](http://arxiv.org/pdf/1504.02603), [webarchive](http://web.archive.org/web/20251008173559/https://arxiv.org/pdf/1504.02603)
 - Sato, Shinya. Design and implementation of a low-level language for interaction nets. Diss. University of Sussex, 2015. $${\textbf{\color{red}efficiency}}$$ $${\textbf{\color{cyan}implementation}}$$ $${\textbf{\color{thistle}programming}}$$
   <br>[URL](https://sussex.figshare.com/articles/thesis/Design_and_implementation_of_a_low-level_language_for_interaction_nets/23417312/1)
 - Hassan, Abubakar, Ian Mackie, and Shinya Sato. "An implementation model for interaction nets." arXiv preprint arXiv:1505.07164 (2015). $${\textbf{\color{red}efficiency}}$$ $${\textbf{\color{cyan}implementation}}$$
   <br>[URL](https://arxiv.org/pdf/1505.07164), [webarchive](http://web.archive.org/web/20250916003558/https://arxiv.org/pdf/1505.07164)

### 2016

 - Mackie, Ian, and Shinya Sato. "In-place Graph Rewriting with Interaction Nets." arXiv preprint arXiv:1609.03641 (2016). $${\textbf{\color{red}efficiency}}$$
   <br>[URL](https://arxiv.org/pdf/1609.03641), [webarchive](http://web.archive.org/web/20241210105346/https://arxiv.org/pdf/1609.03641)
 - Mackie, Ian, and Shinya Sato. "Parallel Evaluation of Interaction Nets: Case Studies and Experiments." Electronic Communications of the EASST 73 (2016). $${\textbf{\color{red}efficiency}}$$ $${\textbf{\color{aquamarine}parallelism}}$$
   <br>[URL](https://eceasst.org/index.php/eceasst/article/download/2205/2376/2387)
 - Gimenez, Stéphane, and Georg Moser. "The complexity of interaction." Proceedings of the 43rd Annual ACM SIGPLAN-SIGACT Symposium on Principles of Programming Languages. 2016. $${\textbf{\color{crimson}complexity}}$$
   <br>[URL](https://dl.acm.org/doi/10.1145/2837614.2837646)
 - Gimenez, Stéphane, and David Obwaller. "Interaction Automata and the ia2d Interpreter." 1st International Conference on Formal Structures for Computation and Deduction (FSCD 2016). Schloss Dagstuhl–Leibniz-Zentrum für Informatik, 2016. $${\textbf{\color{cyan}implementation}}$$
   <br>[URL](http://cl-informatik.uibk.ac.at/users/sgimenez/data/articles/ia2d.pdf), [webarchive](http://web.archive.org/save/http://cl-informatik.uibk.ac.at/users/sgimenez/data/articles/ia2d.pdf)
 - Salikhmetov, Anton. "Token-passing Optimal Reduction with Embedded Read-back." arXiv preprint arXiv:1609.03644 (2016). $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$
   <br>[URL](https://arxiv.org/pdf/1609.03644), [webarchive](http://web.archive.org/web/20251016070555/https://arxiv.org/pdf/1609.03644)

### 2017

 - Asperti, Andrea. "About the efficient reduction of lambda terms." arXiv preprint arXiv:1701.04240 (2017). $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$ $${\textbf{\color{red}efficiency}}$$ $${\textbf{\color{crimson}complexity}}$$
   <br>[URL](https://arxiv.org/pdf/1701.04240), [webarchive](http://web.archive.org/web/20251016070315/https://arxiv.org/pdf/1701.04240)
 - Barenbaum, Pablo, and Eduardo Bonelli. "Optimality and the linear substitution calculus." 2nd International Conference on Formal Structures for Computation and Deduction (FSCD 2017). Schloss Dagstuhl–Leibniz-Zentrum für Informatik, 2017. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$
   <br>[URL](https://drops.dagstuhl.de/storage/00lipics/lipics-vol084-fscd2017/LIPIcs.FSCD.2017.9/LIPIcs.FSCD.2017.9.pdf), [webarchive](http://web.archive.org/web/20250723194427/https://drops.dagstuhl.de/storage/00lipics/lipics-vol084-fscd2017/LIPIcs.FSCD.2017.9/LIPIcs.FSCD.2017.9.pdf)
 - Dal Lago, Ugo, Ryo Tanaka, and Akira Yoshimizu. "The geometry of concurrent interaction: Handling multiple ports by way of multiple tokens." 2017 32nd Annual ACM/IEEE Symposium on Logic in Computer Science (LICS). IEEE, 2017.
   <br>[URL](http://ieeexplore.ieee.org/document/8005112/)
 - Muroya, Koko, and Dan R. Ghica. "The dynamic Geometry of Interaction machine: a call-by-need graph rewriter." arXiv preprint arXiv:1703.10027 (2017). $${\textbf{\color{orchid}λ-calculus}}$$
   <br>[URL](https://arxiv.org/pdf/1803.00427), [webarchive](http://web.archive.org/web/20251016070027/https://arxiv.org/pdf/1803.00427)

### 2018

 - Muroya, Koko, and Dan R. Ghica. "Efficient implementation of evaluation strategies via token-guided graph rewriting." arXiv preprint arXiv:1802.06495 (2018). $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{red}efficiency}}$$
   <br>[URL](https://arxiv.org/pdf/1802.06495), [webarchive](http://web.archive.org/web/20250810125528/https://arxiv.org/pdf/1802.06495)

### 2019

 - Aschieri, Federico, and Francesco A. Genco. "Par means parallel: multiplicative linear logic proofs as concurrent functional programs." Proceedings of the ACM on Programming Languages 4.POPL (2019): 1-28. $${\textbf{\color{aquamarine}parallelism}}$$
   <br>[URL](https://dl.acm.org/doi/10.1145/3371086)
 - Lai, Anna Chiara, Marco Pedicini, and Mario Piazza. "Abstract machines, optimal reduction, and streams." Mathematical Structures in Computer Science 29.9 (2019): 1379-1410. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$
   <br>[URL](https://iris.uniroma1.it/bitstream/11573/1408275/6/Lai_preprint_abstract_2019.pdf), [webarchive](http://web.archive.org/web/20251016065751/https://iris.uniroma1.it/bitstream/11573/1408275/6/Lai_preprint_abstract_2019.pdf)

### 2020

 - Accattoli, Beniamino, Ugo Dal Lago, and Gabriele Vanoni. "The machinery of interaction." Proceedings of the 22nd International Symposium on Principles and Practice of Declarative Programming. 2020. $${\textbf{\color{orchid}λ-calculus}}$$
   <br>[URL](https://arxiv.org/pdf/2002.05649), [webarchive](http://web.archive.org/web/20251016065632/https://arxiv.org/pdf/2002.05649)
 - Muroya, Koko. Hypernet semantics of programming languages. Diss. University of Birmingham, 2020. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{red}efficiency}}$$
   <br>[URL](https://group-mmm.org/~koko/papers/phdthesis.pdf), [webarchive](http://web.archive.org/web/20250226193134/https://group-mmm.org/~koko/papers/phdthesis.pdf)

### 2022

 - Dal Lago, Ugo. "Implicit computation complexity in higher-order programming languages: A Survey in Memory of Martin Hofmann." Mathematical Structures in Computer Science 32.6 (2022): 760-776. $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{crimson}complexity}}$$
   <br>[URL](https://www.researchgate.net/publication/359247675_Implicit_computation_complexity_in_higher-order_programming_languages_A_Survey_in_Memory_of_Martin_Hofmann)

### 2025

 - Huber, Nikolaus, and Wang Yi. "An Encoding of Interaction Nets in OCaml." arXiv preprint arXiv:2503.20463 (2025). $${\textbf{\color{cyan}implementation}}$$
   <br>[URL](https://arxiv.org/pdf/2503.20463), [webarchive](http://web.archive.org/web/20251016070906/https://arxiv.org/pdf/2503.20463)
 - Borner, Marvin. "Optimal Interaction With the Real World." 2025. Eberhard Karls Universität Tübingen, Bachelor's thesis. $${\textbf{\color{lightgreen}introductory}}$$ $${\textbf{\color{orchid}λ-calculus}}$$ $${\textbf{\color{purple}optimality}}$$ $${\textbf{\color{thistle}input-output}}$$
   <br>[URL](https://raw.githubusercontent.com/marvinborner/optimal-effects/refs/heads/bachelor/thesis.pdf)
