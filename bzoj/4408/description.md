
# Description

<div class="content"><p>一个可重复数字集合S的神秘数定义为最小的不能被S的子集的和表示的正整数。例如S={1,1,1,4,13}，<br/>
<br/>
1 = 1<br/>
<br/>
2 = 1+1<br/>
<br/>
3 = 1+1+1<br/>
<br/>
4 = 4<br/>
<br/>
5 = 4+1<br/>
<br/>
6 = 4+1+1<br/>
<br/>
7 = 4+1+1+1<br/>
<br/>
8无法表示为集合S的子集的和，故集合S的神秘数为8。<br/>
<br/>
现给定n个正整数a[1]..a[n]，m个询问，每次询问给定一个区间[l,r](l&lt;=r)，求由a[l],a[l+1],…,a[r]所构成的可重复数字集合的神秘数。</p></div>

# Input

<div class="content"><p>第一行一个整数n，表示数字个数。<br/>
第二行n个整数，从1编号。<br/>
第三行一个整数m，表示询问个数。<br/>
以下m行，每行一对整数l,r，表示一个询问。</p></div>

# Output

<div class="content"><p>对于每个询问，输出一行对应的答案。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2 4 9 10<br/>
5<br/>
1 1<br/>
1 2<br/>
1 3<br/>
1 4<br/>
1 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
4<br/>
8<br/>
8<br/>
8</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据点，n,m &lt;= 100000，∑a[i] &lt;= 10^9</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢yyh上传">鸣谢yyh上传</a></p></div>

