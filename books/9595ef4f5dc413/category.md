---
title: "圏"
free: false
---

## 定義

圏(*Category*)$\mathbf C$は、以下のものからなる:

- 対象(*Object*)のあつまり$\mathrm{ob}(C)$
- 対象間の射(*Morphism*)のあつまり$\hom_C$
    - 対象$A$から対象$B$への射$f \in \hom_C$を$f : A \to B$のように書く。
    - また対象$A$から対象$B$への射のあつまりを$\hom_C(A, B)$のように書く。

ここで、2つの射$f: A \to B$, $g: B \to C$は合成(*Composition*) $g \circ f: A \to C$を持ち、以下を満たす:

- 結合律(*Associativity*): $h \circ (g \circ f) = (h \circ g) \circ f$
- 単位律(*Identity*): 任意の対象$X \in \mathrm{ob}(C)$に対して$X$の恒等射(*Identity morphism*) $\mathrm{id}_X: X \to X$が存在して、任意の射$f: A \to B$に対して$\mathrm{id}_B \circ f = f \circ id_A = f$

## 記法

記法について、さまざまに流派が存在するので紹介する。このノートではなるべく上で使った記法で統一するが、便利のために文脈に応じて使い分けることがあるかもしれない。

- 一般の圏$\mathbf{C}$
    - $\mathscr C$
    - $\mathcal C$
    - $C$
- 対象のあつまり$\mathrm{ob}(C)$
    - $|{C}|$
    - $C$
- 射のあつまり$\hom_C$
    - $\mathrm{Hom}_C$
    - $\mathrm{Mor}(C)$
    - $\mathrm{Arr}(C)$
    - $C$
- 射の合成$g \circ f$
    - $gf$
    - $f; g$
    - $f \ggg g$


