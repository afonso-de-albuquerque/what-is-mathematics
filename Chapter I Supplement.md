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

If $a = 1$, then $a$ has only one divisor, which is $1$. Each $\alpha_i = 0$ and each $\beta_i = 0$. Therefore the statement is true for $a = 1$.

If $a > 1$, then according to the Fundamental Theorem of Arithmetic, $a$ can be factored into a product of primes in only one way, which is $a = p_1^{\alpha_1} \cdot p_2^{\alpha_2} \dots p_r^{\alpha_r}$, where $p_1, p_2, \dots, p_r$ are distinct primes and each $\alpha_i$ is a positive integer. Therefore, $a$ has no other prime factors than $p_1, p_2, \dots, p_r$. Its divisors, being able to divide $a$, must also have no other prime factors than $p_1, p_2, \dots, p_r$. Therefore, all the divisors can be factored into the form $p_1^{\beta_1} \cdot p_2^{\beta_2} \dots p_r^{\beta_r}$. Any divisor must satisfy that $\beta_i \geq 0$, since otherwise the divisor is not an integer. Any divisor must also satisfy that $\beta_i \leq \alpha_i$, since otherwise the divisor has at least one prime factor $p_i$ that has a higher power than $a$, causing it unable to divide $a$. Therefore the statement is true for $a > 1$ too.

Each $\beta_i$ can take $\alpha_i + 1$ possible values ($0, 1, 2, \dotsc, \alpha_i$). Therefore the number of different divisors of $a$ is $(\alpha_1 + 1)(\alpha_2 + 1) \dots (\alpha_r + 1)$.

### 2. The Distribution of the Primes. 素数的分布

> (Page 25) *Exercise:* Prove the corresponding theorem for the progressions $6n+5$.

Any prime greater than $2$ is odd and hence is of the form $6n+1$, $6n+3$, or $6n+5$. However, $6n+3$ is divisible by $3$, so it cannot be a prime. Therefore any prime greater than $2$ can only be of the form $6n+1$ or $6n+5$. Furthermore, the product of two numbers of the form $6n+1$ is again of that form, since

$$
(6a + 1)(6b + 1) = 36ab + 6a + 6b + 1 = 6(6ab + a + b) + 1.
$$

Suppose there were but a finite number of primes, $p_1, p_2, \dotsc, p_n$ of the form $6n+5$, and consider the number

$$
N = 6(p_1 p_2 \dots p_n) - 1 = 6(p_1 p_2 \dots p_n - 1) + 5.
$$

Either $N$ is itself a prime, or it may be decomposed into a product of primes, none of which can be $p_1, p_2, \dotsc, p_n$, since these divide $N$ with a remainder $-1$. Furthermore, all the prime factors of $N$ cannot be of the form $6n+1$, for $N$ is not of that form and, as we have seen, the product of numbers of the form $6n+1$ is again of the form. Hence at least one prime factor must be of the form $6n+5$, which is impossible, since we saw that none of the $p$'s, which we supposed to be *all* the primes of the form $6n+5$, can be a factor of $N$. Therefore the assumption that the number of primes of the form $6n+5$ is finite has led to a contradiction, and hence the number of such primes must be infinite.

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

$$
3 \cdot (-6) \cdot (-2) \cdot 4 \cdot 6 \cdot (-3) \cdot 3 \cdot (-4) = 144 \cdot 216 \equiv 1 \cdot (-5) \equiv 8 \pmod{13}
$$

> 3\) To what number between $0$ and $4$ inclusive is the sum $1 + 2 + 2^2 + \dots + 2^{19}$ congruent modulo $5$?

$$
\begin{aligned}
1 + 2 + 2^2 + \dots + 2^{19} &= \frac{1-2^{20}}{1-2} = 2^{20} - 1 = (2^4)^5 - 1 \\
&= 16^5 - 1 \equiv 1^5 - 1 \equiv 0 \pmod{5}
\end{aligned}
$$

### 2. Fermat’s Theorem. 费马定理

> (Page 38) *Exercise:* 1\) Show by similar computation that $2^8 \equiv 1 \pmod{17}$; $3^8 \equiv -1 \pmod{17}$; $3^{14} \equiv -1 \pmod{29}$; $2^{14} \equiv -1 \pmod{29}$; $4^{14} \equiv 1 \pmod{29}$; $5^{14} \equiv 1 \pmod{29}$.

