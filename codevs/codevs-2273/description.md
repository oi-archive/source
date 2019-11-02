<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>扬帆远洋为了打败牧师妹酱，不惜一切代价通过各种各样的手段得到了传奇道具“れいじまいご”来释放能量使得全球充满扬帆远洋的威严气场和能量场。但是，“れいじまいご”释放的能量只能在某个很小的区域中存在，为了使得效果可以逸散的全球，扬帆远洋决定效仿心灵操控者——尤里，在世界各地修建了N个“れいじまいご·ベクトル変換”使得其能量场可以在全世界张开。</p>
<p>根据计算机的计算结果，这N个地点大多都是非常偏僻的城镇。因此，之间的道路并不定都是畅通的。这些地区之间通过R条道路连接，为了使得之间前往的方便，扬帆远洋TEL还帮助扬帆远洋产生了P个空间隧道，扬帆远洋称之为“時間と空間の扉”。每条道路i或者“時間と空間の扉”i连接地区A<sub>i</sub>到B<sub>i</sub>，花费为C<sub>i</sub>。道路是双向的，可以从A<sub>i</sub>到B<sub>i</sub>，也可以从B<sub>i</sub>到A<sub>i</sub>，花费都是C<sub>i</sub>。然而“時間と空間の扉”与之不同，只可以从A<sub>i</sub>到B<sub>i</sub>。事实上，由于牧师妹酱的墨镜党(看看我的头像就知道了)的不断干扰使得链接非常不稳定。牧师妹酱的墨镜党的干扰如下：如果有一条“時間と空間の扉”可以从A<sub>i</sub>到B<sub>i</sub>，那么保证不可能通过一些道路和“時間と空間の扉”从B<sub>i</sub>回到A<sub>i</sub>。所以有些地区可能无法到达，需要扬帆远洋对自己进行Teleport才可以。</p>
<p>扬帆远洋现在呆在S城镇，由于他需要把每个“れいじまいご·ベクトル変換”的装置调整完毕，因此扬帆远洋写了一个程序计算从S出发，对于每个地区而言计算出了最小的花费，如果不可能，则输出“Need Teleport To Repair”。最后输出，一共有多少个地方是需要用Teleport的。</p>
<p><span>但是由于墨镜党不断的捣乱，这个程序现在无法工作，请你复述出来这个程序。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第1行有四个空格隔开的整数T、R、P和S。</span><br><span>第2至R+1行每行有3个空格隔开的正整数，表示一条道路的Ai、Bi和Ci。</span><br><span>第R+2至R+P+1行每行有3个空格隔开的正整数，表示一条“時間と空間の扉”的Ai、Bi和Ci。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>第1到T行每行输出的是从S到达地区i的最小花费，如果不存在输出&ldquo;Need&nbsp;Teleport&nbsp;To&nbsp;Repair&rdquo;（没有引号）。</span><br /><span>最后一行为一共有多少个地方是需要用Teleport的。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>6 3 3 4</span><br><span>1 2 5</span><br><span>3 4 5</span><br><span>5 6 10</span><br><span>3 5 -100</span><br><span>4 6 -100</span><br><span>1 3 -10</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>Need Teleport To Repair</span><br><span>Need Teleport To Repair</span><br><span>5</span><br><span>0</span><br><span>-95</span><br><span>-100</span><br><span>2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>1≤T≤25000，1≤R≤50000，1≤P≤50000，1≤S≤T</span><br><span>1≤Ai≤T，1≤Bi≤T，-10000≤Ci≤10000（对于“時間と空間の扉”来说花费才可能是负数）</span></p>
<p><span>牧师妹酱, 扬帆远洋, 扬帆远洋TEL均为真实存在的人物.</span></p>
<p><span>故事取材于大B吧奇幻史, 可以查看Bilibili上的一个视频:&lt;a href="http://www.bilibili.tv/video/av441478/"&gt;http://www.bilibili.tv/video/av441478/&lt;/a&gt;</span></p>
<p><span>题目修改自USACO</span></p>
</div>
</div>