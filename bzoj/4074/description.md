
# Description

<div class="content"><p> <span style="text-indent: 21pt; font-family: 宋体;">作为刚刚从蓝翔毕业的优秀学子，你成为了一名吊车司机。在施工作业中，你必须时刻保证吊车的平衡，如果吊起的重物太重或太轻，你的吊车就会因失去平衡而倒下。现在，</span><span lang="EN-US" style="text-indent: 21pt;">ACM(The Association of Crane Manufacturers)</span><span style="text-indent: 21pt; font-family: 宋体;">公司准备请既会玩吊车，又能码代码的你来设计一款吊车平衡计算软件。为了方便起见，我们将吊车视作一个密度均匀的</span><i style="text-indent: 21pt;"><span lang="EN-US">n</span></i><span style="text-indent: 21pt; font-family: 宋体;">边形，其顶点依次标号为</span><span lang="EN-US" style="text-indent: 21pt;">1...<i>n</i></span><span style="text-indent: 21pt; font-family: 宋体;">，挂载重物的吊钩就是</span><span lang="EN-US" style="text-indent: 21pt;">1</span><span style="text-indent: 21pt; font-family: 宋体;">号点。现在要在<b><u>编号为</u></b></span><b style="text-indent: 21pt;"><u><span lang="EN-US">1</span></u></b><span style="text-indent: 21pt; font-family: 宋体;">的端点放上一个<b><u>大小忽略不计</u></b>的重物，问放的重物的重量在什么区间内，才能使这个多边形保持平衡</span><span lang="EN-US" style="text-indent: 21pt;">(</span><span style="text-indent: 21pt; font-family: 宋体;">不会往左或往右翻</span><span lang="EN-US" style="text-indent: 21pt;">)</span><span style="text-indent: 21pt; font-family: 宋体;">。<br/>
</span></p>
<p class="MsoNormal"></p></div>

# Input

<div class="content"><p><span style="font-family: 宋体;">输入数据的第一行是一个整数</span><i><span lang="EN-US">n</span></i><span style="font-family: 宋体;">，代表这个多边形的边数。<span style="font-family: 宋体;">之后</span><i><span lang="EN-US">n</span></i><span style="font-family: 宋体;">行，每行两个整数，依次代表这个多边形的第</span><span lang="EN-US">1</span><span style="font-family: 宋体;">号点、第</span><span lang="EN-US">2</span><span style="font-family: 宋体;">号点</span><span lang="EN-US">......</span><span style="font-family: 宋体;">第</span><i><span lang="EN-US">n</span></i><span style="font-family: 宋体;">号点的坐标</span><br/>
</span></p></div>

# Output

<div class="content"><p> <span style="font-family: 宋体;">输出只有一行，代表吊起的重物质量的闭区间</span><span lang="EN-US">[<i>a,b</i>]</span><span style="font-family: 宋体;">，注意<b><u>左端点向下取整，右端点向上取整</u></b>。例如，如果区间为</span><span lang="EN-US">[1.5,13.3]</span><span style="font-family: 宋体;">，则<b><u>输出</u></b></span><b><u><span lang="EN-US">1 .. 14</span></u></b><span style="font-family: 宋体;">。若区间为</span><span lang="EN-US">[<i>a</i>,+</span><span style="font-family: 宋体;">∞</span><span lang="EN-US">)</span><span style="font-family: 宋体;">，则<b><u>输出</u></b></span><b><i><u><span lang="EN-US">a</span></u></i><u><span lang="EN-US"> .. inf</span></u></b><span style="font-family: 宋体;">。如果吊车不能承载任何质量的重物，则<b><u>输出</u></b></span><b><u><span lang="EN-US">unstable</span></u></b><span style="font-family: 宋体;">。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
50 50<br/>
0 50<br/>
0 0<br/>
30 0<br/>
30 30<br/>
40 40<br/>
50 40<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 .. 1017<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢qpswwww提供译文">鸣谢qpswwww提供译文</a></p></div>