$$
2^2 \equiv 4, 2^4 \equiv -1, 2^8 \equiv 1 \pmod{17}
$$

$$
3^2 \equiv -8, 3^4 \equiv -4, 3^8 \equiv -1 \pmod{17}
$$

$$
3^2 \equiv 9, 3^4 \equiv -6, 3^8 \equiv 7, 3^{14} = 3^2 \cdot 3^4 \cdot 3^8 \equiv -1 \pmod{29}
$$

$$
2^2 \equiv 4, 2^4 \equiv -13, 2^8 \equiv -5, 2^{14} = 2^2 \cdot 2^4 \cdot 2^8 \equiv -1 \pmod{29}
$$

$$
4^{14} = (2^{14})^2 \equiv (-1)^2 \equiv 1 \pmod{29}
$$

$$
5^2 \equiv -4, 5^4 \equiv -13, 5^8 \equiv -5, 5^{14} = 5^2 \cdot 5^4 \cdot 5^8 \equiv 1 \pmod{29}
$$

> 2\) Check Fermat's theorem for $p = 5, 7, 11, 17$, and $23$ with different values of $a$.

$$
2^4 = 16 \equiv 1, 3^4 = 81 \equiv 1 \pmod{5}
$$

$$
2^6 = 64 \equiv 1, 3^6 = 729 \equiv 1 \pmod{7}
$$

$$
\begin{aligned}
2^{10} = (2^5)^2 = 32^2 \equiv (-1)^2 &\equiv 1 \pmod{11} \\
3^{10} = (3^2)^5 \equiv (-2)^5 \equiv -33 &\equiv 1 \pmod{11}
\end{aligned}
$$

$$
\begin{aligned}
2^{16} = (2^4)^4 = 16^4 \equiv (-1)^4 &\equiv 1 \pmod{17} \\
3^{16} = ((3^4)^2)^2 = (81^2)^2 \equiv ((-4)^2)^2 \equiv (-1)^2 &\equiv 1 \pmod{17}
\end{aligned}
$$

> 3\) Prove the general theorem: The smallest positive integer $e$ for which $a^e \equiv 1 \pmod{p}$ must be a divisor of $p-1$. (Hint: Divide $p-1$ by $e$, obtaining
>
> $$
> p - 1 = ke + r
> $$
>
> where $0 \leq r < e$, and use the fact that $a^{p-1} \equiv a^e \equiv 1 \pmod{p}$.)

$$
\begin{aligned}
a^{p-1} \equiv 1 \implies a^{ke+r} \equiv 1 \implies (a^e)^k \cdot a^r \equiv 1 \pmod{p} \\
\text{Since } a^e \equiv 1 \text{, then } a^r \equiv 1 \pmod{p}
\end{aligned}
$$

Since $e$ is the smallest positive integer such that $a^e \equiv 1 \pmod{p}$ and $0 \leq r < e$, then $r = 0$. Therefore $(p-1) = ke$ and $e$ must be a divisor of $p-1$.

### 3. Quadratic Residues. 二次剩余

> (Page 40) *Exercise:* 1\) $6^2 = 36 \equiv 13 \pmod{23}$. Is 23 a quadratic residue $\pmod{13}$?

Since $13 \equiv 6^2 \pmod{23}$, $13$ is a quadratic residue $\pmod{23}$. Since the product $\left( \frac{13-1}{2} \right) \cdot \left( \frac{23-1}{2} \right) = 6 \cdot 11$ is even, according to the Law of Quadratic Reciprocity, $23$ is a quadratic residue $\pmod{13}$. In confirmation of this, we observe that $23 \equiv 6^2 \pmod{13}$.

> 2\) We have seen that $x^2 \equiv (p-x)^2 \pmod{p}$. Show that these are the only congruences among the numbers $1^2, 2^2, 3^2, \dotsc, (p-1)^2$.

Let $x$ be any integer among $1, 2, 3, \dotsc, p-1$, and we have $x^2 \equiv (p-x)^2 \pmod{p}$. Since $p$ is odd, $p-x \neq x$. Therefore there exist at least one integer $(p-x)^2$ among the numbers $1^2, 2^2, 3^2, \dotsc, (p-1)^2$ that is congruent to $x^2$.

