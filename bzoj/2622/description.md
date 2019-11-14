
# Description

<div class="content"><p><span class="Apple-style-span" style="word-spacing: 0px; font: medium Arial,Microsoft Yahei,Simsun,sans-serif; text-transform: none; color: rgb(0,0,0); text-indent: 0px; white-space: normal; letter-spacing: normal; border-collapse: separate; orphans: 2; widows: 2; webkit-border-horizontal-spacing: 0px; webkit-border-vertical-spacing: 0px; webkit-text-decorations-in-effect: none; webkit-text-size-adjust: auto; webkit-text-stroke-width: 0px"><span class="Apple-style-span" style="font-size: 16px; color: rgb(32,0,0); font-family: &#39;Times New Roman&#39;, 宋体">虎是中国传统文化中一个独特的意象。我们既会把老虎的形象用到喜庆的节日装饰画上，也可能把它视作一种邪恶的可怕的动物，例如“武松打虎”或者“三人成虎”。“不入虎穴焉得虎子”是一个对虎的威猛的形象的极好体现，而小强确偏偏进入了虎穴，但问题是怎么出来。<br/>
　　有一个复杂的虎穴包括了N个节点(编号为0至N-1)和M条无向的通道，其中通道i（0&lt;=i&lt;M）连接两个节点R[i][0]和R[i][1]，长为L[i]。有K个出口节点，分别为P[0], P[1]至P[K-1]。小强从0号节点出发，他想尽快到达一个出口节点。而洞穴中有一只会瞬间移动的老虎。小强每次到达一个节点，老虎就会瞬间移动到与这个节点相邻的某个通道里使得小强无法使用这个通道。不过，小强一旦选择了另一个没有被封锁的通道，老虎就不会在小强到达这个通道的目的地前改变位置。<br/>
　　老虎非常聪明，它总能让小强离开洞穴所要消耗的时间最长。而小强也非常聪明，他能够计算出最快的逃生方案。<br/>
　　为了让题目更加严谨，我们规定小强的逃生方案是如下的形式：对于每个节点X，给它的所有相邻的边&lt;X,Y&gt;指定一个权值f(X,Y)，注意，f(X,Y)不等于f(Y,X)；在一个节点，小强选择未被封锁的权值最大的通道逃生，直到到达出口。所有的f(X,Y)两两不同。<br/>
　　你要计算小强的最快逃离时间T并输出。</span></span></p></div>

# Input

<div class="content"><p>第一行三个整数 N M K<br/>
接下来M行 每行三个整数 表示一条无向边的两端和长度（无重边）<br/>
接下来K个整数 表示出口洞穴<br/>
输入直接保留这个就行<br/>
</p></div>

# Output

<div class="content"></div>

# Sample Input

<div class="content"><span class="sampledata">13 12 9<br/>
0 1 1<br/>
0 2 4<br/>
0 3 11<br/>
1 4 11<br/>
1 5 7<br/>
1 6 15<br/>
2 7 3<br/>
2 8 13<br/>
2 9 23<br/>
3 10 3<br/>
3 11 1<br/>
3 12 2<br/>
4 5 6 7 8 9 10 11 12<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">13</span></div>

# Hint

<div class="content"><p></p><p><span class="Apple-style-span" style="word-spacing: 0px; font: medium Arial,Microsoft Yahei,Simsun,sans-serif; text-transform: none; color: rgb(0,0,0); text-indent: 0px; white-space: normal; letter-spacing: normal; border-collapse: separate; orphans: 2; widows: 2; webkit-border-horizontal-spacing: 0px; webkit-border-vertical-spacing: 0px; webkit-text-decorations-in-effect: none; webkit-text-size-adjust: auto; webkit-text-stroke-width: 0px"><span class="Apple-style-span" style="font-size: 16px; color: rgb(32,0,0); font-family: &#39;Times New Roman&#39;, 宋体">时间限制：3秒（包括系统读数据约1.1秒。函数中运行的时间限制约为1.9秒）<br/><br/>
　　空间使用注意：系统大约需要使用116M空间，因此你的程序的所能使用的空间不到400M。<br/><br/>
　　对前6个测试点，3&lt;=N&lt;=1000，M=N-1。<br/><br/>
　　对中间7个测试点，3&lt;=N&lt;=1000，2&lt;=M&lt;=100000。<br/><br/>
　　对最后7个测试点，3&lt;=N&lt;=100000，2&lt;=M&lt;=1000000。<br/><br/>
　　一共20个测试点。</span></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

