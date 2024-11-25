# CHAPTER I. THE NATURAL NUMBERS 第一章 自然数

## § 1. Calculation with Integers. 整数的计算

### 1. Laws of Arithmetic. 算术的规律

### 2. The Representation of Integers. 整数的表示

### 3. Computation in Systems Other than the Decimal. 非十进位制中的计算

> (Page 8) *Exercises:* 1\) Set up the addition and multiplication tables in the duodecimal system and work some examples of the same sort.

$$
\textbf{Addition (base 12)} \\
\begin{array}{r:rrrrrrrrrrr}
  &  1 &  2 &  3 &  4 &  5 &  6 &  7 &  8 &  9 &  A &  B \\
\hline
1 &  2 &  3 &  4 &  5 &  6 &  7 &  8 &  9 &  A &  B & 10 \\
2 &  3 &  4 &  5 &  6 &  7 &  8 &  9 &  A &  B & 10 & 11 \\ 
3 &  4 &  5 &  6 &  7 &  8 &  9 &  A &  B & 10 & 11 & 12 \\
4 &  5 &  6 &  7 &  8 &  9 &  A &  B & 10 & 11 & 12 & 13 \\
5 &  6 &  7 &  8 &  9 &  A &  B & 10 & 11 & 12 & 13 & 14 \\
6 &  7 &  8 &  9 &  A &  B & 10 & 11 & 12 & 13 & 14 & 15 \\
7 &  8 &  9 &  A &  B & 10 & 11 & 12 & 13 & 14 & 15 & 16 \\
8 &  9 &  A &  B & 10 & 11 & 12 & 13 & 14 & 15 & 16 & 17 \\
9 &  A &  B & 10 & 11 & 12 & 13 & 14 & 15 & 16 & 17 & 18 \\
A &  B & 10 & 11 & 12 & 13 & 14 & 15 & 16 & 17 & 18 & 19 \\
B & 10 & 11 & 12 & 13 & 14 & 15 & 16 & 17 & 18 & 19 & 1A \\
\end{array}
$$

$$
\textbf{Multiplication (base 12)} \\
\begin{array}{r:rrrrrrrrrrr}
  &  1 &  2 &  3 &  4 &  5 &  6 &  7 &  8 &  9 &  A &  B \\
\hline
1 &  1 &  2 &  3 &  4 &  5 &  6 &  7 &  8 &  9 &  A &  B \\
2 &  2 &  4 &  6 &  8 &  A & 10 & 12 & 14 & 16 & 18 & 1A \\ 
3 &  3 &  6 &  9 & 10 & 13 & 16 & 19 & 20 & 23 & 26 & 29 \\
4 &  4 &  8 & 10 & 14 & 18 & 20 & 24 & 28 & 30 & 34 & 38 \\
5 &  5 &  A & 13 & 18 & 21 & 26 & 2B & 34 & 39 & 42 & 47 \\
6 &  6 & 10 & 16 & 20 & 26 & 30 & 36 & 40 & 46 & 50 & 56 \\
7 &  7 & 12 & 19 & 24 & 2B & 36 & 41 & 48 & 53 & 5A & 65 \\
8 &  8 & 14 & 20 & 28 & 34 & 40 & 48 & 54 & 60 & 68 & 74 \\
9 &  9 & 16 & 23 & 30 & 39 & 46 & 53 & 60 & 69 & 76 & 83 \\
A &  A & 18 & 26 & 34 & 42 & 50 & 5A & 68 & 76 & 84 & 92 \\
B &  B & 1A & 29 & 38 & 47 & 56 & 65 & 74 & 83 & 92 & A1 \\
\end{array}
$$

> 2\) Express “thirty” and “one hundred and thirty-three” in the systems with the bases $5,7,11,12$.

$$
\begin{aligned}
30_{10} &= 110_5 = 42_7 = 28_{11} = 26_{12} \\
133_{10} &= 1013_5 = 250_7 = 111_{11} = B1_{12}
\end{aligned}
$$

> 3\) What do the symbols $11111$ and $21212$ mean in these systems?

