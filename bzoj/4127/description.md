
# Description

<div class="content"><pre style="white-space: pre-wrap;"> 给定一棵树,设计数据结构支持以下操作

    1 u v　d　 表示将路径 (u,v) 加d

    2　u　v  表示询问路径 (u,v) 上点权绝对值的和<br/></pre>
<p></p></div>

# Input

<div class="content"><div><span style="white-space: pre-wrap;">第一行两个整数n和m，表示结点个数和操作数</span></div>
<div>
<pre style="white-space: pre-wrap;">接下来一行n个整数a_i,表示点i的权值

接下来n-1行,每行两个整数u,v表示存在一条(u,v)的边

接下来m行,每行一个操作,输入格式见题目描述<br/></pre>
</div>
<p></p></div>

# Output

<div class="content"><div><span style="white-space: pre-wrap;">对于每个询问输出答案</span></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">    4 4<br/>
    -4 1 5 -2<br/>
    1 2<br/>
    2 3<br/>
    3 4<br/>
    2 1 3<br/>
    1 1 4 3<br/>
    2 1 3<br/>
    2 3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">    10<br/>
    13<br/>
    9</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，n,m &lt;= 10^5 且 0&lt;= d,|a_i|&lt;= 10^8</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

