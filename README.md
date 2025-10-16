# 📚 `interaction-net-resources`

_Interaction nets_ are a local graph rewriting formalism introduced by Yves Lafont in 1989. A particular interaction net is an undirected graph of **agents** connected through their **principal** & **auxiliary** ports; two agents connected through their principal ports form an **active pair**. By fixing (1) a set of **interaction rules** for reducing active pairs & (2) a suitable reduction strategy, we can evaluate the entire net to a normal form by repeatedly firing appropriate rules, until there are no more active pairs in the net. Since interaction nets were introduced, they have been mainly used for Lévy-optimal implementations of the lambda calculus, yet they constitute a universal model of computation, & can therefore serve as efficient implementations of conventional programming languages. Unlike more traditional computing formalisms, duplication and erasing are dealt with explicitly, allowing for a very high degree of sharing.

This is a collection of resources for studying interaction nets & their applications, ranging from introductory materials to advanced papers. Any questions regarding interaction nets will be welcomed in the issues.

## Projects

 - [BOHM](https://github.com/asperti/BOHM1.1) -- The Bologna Optimal Higher-Order Machine, version 1.1.
 - [PECLR](https://github.com/pis147879/PELCR) -- A parallel environment for optimal lambda calculus reduction.
 - [Optiscope](https://github.com/etiamz/optiscope) -- A Lévy-optimal lambda calculus reducer with a backdoor to C.
 - [Inpla](https://github.com/inpla/inpla) -- A multi-threaded parallel interpreter of interaction nets.
 - [ingpu](https://github.com/euschn/ingpu) -- A GPU-based evaluator for interaction nets.
 - [Linr](http://cl-informatik.uibk.ac.at/users/sgimenez/lin/) -- A lightweight parallel computation server for interaction nets.
 - [Vine](https://github.com/VineLang/vine) -- An experimental new programming language based on interaction nets.
 - [HVM](https://github.com/HigherOrderCO/HVM) -- A massively parallel functional runtime written in Rust.
 - [Bend](https://github.com/HigherOrderCO/Bend) -- A massively parallel, high-level programming language.