$$
\begin{aligned}
11111_5 &= 781_{10}, & 11111_7 &= 2801_{10}, & 11111_{11} &= 16105_{10}, & 11111_{12} &= 22621_{10} \\
21212_5 &= 1432_{10}, & 21212_7 &= 5252_{10}, & 21212_{11} &= 30868_{10}, & 21212_{12} &= 43502_{10}
\end{aligned}
$$

> 4\) Form the addition and multiplication tables for the bases $5,11,13$.

$$
\textbf{Addition (base 5)} \\
\begin{array}{r:rrrr}
  &  1 &  2 &  3 &  4 \\
\hline
1 &  2 &  3 &  4 & 10 \\
2 &  3 &  4 & 10 & 11 \\
3 &  4 & 10 & 11 & 12 \\
4 & 10 & 11 & 12 & 13 \\
\end{array}
$$

$$
\textbf{Multiplication (base 5)} \\
\begin{array}{r:rrrr}
  &  1 &  2 &  3 &  4 \\
\hline
1 &  1 &  2 &  3 &  4 \\
2 &  2 &  4 &  6 &  8 \\
3 &  3 & 11 & 14 & 22 \\
4 &  4 & 13 & 22 & 31 \\
\end{array}
$$

$$
\textbf{Addition (base 11)} \\
\begin{array}{r:rrrrrrrrrr}
  &  1 &  2 &  3 &  4 &  5 &  6 &  7 &  8 &  9 &  A \\
\hline
1 &  2 &  3 &  4 &  5 &  6 &  7 &  8 &  9 &  A & 10 \\
2 &  3 &  4 &  5 &  6 &  7 &  8 &  9 &  A & 10 & 11 \\
3 &  4 &  5 &  6 &  7 &  8 &  9 &  A & 10 & 11 & 12 \\
4 &  5 &  6 &  7 &  8 &  9 &  A & 10 & 11 & 12 & 13 \\
5 &  6 &  7 &  8 &  9 &  A & 10 & 11 & 12 & 13 & 14 \\
6 &  7 &  8 &  9 &  A & 10 & 11 & 12 & 13 & 14 & 15 \\
7 &  8 &  9 &  A & 10 & 11 & 12 & 13 & 14 & 15 & 16 \\
8 &  9 &  A & 10 & 11 & 12 & 13 & 14 & 15 & 16 & 17 \\
9 &  A & 10 & 11 & 12 & 13 & 14 & 15 & 16 & 17 & 18 \\
A & 10 & 11 & 12 & 13 & 14 & 15 & 16 & 17 & 18 & 19 \\
\end{array}
$$

$$
\textbf{Multiplication (base 11)} \\
\begin{array}{r:rrrrrrrrrr}
  &  1 &  2 &  3 &  4 &  5 &  6 &  7 &  8 &  9 &  A \\
\hline
1 &  1 &  2 &  3 &  4 &  5 &  6 &  7 &  8 &  9 &  A \\
2 &  2 &  4 &  6 &  8 &  A & 11 & 13 & 15 & 17 & 19 \\
3 &  3 &  6 &  9 & 11 & 14 & 17 & 1A & 22 & 25 & 28 \\
4 &  4 &  8 & 11 & 15 & 19 & 22 & 26 & 2A & 33 & 37 \\
5 &  5 &  A & 14 & 19 & 23 & 28 & 32 & 37 & 41 & 46 \\
6 &  6 & 11 & 17 & 22 & 28 & 33 & 39 & 44 & 4A & 55 \\
7 &  7 & 13 & 1A & 26 & 32 & 39 & 45 & 51 & 58 & 64 \\
8 &  8 & 15 & 22 & 2A & 37 & 44 & 51 & 59 & 66 & 73 \\
9 &  9 & 17 & 25 & 33 & 41 & 4A & 58 & 66 & 74 & 82 \\
A &  A & 19 & 28 & 37 & 46 & 55 & 64 & 73 & 82 & 91 \\
\end{array}
$$

