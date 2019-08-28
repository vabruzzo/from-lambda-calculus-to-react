# From Lambda Calculus to React

Everything here is highly recommended. I've put *s by the things I believe to be absolute musts.

## Lambda Calculus

- [Computerphile Introduction to Lambda Calculus](https://www.youtube.com/watch?v=eis11j_iGMs)*
- [Y Not - Adventures in Functional Programming](https://www.youtube.com/watch?v=FITJMJjASUs)* - truly amazing talk about recursion in Lambda Calculus
- [The Universe in a Single Arrow: A Live Dive into the Lambda Calculus](https://www.youtube.com/watch?v=8dKljTMDGu0&t=1730s) - React Rally 2019 talk
- [Lambda Calculus Wikipedia Entry](https://en.wikipedia.org/wiki/Lambda_calculus)

## Lisp and S-expressions

- [Recursive Functions of Symbolic Expressions and Their Computation by Machine, Part I](https://web.archive.org/web/20131004232653/http://www-formal.stanford.edu/jmc/recursive.pdf)* - John McCarthy's original paper where he introduces Lisp and S-expressions; though academic, it is surprisingly approachable
- [Reagent](https://reagent-project.github.io/) - what it looks like to write React with a Lisp
- [S-expression Wikipedia Entry](https://en.wikipedia.org/wiki/S-expression)

## Immutability and Hash Array Mapped Tries

- [The Future of MVC Frameworks](https://swannodette.github.io/2013/12/17/the-future-of-javascript-mvcs)- David Nolen's post detailing his performance gains with ClojureScript and Om, his React Cljs library
- [Immutable Data and React](https://www.youtube.com/watch?v=I7IdS-PbEgI)* - Lee Byron's introduction to Immutable.js
- [Introduction to HAMTs](https://idea.popcount.org/2012-07-25-introduction-to-hamt/)
- [Understanding Clojure's Persistent Vectors](https://hypirion.com/musings/understanding-persistent-vector-pt-1)
- [Ideal Hash Trees](https://lampwww.epfl.ch/papers/idealhashtrees.pdf) - difficult, academic paper

## Algebraic Effects

- [Algebraic Effects for the Rest of Us](https://overreacted.io/algebraic-effects-for-the-rest-of-us/)*

## Takeaways

- [React Basic Conceptual Model](https://github.com/reactjs/react-basic)* - React mental model as understood by Sebastian Markbåge, React core team member; these concepts help to pull everything together

Write React in a functional language! At least for small demo projects. This has been an immensely rewarding experience in my own case.

- [ReasonML](https://reasonml.github.io/) - OCaml for JS; statically typed language developed by the creator of React; you can think of this as the way the React creator intended it to be written
- ClojureScript - [re-frame](https://github.com/Day8/re-frame) & [Learn re-frame](https://www.learnreframe.com/), [Rum](https://github.com/tonsky/rum), [Om](https://github.com/omcljs/om) (I prefer re-frame)
- [Elm](https://elm-lang.org/) - Haskell for JS; statically typed; heavily inspired Redux
