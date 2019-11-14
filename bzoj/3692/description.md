
# Description

<div class="content"><div><span style="font-size: medium">         对于一个1~n的排列{p1,p2,…,pn}，将pi和pj交换，需要的代价为2*|i-j|-1，记f(p)表示通过交换将排列p变成从小到大的排列，即{1,2,3…,n}的最小代价。一个愚蠢的算法是用g(p)=Σmax(0, i-pi)来估算f(p)。给出1~n的排列的前m个元素，求有多少个排列p满足条件f(p)=g(p)。</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">         输入n和m，表示1~n的排列，以及确定了前m个数。</span></div>
<div><span style="font-size: medium">         接下来一行包含m个数，表示排列中确定的前m个数。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">         输出一行，表示有多少个排列满足条件，输出答案mod 10^9+7。</span></div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">样例输入1<br/>
         3 0<br/>
 <br/>
样例输入 2<br/>
         5 2 1 4<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例输出 1<br/>
         5<br/>
<br/>
样例输出 2<br/>
         3<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p> 对于100%的数据，n≤2000，m≤n</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