$$
\textbf{Addition (base 13)} \\
\begin{array}{r:rrrrrrrrrrrr}
  &  1 &  2 &  3 &  4 &  5 &  6 &  7 &  8 &  9 &  A &  B &  C \\
\hline
1 &  2 &  3 &  4 &  5 &  6 &  7 &  8 &  9 &  A &  B &  C & 10 \\
2 &  3 &  4 &  5 &  6 &  7 &  8 &  9 &  A &  B &  C & 10 & 11 \\
3 &  4 &  5 &  6 &  7 &  8 &  9 &  A &  B &  C & 10 & 11 & 12 \\
4 &  5 &  6 &  7 &  8 &  9 &  A &  B &  C & 10 & 11 & 12 & 13 \\
5 &  6 &  7 &  8 &  9 &  A &  B &  C & 10 & 11 & 12 & 13 & 14 \\
6 &  7 &  8 &  9 &  A &  B &  C & 10 & 11 & 12 & 13 & 14 & 15 \\
7 &  8 &  9 &  A &  B &  C & 10 & 11 & 12 & 13 & 14 & 15 & 16 \\
8 &  9 &  A &  B &  C & 10 & 11 & 12 & 13 & 14 & 15 & 16 & 17 \\
9 &  A &  B &  C & 10 & 11 & 12 & 13 & 14 & 15 & 16 & 17 & 18 \\
A &  B &  C & 10 & 11 & 12 & 13 & 14 & 15 & 16 & 17 & 18 & 19 \\
B &  C & 10 & 11 & 12 & 13 & 14 & 15 & 16 & 17 & 18 & 19 & 1A \\
C & 10 & 11 & 12 & 13 & 14 & 15 & 16 & 17 & 18 & 19 & 1A & 1B \\
\end{array}
$$

$$
\textbf{Multiplication (base 13)} \\
\begin{array}{r:rrrrrrrrrrrr}
  &  1 &  2 &  3 &  4 &  5 &  6 &  7 &  8 &  9 &  A &  B &  C \\
\hline
1 &  1 &  2 &  3 &  4 &  5 &  6 &  7 &  8 &  9 &  A &  B &  C \\
2 &  2 &  4 &  6 &  8 &  A &  C & 11 & 13 & 15 & 17 & 19 & 1B \\
3 &  3 &  6 &  9 &  C & 12 & 15 & 18 & 1B & 21 & 24 & 27 & 2A \\
4 &  4 &  8 &  C & 13 & 17 & 1B & 22 & 26 & 2A & 31 & 35 & 39 \\
5 &  5 &  A & 12 & 17 & 1C & 24 & 29 & 31 & 36 & 3B & 43 & 48 \\
6 &  6 &  C & 15 & 1B & 24 & 2A & 33 & 39 & 42 & 48 & 51 & 57 \\
7 &  7 & 11 & 18 & 22 & 29 & 33 & 3A & 44 & 4A & 55 & 5C & 66 \\
8 &  8 & 13 & 1B & 26 & 31 & 39 & 44 & 4C & 57 & 62 & 6A & 75 \\
9 &  9 & 15 & 21 & 2A & 36 & 42 & 4B & 57 & 63 & 6C & 78 & 84 \\
A &  A & 17 & 24 & 31 & 3B & 48 & 55 & 62 & 6C & 79 & 86 & 93 \\
B &  B & 19 & 27 & 35 & 43 & 51 & 5C & 6A & 78 & 86 & 94 & A2 \\
C &  C & 1B & 2A & 39 & 48 & 57 & 66 & 75 & 84 & 93 & A2 & B1 \\
\end{array}
$$

> (Page 9) *Exercises:* Consider the question of representing integers with the base $a$. In order to name the integers in this system we need words for the digits $0,1,\dotsc,a-1$ and for the various powers of $a:a,a^2,a^3,\dotsc$. How many different number words are needed to name all numbers from zero to on thousand, for $a=2,3,4,5,\dotsc,15$? Which base requires the fewest? (Examples: If $a=10$, we need ten words for the digits, plus words for $10$, $100$, and $1000$, making a total of 13. For $a=20$, we need twenty words for the digits, plus words for $20$ and $400$, making a total of 22. If $a=100$, we need $100$ plus $1$.)

