FA 2
================
Baybayon, Darlyn Antoinette

#### 3.49 Prove that $\sum_{j=1}^N{(X_{j}-1)^2} = \sum_{j=1}^N{X_{j}^2} - 2 \sum_{j=1}^N{X_{j}} +N$.

Expand the left-hand side of the equation:

$(X_{j}-1)^2 = (X_{j}^2 - 2X_{j} + 1)$

By the addition property of summation notation, distribute the summation
to all terms in the expression:

$\sum_{j=1}^N{X_{j}^2} - \sum_{j=1}^N 2{X_{j}} + \sum_{j=1}^N 1$

Simplify:

- $\sum_{j=1}^N{X_{j}} = 2 \sum_{j=1}^N{X_{j}}$ \* take out the constant

- $\sum_{j=1}^N{1} = N$ \* since we are adding 1 over N terms, this
  expression can be rewritten simply as N

Finally, rewrite the equation:

$\sum_{j=1}^N{(X_{j}-1)^2} = \sum_{j=1}^N{X_{j}^2} - 2 \sum_{j=1}^N{X_{j}} +N$

Since both sides of the equation are the same as shown, the equality
must be true.

------------------------------------------------------------------------

#### 3.51 Two variables, U and V, assume the values $U_1 = 3, U_2 = - 2, U_3 = 5,$ and $V_1 = -4, V_2 = -1,$ and $V_3 = 6$, respectively. Calculate:

##### a) $\sum{UV}$

$\sum{UV} = U_1V_1 + U_2V_2 + U_3V_3$

$= (3 \cdot -4) + (-2 \cdot -1) + (5 \cdot 6)$

$= (-12) + (2) + (30)$

$\boxed{\sum{UV} = 20 }$

##### b) $\sum{(U+3)(V-4)}$

$\sum{(U+3)(V-4)} = (U_1 + 3)(V_1 - 4) + (U_2 + 3)(V_2 - 4) + (U_3 + 3)(V_3 - 4)$

$= (3+3)(-4-4) + (-2+3)(-1-4) + (5+3)(6-4)$

$= (6)(-8) + (1)(-5) + (8)(2)$

$= (-48) + (-5) + (16)$

$\boxed{\sum{(U+3)(V-4)} = -37 }$

##### c) $\sum{V^2}$

$\sum{V^2} = V_1^2 + V_2^2 + V_3^2$

$= (-4)^2 + (-1)^2 + 6^2 = 16 + 1 + 36$

$\boxed{\sum{V^2} = 53 }$

##### d) $(\sum{U})(\sum{V})^2$

$(\sum{U})(\sum{V})^2 = (U_1 + U_2 + U_3) \cdot (V_1 + V_2 + V_3)^2$

$= (3 - 2 + 5) \cdot (-4 - 1 + 6)^2 = 6 \cdot 1^2$

$\boxed{(\sum{U})(\sum{V})^2 = 6 }$

##### e) $\sum{UV^2}$

$\sum{UV^2} = (U_1 \cdot V_1^2) + (U_2 \cdot V_2^2) + (U_3 \cdot V_3^2)$

$= (3 \cdot (-4)^2) + ((-2) \cdot (-1)^2) + (5 \cdot 6^2)$

$= (3 \cdot 16) + (-2  \cdot 1) + (5  \cdot 36) = 48 + (-2) + 180$

$\boxed{\sum{UV^2} = 226 }$

##### f) $\sum{U^2 -2V^2 + 2}$

$\sum{U^2 -2V^2 + 2} = [U_1^2 - (2 \cdot V_1^2) + 2] + [U_2^2 - (2 \cdot V_2^2) + 2] + [U_3^2 - (2 \cdot V_3^2) + 2]$

$= [3^2 - (2 \cdot (-4)^2) + 2] + [(-2)^2 - (2 \cdot (-1)^2) + 2] + [5^2 - (2 \cdot 6^2) + 2]$

$= [9 - (32) + 2] + [4 - (2) + 2] + [25 - (72) + 2] = -21 +  4 - 45$

$\boxed{\sum{U^2 -2V^2 + 2} = -62 }$

##### g) $\sum{U/V}$

$\sum{U/V} = (\frac{U_1}{V_1}) + (\frac{U_2}{V_2}) + (\frac{U_3}{V_3})$

$= (\frac{3}{-4}) + (\frac{-2}{-1}) + (\frac{5}{6})$

$\boxed{\sum{U/V} = 2.08 }$

------------------------------------------------------------------------

#### 3.90 Find the geometric mean of the sets:

##### a) 3,5,8,3,7,2

$\text{GM} = \sqrt[6]{3 \cdot 5 \cdot 8 \cdot 3 \cdot 7 \cdot 2}$

``` r
gm_a <- (3*5*8*3*7*2)^(1/6)
gm_a
```

    ## [1] 4.140681

##### b) 28.5, 73.6, 47.2, 31.5, 64.8

$\text{GM} = \sqrt[5]{28.5 \cdot 73.6 \cdot 47.2 \cdot 31.5 \cdot 64.8}$

``` r
gm_b <- (28.5*73.6*47.2*31.5*64.8)^(1/5)
gm_b
```

    ## [1] 45.8258
