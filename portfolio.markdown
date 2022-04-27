---
title: Portfolio
---

### A Calculus For Scoped Effects & Handlers
**Date**: draft.\
**Venue**: t.b.d.\
**Author(s)**: Roger Bosman, Birthe van den Berg, Wenhao Tang, Tom Schrijvers\
**PDF**: *[here](../publications/bosman-et-al-a-calculus-for-scoped-effects-and-handlers.pdf)*\
<details> <summary><strong>Abstract</strong>: (unfold me)</summary> 
  <p> Algebraic effects \& handlers have become a standard approach for working
    with side-effects in functional programming languages. Their modular
    composition with other effects and clean separation of syntax and semantics
    make them attractive to a wide audience of programmers. However, not all
    effects can be classified as algebraic; some need a more sophisticated
    handling. In particular, effects that have or create a delimited scope need
    special care, as their continuation consists of two parts---in and out of
    the scope---and their modular composition with other effects brings in
    additional complexity. This class of effects is called scoped effects and
    has gained attention by their growing applicability and adoption in popular
    libraries. Although calculi have been designed with algebraic effects \&
    handlers as first-class operations, effectively easing programming with
    those features, a calculus to support scoped effects \& handlers in a
    similar matter is missing from the literature. In this work we fill this
    gap: we present a novel calculus, in which both algebraic and scoped effects
    \& handlers are first-class. This involves the need for polymorphic handlers
    and explicit forwarding clauses to forward unknown scoped operations to
    other handlers. Our calculus is based on Eff, an existing calculus for
    algebraic effects, extended with Koka-style row polymorphism, and consists
    of a formal grammar, operational semantics and (type-safe) type-and-effect
    system. We demonstrate the usability of our work by discussing a range of
    scoped effect examples. In summary, our novel calculus allows modular
    composition of different algebraic and scoped effects \& handlers and eases
    programming with these features. </p> 
</details>

### Mechanizing an elaboration algorithm for the Hindley-Damas-Milner system [Extended Abstract]
**Date**: 07-2021\
**Venue**: ICFP Student Research Competition\
**Author(s)**: Roger Bosman\
**PDF**: *[here](../publications/bosman-mechanizing-an-elaboration-algorithm-for-the-hindley-damas-milner-system.pdf)*\
**Note**: Submitted as prerequisite for joining the 2021 ICFP Student Research competition, and was accepted. Presentation and poster below.

### Unboxed Function Closures
**Date**: 08-2020\
**Author(s)**: Roger Bosman\
**PDF**: *[here](../publications/bosman-unboxed-function-closures.pdf)*\
**Note**: master thesis @ Utrecht University
<details>
  <summary><strong>Abstract</strong>: (unfold me)</summary>
  
  <p>In Haskell, both thunks and values are generally represented as a
  heap-allocated closure [18]. This introduces overhead, as the heap generally
  is much slower than the stack. To combat this inefficiency, programmers can
  use unboxed types [19]. These types are represented directly on the stack, and
  therefore do not carry such overhead. So far, only data values such as Int and
  Char can be unboxed. In this thesis we explore the possibility of extending
  this notion, allowing for function values to be unboxed as well. As functions
  can close over variables, they must be represented as a closure. Therefore,
  unboxing function values requires representing closures on the stack. This
  introduces a significant challenge, as variations in the set of closed over
  variables now affect the stack representation. We propose an extension to
  function types, where the types of the closed over variables are annotated on
  the function arrow. These annotations make it possible to reason about the
  exact runtime representation of a closure at compile time. We do so by
  presenting two languages, L and M, and a compilation function L → M.
  Furthermore, we identify the key correctness criteria of L → M, and proof that
  they hold. </p>

</details>

# Talks

### 22-04-2022: FP Dag 2022
**Title**: Getting a hanlde on (scoped) effects\
**Slides**: *[here](../talks/bosman-fp-dag-2022-getting-a-handle-on-scoped-effects.pdf)*\
<details>
  <summary><strong>Abstract</strong>: (unfold me)</summary>
  
  <p>Algebraic effects & handlers have become a standard approach for working
   with side-effects in functional programming languages. However, not all
   effects can be classified as algebraic; some need a more sophisticated
   handling. In particular, effects that have or create a delimited scope -
   called scoped effects - need special care.</p>

  <p>Although calculi have been designed with algebraic effects & handlers as
  first-class operations, calculus to support scoped effects & handlers in a
  similar matter is missing from the literature. In this presentation we cover
  our work to fill this gap: we present a novel calculus in which both algebraic
  and scoped effects & handlers are first-class.</p>

</details>

### 24-08-2021: ICFP 2022 Student Research Competition Finalist Presentation
**Title**: Mechanizing an elaboration algorithm for the Hindley-Damas-Milner type system\
**Slides**: *[here](../talks/bosman-icfp-src-2022-mechanizing-an-elaboration-algorithm-for-the-hindley-damas-milner-type-system.pdf)*\

### 12-04-2021: Midlands Graduate School Participant Talk
**Title**: A mechanical formalization of Hindley-Damas-Milner type inference\
**Slides**: *[here](../talks/bosman-midlands-graduate-school-a-mechanical-formalization-of-hindley-damas-milner-type-inference.pdf)*\

# Other

### 2022 ICFP Student Research Competition -- Poster
**Title**: Mechanizing an elaboration algorithm for the Hindley-Damas-Milner type system\
**Date**: 23-08-2020\
**PDF**: *[here](../other/bosman-icfp-src-2022-poster-mechanizing-an-elaboration-algorithm-for-the-hindley-damas-milner-type-system.pdf)*\


