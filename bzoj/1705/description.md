
# Description

<div class="content"><p><span style="font-size: medium">最近，Farmer John的奶牛们越来越不满于牛棚里一塌糊涂的电话服务 于是，她们要求FJ把那些老旧的电话线换成性能更好的新电话线。 新的电话线架设在已有的N(2 &lt;= N &lt;= 100,000)根电话线杆上， 第i根电话线杆的高度为height_i米(1 &lt;= height_i &lt;= 100)。 电话线总是从一根电话线杆的顶端被引到相邻的那根的顶端 如果这两根电话线杆的高度不同，那么FJ就必须为此支付 C*电话线杆高度差(1 &lt;= C &lt;= 100)的费用。当然，你不能移动电话线杆， 只能按原有的顺序在相邻杆间架设电话线。Farmer John认为 加高某些电话线杆能减少架设电话线的总花费，尽管这项工作也需要支出一定的费用。 更准确地，如果他把一根电话线杆加高X米的话，他得为此付出X^2的费用。 请你帮Farmer John计算一下，如果合理地进行这两种工作，他最少要在这个电话线改造工程上花多少钱。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第1行: 2个用空格隔开的整数：N和C </span></p>
<p><span style="font-size: medium">* 第2..N+1行: 第i+1行仅有一个整数：height_i</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第1行: 输出Farmer John完成电话线改造工程所需要的最小花费 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 2<br/>
2<br/>
3<br/>
5<br/>
1<br/>
4<br/>
输入说明:<br/>
 一共有5根电话线杆，在杆间拉电话线的费用是每米高度差$2。<br/>
在改造之前，电话线杆的高度依次为2，3，5，1，4米。<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">15<br/>
输出说明:<br/>
最好的改造方法是：Farmer John把第一根电话线杆加高1米，把第四根加高2米，<br/>
使得它们的高度依次为3，3，5，3，4米。这样花在加高电线杆上的钱是$5。<br/>
此时，拉电话线的费用为$2*(0+2+2+1) = $10，总花费为$15。<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

