
# Description

<div class="content"><p>给你一个字符串，每次询问你一个长度为w的区间[i,i-w+1]中不同的子串个数</p></div>

# Input

<div class="content"><p>第一行一个字符串D。<br/>
第二行两个正整数Q和w，分别表示询问总数和所有询问的区间长度<br/>
接下来Q行，每行一个正整数，表示询问区间的起始位置<br/>
1&lt;=|D|&lt;=100000<br/>
1&lt;=Q&lt;=100000<br/>
1&lt;=W&lt;=|D|<br/>
1&lt;=i&lt;=|D|-w+1</p></div>

# Output

<div class="content"><p>对于每个询问，输出一个整数，表示该区间的不同子串个数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">样例输入1：<br/>
acat<br/>
2 3<br/>
1<br/>
2<br/>
样例输入2：<br/>
portoisamazing<br/>
2 7<br/>
6<br/>
3</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例输出1：<br/>
5<br/>
6<br/>
<br/>
样例输出2：<br/>
26<br/>
28<br/>
<br/>
样例解释1：<br/>
第一个询问询问区间[1,3]-&gt;(aca)该区间有5个不同的子串(a,c,ac,ca,aca)<br/>
第二个询问询问区间[2,4]-&gt;(cat)该区间有6个不同的子串(c,a,t,ca,at,cat)</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