Suppose $y^2$ is one integer congruent to $x^2$, where $y$ is among the numbers $1, 2, 3, \dotsc, p-1$ and $y \neq x$. Then we have:

$$
y^2 \equiv x^2 \implies y^2 - x^2 \equiv 0 \implies (y-x)(y+x) \equiv 0 \pmod{p}
$$

Since $y \neq x$, and $x, y$ are both among the numbers $1, 2, 3, \dotsc, p-1$, then $y \equiv -x \pmod{p}$, then $y - x \not\equiv 0 \pmod{p}$. Therefore $y + x \equiv 0 \implies y \equiv -x \pmod{p}$. The only possible value of $y$ among the numbers $1, 2, 3, \dotsc, p-1$ is $y = p-x$. Therefore the only congruences among the numbers $1^2, 2^2, 3^2, \dotsc, (p-1)^2$ are $x^2 \equiv (p-x)^2 \pmod{p}$.

## § 3. Pythagorean Numbers and Fermat’s Last Theorem. 毕达哥拉斯数和费马大定理

> (Page 41) *Exercise:* Prove the last statement.

This exercise is to prove that the formulas

$$
\begin{aligned}
a &= v^2 - u^2, \\
b &= 2uv, \\
c &= u^2 + v^2,
\end{aligned}
$$

for any positive integers $u$ and $v$ with $v > u$, where $u$ and $v$ have no common factor and are not both odd, yield all primitive Pythagorean number triples. It's already proven that $(a, b, c)$ in a Pythagorean number triple are proportional to $v^2 - u^2, 2uv, u^2 + v^2$ respectively. Therefore it's only needed to prove that $a, b, c$ in the formulas above have no common factor.

Since $u$ and $v$ have no common factor, then $u$ and $v$ are not both even, otherwise they have a common factor $2$. Since $u$ and $v$ are not both odd either, then $u + v$ and $u - v$ are both odd.

Besides, since $u$ and $v$ have no common factor, then:
* $u + v$ has no common factor with $u$ or $v$;
* $u - v$ has no common factor with $u$ or $v$.

Therefore $v^2 - u^2 = (v+u)(v-u)$ is odd and has no common factor with $u$ or $v$, thus $a = v^2 - u^2$ has no common factor with $b = 2uv$.

Similarly, $(u + v)^2$ is odd and has no common factor with $u$ or $v$. Therefore $b + c = (u + v)^2$ has no common factor with $b = 2uv$, thus $c = u^2 + v^2$ has no common factor with $b = 2uv$.

Finally, $v^2 - u^2 = (v+u)(v-u)$ is odd and has no common factor with $v$. Therefore $a = v^2 - u^2 = (v+u)(v-u)$ has no common factor with $a + c = 2v^2$, thus $a = v^2 - u^2$ has no common factor with $c = u^2 + v^2$.

As a result, $a = v^2 - u^2$, $b = 2uv$, and $c = u^2 + v^2$ have no common factor.

## § 4. The Euclidean Algorithm. 欧几里得辗转相除法

### 1. General Theory. 一般理论

> (Page 45) *Exercise:* Carry out the Euclidean algorithm for finding the greatest common divisor of (a) $187, 77$. (b) $105, 385$. (c) $245, 193$.

$$
(187, 77) = (77, 33) = (33, 11) = (11, 0) = 11
$$

$$
(105, 385) = (105, 70) = (35, 70) = (35, 0) = 35
$$

$$
(245, 193) = (193, 52) = (52, 37) = (37, 15) = (15, 7) = (7, 1) = (1, 0) = 1
$$

### 2. Application to the Fundamental Theorem of Arithmetic. 在算术基本定理上的应用

> (Page 47) *Exercise:* The extension of this argument to products of any number $n$ of integers requires the explicit or implicit use of the principle of mathematical induction. Supply the details of this argument.

It has been proven that if a prime $p$ divides a product $ab$, then $p$ must divide $a$ or $b$. This exercise is to prove that if a prime $p$ divides a product $a_1 a_2 \dots a_n$, then $p$ must divide at least one of the $a_i$ where $i$ is an integer between $1$ and $n$.

