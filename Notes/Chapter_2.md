---
id: Chapter_2
aliases:
  - Chapter 2 - The Real Numbers
tags: []
---

# Chapter 2 
<!-- vim-markdown-toc GFM -->

* [2.1 The Algebraic and Order Properties of $\mathbb{R}$](#21-the-algebraic-and-order-properties-of-mathbbr)
* [The Algebraic Properties of R](#the-algebraic-properties-of-r)
    * [Addition](#addition)
    * [Multiplication](#multiplication)
* [[[1766961657-ZUWT|2.1.3 Theorem - Zero Product Property and Multiplicative Inverses]]](#1766961657-zuwt213-theorem---zero-product-property-and-multiplicative-inverses)
* [[[1766962739-AMFZ|Building Sets in R]]](#1766962739-amfzbuilding-sets-in-r)
    * [Natural Numbers](#natural-numbers)
    * [Integers](#integers)
    * [Rational Numbers](#rational-numbers)
        * [Subfields](#subfields)
    * [Irrational Numbers](#irrational-numbers)
    * [Natural Numbers](#natural-numbers-1)
    * [Integers](#integers-1)
    * [Rational Numbers](#rational-numbers-1)
        * [Subfields](#subfields-1)
    * [Irrational Numbers](#irrational-numbers-1)
* [[[1766962818-EODE|2.1.4 Theorem - Irrationality of √2]]](#1766962818-eode214-theorem---irrationality-of-2)
    * [Proof](#proof)
* [[[1766962878-RPBP|2.1.5 Order Properties of R]]](#1766962878-rpbp215-order-properties-of-r)
    * [[[1766963059-MASZ|2.1.b Theorem - Trichotomy on Positive Real Numbers]]](#1766963059-masz21b-theorem---trichotomy-on-positive-real-numbers)
* [Ordering on $\mathbb{R}$](#ordering-on-mathbbr)
    * [2.1.7 Theorem - Rules of Inequality](#217-theorem---rules-of-inequality)

<!-- vim-markdown-toc -->

# 2.1 The Algebraic and Order Properties of $\mathbb{R}$
A *binary operation* on a set $S$ is a map $B: S \times S \rightarrow S$ [e.g. +,-,*,exp,etc.]

# [The Algebraic Properties of R](1766959914-XULY.md) 
On the set $\mathbb{R}$ there are two binary operations + and $\cdot$ which satisfy the following axioms:

## Addition 
* Communitive Property of Addition
    * $\forall a,b \in \mathbb{R}$
    * $a+b = b+a$ 
* Associative Property of Addition
    * $\forall a,b,c \in \mathbb{R}$
    * $(a+b)+c = a+(b+c)$ 
* Existence of Zero / Addative Identity
    * $\exists ~0 \in \mathbb{R}$ s.t. $\forall ~a \in \mathbb{R}, 0+a=a \land a+0=a$
* Existence of Additive Inverse
    * $\forall ~a \in \mathbb{R}, \exists ~(-a) \in \mathbb{R}$ s.t. $a+(-a)=0 \land (-a)+a=0$
## Multiplication
* Communitivity of Multiplication
    * $\forall ~a,b \in \mathbb{R}$
    * $ab=ba$
* Associativity of Multiplication
    * $\forall ~a,b,c \in \mathbb{R}$
    * $(ab)c = a(bc)$
* Existence of Unit Element / Multiplicative Identity
    * $\exists ~1 \in \mathbb{R}$ ***distinct from zero*** s.t. $1*a=a \land a*1=a$
* Existance of Multiplactive Inverses
    * $\forall ~a \neq 0 \in \mathbb {R}, \exists ~(\frac{1}{a}) \in \mathbb{R}$ s.t. $a*\frac{1}{a} = 1 \land \frac{1}{a}*a=1$
* Distributive Properties of Multiplication Over Addition
    * $a(b+c) = (ab) + (ac)$

*From these axioms we can prove the rest of algebra*

# [[1766961657-ZUWT|2.1.3 Theorem - Zero Product Property and Multiplicative Inverses]]
* (a) If $a \neq 0$ and $b \in \mathbb{R}$ are such that $ab=1$ then $b=\frac{1}{a}$
    * Uniquness of Mult. Inverses
* (b) If $a*b = 0$ then either $a=0 \lor b=0$

*Proof*:
- Suppose $ab=0$ and $a \neq 0$
- Goal: Show $b=0$

Invoking Multiplicative Identity
$$ 
b = 1*b = b 
$$

Existance of Multiplicative Inverse
$$
1*b = (\frac{1}{a}*{a})b
$$

Communitive Property of Multiplication
$$
(\frac{1}{a}*{a})b = \frac{1}{a}*{ab}
$$

By Supposition:
$$
b = \frac{1}{a}*{ab} = \frac{1}{a}*{a*0} = 0
$$

# [[1766962739-AMFZ|Building Sets in R]]

## Natural Numbers
We have $0, 1 \in \mathbb{R}$
* I can build a copy of $\mathbb{N} \in \mathbb{R}$ 
    * By assigning to each $n \in \mathbb{N}$ the number $1+1+1+...+1$ n-times


## Integers
To get the rest of $\mathbb{Z}$, use $-n = \text{inverse of } n$.

$$
\begin{array}{ccccccccccccccc}
\cdots & \longleftarrow & -2 & \longrightarrow & -1 & \longrightarrow & 0 & \longrightarrow & 1 & \longrightarrow & 2 & \longrightarrow & \cdots \\
\end{array}
$$


## Rational Numbers
Build $\mathbb{Q} \in \mathbb{R}$ by taking each $q\in \mathbb{Q}$ to be $\frac{a}{b}$ for some $a,b \in \mathbb{Z}, b \neq 0$ so that $q = a \cdot \frac{1}{b}$


### Subfields
Since $\mathbb{Q}$ is a field and $\mathbb{Q} \subset \mathbb{R}$, we say $\mathbb{Q}$ is a ***subfield*** of $\mathbb{R}$

## Irrational Numbers
$\mathbb{R}\backslash\mathbb{Q}$ or $\mathbb{Q}'$ are irrational numbers

## Natural Numbers
We have $0, 1 \in \mathbb{R}$
* I can build a copy of $\mathbb{N} \in \mathbb{R}$ 
    * By assigning to each $n \in \mathbb{N}$ the number $1+1+1+...+1$ n-times


## Integers
To get the rest of $\mathbb{Z}$, use $-n = \text{inverse of } n$.

$$
\begin{array}{ccccccccccccccc}
\cdots & \longleftarrow & -2 & \longrightarrow & -1 & \longrightarrow & 0 & \longrightarrow & 1 & \longrightarrow & 2 & \longrightarrow & \cdots \\
\end{array}
$$


## Rational Numbers
Build $\mathbb{Q} \in \mathbb{R}$ by taking each $q\in \mathbb{Q}$ to be $\frac{a}{b}$ for some $a,b \in \mathbb{Z}, b \neq 0$ so that $q = a \cdot \frac{1}{b}$


### Subfields
Since $\mathbb{Q}$ is a field and $\mathbb{Q} \subset \mathbb{R}$, we say $\mathbb{Q}$ is a ***subfield*** of $\mathbb{R}$

## Irrational Numbers
$\mathbb{R}\backslash\mathbb{Q}$ or $\mathbb{Q}'$ are irrational numbers

# [[1766962818-EODE|2.1.4 Theorem - Irrationality of √2]]

$$\text{Statement: }\not \exists ~r \in \mathbb{Q} \ni r^2=2$$

## Proof

Supppose for the sake of contradiction:
* Let $p,q \in \mathbb{Z}, q \neq 0$
* $\exists ~r \ni r=\frac{p}{q}$ 
* And $\frac{p}{q}$ are in their lowest terms 
    * $\implies$ $p,q$ how no common divisors greater than one

By supposition:
$$
\begin{align*}
\text{Suppose } r^2=2
\implies (\frac{p}{q})^2 &= 2 \\
\implies \frac{p^2}{q^2} &= 2 \\
\implies p^2 &= 2q^2 \\
\end{align*}
$$

Observe RHS is even implies LHS is even:
* $2q^2$ is even $\implies p^2=2k, k \in \mathbb{Z} \implies p=2d, d\in \mathbb{Z}$

This clearly demonstrates that $p,q$ are both divisible by two
* ***Note***: $p,q$ were said to be at their lowest possible terms, thus should not be divisible by any factor other than one

$$\implies \not \exists ~p,q \ni r \in {\mathbb{Q}} \implies r \in \mathbb{Q}' \text{ if it exists}$$

# [[1766962878-RPBP|2.1.5 Order Properties of R]]

There is a nonempty subset of $\mathbb{P}$ of $\mathbb{R}$, called the set of **positive real numbers**, with the following propeties: 

1.  $\mathbb{P}$ Closed Addition
    * $\forall ~a,b \in \mathbb{P}, (a+b) \in \mathbb{P}$
2. $\mathbb{P}$ Closed Multiplication
    * $\forall ~a,b, \in \mathbb{P}, a \cdot b \in \mathbb{P}$
3. ***Trichotony Property***
    * $\forall ~a \in \mathbb{R},$ either:
        * $a \in \mathbb{P}$
        * $(-a) \in \mathbb{P}$
        * $a = 0$
    * This states any real nuber is either positive, negative, or zero

---

If $a \in \mathbb{P}$, we write $a>0$ and say $a$ is a **strictly positive real number**

$$
\begin{array}{ccccccccccc}
-(-a) \in \mathbb{P} \text{ -------- } a < 0 \text{ --------  (strictly negative real number)}
\end{array}
$$

If $a \in \mathbb{P} \cup \{0\}$ we write $a \geq 0$ and say a is **non-negative**

## [[1766963059-MASZ|2.1.b Theorem - Trichotomy on Positive Real Numbers]]
Implications of Trichotomy Property on Positive Real Numbers:

$\text{Let } a,b \in \mathbb{R}$

$$
\begin{align*}
a-b \in \mathbb{P} \implies (a>b) \lor (b<a) \\
a-b \in \mathbb{P}\cup \{0\} \implies (a \geq b) \lor (b \leq a)
\end{align*}
$$

From the Trichotomy Property:
* We know that for any two $a,b \in \mathbb{R}$ either: $a>b, a<b, a=b$

# Ordering on $\mathbb{R}$

An **ordered set** is any set $S$ on which $\forall ~a,b \in S$, either $a<b, a>b, a=b$

## 2.1.7 Theorem - Rules of Inequality

$\text{Let } a,b,c \in \mathbb{R}$ 

$$
\begin{align}
  (a>b) \land (b>c) \implies a>c
\end{align}
$$
