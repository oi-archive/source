
# Description

<div class="content"><p><span style="font-size: medium">   有一个由M 条电缆连接的 N 个站点组成的网络。为了防止垄断，由 C 个公司控制所有的电缆，规定任何公司不能控制连接同一个站点的两条以上的电缆（可以控制两条）。同时规定，每个公司不能有多余的电缆，所谓的多余，是指属于同一个公司的电缆不能形成环。  <br/>
在运作过程中，不同公司之间会进行电缆买卖。请你写一个程序判断买卖是否合法。 <br/>
</span></p></div>

# Input

<div class="content"><p><br/>
<font size="4">输入第一行有4个由空格隔开的整数 N，M，C和 T。N(1≤N≤ 8 000)表示站点数，M(0≤M≤100 000)表示连接站点的电缆数。C(1≤C≤ 100)表表示公司数量，T 表示电缆买卖次<br/>
数。后面有M行，每行三个整数Sj1,Sj2和Kj，表示连接站点Sj1和Sj2(1≤Sj1&lt; Sj2  ≤ n)的电缆属于Kj(1≤Kj≤C)公司拥有，任意两个站点只有一条直接相连的电缆，输入状态合法。最后T(0≤T≤100 000)行，每行三个整数 Si1, Si2和  Ki,表示 Ki公司想购买站点Si1和Si2之间的电缆。 <br/>
</font></p></div>

# Output

<div class="content"><p><br/>
<font size="4">输出共 T行，表示处理的结果，有以下几种可能的结果： <br/>
1、“No such cable.”  两个站点间没有电缆。 <br/>
2、 “Already owned.”  电缆己经是 Ki 公司控制。 <br/>
3、 “Forbidden: monopoly.” Ki 公司己经控制了两条连接 Si1  或  Si2 的电缆。 <br/>
4、 “Forbidden: redundant.” Ki 公司控制的线路会出现环。 <br/>
5、 “Sold.”  可以买卖。 </font></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 5 3 5 <br/>
1 2 1 <br/>
2 3 1 <br/>
3 4 2 <br/>
1 4 2 <br/>
1 3 3 <br/>
1 2 3 <br/>
1 2 3 <br/>
1 4 3 <br/>
2 3 3 <br/>
2 4 3 </span></div>

# Sample Output

<div class="content"><span class="sampledata">Sold. <br/>
Already owned. <br/>
Forbidden: monopoly. <br/>
Forbidden: redundant. <br/>
No such cable. </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

