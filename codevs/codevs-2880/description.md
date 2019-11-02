<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>长跑运动员的体能分配是很有讲究的。如果一开始跑得太快，有可能导致后续跑不快甚至不能跑到终点；如果一开始跑得太慢就有可能在后续无法追赶别人。大致比较理想的体能分配方案是一开始根据自己的体能情况每圈都匀速跑，然后在最后一圈用尽全力冲刺。</p>
<p>要求编一个程序判断某运动员的体能分配方案是否合理。</p>
<p>输入第一行为一个正整数n，表示运动员一共需要跑的圈数。接下来一行共包含n个正整数，依次表示该运动员跑第一圈、第二圈、第三圈….第n圈各自所需的时间，单位为秒。</p>
<p>输出文件包含2行。第一行为一个正整数，表示运动员跑完全程所需的总时间（单位：秒）。第二行包含一个字符串，表示该运动员体能分配方案的合理程度。如果体能分配非常合理则输出“Good”，如果一般合理则输出“Pass”，如果不合理则输出“Bad”。</p>
<p>体能分配合理性判别标准如下：</p>
<p>（1）前n-1圈每圈所需时间和跑前n-1圈平均时间差的绝对值没有超过跑前n-1圈平均时间的10%（用小数表示就是0.1）；</p>
<p>（2）跑最后一圈是跑所有圈中最快的（可以和前n-1圈中跑得最快一圈一样快）。</p>
<p>    如果上述2个条件都满足则说明体能分配“非常合理”，如果第（1）条和第（2）条中只满足一条则说明体能分配“一般合理”，如果第（1）、（2）条都不满足则说明体能分配“不合理”。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行为一个正整数n，表示运动员一共需要跑的圈数。接下来一行共包含n个正整数，依次表示该运动员跑第一圈、第二圈、第三圈….第n圈各自所需的时间，单位为秒。</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件包含2行。第一行为一个正整数，表示运动员跑完全程所需的总时间（单位：秒）。第二行包含一个字符串，表示该运动员体能分配方案的合理程度。如果体能分配非常合理则输出&ldquo;Good&rdquo;，如果一般合理则输出&ldquo;Pass&rdquo;，如果不合理则输出&ldquo;Bad&rdquo;。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>50 51 55 53</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Pass</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>3&lt;=n&lt;=30，每圈跑步所需的时间（秒）都小于100.</p>
</div>
</div>