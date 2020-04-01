
# Description

<div class="content"><div>小Z经营一家加油店。小Z加油的方式非常奇怪。他有一排瓶子，每个瓶子有一个容量vi。每次别人来加油，他会让</div>
<div>别人选连续一段的瓶子。他可以用这些瓶子装汽油，但他只有三种操作：</div>
<div>1.把一个瓶子完全加满；</div>
<div>2.把一个瓶子完全倒空；</div>
<div>3.把一个瓶子里的汽油倒进另一个瓶子，直到倒出瓶子空了或者倒进的瓶子满了。</div>
<div>当然，为了回馈用户，小Z会时不时选择连续一段瓶子，给每个瓶子容积都增加x。</div>
<div>为了尽可能给更多的人加油，每次客户来加油他都想知道他能够倒腾出的汽油量最少是多少？</div>
<div>当然他不会一点汽油都不给客户。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包括两个数字：瓶子数n，事件数m。</div>
<div>第二行包含n个整数，表示每个瓶子的容量vi。</div>
<div>接下来m行，每行先有三个整数fi li ri。</div>
<div>若fi=1表示询问li到ri他最少能倒腾出的汽油量最少是多少？</div>
<div>若fi=2 再读入一个整数x。表示他将li到ri的瓶子容量都增加了x。</div>
<div>1 &lt;= n,m &lt;= 10^5 , 1&lt;=li&lt;=ri&lt;=n , 1&lt;=初始容量,增加的容量&lt;=1000</div>
<p></p></div>

# Output

<div class="content"><div>对于每个询问输出对应的答案</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
2 3 4<br/>
1 1 3<br/>
2 2 2 1<br/>
1 1 3<br/>
1 2 3	</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
4</span></div>

# Hint

<div class="content"><p></p><p> 有可能出现L&gt;R,<span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.549334526062px;">读入的p不只有0和1，把所有非1操作当成2才能AC</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

