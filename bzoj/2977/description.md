
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">在比特山,有一个风景胜地.它以纵横交错的滑雪轨道而出名. 而它们中的某些地区位于山顶或者很难到达的地方.因此人们使用滑雪电梯来帮助人们到达某些滑道.每个滑雪轨道和滑雪电梯的开始和结束都在一个空旷地带.而滑雪轨道都不会交叉,因此他们可以顺利的穿越. 而滑雪轨道和滑雪电梯都有一条或两条路线. </span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">使用滑雪电梯必须要使用一种独特的磁卡,这个卡可以用现金购买.每个卡都含有一定数目的点数.使用滑雪电梯时必须付相应数目的点数.但留在卡上的点数并不能兑换成现金.</span></div>
<div><span style="font-size: medium">今天是比特风景区的最后一天.他的磁卡上还拥有一定数目的点数.他想尽最大可能的消费,以使得在离开比特山时,卡上剩余的点数最少. 你可以假定卡上的点数足以使他返回. </span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div> </div>
<div style="text-indent: 21pt"><span style="font-size: medium">第一行有两个整数<i>n</i> 和 <i>n</i>&#39;, 1 &lt;= <i>n</i>&#39; &lt; <i>n</i> &lt;= 1000, 他们之间用一个空格分开,他们分别表示空旷地带的数量和能直接返回的空旷地带数量(编号从1 到 <i>n</i>&#39; ). </span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">在第二行有一个整整数<i>k</i>, 1 &lt;= <i>k</i> &lt;= 5000, 表示所有的滑雪轨道的数量. 接下来的k行,每行有由空格分开的两个整数, 1 &lt;= <i>p</i><sub>1</sub> &lt;&gt; <i>p</i><sub>2</sub> &lt; <i>n</i>. 分别表示开始和结束空旷地带编号.如果有上下两个轨道,则输出有两行(例如 &#34;<i>p</i><sub>1</sub> <i>p</i><sub>2</sub>&#34; 和 &#34;<i>p</i><sub>2</sub> <i>p</i><sub>1</sub>&#34;,并不一定按顺序). </span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">在第<i>k</i>+3 行有一个正整数<i>m</i>, 1 &lt;= <i>m</i> &lt;= 300, 表示滑雪电梯的数量,接下来的<i>m</i> 行描述了每个滑雪电梯,每行有三个正整数<i>q</i><sub>1</sub>, <i>q</i><sub>2</sub> 和 <i>r</i>; 分别表示起始和结束空旷地带编号和乘该电梯需要消费的点数1 &lt;= <i>q</i><sub>1</sub> &lt;&gt; <i>q</i><sub>2</sub> &lt;= <i>n</i>, 1 &lt;= <i>r</i> &lt;= 1000. 如果有上下两部电梯,则表示为&#34;<i>q</i><sub>1</sub> <i>q</i><sub>2</sub> <i>r</i><sub>1</sub>&#34; 和&#34;<i>q</i><sub>2</sub> <i>q</i><sub>1</sub> <i>r</i><sub>2</sub>&#34;,并且上下的价格可能也不同. </span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">最后一行为两个正整数 <i>b</i> 和 <i>s</i>, 1 &lt;= <i>b</i> &lt;= <i>n</i>, 1 &lt;= <i>s</i> &lt;= 2000. b是当前他所处的空旷地带编号,s是他磁卡上的点数. </span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div> </div>
<div style="text-indent: 21pt"><span style="font-size: medium"><tt>第一行写入一个整数</tt>.为返回后卡上剩余的最少点数</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 2<br/>
6<br/>
3 2<br/>
3 5<br/>
1 5<br/>
3 4<br/>
1 2<br/>
4 3<br/>
4<br/>
3 1 1<br/>
4 3 5<br/>
5 2 2<br/>
3 4 5<br/>
4 9<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

