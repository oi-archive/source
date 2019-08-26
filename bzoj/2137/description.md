
# Description

<div class="content"><p>设函数g(N)表示N的约数个数。现在给出一个数M，求出所有M的约数x的g(x)的K次方和。</p></div>

# Input

<div class="content"><p>第一行输入N，K。N表示M由前N小的素数组成。接下来N行，第i+1行有一个正整数Pi，表示第Ai小的素数 有 Pi次。等式：</p></div>

# Output

<div class="content"><p>输出一个数，表示答案。只需输出最后答案除以1000000007的余数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2 3<br/>
1<br/>
3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">900<br/>
【样例说明】<br/>
M=2^1*3^3=54<br/>
M的约数有1,2,3,6,9,18,27,54.约数个数分别为1,2,2,4,3,6,4,8.<br/>
Answer=1^3+2^3+2^3+4^3+3^3+6^3+4^3+8^3=900<br/>
<br/>
<br/>
编号	N	K	Pi&lt;=<br/>
1	50	3	10000<br/>
2	50	100	10000<br/>
3	50	20101125	10000<br/>
4	999	17651851	100000<br/>
5	5000	836954247	100000<br/>
6	4687	1073741823	100000<br/>
7	4321	123456789	100000<br/>
8	5216	368756432	100000<br/>
9	8080	2^31-1	100000<br/>
10	10086	3	2^63-1<br/>
11	64970	3	2^63-1<br/>
12	71321	3	2^63-1<br/>
13	350	5	2^31-1<br/>
14	250	6	2^31-1<br/>
15	110	7	2^31-1<br/>
16	99	8	2^31-1<br/>
17	80	9	2^31-1<br/>
18	70	10	2^31-1<br/>
19	60	11	2^31-1<br/>
20	50	12	2^31-1<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

