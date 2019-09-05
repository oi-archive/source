# 题目描述


<h3>
<span style="color:#4F81BD;font-size:12pt;font-family:宋体;"><span style="font-family:Microsoft YaHei;">第一题：容易题</span><span style="font-family:Microsoft YaHei;">(easy)</span></span><span style="color:#4F81BD;font-size:12pt;font-family:Cambria;"></span> 
</h3>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span style="font-family:Microsoft YaHei;">时间限制：</span><span style="font-family:Microsoft YaHei;">1</span><span style="font-family:Microsoft YaHei;">秒</span></span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span style="font-family:Microsoft YaHei;">输入：</span><span style="font-family:Microsoft YaHei;">easy.in</span></span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span style="font-family:Microsoft YaHei;">输出：</span><span style="font-family:Microsoft YaHei;">easy.out</span></span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<h3>
<span style="color:#4F81BD;font-size:12pt;font-family:Microsoft YaHei;">问题描述</span><span style="color:#4F81BD;font-size:12pt;font-family:Cambria;"></span> 
</h3>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span style="font-family:Microsoft YaHei;">为了使得大家高兴，小</span><span style="font-family:Microsoft YaHei;">Q</span><span style="font-family:Microsoft YaHei;">特意出个自认为的简单题（</span><span style="font-family:Microsoft YaHei;">easy</span><span style="font-family:Microsoft YaHei;">）来满足大家，这道简单题是描述如下：</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span style="font-family:Microsoft YaHei;">有一个数列</span><span style="font-family:Microsoft YaHei;">A</span><span style="font-family:Microsoft YaHei;">已知对于所有的</span><span style="font-family:Microsoft YaHei;">A[i]</span><span style="font-family:Microsoft YaHei;">都是</span><span style="font-family:Microsoft YaHei;">1~n</span><span style="font-family:Microsoft YaHei;">的自然数，并且知道对于一些</span><span style="font-family:Microsoft YaHei;">A[i]</span><span style="font-family:Microsoft YaHei;">不能取哪些值，我们定义一个数列的积为该数列所有元素的乘积，要求你求出所有可能的数列的积的和 </span><span style="font-family:Microsoft YaHei;">mod 1000000007</span><span style="font-family:Microsoft YaHei;">的值，是不是很简单呢？呵呵！</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<h3>
<span style="color:#4F81BD;font-size:12pt;font-family:Microsoft YaHei;">输入</span><span style="color:#4F81BD;font-size:12pt;font-family:Cambria;"></span> 
</h3>
<p style="text-indent:21.7500pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span style="font-family:Microsoft YaHei;">第一行三个整数</span><span style="font-family:Microsoft YaHei;">n,m,k</span><span style="font-family:Microsoft YaHei;">分别表示数列元素的取值范围，数列元素个数，以及已知的限制条数。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span style="font-family:Microsoft YaHei;">接下来</span><span style="font-family:Microsoft YaHei;">k</span><span style="font-family:Microsoft YaHei;">行，每行两个正整数</span><span style="font-family:Microsoft YaHei;">x,y</span><span style="font-family:Microsoft YaHei;">表示</span><span style="font-family:Microsoft YaHei;">A[x]</span><span style="font-family:Microsoft YaHei;">的值不能是</span><span style="font-family:Microsoft YaHei;">y</span><span style="font-family:Microsoft YaHei;">。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<h3>
<span style="color:#4F81BD;font-size:12pt;font-family:Microsoft YaHei;">输出</span><span style="color:#4F81BD;font-size:12pt;font-family:Cambria;"></span> 
</h3>
<p style="text-indent:21.7500pt;">
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">一行一个整数表示所有可能的数列的积的和对</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span style="font-family:Microsoft YaHei;">1000000007</span><span style="font-family:Microsoft YaHei;">取模</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span style="font-family:Microsoft YaHei;">后的结果。如果一个合法的数列都没有，答案输出</span><span style="font-family:Microsoft YaHei;">0</span><span style="font-family:Microsoft YaHei;">。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<h3>
<span style="color:#4F81BD;font-size:12pt;font-family:Microsoft YaHei;">样例输入</span><span style="color:#4F81BD;font-size:12pt;font-family:Cambria;"></span> 
</h3>
<p>
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">3 4 5</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">1 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">1 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">2 2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">2 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">4 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<h3>
<span style="color:#4F81BD;font-size:12pt;font-family:Microsoft YaHei;">样例输出</span><span style="color:#4F81BD;font-size:12pt;font-family:Cambria;"></span> 
</h3>
<p>
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">90</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<h3>
<span style="color:#4F81BD;font-size:12pt;font-family:Microsoft YaHei;">样例解释</span><span style="color:#4F81BD;font-size:12pt;font-family:宋体;"></span> 
</h3>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span style="font-family:Microsoft YaHei;">A[1]</span><span style="font-family:Microsoft YaHei;">不能取</span><span style="font-family:Microsoft YaHei;">1</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span style="font-family:Microsoft YaHei;">A[2]</span><span style="font-family:Microsoft YaHei;">不能去</span><span style="font-family:Microsoft YaHei;">2</span><span style="font-family:Microsoft YaHei;">、</span><span style="font-family:Microsoft YaHei;">3</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span style="font-family:Microsoft YaHei;">A[4]</span><span style="font-family:Microsoft YaHei;">不能取</span><span style="font-family:Microsoft YaHei;">3</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span style="font-family:Microsoft YaHei;">所以可能的数列有以下</span><span style="font-family:Microsoft YaHei;">12</span><span style="font-family:Microsoft YaHei;">种</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">数列      积</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">2 1 1 1     2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">2 1 1 2     4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">2 1 2 1     4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">2 1 2 2     8</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">2 1 3 1     6</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">2 1 3 2     12</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">3 1 1 1     3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">3 1 1 2     6</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">3 1 2 1     6</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">3 1 2 2     12</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">3 1 3 1     9</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5pt;font-family:Microsoft YaHei;">3 1 3 2     18</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<h3>
<span style="color:#4F81BD;font-size:12pt;font-family:Microsoft YaHei;">数据范围</span><span style="color:#4F81BD;font-size:12pt;font-family:宋体;"></span> 
</h3>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span style="font-family:Microsoft YaHei;">30%</span><span style="font-family:Microsoft YaHei;">的数据</span><span style="font-family:Microsoft YaHei;">n&lt;=4,m&lt;=10,k&lt;=10</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span style="font-family:Microsoft YaHei;">另有</span><span style="font-family:Microsoft YaHei;">20%</span><span style="font-family:Microsoft YaHei;">的数据</span><span style="font-family:Microsoft YaHei;">k=0</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span style="font-family:Microsoft YaHei;">70%</span><span style="font-family:Microsoft YaHei;">的数据</span><span style="font-family:Microsoft YaHei;">n&lt;=1000,m&lt;=1000,k&lt;=1000</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span style="font-family:Microsoft YaHei;">100%</span><span style="font-family:Microsoft YaHei;">的数据 </span><span style="font-family:Microsoft YaHei;">n&lt;=10</span></span><span style="font-size:10.5pt;font-family:Microsoft YaHei;vertical-align:super;">9</span><span style="font-size:10.5pt;font-family:Microsoft YaHei;">,m&lt;=10</span><span style="font-size:10.5pt;font-family:Microsoft YaHei;vertical-align:super;">9</span><span style="font-size:10.5pt;font-family:Microsoft YaHei;">,k&lt;=10</span><span style="font-size:10.5pt;font-family:Microsoft YaHei;vertical-align:super;">5</span><span style="font-size:10.5pt;font-family:Microsoft YaHei;">,1&lt;=y&lt;=n,1&lt;=x&lt;=m</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
