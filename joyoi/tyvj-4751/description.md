# 

 
 # 题目背景 
<p>NOIP春季系列课程</p> 

 
 # 题目描述 
<p>小H是一个喜欢逛街的女孩子，但是由于上了大学，DDL越来越多了，她不能一直都处于逛街的状态。为了让自己能够更加沉迷于学习，她规定一次逛街只逛T个单位的时间。</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;小H从1号店出发，从1号店走到第i号店需要花费ai的时间，这些店形成了一条直线，也就是说小H从第i号店走到第i+1号店需要花费的时间为a{i+1}-ai。若小H选择了第i号店并且进去逛，则会消耗bi的时间。对于第i家店，小H都对它有自己的看法。具体地，可以用ci来表示小H是否喜欢这家店。如果ci=1，则表示小H喜欢i号店，否则若ci=0，则表示小H不喜欢这家店。</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;小H想尽可能逛更多的店，但是她也有属于自己的目标，也就是说逛至少k家喜欢的店，在这个基础上，能逛的店越多越好。</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;小H现在想知道自己最多能逛多少店，当然若小H无论如何也逛不到k家喜欢的店，那么你输出-1就行了。</p>

<p>&nbsp;</p> 

 
 # 输入格式 
<p>第一行3个数n,T,k。</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接下来一行n个数表示ai。</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接下来一行n个数表示bi。</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;接下来一行n个数表示ci。</p>

<p>请在此填写输入格式</p> 

 
 # 输出格式 
<p>输出一个数表示答案。</p>

<p>请在此填写输出格式</p> 

 
 # 提示 
<p>输入样例</p>

<p>4&nbsp;11&nbsp;1</p>

<p>0&nbsp;1&nbsp;2&nbsp;10</p>

<p>1&nbsp;1&nbsp;1&nbsp;1</p>

<p>0&nbsp;0&nbsp;0&nbsp;1</p>

<p>&nbsp;</p>

<p>输出样例</p>

<p>1</p>

<p>&nbsp;</p>

<p>数据范围</p>

<p>对于20%的数据n&lt;=20。</p>

<p>对于40%的数据n&lt;=1000。</p>

<p>对于100%的数据n&lt;=100000，1&lt;=T&lt;=10^9，0&lt;=k&lt;=n，a1=0，a1&lt;a2&lt;&hellip;&lt;an&lt;=10^9，1&lt;=bi&lt;=10^9，0&lt;=ci&lt;=1，数据有梯度。</p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<p>&nbsp;</p>

<p>&nbsp;</p> 