$$
\begin{array}{rc:rrrrrr}
\text{Base} & a & 2 & 3 & 4 & 5 & 6 & 7 \\
\hline
\text{Number of words for digits} & a & 2 & 3 & 4 & 5 & 6 & 7 \\
\text{Number of words for powers} & \log_{a}{1000} & 9 & 6 & 4 & 4 & 3 & 3 \\
\text{Total number of words} & a + \log_{a}{1000} & 11 & 9 & 8 & 9 & 9 & 10 \\
\end{array}
$$

Answer: Base $4$ requires only $8$ words, which is the fewest.

## *§ 2. The Infinitude of the Number System. Mathematical Induction. 数系的无限性 数学归纳法

### 1. The Principle of Mathematical Induction. 数学归纳法原理

### 2. The Arithmetical Progression. 等差级数

### 3. The Geometrical Progression. 等比级数

### 4. The Sum of the First $n$ Squares. 前 $n$ 个平方数的和

### *5. An Important Inequality. 一个重要的不等式

### *6. The Binomial Theorem. 二项式定理

> (Page 17~18) *Exercises:* Prove by mathematical induction:
>
> 1\) $\frac{1}{1\cdot2} + \frac{1}{2\cdot3} + \dots + \frac{1}{n\cdot(n+1)} = \frac{n}{n+1}$.

$$
\begin{aligned}
\frac{1}{1\cdot2} &= \frac{1}{1+1} \quad \text{when } n=1 \\
f(r+1) &= f(r) + \frac{1}{(r+1)\cdot(r+2)} \\
&= \frac{r}{r+1} + \frac{1}{(r+1)\cdot(r+2)} \\
&= \frac{r^2+2r+1}{(r+1)\cdot(r+2)} = \frac{(r+1)^2}{(r+1)\cdot(r+2)} \\
&= \frac{r+1}{r+2}
\end{aligned}
$$

> 2\) $\frac{1}{2} + \frac{1}{2^2} + \frac{1}{2^3} + \dots + \frac{1}{2^n} = 2 - \frac{n+2}{2^n}$.

$$
\begin{aligned}
\frac{1}{2} &= 2 - \frac{1+2}{2^1} \quad \text{when } n=1 \\
f(r+1) &= f(r) + \frac{r+1}{2^{r+1}} \\
&= 2 - \frac{r+2}{2^r} + \frac{r+1}{2^{r+1}} = 2 - \frac{2r+4-r-1}{2^{r+1}} \\
&= 2 - \frac{r+3}{2^{r+1}}
\end{aligned}
$$

> *3\) $1 + 2q + 3q^2 + \dots + nq^{n-1} = \frac{1-(n+1)q^n+nq^{n+1}}{(1-q)^2}$.

$$
\begin{aligned}
1 &= \frac{1-(1+1)q+q^2}{(1-q)^2} \quad \text{when } n=1 \\
f(r+1) &= f(r) + (r+1)q^r \\
&= \frac{1-(r+1)q^r+rq^{r+1}}{(1-q)^2} + (r+1)q^r \\
&= \frac{1-(r+1)q^r+rq^{r+1}+(r+1)q^r(1-q)^2}{(1-q)^2} \\
&= \frac{1+q^r\left(-r-1+rq+(r+1)(1-2q+q^2)\right)}{(1-q)^2} \\
&= \frac{1+q^r(rq-r-1+r+1-2rq-2q+rq^2+q^2)}{(1-q)^2} \\
&= \frac{1+q^r(-rq-2q+rq^2+q^2)}{(1-q)^2} = \frac{1+q^{r+1}(-r-2+rq+q)}{(1-q)^2} \\
&=  \frac{1-(r+2)q^{r+1}+(r+1)q^{r+2}}{(1-q)^2}
\end{aligned}
$$

> *4) $(1+q)(1+q^2)(1+q^4)\dots(1+q^{2^n}) = \frac{1-q^{2^{n+1}}}{1-q}$.

