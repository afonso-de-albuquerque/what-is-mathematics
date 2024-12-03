# CHAPTER II. THE NUMBER SYSTEM OF MATHEMATICS 第二章 数学中的数系

## § 1. The Rational Numbers. 有理数

### 1. Rational Numbers as a Device for Measuring. 作为度量工具的有理数

### 2. Intrinsic Need for the Rational Numbers. Principle of Generalization. 数学内部对有理数的需要 推广原则

### 3. Geometrical Interpretation of Rational Numbers. 有理数的几何解释

## § 2. Incommensurable Segments, Irrational Numbers, and the Concept of Limit. 不可公度线段 无理数和极限概念

### 1. Introduction. 引言

> (Page 60) *Exercise:* 1\) Prove that $\sqrt[3]2, \sqrt3, \sqrt5, \sqrt[3]3$ are not rational. (Hint: Use the lemma of p. 47).

If $\sqrt[3]2$ were rational, we could find two relatively prime integers $p$ and $q$ such that $\sqrt[3]2 = \frac{p}{q}$. and $p^3 = 2q^3$. Since $2$ appears as a factor of the right side, $p^3$ is an even number, and hence $p$ itself is even. We may write $p = 2r$. Then we have $8r^3 = 2q^3$, or $4r^3 = q^3$. Since $4$ is as a factor of the left side, and hence $q$ must also be even. Thus $p$ and $q$ are both divisible by $2$, which contradicts the assumption that $p$ and $q$ were relatively prime. Therefore $\sqrt[3]2$ is not rational.

If $\sqrt3$ were rational, we could find two relatively prime integers $p$ and $q$ such that $\sqrt3 = \frac{p}{q}$. and $p^2 = 3q^2$. Since $3$ appears as a factor of the right side, $p^2$ is a multiple of $3$, and hence $p$ itself is a multiple of $3$. We may write $p = 3r$. Then we have $9r^2 = 3q^2$, or $3r^2 = q^2$. Since $3$ is as a factor of the left side, and hence $q$ must also be a multiple of $3$. Thus $p$ and $q$ are both divisible by $3$, which contradicts the assumption that $p$ and $q$ were relatively prime. Therefore $\sqrt3$ is not rational.

If $\sqrt5$ were rational, we could find two relatively prime integers $p$ and $q$ such that $\sqrt5 = \frac{p}{q}$. and $p^2 = 5q^2$. Since $5$ appears as a factor of the right side, $p^2$ is a multiple of $5$, and hence $p$ itself is a multiple of $5$. We may write $p = 5r$. Then we have $25r^2 = 5q^2$, or $5r^2 = q^2$. Since $5$ is as a factor of the left side, and hence $q$ must also be a multiple of $5$. Thus $p$ and $q$ are both divisible by $5$, which contradicts the assumption that $p$ and $q$ were relatively prime. Therefore $\sqrt5$ is not rational.

If $\sqrt[3]3$ were rational, we could find two relatively prime integers $p$ and $q$ such that $\sqrt[3]3 = \frac{p}{q}$. and $p^3 = 3q^3$. Since $3$ appears as a factor of the right side, $p^3$ is a multiple of $3$, and hence $p$ itself is a multiple of $3$. We may write $p = 3r$. Then we have $27r^3 = 3q^3$, or $9r^3 = q^3$. Since $3$ is as a factor of the left side, and hence $q$ must also be a multiple of $3$. Thus $p$ and $q$ are both divisible by $3$, which contradicts the assumption that $p$ and $q$ were relatively prime. Therefore $\sqrt[3]3$ is not rational.

> 2\) Prove that $\sqrt2 + \sqrt3$ and $\sqrt2 + \sqrt[3]2$ are not rational. (Hint: if e.g. the first of these numbers were equal to a rational number $r$ then, writing $\sqrt3 = r - \sqrt2$ and squaring, $\sqrt2$ would be rational.)

Let $r = \sqrt2 + \sqrt3$. If $r$ were rational, then we have: $\sqrt3 = r - \sqrt2$. Squaring both sides, we get: $3 = (r - \sqrt2)^2 = r^2 - 2\sqrt2r + 2$. Rearranging the equation, we get: $\sqrt2 = \frac{r^2 - 1}{2r}$. Thus $\sqrt2$ is rational, which is a contradiction. Therefore $\sqrt2 + \sqrt3$ is not rational.

Let $r = \sqrt2 + \sqrt[3]2$. If $r$ were rational, then we have: $\sqrt[3]2 = r - \sqrt2$. Cubing both sides, we get: $2 = (r - \sqrt2)^3 = r^3 - 3\sqrt2r^2 + 6r - 2\sqrt2$. Rearranging the equation, we get: $\sqrt2 = \frac{r^3 + 6r - 2}{3r^2 + 2}$. Thus $\sqrt2$ is rational, which is a contradiction. Therefore $\sqrt2 + \sqrt[3]2$ is not rational.

> 3\) Prove that $\sqrt2 + \sqrt3 + \sqrt5$ is irrational. Try to make up similar and more general examples.

> (Page 63) *Exercise:* Calculate $\sqrt[3]2$ and $\sqrt[3]5$ with an accuracy of at least $10^{-2}$.

### 3. Limits. Infinite Geometrical Series. 极限 无穷等比级数

