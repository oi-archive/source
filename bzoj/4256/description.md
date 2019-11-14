
# Description

<div class="content"><div>经典的推箱子是一个来自日本的古老游戏，目的是在训练你的逻辑思考能力。在一个狭</div>
<div>小的仓库中，要求把木箱放到指定的位置，稍不小心就会出现箱子无法移动或者通道被堵住</div>
<div>的情况，所以需要巧妙的利用有限的空间和通道，合理安排移动的次序和位置，才能顺利的</div>
<div>完成任务。</div>
<div><img src="/source/bzoj/4256/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwOS9hYS5QTkc=.PNG" width="354" height="272" alt=""/></div>
<div></div>
<div>这个游戏有一个相对简单的版本， 就是只有一个木箱， 要将其推到一个确定的目标位置。</div>
<div>举个例子：</div>
<div>..#@.</div>
<div>.X.O.</div>
<div>##..#</div>
<div>其中“.”表示没有障碍的格子，“#”表示有障碍的格子，“X”表示目标位置（注意这个格</div>
<div>子是没有障碍的） ，“O”是箱子（对于人来说箱子存在的格子是不能越过的） ，“@”是人的位</div>
<div>置。注意上面这个情况是可以将箱子推到目标点去的，因为人只要向右一格，向下一格，然</div>
<div>后推着箱子向左走两格，就完成了任务。</div>
<div>而下面这个例子是无解的：</div>
<div>..#..</div>
<div>.X.O.</div>
<div>##.@#</div>
<div>现在我们的主人公想知道，对于一个给定的地图（与上面两个不同的是没有了箱子和人</div>
<div>的初始位置） ，有多少种箱子和人的初始摆放方法（箱子的初始位置和人的初始位置和目标</div>
<div>位置必须两两不同）能够使得箱子能被人成功地推到目标位置。</div>
<p></p></div>

# Input

<div class="content"><div>第一行为两个正整数 n,m。表示整个地图有 n行 m 列。N,M均小于等于1000</div>
<div>接下来是一个 n行 m 列的地图，用 n个长为 m 的字符串表示。</div>
<p></p></div>

# Output

<div class="content"><div>一行，包含一个整数，为方案总数。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 5<br/>
..#..<br/>
.X...<br/>
##..#<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">9</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=JOI2012">JOI2012</a></p></div>