$$
\begin{aligned}
(1+q)(1+q^2) &= \frac{1-q^4}{1-q} \quad \text{when } n=1 \\
f(r+1) &= f(r)(1+q^{2^{r+1}}) \\
&= \frac{(1-q^{2^{r+1}})(1+q^{2^{r+1}})}{1-q} = \frac{1-(q^{2^{r+1}})^2}{1-q} \\
&= \frac{1-q^{2^{r+2}}}{1-q}
\end{aligned}
$$

> Find the sum of the following geometrical progressions:
>
> 5\) $\frac{1}{1+x^2} + \frac{1}{(1+x^2)^2} + \dots + \frac{1}{(1+x^2)^n}$.

$$
\begin{aligned}
G_n &= a\frac{1-q^n}{1-q} \quad \text{if } q \neq 1 \\
a &= \frac{1}{1+x^2}, \quad q = \frac{1}{1+x^2} \quad (x \neq 0) \\
G_n &= \frac{1}{1+x^2}\frac{1-\left(\frac{1}{1+x^2}\right)^n}{1-\frac{1}{1+x^2}} = \frac{1}{x^2}\left(1 - \frac{1}{(1+x^2)^n}\right) \\
&= \frac{(1+x^2)^n-1}{x^2(1+x^2)^n} \quad (x \neq 0) \\
G_n &= \left\lbrace\begin{array}{lc}
\frac{(1+x^2)^n-1}{x^2(1+x^2)^n} & \text{if } x \neq 0 \\
n & \text{if } x = 0
\end{array}\right.
\end{aligned}
$$

> 6\) $1 + \frac{x}{1+x^2} + \frac{x^2}{(1+x^2)^2} + \dots + \frac{x^n}{(1+x^2)^n}$.

$$
\begin{aligned}
G_n &= a\frac{1-q^{n+1}}{1-q} \quad \text{if } q \neq 1 \\
a &= 1, \quad q = \frac{x}{1+x^2} \neq 1 \\
G_n &= \frac{1-\left(\frac{x}{1+x^2}\right)^{n+1}}{1-\frac{x}{1+x^2}} \\
&= \frac{(1+x^2)^{n+1}-x^{n+1}}{(1+x^2)^n(1-x+x^2)} \\
\end{aligned}
$$

> 7\) $\frac{x^2-y^2}{x^2+y^2} + \left(\frac{x^2-y^2}{x^2+y^2}\right)^2 + \dots + \left(\frac{x^2-y^2}{x^2+y^2}\right)^n$.

$$
\begin{aligned}
G_n &= a\frac{1-q^n}{1-q} \quad \text{if } q \neq 1 \\
a &= \frac{x^2-y^2}{x^2+y^2}, \quad q = \frac{x^2-y^2}{x^2+y^2} \quad (y \neq 0) \\
G_n &= \frac{\frac{x^2-y^2}{x^2+y^2}\left(1-\left(\frac{x^2-y^2}{x^2+y^2}\right)^n\right)}{1-\frac{x^2-y^2}{x^2+y^2}} \\
&= \frac{(x^2+y^2)^n(x^2-y^2)-(x^2-y^2)^n}{(x^2+y^2)^n(x^2+y^2-x^2+y^2)} \\
&= \frac{(x^2+y^2)^n(x^2-y^2)-(x^2-y^2)^n}{2y^2(x^2+y^2)^n} \quad (y \neq 0) \\
G_n &= \left\lbrace\begin{array}{lc}
\frac{(x^2+y^2)^n(x^2-y^2)-(x^2-y^2)^n}{2y^2(x^2+y^2)^n} & \text{if } y \neq 0 \\
n & \text{if } y = 0
\end{array}\right.
\end{aligned}
$$

> Using formulas (4) and (5) prove:
>
> *8\) $1^2 + 3^2 + 5^2 + \dots + (2n+1)^2 = \frac{(n+1)(2n+1)(2n+3)}{3}$.

