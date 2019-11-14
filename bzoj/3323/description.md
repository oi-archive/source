
# Description

<div class="content"><div align="left"><span style="font-size: 12pt">某天，mzry1992 一边思考着一个项目问题一边在高速公路上骑着摩托车。一个光头踢了他一脚，摩托车损坏，而他也被送进校医院打吊针。现在该项目的截止日期将近，他不得不请你来帮助他完成这个项目。该项目的目的是维护一个动态的关于x 的无穷多项式F(x) = a0 * x^0 + a1 * x^1 + a2 * x^2 + ... ，这个多项式初始时对于所有i有ai = 0。</span></div>
<div align="left"><span style="font-size: 12pt">操作者可以进行四种操作：</span></div>
<div align="left"><span style="font-size: 12pt">1. </span><span style="font-size: 12pt">将x^L 到x^R 这些项的系数乘上某个定值v</span></div>
<div align="left"><span style="font-size: 12pt">2. </span><span style="font-size: 12pt">将x^L 到x^R 这些项的系数加上某个定值v</span></div>
<div align="left"> </div>
<div align="left"><span style="font-size: 12pt">3. </span><span style="font-size: 12pt">将x^L 到x^R 这些项乘上x变量</span></div>
<div align="left"><span style="font-size: 12pt">4. </span><span style="font-size: 12pt">将某个定值v代入多项式F(x)，并输出代入后多项式的值，之后多项式还原为代入前的状况</span></div>
<div align="left"><span style="font-size: 12pt">经过观察，项目组发现使用者的操作集中在前三种，第四种操作不会出现超过10次。mzry1992 负责这个项目的核心代码，你能帮他实现么。</span></div></div>

# Input

<div class="content"><div align="left"><span style="font-size: 12pt">输入的第一行有一个整数n 代表操作的个数。<br/>
接下来n 行，每行一个操作，格式如下：<br/>
mul L R v 代表第一种操作<br/>
add L R v 代表第二种操作<br/>
mulx L R 代表第三种操作<br/>
query v 代表第四种操作<br/>
<br/>
对于30% 的数据：N &lt;= 5000，0 &lt;= L &lt;= R &lt;= 5000，0 &lt;= v &lt;= 10^9<br/>
另有20% 的数据：N &lt;= 10^5，0 &lt;= L &lt;= R &lt;= 10^5，0 &lt;= v &lt;= 10^9，没有mulx 操作<br/>
剩下的50% 的数据：N &lt;= 10^5，0 &lt;= L &lt;= R &lt;= 10^5，0 &lt;= v &lt;= 10^9 </span></div></div>

# Output

<div class="content"><div align="left"><span style="font-size: 12pt">对于每个query 操作，输出对应的答案，结果可能较大，需要模上20130426。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
add 0 1 7<br/>
query 1<br/>
mul 0 1 7<br/>
query 2<br/>
mulx 0 1<br/>
query 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">14<br/>
147<br/>
588<br/>
Hint<br/>
操作一之后，多项式为F(x) = 7x + 7。<br/>
操作三之后，多项式为F(x) = 49x + 49。<br/>
操作五之后，多项式为F(x) = 49x^2 + 49x。 </span></div>

# Hint

<div class="content"><p></p><p>应上传者要求，此系列试题不公开,如有异议，本站将删除之。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

