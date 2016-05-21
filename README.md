Resources from the chapter notes on the book *Introduction to Functional
Programming using Haskell, second edition.*
Note that it is a 1998 book, so not everything said might be entirely
up-to-date. Nonetheless, the resources should still be relevant.
Most of the text explanations are taken verbatim from the chapter notes on the
book, adding links to the resources whenever available. If it's a freely
available paper or book, there is a link to it, otherwise it's just the
resource's name.

# Fundamental concepts
For further information about the denotational aspects of programming
languages, consult [Stoy (1977)](https://github.com/contiver/itfpuh2-resources#joe-stoy-denotational-semantics-the-scott-strachey-approach-to-programming-language-theory)
or [Gordon (1979)](https://github.com/contiver/itfpuh2-resources#michael-jc-gordon-the-denotational-description-of-programming-languages-an-introduction).
The implementation of lazy functional languages is covered in 
[Peyton Jones(1987)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Peyton%20Jones%20-%20The%20Implementation%20of%20Functional%20Programming%20Languages.djvu)
and [Peyton Jones and Lester (1991)](https://github.com/contiver/itfpuh2-resources#peyton-jones-lester-implementing-functional-languages-a-tutorial).
The formal derivation of programs from their specifications is
the subject of [Morgan (1996)](https://github.com/contiver/itfpuh2-resources#morgan-programming-from-specifications)
and [Kaldewaij (1990)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Kaldewaij%20-%20Programming.%20The%20Derivation%20of%20Algorithms.pdf),
although the target programming language is procedural, not functional. For
functional and relational treatment of program derivation in categorical
setting, consult [Bird and de Moor (1997)](https://github.com/contiver/itfpuh2-resources#bird-and-de-moor-the-algebra-of-programming).
This is and advanced text, suitable for those particularly interested in the
mathematics of programming, and can be studied after the present one.

##### A Gentle Introduction to Haskell
##### Joe Stoy. Denotational Semantics: The Scott-Strachey Approach to Programming Language Theory
##### Michael J.C. Gordon. The Denotational Description of Programming Languages: An Introduction
##### Peyton Jones, Lester. Implementing Functional Languages: a tutorial
##### Morgan. Programming from Specifications
##### Kaldewaij. Programming: The derivation of algorithms
##### Bird and de Moor. The Algebra of Programming

# Simple datatypes
Modern accounts of boolean algebra and logic, suitable for computing
scientists, include [Ben-Ari (1993)](https://github.com/contiver/itfpuh2-resources#ben-ari-mathematical-logic-for-computer-science),
[Burke and Foxley (1996)](https://github.com/contiver/itfpuh2-resources#burke-and-foxley-logic-and-its-applications),
[Gries and Schneider (1995)](https://github.com/contiver/itfpuh2-resources#gries-and-schneider-a-logical-approach-to-discrete-math).  
The theoretical foundations of type classes are studied in
[Wadler and Blott (1989)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Wadler%2C%20Blott%20-%20How%20to%20make%20ad-hoc%20polymorphism%20less%20ad-hoc.pdf)
and Jones ([1992](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Jones%20-%20Qualified%20Types.%20Theory%20and%20Practice.pdf),
[1995](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Jones%20-%20Qualified%20Types.%20Theory%20and%20Practice.pdf)).  
The notations *f* **x** *g* and *f* **+** *g* are used in a branch of mathematics
called category theory, which from one point of view can be regarded as a
foundation for functional programming. Suitable texts for computing scientists
include [Barr and Wells (1995)](https://github.com/contiver/itfpuh2-resources#barr-and-wells-category-theory-for-computing-science),
[Pierce (1991)](https://github.com/contiver/itfpuh2-resources#pierce-basic-category-theory-for-computer-scientists),
[Bird and de Moor (1997)](https://github.com/contiver/itfpuh2-resources#pierce-basic-category-theory-for-computer-scientists).

##### Ben-Ari. Mathematical Logic for Computer Science
##### Burke and Foxley. Logic and Its Applications
##### Gries and Schneider. A Logical Approach to Discrete Math
##### Barr and Wells. Category Theory for Computing Science
##### Pierce. Basic Category Theory for Computer Scientists 

# Numbers 
A full discussion of computer arithmetic can be found in
[Knuth (1981)](https://github.com/contiver/itfpuh2-resources#knuth-the-art-of-computer-programming-volume-2-seminumerical-algorithms).
Linear and binary search are fundamental programming techniques and are covered in
[Morgan (1996)](https://github.com/contiver/itfpuh2-resources#morgan-programming-from-specifications)
and [Kaldewaij (1990)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Kaldewaij%20-%20Programming.%20The%20Derivation%20of%20Algorithms.pdf).
The properties of floors, as well as many other useful numerical functions, are given in 
[Graham, Knuth, and Patashnik (1990)](https://github.com/contiver/itfpuh2-resources#graham-knuth-patashnik-concrete-mathematics-a-foundation-for-computer-science).
Church numerals are presented in
[Church (1941)](https://github.com/contiver/itfpuh2-resources#church-the-calculi-of-lambda-conversion)
and discussed in
[Gordon (1994)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Gordon%20-%20Programming%20Language%20Theory%20and%20its%20Implementation.pdf).

##### Knuth. The Art of Computer Programming, Volume 2: Seminumerical Algorithms
##### Graham, Knuth, Patashnik. Concrete Mathematics: A Foundation for Computer Science
##### Church. The Calculi of Lambda-Conversion

# Lists
A great deal of work has been done on automatic or machine-aided generation of
induction proofs; see, for example, [Boyer and Moore (1979)](https://www.cs.utexas.edu/users/boyer/acl.pdf),
[Gordon, Milner, and Wadsworth (1979)](https://github.com/contiver/itfpuh2-resources#gordon-milner-and-wadsworth-edinburgh-lcf-a-mechanized-logic-of-computation),
[Paulson (1983)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Paulson.%20A%20higher-order%20implementation%20of%20rewriting.pdf),
[Martin and Nipkow (1990)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Martin%2C%20Nipkow%20-%20Automating%20Squiggol.pdf).  
The relationship between polymorphic functions and naturality conditions is
explored in [Wadler (1989)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Wadler%20-%20Theorems%20for%20free!.pdf);
see also [Bird and de Moor (1997)](https://github.com/contiver/itfpuh2-resources#bird-and-de-moor-the-algebra-of-programming).  
The fusion laws for fold operators were systematised in
[Malcolm (1990)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Malcom%20-%20Algebraic%20Data%20Types%20and%20Program%20Transformation.pdf),
[Fokkinga (1992)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Fokkinga%20-%20Law%20and%20Order%20in%20Algorithmics.pdf),
[Jeuring (1993)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Jeuring%20-%20Theories%20for%20Algorithm%20Calculation.pdf),
and [Meijer (1992)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Meijer%20-%20Calculating%20Compilers.pdf).  
The maximum segment sum problem is described in 
[Bentley (1987)](https://github.com/contiver/itfpuh2-resources#bentley-programming-pearls).
The derivation recorded in this chapter was first given in
[Bird (1989, Algebraic Identities for Program Calculation)](http://comjnl.oxfordjournals.org/content/32/2/122.short).

##### Gordon, Milner, and Wadsworth. Edinburgh LCF. A Mechanized Logic of Computation
##### Bentley. Programming Pearls

# Trees
Good source books on trees include 
[Cormen, Leiserson, and Rivest (1990)](https://github.com/contiver/itfpuh2-resources#cormen-leiserson-rivest-stein-introduction-to-algorithms)
and [Knuth (1973b)](https://github.com/contiver/itfpuh2-resources#knuth-the-art-of-computer-programming-volume-3-sorting-and-searching).
Rose trees, which also go under the name general trees, were so named in 
[Meertens (1987)](#Meertens. Lambert Meertens. First steps towards the theory of rose trees. CWI, Amsterdam; IFIP Working Group 2.1 working paper 592 ROM-25, 1988). 
[Gibbons' thesis (1991)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Gibbons%20-%20Algebras%20for%20Tree%20Algorithms.pdf)
contains a systematic treatment of a number of algorithms on trees.

Huffman coding was described in [Huffman (1952; A Method for the Construction of Minimum-Redundancy Codes)](https://github.com/contiver/itfpuh2-resources#fundamental-concepts);
see also [Hu (1982)](https://github.com/contiver/itfpuh2-resources#hu-combinatorial-algorithms)
and [Knuth (1973a)](https://github.com/contiver/itfpuh2-resources#knuth-the-art-of-computer-programming-volume-1-fundamental-algorithms).
[Thompson (1996)](https://github.com/contiver/itfpuh2-resources#simon-thompson-haskell-the-craft-of-functional-programming) 
also gives a functional program for Huffman coding.

The problem of computing Meertens' number was first considered in 
[Bird (1991)](https://github.com/contiver/itfpuh2-resources#bird-meertens-number).
Gödel numbering was used by Gödel in his 1931 proof of his famous theorem on
the incompletness of arithmetic; see the collected works:
[Gödel (1990)](https://github.com/contiver/itfpuh2-resources#kurt-gödel-collected-works-volume-i-publications-1929-1936).
Popular accounts of the importance of this result on twentieth-century thought
are given in [Hofstadter (1979)](https://github.com/contiver/itfpuh2-resources#hofstadter-gödel-escher-bach-an-eternal-golden-braid)
and [Penrose (1994)](https://github.com/contiver/itfpuh2-resources#penrose-shadows-of-the-mind-a-search-for-the-missing-science-of-consciousness).

##### Cormen, Leiserson, Rivest, Stein. Introduction to Algorithms
##### Knuth. The Art of Computer Programming, Volume 1: Fundamental Algorithms
##### Knuth. The Art of Computer Programming, Volume 3: Sorting and Searching
##### Simon Thompson. Haskell: The Craft of Functional Programming
##### Hu. Combinatorial Algorithms 
##### Bird. Meertens' Number
Published in: Journal of Functional Programming, Volume 8 Issue 1, January 1998, Pages 83 - 88 
##### Kurt Gödel. Collected Works, Volume I: Publications 1929-1936
##### Hofstadter. Gödel, Escher, Bach: an Eternal Golden Braid
##### Penrose. Shadows of the Mind: A Search for the Missing Science of Consciousness

# Efficiency
For more information on lazy evaluation and grah reduction, consult the books
[Peyton Jones (1987)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Peyton%20Jones%20-%20The%20Implementation%20of%20Functional%20Programming%20Languages.djvu)
and [Peyton Jones and Lester (1991)](https://github.com/contiver/itfpuh2-resources#peyton-jones-lester-implementing-functional-languages-a-tutorial).
Asymptotic notation and the solution of recurrence relations using O-notation
is covered in [Cormen et al (1990)](https://github.com/contiver/itfpuh2-resources#cormen-leiserson-rivest-stein-introduction-to-algorithms).
The subject of aysmptotic timing analyses of lazy functional programs is still
a research area; for various approaches to the problem, see
[Bjerner and Holmström (1989)](#A composition approach to time analysis of first order lazy functional programs),
[Sands (1995, A Naïve Time Analysis and its Theory of Cost Equivalence)](http://logcom.oxfordjournals.org/content/5/4/495.abstract),
and [Wadler (1987)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Wadler%20-%20Strictness%20Analysis%20Aids%20Time%20Analysis.pdf).  
The idea of fusing two computations is as old as the subject of program
transformation itself; for an early reference on the technique in a functional
setting, see [Burstall and Darlington (1997)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Burstall%2C%20Darlington%20-%20A%20transformation%20System%20for%20Developing%20Recursive%20Programs.pdf).
The accumulating parameter technique is studied in 
[Bird (1984)](http://dl.acm.org/citation.cfm?id=1781).  
For more on the tupling strategy of program optimisation, see 
[Bird (1980)](http://dl.acm.org/citation.cfm?id=356831) and
[Pettrossi (1984)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Pettorossi%20-%20Methodologies%20for%20Transformations%20and%20Memoing%20in%20Applicative%20Languages.pdf).
The principle of optimality, and its importance to dynamic programming
algorithms (of which the paragraph problem is an example), is discussed in most
books on algorithm design; see [Bellman (1957; Dynamic Programming)](https://github.com/contiver/itfpuh2-resources#fundamental-concepts)
where the technique was first discussed, and also
[de Moor (1994)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/de%20Moor%20-%20Categories%2C%20Relations%20and%20Dynamic%20Programming.pdf)
which presents the ideas in a categorical setting.
[Bird and de Moor (1997)](https://github.com/contiver/itfpuh2-resources#bird-and-de-moor-the-algebra-of-programming)
contains a systematic account of the use of dynamic programming in solving
optimisation problems.  The problem of filling a paragraph is treated in
[Bird (1986)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Bird%20-%20Transformational%20Programming%20and%20the%20Paragraph%20Problem.pdf) 
and in [Knuth and Plass (1981; Breaking paragraphs into lines)](https://github.com/contiver/itfpuh2-resources#fundamental-concepts).  
The idea of eliminating intermediate datatypes from a computation is studied in
Wadler ([1984; Listlessness is better than laziness. PhD thesis;](https://github.com/contiver/itfpuh2-resources#fundamental-concepts),
[1990b](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Wadler%20-%20Deforestation.%20Transforming%20programs%20to%20eliminate%20trees.pdf));
see also [Bird and de Moor (1997)](https://github.com/contiver/itfpuh2-resources#bird-and-de-moor-the-algebra-of-programming)
for other examples.  
Quicksort is due to [Hoare (1962)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Hoare%20-%20Quicksort.pdf).
[Hughes (1984)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Hughes%20-%20The%20Design%20and%20Implementation%20of%20Programming%20Languages.pdf)
was the first to notice the space leak in quicksort when expressed as a
functional program. See
[Runciman and Röjemo (1996)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Runciman%2C%20R%C3%B6jemo%20-%20New%20dimensions%20in%20heap%20profiling.pdf)
for techniques for identifying space leaks.

# Abstract datatypes
The algebraic specification of abstract datatypes is described in
[Guttag and Horning (1987, The algebraic specification of abstract data types)](https://github.com/contiver/itfpuh2-resources#fundamental-concepts).
Two useful source texts on datatypes and their specification
are [Martin (1986, Data Types and Data Structures)](https://github.com/contiver/itfpuh2-resources#fundamental-concepts)
and [Harrison (1989, abstract data types in modula-2)](https://github.com/contiver/itfpuh2-resources#fundamental-concepts).
Amortised complexity is described in
[Cormen et al. (1990)](https://github.com/contiver/itfpuh2-resources#cormen-leiserson-rivest-stein-introduction-to-algorithms)
and, in a functional setting, in
[Schoenmakers (1992)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Schoenmakers%20-%20Data%20Structures%20and%20Amortized%20Complexity%20in%20a%20Functional%20Setting.pdf)
and [Okasaki (1996)](https://github.com/contiver/itfpuh2-resources#okasaki-purely-functional-data-structures).  
The original presentation of AVL trees can be found in
[Adelson-Velski and Landis (1962)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Adelson-Velskii%20and%20Landis%20-%20An%20Algorithm%20for%20the%20Organization%20of%20Information.pdf);
see also [Knuth (1973b)](https://github.com/contiver/itfpuh2-resources#knuth-the-art-of-computer-programming-volume-3-sorting-and-searching).
There are many other balanced tree schemes; for example,
[Cormen et al. (1990)](https://github.com/contiver/itfpuh2-resources#cormen-leiserson-rivest-stein-introduction-to-algorithms)
discusses *red-black trees*, and
[Andersson (1993)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Andersson%20-%20Balanced%20Search%20Trees%20Made%20Simple.pdf)
a simple scheme based on two operations, *skew* and *split*.  
The simple implementation of flexible arrays is described in 
[Dielissen and Kaldewaji (1995)](https://github.com/contiver/itfpuh2-resources#dielissen-and-kaldewaji-a-simple-efficient-and-flexible-implementation-of-flexible-arrays);
see also [Hoogerwoord (1991)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Hoogerwoord%20-%20A%20Logarithmic%20Implementation%20of%20Flexible%20Arrays.pdf).
The fast queue implementations can be found in
[Okasaki (1995)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Okasaki%20-%20Simple%20and%20Efficient%20Purely%20Functional%20Queues%20and%20Deques.pdf).
[Okasaki (1996)](https://github.com/contiver/itfpuh2-resources#okasaki-purely-functional-data-structures)
contains a wealth of additional material on purely functional data structures.

##### Okasaki. Purely Functional Data Structures
Originally a Ph.D thesis, later expanded into a book.
##### Dielissen and Kaldewaji. A simple, efficient, and flexible implementation of flexible arrays

# Infinite lists
Domain theory grew out of the work of Dana Scott in the late 1960s, see
[Scott (1976)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Scott%20-%20Data%20Types%20as%20Lattices.pdf)
and [Scott (1982)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Scott%20-%20Domains%20for%20Denotational%20Semantics.pdf).
An accessible account of the basic mathematics is
given in [Davey and Priestly (1990)](https://github.com/contiver/itfpuh2-resources#davey-and-priestly-introduction-to-lattices-and-order);
see also [Gunter (1992)](https://github.com/contiver/itfpuh2-resources#gunter-semantics-of-programming-languages)
for a modern treatment of domains and their importance in the semantics of
programming languages.
[Sijtsma's thesis (1988)](https://github.com/contiver/itfpuh2-resources#sijtsma-verification-and-derivation-of-infinite-list-programs)
studies various aspects of infinite-list programs, and gives a number of
techniques for reasoning about infinite lists.  One chapter is devoted to proof
of fairness in the paper-rock-scissors game.
[Gordon's thesis (1993)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Gordon%20-%20Functional%20Programming%20and%20IO.pdf)
contains a useful history of the various approaches to the treatment of
interaction in a functional setting.  One of the most exciting recent
develpments in programming semantics has been the use of games and strategies
to provide a model for interactive processes. See the chapters by S.
Abramsky and M. Hyland in 
[Pitts and Dyber (1997)](https://github.com/contiver/itfpuh2-resources#pitts-and-dyber-semantics-and-logics-of-computation)
for readable accounts of the basic ideas.

##### Davey and Priestly. Introduction to Lattices and Order
##### Gunter. Semantics of Programming Languages
##### Sijtsma. Verification and derivation of infinite-list programs
##### Pitts and Dyber. Semantics and Logics of Computation

# Monads
Moggi ([1989](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Moggi%20-%20Computational%20lambda-calculus%20and%20monads.pdf),
[1991](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Moggi%20-%20Notions%20of%20computation%20and%20monads.pdf)) 
introduced monads to computing science as a way of structuring denotational
semantics. Independently, 
[Spivey (1990)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Spivey%20-%20A%20Functional%20Theory%20of%20exceptions.pdf) 
noted that monads provided a useful way of structuring exception handling in
functional programs. Subsequently, Wadler 
([1990a](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Wadler%20-%20Comprehending%20monads.pdf), 
[1995](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Wadler%20-%20Monads%20for%20functional%20programming.pdf))
proposed monads as a general technique for structuring functional programs.

Monads are used to structure the Glasgow Haskell compiler, which itself is
written in Haskell; see [Hall, Hammond, Partain, Jones, and Wadler (1992)](https://github.com/contiver/itfpuh2-resources#hall-hammond-partain-jones-and-wadler-the-glasgow-haskell-compiler-a-retrospective). Each
phase of the compiler uses a monad for bookkeeping information. For instance,
the type checker uses a monad that combines state (to maintain a current
substitution), a name supply (for fresh type variable names), and exceptions.
Monads for interaction have been extended to include concurrency; see 
[Jones, Gordon, and Finne (1996)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Peyton%20Jones%2C%20Gordon%2C%20Finne%20-%20Concurrent%20Haskell.pdf).
Monad transformers are discussed in 
[Liang, Hudak, and Jones (1995)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Liang%2C%20Hudak%2C%20Jones%20-%20Monad%20Transformers%20and%20Modular%20Interpreters.pdf).

The program for the game of Hangman was adapted from a similar program in
[Hutton and Meijer (1996)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Hutton%2C%20Meijers%20-%20Monadic%20Parser%20Combinators.pdf).

The special **do** notation was suggested by 
[Launchbury (1993)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Launchbury%20-%20Lazy%20imperative%20programming.pdf) 
and was first implemented by [Jones (1993) in a version of Gofer](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Jones%20-%20Gofer%202.28%20release%20notes.pdf).
Subsequently, it was adopted in Haskell.

##### Hall, Hammond, Partain, Jones, and Wadler. The Glasgow Haskell Compiler: A Retrospective

# Parsing
For a general introduction to practical parsing techniques, and their
application in compiler design, consult
[Aho, Sethi, and Ullman (1986)](https://github.com/contiver/itfpuh2-resources#aho-sethi-lam-and-ullman-compilers-principles-techniques-and-tools).
The design of functional parsers has been a favourite application of functional
programming ofr many years, e.g.
[Burge (1975)](https://github.com/contiver/itfpuh2-resources#burge-recursive-programming-techniques),
[Wadler (1985)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Wadler%20-%20How%20to%20replace%20failure%20by%20a%20list%20of%20successes.pdf).
Modern treatments include
[Fokker (1995)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Fokker%20-%20Functional%20Parsers.pdf),
[Hutton (1992)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Hutton%20-%20Higher-Order%20Functions%20for%20Parsing.pdf), and 
[Hutton and Meijer (1996)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Hutton%2C%20Meijers%20-%20Monadic%20Parser%20Combinators.pdf),
on which this chapter is closely based.  The converse problem to parsing is
pretty printing, the laying out of a structured document in an aesthetically
pleasing manner. See
[Hughes (1995 pretty printing)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Hughes%20-%20The%20Design%20of%20a%20Pretty-printing%20Library.pdf)
for a design for a pretty-printing library.

##### Aho, Sethi, Lam, and Ullman. Compilers: Principles, Techniques, and Tools
##### Burge. Recursive Programming Techniques

# An automatic calculator
Mike Spivey's original calculator was written in Orwell, a predecessor of
Haskell; although the program hasn't been documented in the literature,
[Spivey (1990)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Spivey%20-%20A%20Functional%20Theory%20of%20exceptions.pdf)
contains a discussion on matching and rewriting expressions. Another
interactive equational reasoning assistant for Orwell, called ERA, is described
in [Wilson (1993)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Wilson%20-%20Equational%20Reasoning%20Support%20for%20Orwell.pdf).
Mechanical theorem proving and interactive proof assistance
form a large and buoyant subject, and dozens of systems are available to the
interested user. We will not attempt to enumerate them, but the references in
Chapter 4 five some pointers. For an easily accessible reference, consult
[Paulson (1996)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Paulson.%20A%20higher-order%20implementation%20of%20rewriting.pdf).
This text describes the implementation in ML of a tactical
theorem prover called Hal.  

The hidden agenda of this chapter was to demonstrate the advantages of
phrasing laws and proofs as equations between functional expressions. The
mathematical foundations of this approach is the subject matter of category
theory (see the [references cited in Chapter 2](https://github.com/contiver/itfpuh2-resources#simple-datatypes)).
However, for a truly viable method of specification and proof, one needs to
replace functional expressions by *relational* ones, and equational reasoning
by *inequational* reasoning.
See [Bird and de Moor (1997)](https://github.com/contiver/itfpuh2-resources/raw/master/resources/Scott%20-%20Domains%20for%20Denotational%20Semantics.pdf)
for details.