$$
\begin{aligned}
1^2 + 2^2 + 3^2 + \dots + n^2 &= \frac{n(n+1)(2n+1)}{6} \quad \text{formula (4)} \\
4(1^2 + 2^2 + 3^2 + \dots + n^2) &= \frac{4n(n+1)(2n+1)}{6} \\
2^2 + 4^2 + 6^2 + \dots + (2n)^2 &= \frac{4n(n+1)(2n+1)}{6} \\
1^2 + 2^2 + 3^2 + \dots + (2n+1)^2 &= \frac{(2n+1)(2n+2)(4n+3)}{6} \quad \text{from formula (4)} \\
1^2 + 3^2 + 5^2 + \dots + (2n+1)^2 &= \frac{(2n+1)(2n+2)(4n+3)}{6} - \frac{4n(n+1)(2n+1)}{6} \\
&= \frac{(2n+1)\left((2n+2)(4n+3)-4n(n+1)\right)}{6} \\
&= \frac{(2n+1)(8n^2+14n+6-4n^2-4n)}{6} \\
&= \frac{(2n+1)(4n^2+10n+6)}{6} = \frac{(2n+1)(2n^2+5n+3)}{3} \\
&= \frac{(n+1)(2n+1)(2n+3)}{3}
\end{aligned}
$$

> *9\) $1^3 + 3^3 + 5^3 + \dots + (2n+1)^3 = (n+1)^2(2n^2+4n+1)$.

$$
\begin{aligned}
1^3 + 2^3 + 3^3 + \dots + n^3 &= \left(\frac{n(n+1)}{2}\right)^2 \quad \text{formula (5)} \\
8(1^3 + 2^3 + 3^3 + \dots + n^3) &= 8\left(\frac{n(n+1)}{2}\right)^2 \\
2^3 + 4^3 + 6^3 + \dots + (2n)^3 &= 2n^2(n+1)^2 \\
1^3 + 2^3 + 3^3 + \dots + (2n+1)^3 &= \left(\frac{(2n+1)(2n+2)}{2}\right)^2 \quad \text{from formula (5)} \\
1^3 + 3^3 + 5^3 + \dots + (2n+1)^3 &= \left(\frac{(2n+1)(2n+2)}{2}\right)^2 - 2n^2(n+1)^2 \\
&= (2n+1)^2(n+1)^2 - 2n^2(n+1)^2 \\
&= (n+1)^2(2n^2+4n+1)
\end{aligned}
$$

> 10\) Prove the same results directly by mathematical induction.

$$
\begin{aligned}
1^2 + 3^2 &= \frac{2\cdot3\cdot5}{3} \quad \text{when } n=1 \\
f(r+1) &= f(r) + (2r+3)^2 \\
&= \frac{(r+1)(2r+1)(2r+3)}{3} + (2r+3)^2 \\
&= \frac{(2r+3)(2r^2+3r+1+6r+9)}{3} = \frac{(2r+3)(2r^2+9r+10)}{3} \\
&= \frac{(r+2)(2r+3)(2r+5)}{3}
\end{aligned}
$$

$$
\begin{aligned}
1^3 + 3^3 &= (1+1)^2(2\cdot1^2+4\cdot1+1) \quad \text{when } n=1 \\
f(r+1) &= f(r) + (2r+3)^3 \\
&= (r+1)^2(2r^2+4r+1) + (2r+3)^3 \\
&= (r^2+2r+1)(2r^2+4r+1) + (2r+3)^3 \\
&= (2r^4+4r^3+r^2+4r^3+8r^2+2r+2r^2+4r+1) + (8r^3+36r^2+54r+27) \\
&= 2r^4 + 16r^3 + 47r^2 + 60r + 28 = (r^2+4r+4)(2r^2+8r+7) \\
&= (r+2)^2\left(2(r+1)^2+4(r+1)+1\right)
\end{aligned}
$$

### *7. Further Remarks on Mathematical Induction. 再谈数学归纳法

# SUPPLEMENT TO CHAPTER I. THE THEORY OF NUMBERS 第一章补充 数论

## § 1. The Prime Numbers. 素数

### 1. Fundamental Facts. 基本事实

