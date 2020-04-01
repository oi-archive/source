# 

 
 # 题目描述 
<p>
LMY and YY are mathematics lovers. They like to find and solve interesting mathematic problems together. One day, they found that the polynomial “x^n-1” can be factorized into a large number of long polynomials, although the polynomial “x^n-1” looks simple. They were interested in how to factorize it into irreducible polynomials.<br><br>By “irreducible” we mean that it has co-prime coefficients and cannot be further factorized.<br><br>Now your task is to help LMY and YY to factorize x^n-1 into several irreducible polynomials over the integers.<br><br></p> 

 
 # 输入格式 
<p>
The input consists of multiple test cases.<br>For each test case, there is one line containing only one integer N. (2<=N<=1001)<br><br>End of input is indicated by a line containing a zero.<br></p> 

 
 # 输出格式 
<p>
For each test case, output the factorization of the given polynomial according to the writing habit, i.e. x^5, 5x^2, 3x, x^2-x.<br><br>There are multiple ways to express the factorization of a polynomial. To make it unique, we sort the irreducible polynomials according to the following rules:<br><br>Lower order polynomials are always lexicographically smaller than higher order polynomials. Same order polynomials should be sorted by their coefficients. We compare the coefficients from high degree terms to low degree terms, including the omitted terms, which the coefficients are regard as 0. Coefficients are being compared first by absolute value then by sign. Smaller absolute values are lexicographically smaller. For the same absolute value, negative coefficients are lexicographically smaller than positive coefficients.<br><br></p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>2
3
4
5
6
12
256
0

</td><td>(x-1)(x+1)
(x-1)(x^2+x+1)
(x-1)(x+1)(x^2+1)
(x-1)(x^4+x^3+x^2+x+1)
(x-1)(x+1)(x^2-x+1)(x^2+x+1)
(x-1)(x+1)(x^2+1)(x^2-x+1)(x^2+x+1)(x^4-x^2+1)
(x-1)(x+1)(x^2+1)(x^4+1)(x^8+1)(x^16+1)(x^32+1)(x^64+1)(x^128+1)</td></tr></table>
