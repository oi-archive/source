
# Description

<div class="content"><div>我们讲一个悲伤的故事。</div>
<div>从前有一个贫穷的樵夫在河边砍柴。</div>
<div>这时候河里出现了一个水神，夺过了他的斧头，说：</div>
<div>“这把斧头，是不是你的？”</div>
<div>樵夫一看：“是啊是啊！”</div>
<div>水神把斧头扔在一边，又拿起一个东西问：</div>
<div>“这把斧头，是不是你的？”</div>
<div>樵夫看不清楚，但又怕真的是自己的斧头，只好又答：“是啊是啊！”</div>
<div>水神又把手上的东西扔在一边，拿起第三个东西问：</div>
<div>“这把斧头，是不是你的？”</div>
<div>樵夫还是看不清楚，但是他觉得再这样下去他就没法砍柴了。</div>
<div>于是他又一次答：“是啊是啊！真的是！”</div>
<div>水神看着他，哈哈大笑道：</div>
<div>“你看看你现在的样子，真是丑陋！”</div>
<div>之后就消失了。</div>
<div></div>
<div>樵夫觉得很坑爹，他今天不仅没有砍到柴，还丢了一把斧头给那个水神。</div>
<div>于是他准备回家换一把斧头。</div>
<div>回家之后他才发现真正坑爹的事情才刚开始。</div>
<div>水神拿着的的确是他的斧头。</div>
<div>但是不一定是他拿出去的那把，还有可能是水神不知道怎么偷偷从他家里拿走的。</div>
<div>换句话说，水神可能拿走了他的一把，两把或者三把斧头。</div>
<div></div>
<div>樵夫觉得今天真是倒霉透了，但不管怎么样日子还得过。</div>
<div>他想统计他的损失。</div>
<div>樵夫的每一把斧头都有一个价值，不同斧头的价值不同。总损失就是丢掉的斧头价值和。</div>
<div>他想对于每个可能的总损失，计算有几种可能的方案。</div>
<div>注意：如果水神拿走了两把斧头a和b，(a,b)和(b,a)视为一种方案。拿走三把斧头时，(a,b,c),(b,c,a),(c,a,b),(c,b,a),(b,a,c),(a,c,b)视为一种方案。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行是整数N，表示有N把斧头。</div>
<div>接下来n行升序输入N个数字Ai，表示每把斧头的价值。</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>若干行，按升序对于所有可能的总损失输出一行x y，x为损失值，y为方案数。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
4<br/>
5<br/>
6<br/>
7<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4 1<br/>
5 1<br/>
6 1<br/>
7 1<br/>
9 1<br/>
10 1<br/>
11 2<br/>
12 1<br/>
13 1<br/>
15 1<br/>
16 1<br/>
17 1<br/>
18 1<br/>
样例解释<br/>
11有两种方案是4+7和5+6，其他损失值都有唯一方案，例如4=4,5=5,10=4+6,18=5+6+7.</span></div>

# Hint

<div class="content"><p></p><p>所有数据满足：Ai&lt;=40000</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

