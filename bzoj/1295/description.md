
# Description

<div class="content"><p>windy有一块矩形土地，被分为 N*M 块 1*1 的小格子。 有的格子含有障碍物。 如果从格子A可以走到格子B，那么两个格子的距离就为两个格子中心的欧几里德距离。 如果从格子A不可以走到格子B，就没有距离。 如果格子X和格子Y有公共边，并且X和Y均不含有障碍物，就可以从X走到Y。 如果windy可以移走T块障碍物，求所有格子间的最大距离。 保证移走T块障碍物以后，至少有一个格子不含有障碍物。</p></div>

# Input

<div class="content"><p>输入文件maxlength.in第一行包含三个整数，N M T。 接下来有N行，每行一个长度为M的字符串，&#39;0&#39;表示空格子，&#39;1&#39;表示该格子含有障碍物。</p></div>

# Output

<div class="content"><p>输出文件maxlength.out包含一个浮点数，保留6位小数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">【输入样例一】<br/>
3 3 0<br/>
001<br/>
001<br/>
110<br/>
<br/>
<br/>
【输入样例二】<br/>
4 3 0<br/>
001<br/>
001<br/>
011<br/>
000<br/>
<br/>
<br/>
【输入样例三】<br/>
3 3 1<br/>
001<br/>
001<br/>
001<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">【输出样例一】<br/>
1.414214<br/>
<br/>
【输出样例二】<br/>
3.605551<br/>
<br/>
【输出样例三】<br/>
2.828427<br/>
</span></div>

# Hint

<div class="content"><p></p><p>20%的数据，满足 1 &lt;= N,M &lt;= 30 ； 0 &lt;= T &lt;= 0 。 40%的数据，满足 1 &lt;= N,M &lt;= 30 ； 0 &lt;= T &lt;= 2 。 100%的数据，满足 1 &lt;= N,M &lt;= 30 ； 0 &lt;= T &lt;= 30 。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