> (Page 23) *Exercise:* Carry out this construction starting with $p_1=2$, $p_2=3$ and find 5 more primes.

$$
\begin{aligned}
2 \cdot 3 + 1 &= 7 \text{ is a prime} \\
2 \cdot 3 \cdot 7 + 1 &= 43 \text{ is a prime} \\
2 \cdot 3 \cdot 7 \cdot 43 + 1 &= 1807 = 13 \cdot 139 \quad \text{13 and 139 are primes} \\
2 \cdot 3 \cdot 7 \cdot 13 \cdot 43 \cdot 139 + 1 &= 3263443 \text{ is a prime}
\end{aligned}
$$

Answer: 5 more primes are $7, 13, 43, 139, 3263443$.

> (Page 25) *Exercise:* In order to find all the divisors of any number $a$ we need only decompose $a$ into a product
>
> $$
> a = p_1^{\alpha_1} \cdot p_2^{\alpha_2} \dots p_r^{\alpha_r},
> $$
>
> where the $p$'s are distinct primes, each raised to a certain power. *All* the divisors of $a$ are the numbers
>
> $$
> b = p_1^{\beta_1} \cdot p_2^{\beta_2} \dots p_r^{\beta_r},
> $$
>
> where the $\beta$'s are any integers satisfying the inequalities
>
> $$
> 0 \leq \beta_1 \leq \alpha_1, 0 \leq \beta_2 \leq \alpha_2, \dots, 0 \leq \beta_r \leq \alpha_r.
> $$
>
> Prove this statement. As a consequence, show that the number of different divisors of $a$ (including the divisors $a$ and $1$) is  given by the product
>
> $$
> (\alpha_1 + 1)(\alpha_2 + 1) \dots (\alpha_r + 1).
> $$
>
> For example,
>
> $$
> 144 = 2^4 \cdot 3^2
> $$
>
> has $5\cdot3$ divisors. They are $1, 2, 4, 8, 16, 3, 6, 12, 24, 48, 9, 18, 36, 72, 144$.

> (Page 25) *Exercise:* Prove the corresponding theorem for the progressions $6n+5$

### 2. The Distribution of the Primes. 素数的分布

## § 2. Congruences. 同余

### 1. General Concepts. 一般概念

> (Page 35) *Exercise:* Find a similar rule for divisibility by 13.

$$
\begin{aligned}
10 \equiv -3, 10^2 \equiv -4, 10^3 \equiv -1, 10^4 \equiv 3, 10^5 \equiv 4, 10^6 \equiv 1 \\
r = a_0 - 3a_1 - 4a_2 - a_3 + 3a_4 + 4a_5 + a_6 - 3a_7 - \dots
\end{aligned}
$$

> (Page 36) *Exercise:* Show that the following *law of cancellation* holds for congruences with respect to a prime modulus:
>
> If $ab \equiv ac$ and $a \not\equiv 0$, then $b \equiv c $.

$$
\begin{aligned}
ab \equiv ac \implies ab - ac \equiv 0 \implies a(b-c) \equiv 0 \implies a \equiv 0 \text{ or } b - c \equiv 0 \\
\text{Since } a \not\equiv 0, \text{then } b - c \equiv 0 \implies b \equiv c.
\end{aligned}
$$

> (Page 36) *Exercise:* 1\) To what number between $0$ and $6$ inclusive is the product $11\cdot18\cdot2322\cdot13\cdot19$ congruent modulo $7$?

$$
(-3) \cdot (-3) \cdot (-2) \cdot (-1) \cdot (-2) = -36 \equiv 6 \pmod{7}
$$

> 2\) To what number between $0$ and $12$ inclusive is $3\cdot7\cdot11\cdot17\cdot19\cdot23\cdot29\cdot113$ congruent modulo $13$?

> 3\) To what number between $0$ and $4$ inclusive is the sum $1 + 2 + 2^2 + \dots + 2^{19}$ congruent modulo $5$?

### 2. Fermat’s Theorem. 费马定理