> (Page 66) *Exercise:* 1\) Prove that $1 - q + q^2 - q^3 + \dots = \frac{1}{1 + q}$, if $|q| < 1$.

> 2\) What is the limit of the sequence $a_1, a_2, a_3, \dots$, where $a_n = n/(n+1)$? (Hint: Write the expression in the form $n/(n+1) = 1 - 1/(n+1)$ and observe that the second term tends to zero).

> 3\) What is the limit of $\frac{n^2+n+1}{n^2-n+1}$ for $n \to \infty$? (Hint: Write the expression in the form
>
> $$
> \frac{1+\frac{1}{n}+\frac{1}{n^2}}{1-\frac{1}{n}+\frac{1}{n^2}}.)
> $$

> 4\) Prove, for $|q| < 1$, that $1 + 2q + 3q^2 + 4q^3 + \dots = \frac{1}{(1-q)^2}$. (Hint: Use the result of exercise 3 on p.18.)

> 5\) What is the limit of the infinite series
>
> $$
> 1 - 2q + 3q^2 - 4q^3 + \dots \quad?
> $$

> 6\) What is the limit of $\frac{1+2+3+\dots+n}{n^2}$, of $\frac{1^2+2^2+3^2+\dots+n^2}{n^3}$, and of $\frac{1^3+2^3+3^3+\dots+n^3}{n^4}$? (Hint: Use the results of pp. 12, 14, 15.)

### 4. Rational Numbers and Periodic Decimals. 有理数和循环小数

> (Page 67~68) *Exercise:* 1\) Expand the fractions $\frac{1}{1}$, $\frac{1}{13}$, $\frac{2}{13}$, $\frac{3}{13}$, $\frac{1}{17}$, $\frac{2}{17}$ into decimal fractions and determine the period.

> *2\) The number $142,857$ has the property that multiplication with any one of the numbers $2, 3, 4, 5,$ or $6$ produces only a cyclic permutation of its digits. Explain this property, using the expansion of $\frac{1}{7}$ into a decimal fraction.

> 3\) Expand the rational numbers of exercise 1 as "decimals" with bases $5, 7,$ and $12$.

> 4\) Expand one-third as a dyadic number.

> 5\) Write $.11212121\dots$ as a fraction. Find the value of this symbol if it is meant in the systems with the bases $3$ or $5$.

### 5. General Definition of Irrational Numbers by Nested Intervals. 用区间套给出无理数的一般定义

### *6. Alternative Methods of Defining Irrational Numbers. Dedekind Cuts. 定义无理数的另一个方法 戴德金分割

## § 3. Remarks on Analytic Geometry. 解析几何概述

### 1. The Basic Principle. 基本原理

### *2. Equations of Lines and Curves. 直线方程和曲线方程

## § 4. The Mathematical Analysis of Infinity. 无限的数学分析

### 1. Fundamental Concepts. 基本概念

### 2. The Denumerability of the Rational Numbers and the Non-Denumerability of the Continuum. 有理数的可数性和连续统的不可数性

> (Page 80~81) *Exercise:* 1\) Show that the set of all positive and negative integers is denumerable. Show that the set of all positive and negative rational numbers is denumerable.

> 2\) Show that the set $S + T$ (see p. 110) is denumerable if $S$ and $T$ are denumerable sets. Show the same for the sum of three, four, or any number, $n$, of sets, and finally for a set composed of denumerably many denumerable sets.

> (Page 82) *Exercose:* Show that any interval $[A, B]$ of the number axis is equivalent to any other interval $[C, D]$.

> (Page 83) *Exercise:* Prove that the same result holds for a denumerable set of points in the plane, replacing lengths of intervals by areas of squares.

### 3. Cantor’s “Cardinal Numbers”. 康托的“基数”

> (Page 85) *Exercise:* If $A$ contains $n$ elements, where $n$ is a positive integer, show that $B$, defined as above, contains $2^n$ elements. If $A$ consists of the set of all positive integers, show that $B$ is equivalent to the continuum of real numbers from $0$ to $1$. (Hint: Symbolize a subset of $A$ in the first case by a finite and in the second case by an infinite sequence of the symbols $0$ and $1$,
>
> $$
> a_1 a_2 a_3 \dots,
> $$
>
> where $a_n = 1$ or $0$, according as the $n$ th element of $A$ does or does not belong to the given subset.)

### 4. The Indirect Method of Proof. 反证法

### 5. The Paradoxes of the Infinite. 有关无限的悖论

### 6. The Foundations of Mathematics. 数学的基础

## § 5. Complex Numbers. 复数

### 1. The Origin of Complex Numbers. 复数的起源

> (Page 91) *Exercise:* 1\) Express $\frac{(1+i)(2+i)(3+i)}{(1-i)}$ in the form $a + bi$.

> 2\) Express
>
> $$
> \left( - \frac{1}{2} + i \frac{\sqrt3}{2} \right)^{3}
> $$
>
> in the form $a + bi$.

> 3\) Express in the form $a + bi$:
>
> $$
> \frac{1+i}{1-i}, \frac{1+i}{2-i}, \frac{1}{(-2+i)(1-3i)}, \frac{(4-5i)^2}{(2-3i)^2}.
> $$

> 4\) Calculate $\sqrt{5+12i}$. (Hint: Write $\sqrt{5+12i} = x + yi$, square, and equate real and imaginary parts.)

### 2. The Geometrical Interpretation of Complex Numbers. 复数的几何解释