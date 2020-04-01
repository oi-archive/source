
# Description

<div class="content"><div><span style="font-size: medium">你需要为你的宠物制定一个成长计划，使得宠物得到良好的发展。</span></div>
<div><span style="font-size: medium">宠物有三项属性：体力<i>H</i>，逻辑<i>P</i>，感受<i>F</i>。</span></div>
<div><span style="font-size: medium">这三项分别决定了宠物的：</span></div>
<div><span style="font-size: medium">健康与强壮程度，逻辑判断与理科思维能力，文采与艺术素养。</span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">初始时3项属性均为0。(中途可为负数)</span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">在接下来的<i>M</i>天里，第<i>i</i>天有温度<i>T</i>[<i>i</i>]，湿度<i>W</i>[<i>i</i>]。</span></div>
<div><span style="font-size: medium">每天你可以选择让宠物：（以下除法均为整数除法）</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -18pt"><span style="font-size: medium">1.<span style="font: 7pt &#39;Times New Roman&#39;">      </span>在家玩</span></div>
<div style="margin: 0cm 0cm 0pt 39pt"><span style="font-size: medium">H’ = H*4/5 + 3 + F/6 + P/6</span></div>
<div style="margin: 0cm 0cm 0pt 39pt"><span style="font-size: medium">P’ = P - 1</span></div>
<div style="margin: 0cm 0cm 0pt 39pt"><span style="font-size: medium">F’ = F - 1</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -18pt"><span style="font-size: medium">2.<span style="font: 7pt &#39;Times New Roman&#39;">      </span>体育课</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: 21pt"><span style="font-size: medium">H’ = H + T[i] – W[i]</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: 21pt"><span style="font-size: medium">P’ = P – T[i]/4</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: 21pt"><span style="font-size: medium">F’ = F + W[i]/6</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -18pt"><span style="font-size: medium">3.<span style="font: 7pt &#39;Times New Roman&#39;">      </span>科学课</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: 21pt"><span style="font-size: medium">H’ = H – |W[i]| - F/4</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: 21pt"><span style="font-size: medium">P’ = P + 3 + T[i]/4</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: 21pt"><span style="font-size: medium">F’ = F – 1 + W[i]/9</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -18pt"><span style="font-size: medium">4.<span style="font: 7pt &#39;Times New Roman&#39;">      </span>艺术课</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: 21pt"><span style="font-size: medium">H’ = H – |T[i]| - P/4</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: 21pt"><span style="font-size: medium">P’ = P – 1 + T[i]/6</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: 21pt"><span style="font-size: medium">F’ = F + 2 + W[i]/3</span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">每天活动结束后，(<i>H</i>’, <i>P</i>’, <i>F</i>’) 将会成为宠物的状态。</span></div>
<div><span style="font-size: medium">宠物的培养是需要侧重点的。</span></div>
<div><span style="font-size: medium">一个培养目标可以用三元组(<i>x</i>,<i>y</i>,<i>z</i>)来表示，其中<i>x</i>,<i>y</i>,<i>z</i>均为非负整数。</span></div>
<div><span style="font-size: medium">即要求<i>H</i>*<i>x</i>+<i>P</i>*<i>y</i>+<i>F</i>*<i>z</i>最大。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行输入天数<i>M</i>，询问数<i>Q</i></span></div>
<div><span style="font-size: medium">接下来一行为<i>T</i>[1..<i>M</i>]</span></div>
<div><span style="font-size: medium">接下来一行为<i>W</i>[1..<i>M</i>]</span></div>
<div><span style="font-size: medium">接下来<i>Q</i>行，每行是三个非负整数<i>x y z</i>表示一次询问</span></div></div>

# Output

<div class="content"><div style="margin: 13pt 0cm"> </div>
<div><span style="font-size: medium">对于<i>Q</i>次询问，每次输出一行，包括一个整数：</span></div>
<div><span style="font-size: medium">即在最优成长计划下<i>H</i>*<i>x</i>+<i>P</i>*<i>y</i>+<i>F</i>*<i>z</i>的最大值。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
10 10 -10 -10 0<br/>
10 -10 10 -10 0<br/>
1 0 0<br/>
0 1 0<br/>
0 0 1<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">22<br/>
17<br/>
10<br/>
【样例说明】<br/>
对于第一个询问：在家玩,体育课,在家玩,在家玩,在家玩<br/>
 <br/>
【范围】<br/>
100% 1 ≤ M ≤ 50; Q ≤ 600;     T[i],W[i],x,y,z的绝对值 ≤ 20</span></div>

# Hint

<div class="content"><p></p><p> 题解:<a href="/JudgeOnline/upload/201604/sol(1).txt">JudgeOnline/upload/201604/sol(1).txt</a></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