> (Page 38) *Exercise:* 1\) Show by similar computation that $2^8 \equiv 1 \pmod{17}$; $3^8 \equiv -1 \pmod{17}$; $3^{14} \equiv -1 \pmod{29}$; $2^{14} \equiv -1 \pmod{29}$; $4^{14} \equiv 1 \pmod{29}$; $5^{14} \equiv 1 \pmod{29}$.

> 2\) Check Fermat's theorem for $p = 5, 7, 11, 17$, and $23$ with different values of $a$.

> 3\) Prove the general theorem: The smallest positive integer $e$ for which $a^e \equiv 1 \pmod{p}$ must be a divisor of $p-1$. (Hint: Divide $p-1$ by $e$, obtaining
>
> $$
> p - 1 = ke + r
> $$
>
> where $0 \leq r < e$, and use the fact that $a^{p-1} \equiv a^e \equiv 1 \pmod{p}$.)

### 3. Quadratic Residues. 二次剩余

> (Page 40) *Exercise:* 1. $6^2 = 36 \equiv 13 \pmod{23}$. Is 23 a quadratic residue $\pmod{13}$?

> 2. We have seen that $x^2 \equiv (p-x)^2 \pmod{p}$. Show that these are the only congruences among the numbers $1^2, 2^2, 3^2, \dotsc, (p-1)^2$.

## § 3. Pythagorean Numbers and Fermat’s Last Theorem. 毕达哥拉斯数和费马大定理

> (Page 41) *Exercise:* Prove the last statement.

## § 4. The Euclidean Algorithm. 欧几里得辗转相除法

### 1. General Theory. 一般理论

> (Page 45) *Exercise:* Carry out the Euclidean algorithm for finding the greatest common divisor of (a) $187, 77$. (b) $105, 385$. (c) $245, 193$.

### 2. Application to the Fundamental Theorem of Arithmetic. 在算术基本定理上的应用

> (Page 47) *Exercise:* The extension of this argument to products of any number $n$ of integers requires the explicit or implicit use of the principle of mathematical induction. Supply the details of this argument.

### 3. Euler’s $\varphi$ Function. Fermat’s Theorem Again. 欧拉函数φ 再谈费马定理

> (Page 48) *Exercise:* Prove the theorem: *If an integer* $r$ *divides a product* $ab$ *and is relatively prime to* $a$, *then* $r$ *must divide* $b$. (Hint: if $r$ is relatively prime to $a$ then we can find integers $k$ and $l$ such that
>
> $$
> kr + al = 1.
> $$
>
> Multiply both sides of this equation by $b$.) This theorem includes the lemma of page 46 as a special case, since a prime $p$ is relatively prime to an integer $a$ if and only if $p$ does not divide $a$.

$$
kr + al = 1 \implies krb + lab = b \\
$$

Since $r$ divides $krb$ and $lab$ respectively, $r$ must divide the sum $krb + lab = b$.

> (Page 49) *Exercise:* Using Euler's $\varphi$ function, generalize Fermat's theorem of page 37. The general theorem state: *If* $n$ *is any integer, and* $a$ *is relatively prime to* $n$, *then*
>
> $$
> a^{\varphi(n)} \equiv 1 \pmod{n}.
> $$

### 4. Continued Fractions. Diophantine Equations. 连分数 丢番都方程

> (Page 50) *Exercise:* Find the continued fraction developments of
>
> $$
> \frac{2}{5}, \frac{43}{30}, \frac{169}{70}
> $$

$$
\begin{aligned}
\frac{2}{5} &= \frac{1}{2 + \frac{1}{2}} \\
\frac{43}{30} &= 1 + \frac{1}{2 + \frac{1}{3 + \frac{1}{4}}} \\
\frac{169}{70} &= 2 + \frac{1}{2 + \frac{1}{2 + \frac{1}{2 + \frac{1}{\frac{1}{2 + \frac{1}{2}}}}}}
\end{aligned}
$$

> (Page 51) *Exercise:* Solve the Diophantine equations (a) $3x - 4y = 29$. (b) $11x - 12y = 58$. (c) $153x - 34y = 51$.
