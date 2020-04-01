
# Description

<div class="content">LMY and YY are mathematics lovers. They like to find and solve interesting mathematic problems together. One day, they found that the polynomial “x^n-1” can be factorized into a large number of long polynomials, although the polynomial “x^n-1” looks simple. They were interested in how to factorize it into irreducible polynomials.

By “irreducible” we mean that it has co-prime coefficients and cannot be further factorized.

Now your task is to help LMY and YY to factorize x^n-1 into several irreducible polynomials over the integers.

</div>

# Input

<div class="content">The input consists of multiple test cases.
For each test case, there is one line containing only one integer N. (2&lt;=N&lt;=1001)

End of input is indicated by a line containing a zero.
</div>

# Output

<div class="content">For each test case, output the factorization of the given polynomial according to the writing habit, i.e. x^5, 5x^2, 3x, x^2-x.

There are multiple ways to express the factorization of a polynomial. To make it unique, we sort the irreducible polynomials according to the following rules:

Lower order polynomials are always lexicographically smaller than higher order polynomials. Same order polynomials should be sorted by their coefficients. We compare the coefficients from high degree terms to low degree terms, including the omitted terms, which the coefficients are regard as 0. Coefficients are being compared first by absolute value then by sign. Smaller absolute values are lexicographically smaller. For the same absolute value, negative coefficients are lexicographically smaller than positive coefficients.

</div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
3<br/>
4<br/>
5<br/>
6<br/>
12<br/>
256<br/>
0<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">(x-1)(x+1)<br/>
(x-1)(x^2+x+1)<br/>
(x-1)(x+1)(x^2+1)<br/>
(x-1)(x^4+x^3+x^2+x+1)<br/>
(x-1)(x+1)(x^2-x+1)(x^2+x+1)<br/>
(x-1)(x+1)(x^2+1)(x^2-x+1)(x^2+x+1)(x^4-x^2+1)<br/>
(x-1)(x+1)(x^2+1)(x^4+1)(x^8+1)(x^16+1)(x^32+1)(x^64+1)(x^128+1)<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

