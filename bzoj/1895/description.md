
# Description

<div class="content">给出一个初始序列fA1;A2;:::Ang，要求你编写程序支持如下操作：
1. ADDxyD：给子序列fAx:::Ayg的每个元素都加上D。例如对f1,2,
3,4,5g执行&#34;ADD 241&#34; 会得到f1,3,4,5,5g。
2. REVERSExy：将子序列fAx:::Ayg翻转。例如对f1,2,3,4,5g执
行&#34;REVERSE 24&#34;会得到f1,4,3,2,5g。
3. REVOLVExyT：将子序列fAx:::Ayg旋转T个单位。例如，
对f1,2,3,4,5g执行&#34;REVOLVE 242&#34;会得到f1,3,4,2,5g。
4. INSERTxP：在Ax后插入P。例如，对f1,2,3,4,5g执行&#34;INSERT
24&#34;会得到f1,2,4,3,4,5g。
5. DELETEx：删去Ax。例如，对f1,2,3,4,5g执行&#34;DELETE 2&#34;会得
到f1,3,4,5g。
6. MINxy：查询子序列fAx:::Ayg中的最小元素。例如，对于序列f1,
2,3,4,5g，询问&#34;MIN 24&#34;的返回应为2。</div>

# Input

<div class="content">第一行包含一个整数n，表示初始序列的长度。
以下n行每行包含一个整数，描述初始的序列。
接下来一行包含一个整数m，表示操作的数目。
以下m行每行描述一个操作。</div>

# Output

<div class="content">对于所有&#34;MIN&#34;操作，输出正确的答案，每行一个。</div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1<br/>
2<br/>
3<br/>
4<br/>
5<br/>
2<br/>
ADD 2 4 1<br/>
MIN 4 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p>输入、输出以及中间运算结果均不会超过32位整数。<br/>
对于30%的数据，n;m 6 1000;<br/>
对于100%的数据，n;m 6 100000。</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

