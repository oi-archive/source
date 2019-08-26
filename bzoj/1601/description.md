
# Description

<div class="content"><p><span style="font-size: medium">Farmer John已经决定把水灌到他的n(1&lt;=n&lt;=300)块农田，农田被数字1到n标记。把一块土地进行灌水有两种方法，从其他农田饮水，或者这块土地建造水库。 建造一个水库需要花费wi(1&lt;=wi&lt;=100000),连接两块土地需要花费Pij(1&lt;=pij&lt;=100000,pij=pji,pii=0). 计算Farmer John所需的最少代价。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">*第一行：一个数n </span></p>
<p><span style="font-size: medium">*第二行到第n+1行：第i+1行含有一个数wi </span></p>
<p><span style="font-size: medium">*第n+2行到第2n+1行：第n+1+i行有n个被空格分开的数，第j个数代表pij。 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">*第一行：一个单独的数代表最小代价. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
5<br/>
4<br/>
4<br/>
3<br/>
0 2 2 2<br/>
2 0 3 3<br/>
2 3 0 4<br/>
2 3 4 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">9<br/>
<br/>
<br/>
输出详解：<br/>
<br/>
Farmer John在第四块土地上建立水库，然后把其他的都连向那一个，这样就要花费3+2+2+2=9<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=资格赛">资格赛</a></p></div>

