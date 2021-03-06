Functional Programming in C++
=============================

List of materials and links about functional programming in C++.

All the materials are in English if the language is not specified explicitly.

## Contents

- [Books](#books)
- [Articles](#articles)
  * [Basics](#basics)
  * [Blogs](#blogs)
  * [Advanced topics](#advanced-topics)
    - [Monads](#monads)
    - [Design Concepts and Approaches](#design-concepts-and-approaches)
  * [Papers](#papers)
- [Talks and Screencasts](#talks-and-screencasts)
  * [Talks](#talks)
  * [Screencasts](#screencasts)
- [Cources](#cources)
- [QA](#qa)
  * [StackOverflow questions](#stackoverflow-questions) 
  * [Quora questions](#quora-questions)
- [Libraries](#libraries)
- [Showcase projects](#showcase-projects)
- [C++ FP Experts](#c-fp-experts)

## Books

- [Functional Programming in C++](https://www.manning.com/books/functional-programming-in-c-plus-plus), **Ivan Čukić**, Manning Publications, 2018
- [Learning C++ Functional Programming](https://www.oreilly.com/library/view/learning-c-functional/9781787281974/), **Wisnu Anggoro**
- [Functional Programming with C++](https://www.amazon.com/Functional-Programming-C-Chris-Weed-ebook/dp/B017AT4OMI), **Chris Weed**

## Articles

### Basics

- [Lambdas: The Functional Programming Companion of Modern C++](https://medium.com/@DakshHub/lambdas-the-companion-of-modern-c-b7dfd43b5abb), **Daksh**, 2018
- [Functional programming in C++](http://blog.madhukaraphatak.com/functional-programming-in-c++/), **Madhukar**, 2014
- [Functional Programming in C++](https://www.codeproject.com/Articles/1267996/Functional-Programming-in-Cplusplus), **MehreenTahir**, 2018
- [What Does Haskell Have to Do with C++?](https://bartoszmilewski.com/2009/10/21/what-does-haskell-have-to-do-with-c/),  **Bartosz Milewski**, 2009
- [Make your functions functional](https://www.fluentcpp.com/2016/11/22/make-your-functions-functional/), **Jonathan Boccara**, 2016
- [Functional Programming Using C++ Templates (Part 1)](https://accu.org/index.php/journals/1422), **Stuart Golodetz**
- [In-depth: Functional programming in C++](https://www.gamasutra.com/view/news/169296/Indepth_Functional_programming_in_C.php), **John Carmack**, 2012
- [An Overview of Elements of Functional Programming in C++](https://community.idera.com/developer-tools/b/blog/posts/an-overview-of-elements-of-functional-programming-in-c), **Kiryll Shynharow**, 2017
- [Introduction to Functional programming in C++](http://www2.lawrence.edu/fast/GREGGJ/CMSC270/functional.html), ?, ?
- [Functional programming in c++ by example](https://nikitablack.github.io/2017/03/23/Functional-programming-in-c-by-example.html), **nikitablack**, 2017
  * [Functional programming in c++ by example (Rus)](https://habr.com/post/324518/), **nikitablack**, 2017
- [Functional in C++17 and C++20](http://www.modernescpp.com/index.php/functional-in-c-17-and-c-20), **Rainer Grimm**, 2017
- [Study Notes: Functional Programming with C++](https://yongweiwu.wordpress.com/2014/12/07/study-notes-functional-programming-with-cplusplus/), **Yongwei**, 2014
- [Efficient Pure Functional Programming in C++ Using Move Semantics](https://blog.knatten.org/2012/11/02/efficient-pure-functional-programming-in-c-using-move-semantics/), **Anders Schau Knatten**, 2012
- [C++ is a Dynamic, Pure, Functional Programming Language](https://cloudalion.org/2016/09/08/c-is-a-dynamic-pure-functional-programming-language/), **brosenan**, 2016
- [The connection between C++ template metaprogramming and functional programming](http://www.tnkcs.inf.elte.hu/vedes/sinkovics_abel_ertekezes.pdf), **Abel Sinkovics**, 2013

### Blogs

- [Functional C++. Abusing the type system like never before. (Blog)](https://functionalcpp.wordpress.com/), ?
  * [Function Traits](https://functionalcpp.wordpress.com/2013/08/05/function-traits/), 2013
  * [Function Composition](https://functionalcpp.wordpress.com/2013/08/09/function-composition/), 2013
  * [Continuation Passing Style](https://functionalcpp.wordpress.com/2013/11/19/continuation-passing-style/), 2013
  * [Composing Continuations](https://functionalcpp.wordpress.com/2015/01/19/composing-continuations/), 2015
  * And more...
- [C++ Truths (Blog)](http://cpptruths.blogspot.com/), **Sumant Tambe**
  * [Understanding Fold Expressions](http://cpptruths.blogspot.com/2016/12/understanding-fold-expressions.html), 2016
  * [Folding Functions](http://cpptruths.blogspot.com/2016/12/folding-functions.html), 2016
  * [Dependently-typed Curried printf in C++](http://cpptruths.blogspot.com/2016/11/dependently-typed-curried-printf.html?m=1), 2016
  * [Folding Monadic Functions](http://cpptruths.blogspot.com/2017/01/folding-monadic-functions.html?m=1), 2017
  * And more...

### Advanced topics

#### Monads

- [Monads in C++](https://bartoszmilewski.com/2011/07/11/monads-in-c/), **Bartosz Milewski**, 2011
- [Monads in C++](http://www.modernescpp.com/index.php/monads-in-c), **Rainer Grimm**, 2017
- [The Vector Monad in C++, Without the Ugly Stuff](http://www.fluentcpp.com/2017/07/14/the-vector-monad-in-c-without-the-ugly-stuff), **Jonathan Boccara**, 2017
- [The Vector Monad in C++, Really Without the Ugly Stuff](https://medium.com/@barryrevzin/the-vector-monad-in-c-really-without-the-ugly-stuff-3112137db5d7), **Barry Revzin**, 2017
- [Multiple error handling with the optional monad in C++](https://www.fluentcpp.com/2017/07/04/multiple-error-handling-with-the-optional-monad-in-c/), **Jonathan Boccara**, 2017
- [Free Monads in C++](https://toby-allsopp.github.io/2016/10/12/free-monads-in-cpp.html), **Toby Allsopp**, 2016
- [An Introduction to Monads for C++ Programmers](https://www.shellblade.net/monad.html), **ShellBlade**
- [An Attempt to Explain Monads in C++](https://izzys.casa/posts/an-attempt-to-explain-monads-in-cxx.html), **Isabella Muerte**, 2014

#### Design Concetps and Approaches

- [Optional Types and Lightweight Continuation Passing in C++](https://izzys.casa/posts/optional-types-and-lightweight-continuation-passing-in-cxx.html), **Isabella Muerte**, 2014
- [Software Transactional Memory in C++: pure functional approach (Tutorial)](https://gist.github.com/graninas/c7e0a603f3a22c7e85daa4599bf92525), **Alexander Granin**, 2018

### Papers
- [Persistence for the Masses: RRB-Vectors in a Systems Language](https://public.sinusoid.es/misc/immer/immer-icfp17.pdf), **Juan Pedro Bolívar Puente**
- [C++ Monadic interface (Proposal P0650R2)](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2018/p0650r2.pdf), 2018
- [Functional Concepts in C++](http://www.cs.nott.ac.uk/~psznhn/TFP2006/Papers/25-RaufBergerSetzer-FunctionalConceptsInC++.pdf), **Rose H. Abdul Rauf, Ulrich Berger, Anton Setzer**
- [Functional Programming in C++](https://people.cs.umass.edu/~yannis/fc++/fc++.main.pdf), **Brian McNamara**, **Yannis Smaragdakis**

## Talks and Screencasts

**Talks**

- **Bartosz Milewski** talks
  * [Functional Patterns in C++, 1. Functors](https://www.youtube.com/watch?v=ph7qt0pkPkc), 2012
  * [Functional Patterns in C++, 2. Currying, Applicative](https://www.youtube.com/watch?v=Hx9jojeBj6w), 2012
  * [Functional Patterns in C++, 3. Async API, Monoid, Monad](https://www.youtube.com/watch?v=ozN6XxsAF84), 2012
  * [Compile-Time/Run-Time Functional Programming in C++](https://www.youtube.com/watch?v=WtHWFoKf8o0), **Bartosz Milewski**, **Eric Niebler**, BoostCon, 2012
  * [Haskell -- The Pseudocode Language for C++ Template Metaprogramming (Part 1)](https://www.youtube.com/watch?v=GjhsSzRtTGY), BoostCon, 2013
  * [Re-discovering monads in C++](https://youtu.be/tc8w8MbJQNs?t=13003), C++ User Group Novosibirsk, 2014
  * [Functional techniques in C++](https://www.youtube.com/watch?v=olZ9SXeUmsU), CDays14, 2014
  * [Categories for the Working C++ Programmer](https://www.youtube.com/watch?v=eCUfzvz7Z20), C++ Russia, 2015
  * [Monads for C++](https://www.youtube.com/watch?v=vkcxgagQ4bM), itCppCon17, 2017

- **Eric Niebler** talks
  * [Compile-Time/Run-Time Functional Programming in C++](https://www.youtube.com/watch?v=WtHWFoKf8o0), **Bartosz Milewski**, **Eric Niebler**, BoostCon, 2012
  * [Ranges for the Standard Library](https://www.youtube.com/watch?v=mFUXNMfaciE), CppCon, 2015
  * [Ranges for the Standard Library](https://www.youtube.com/watch?v=gOKHcQad7xE), C++ Siberia, 2015
  * [Keynote: Ranges for the Standard Library](https://www.youtube.com/watch?v=zsSErwT1S80), C++Now, 2015
  * [STL Concepts and Ranges](https://www.youtube.com/watch?v=uXBcwcF3ln4), Northwest C++ Users Group, 2015
  * [Introducing the Ranges TS](https://www.youtube.com/watch?v=LNXkPh3Z418), code::dive, 2017
  
- **Ivan Čukić** talks
  * [Functional Programming: data](https://www.youtube.com/watch?v=iYipZw4tS-A), Meeting C++, 2017
  * [Atom Heart Monad: FRP in C++](https://www.youtube.com/watch?v=_Ji1HyZxXvo), Curry On!, 2018

- **Juan Pedro Bolívar Puente** talks
  * [Transducers: from Clojure to C++](https://www.youtube.com/watch?v=vohGJjGxtJQ), CppCon, 2015
  * [Postmodern immutable data structures](https://www.youtube.com/watch?v=sPhpelUfu8Q), CppCon, 2017
  * [Most valuable values](https://www.youtube.com/watch?v=_oBx_NbLghY), CppCon, 2018

- **Phil Nash** talks
  * [Functional C++ for Fun and Profit](https://www.youtube.com/watch?v=YgcUuYCCV14), **Phil Nash**, St. Petersburg C++ User Group, 2016
  * [What Could Possibly Go Wrong?: A Tale of Expectations and Exceptions](https://www.youtube.com/watch?v=GC4cp4U2f2E), **Simon Brand**, **Phil Nash**, CppCon, 2018

- **David Sankel** talks
  * [Functional Programming in C++](https://www.youtube.com/watch?v=PVjaFMwV4x0), BoostCon, 2013
  * [Intro to Functional Programming](https://www.youtube.com/watch?v=uHFUpFhWGJs), C++ Now, 2014
  * [Functional Design Explained](https://www.youtube.com/watch?v=x9mIAT-CAwA), CppCon, 2015
  * [The Mathematical Underpinnings of Promises in C++](https://www.youtube.com/watch?v=2OY0Zn3oBCE), BoostCon, 2017
  
- **Alexander Granin** talks (Rus)
  * [Functional and Declarative Design in C++ (Rus)](https://youtu.be/tc8w8MbJQNs?t=9370), C++ User Group Novosibirsk, 2014
  * [Functional Microscope: Lenses in C++ (Rus)](https://www.youtube.com/watch?v=7vyNRD1TRYs), C++ Siberia, 2015
  * [Functional 'Game of Life': Parallel Cellular Automata and Comonads in C++ (Rus)](https://www.youtube.com/watch?v=iKrnGSkWPnw), C++ Russia, 2016
  * [Pure Functional Approach to Software Transactional Memory in C++ (Rus)](https://www.youtube.com/watch?v=VHZPcz8HwZs), C++ Russia, 2018

- [Functional C++](https://www.youtube.com/watch?v=CIg6eyJv4dk&t=169s), **Kevlin Henney**, BUILD STUFF, 2017
- [Goodbye metaprogramming, and hello functional](https://www.youtube.com/watch?v=fH2WBvI8dbk), **Paul Fultz**, 2016
- [Applying functional programming in code design](https://www.youtube.com/watch?v=-ROXIG4raiA), **Michał Dominiak**, CppCon, 2015
- [Practical Functional Programming in C++](https://channel9.msdn.com/Events/CPP/C-PP-Con-2014/009-Practical-Functional-Programming-in-CPP), **Bryce Adelstein-Lelbach**, CppCon, 2014
- [Functional Programming Tools in C++](https://vimeo.com/246623471), **Sumant Tambe**, SF Bay Area ACCU, 2017
- [What Could Possibly Go Wrong?: A Tale of Expectations and Exceptions](https://www.youtube.com/watch?v=GC4cp4U2f2E), **Simon Brand**, **Phil Nash**, CppCon, 2018
- [Generalized Full Duplex Messaging](https://www.youtube.com/watch?v=UalTAQmP3iE), **Jason Rice**, C++ Now, 2018
- [**constexpr** ALL the Things! (Combinatorial parsers)](https://www.youtube.com/watch?v=PJwd4JLYJJY), **Ben Deane**, **Jason Turner**, CppCon, 2017

**Screencasts**

- [Learning Modern C++ Functional Programming: Understand Essential Part](https://www.youtube.com/watch?v=W1IMyrqeqM4), Packt Video, 2018
- [Functional Programming in C++ Using Lambda Expressions](https://www.youtube.com/watch?v=58BrFvjNhWY), CodesBay, 2018

## Cources

- [Functional Programming using C++](https://www.youtube.com/watch?v=jD8Tu1tqvZo), **Tobias Hermann**, 2017

## QA

#### StackOverflow Questions

- [Functional Programming in C++](https://stackoverflow.com/questions/1981400/functional-programming-in-c)
- [What can C++ offer as far as functional programming?](https://stackoverflow.com/questions/21471836/what-can-c-offer-as-far-as-functional-programming)
- [Monad interface in C++](https://stackoverflow.com/questions/39725190/monad-interface-in-c)
- [C++ Design: Functional Programming vs OOP](https://softwareengineering.stackexchange.com/questions/180522/c-design-functional-programming-vs-oop)

#### Quora Questions

- [Is C++ is a functional programming language or not?](https://www.quora.com/Is-C++-is-a-functional-programming-language-or-not)
- [Can C++ be used for functional programming?](https://www.quora.com/Can-C++-be-used-for-functional-programming)

## Libraries

- [Boost.Hana](https://boostorg.github.io/hana)

  Boost.Hana is a library with concepts borrowed from category theory
  
- [cpp_stm_free](https://github.com/graninas/cpp_stm_free), **Alexander Granin**

  Composable monadic STM for C++ on Free monads
  
- [FTL](https://github.com/beark/ftl)
  
  The Functional Template Library
   
- [LIBF++](https://github.com/GJDuck/libf)

  C++ as a Pure Functional Language
  
- [neither](https://github.com/loopperfect/neither)
- [Cat](https://github.com/awgn/cat)
- [Immer](https://github.com/arximboldi/immer), **Juan Pedro Bolívar Puente**

  Postmodern immutable and persistent data structures for C++

- [Lager](https://github.com/arximboldi/lager), **Juan Pedro Bolívar Puente**

  Library for functional interactive C++ programs // Redux for C++
  
- [FunctionalPlus](https://github.com/Dobiasd/FunctionalPlus)

  Functional Programming Library for C++. Write concise and readable C++ code. 
 
## Showcase Projects

- [Ewig](https://github.com/arximboldi/ewig), **Juan Pedro Bolívar Puente**

  A mini-emacs built using C++ in a functional way, using the Redux architecture. Supports efficiently editing huge file and concurrent loading/saving.
  
- [Amber](https://github.com/graninas/Amber), **Alexander Granin**

  The 'Amber' game project demonstranting functional and declarative design in C++.

- [cpp_lenses](https://github.com/graninas/cpp_lenses), **Alexander Granin**

  Functional lenses demo in C++

- [CMLife](https://github.com/graninas/CMLife), **Alexander Granin**

  Functional Game of Life in C++. Based on functional declarative design and functional idioms (comonads, zippers etc.)

- [coroutine_monad](https://github.com/toby-allsopp/coroutine_monad), **Toby Allsopp**

  Using coroutines for monadic composition

## C++ FP Experts

The list of authors of the materials presented here (can be missing by occasion).

_Please, pm me if you don't want to be in this list. Or if you want to be there._

- **John Carmack**
- **Bartosz Milewski**
- **Ivan Čukić**
- **Phil Nash**
- **Kevlin Henney**
- **Rainer Grimm**
- **Eric Niebler**
- **Paul Fultz**
- **Michał Dominiak**
- **Stuart Golodetz**
- **David Sankel**
- **Jonathan Boccara**
- **Barry Revzin**
- **Juan Pedro Bolívar Puente**
- **Bryce Adelstein-Lelbach**
- **Toby Allsopp**
- **Isabella Muerte**
- **Brian McNamara**
- **Ben Deane**
- **Jason Turner**
- **nikitablack**
- **Abel Sinkovics**
- **Wisnu Anggoro**
- **Simon Brand**
- **Chris Weed**
- **Kiryll Shynharow**
- **Alexander Granin**
- **Tobias Hermann**
- **Jason Rice**
- **Toby Allsopp**
- **Sumant Tambe**
- **Anders Schau Knatten**