Suppose the statement is true for $r$, i.e. if a prime $p$ divides a product $a_1 a_2 \dots a_r$, then $p$ must divide at least one of the $a_i$. Then if $p$ divides $(a_1 a_2 \dots a_r) \cdot a_{r+1}$, then $p$ must divide either the product of $a_1 a_2 \dots a_r$, or $a_{r+1}$. Therefore $p$ must divide at least one of the $a_i$ where $i$ is an integer between $1$ and $r+1$.

### 3. Euler’s $\varphi$ Function. Fermat’s Theorem Again. 欧拉函数 $\varphi$ 再谈费马定理

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

Since $r$ divides $krb$ and $ab$ respectively, $r$ must divide the sum $krb + lab = b$.

> (Page 49) *Exercise:* Using Euler's $\varphi$ function, generalize Fermat's theorem of page 37. The general theorem state: *If* $n$ *is any integer, and* $a$ *is relatively prime to* $n$, *then*
>
> $$
> a^{\varphi(n)} \equiv 1 \pmod{n}.
> $$

According to the definition of Euler's $\varphi$ function, $n$ has $\varphi(n)$ number of integers from $1$ to $n$ that are relatively prime to $n$. Let these integers be $q_1, q_2, \dotsc, q_{\varphi(n)}$ in ascending order. Consider the multiples of $a$:

$$
m_1 = q_1 a, m_2 = q_2 a, \dotsc, m_{\varphi(n)} = q_{\varphi(n)} a.
$$

No two of these integers can be congruent modulo $n$, for then $n$ would be a factor of $m_s - m_r = (q_s - q_r)a$ for some pair of integers $r, s$ with $1 \leq r < s \leq \varphi(n) < n$. But $n$ is neither a factor of $a$ nor a factor of $q_s - q_r$. Likewise, none of these numbers can be congruent to $0$. Besides, since $a$ and $n$ are relatively prime, then any $m_i$'s congruences are also relatively prime to $n$, and no two different $m_i$'s are congruent to each other modulo $n$ (for $m_r \equiv m_s \implies q_r a \equiv q_s a \implies q_r \equiv q_s \implies r = s$). Therefore, the numbers $m_1, m_2, \dotsc, m_{\varphi(n)}$ must be respectively congruent to the numbers $q_1, q_2, \dotsc, q_{\varphi(n)}$, in some arrangement. It follows that

$$
m_1 m_2 \dots m_{\varphi(n)} = q_1 q_2 \dots q_{\varphi(n)} a^{\varphi(n)} \equiv q_1 q_2 \dots q_{\varphi(n)} \pmod{n},
$$

or, if for brevity we write $K$ for $q_1 q_2 \dots q_{\varphi(n)}$, knowing that $K$ is not divisible by $n$,

$$
K a^{\varphi(n)} \equiv K \implies a^{\varphi(n)} \equiv 1 \pmod{n}.
$$

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

> (Page 51) *Exercise:* Solve the Diophantine equations (a) $3x - 4y = 29$. (b) $11x + 12y = 58$. (c) $153x - 34y = 51$.

$$
\begin{aligned}
4 = 1 \cdot 3 + 1 \\
1 = 4 - 3 \\
\text{Hence } \quad 3 \cdot (-1) - 4 \cdot (-1) = 1 \\
3 \cdot (-29) - 4 \cdot (-29) = 29 \\
\text{General solutions to (a): } x = -29 - 4r, y = -29 - 3r
\end{aligned}
$$

$$
\begin{aligned}
12 = 1 \cdot 11 + 1 \\
1 = 12 - 11 \\
\text{Hence } \quad 11 \cdot (-1) + 12 \cdot 1 = 1 \\
11 \cdot (-58) + 12 \cdot 58 = 58 \\
\text{General solutions to (b): } x = -58 + 12r, y = 58 - 11r
\end{aligned}
$$

$$
\begin{aligned}
153 = 4 \cdot 34 + 17, \quad 34 = 2 \cdot 17, \quad (153, 34) = 17 \\
17 = 153 - 4 \cdot 34 \\
\text{Hence } \quad 153 \cdot 1 - 34 \cdot 4 = 17 \\
153 \cdot 3 - 34 \cdot 12 = 51 \\
\text{General solutions to (c): } x = 3 - 2r, y = 12 - 9r
\end{aligned}
$$
