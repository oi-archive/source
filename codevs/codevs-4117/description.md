<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"> <span style="">随着高斯奥特曼的进化，出现了越来越多的新形态。心态之间的变形不畅严重影响了打怪兽的顺利。这时，科学家发明了形态变化机器人，正好可以解决这一难题。</span></p><p>高斯有M种，每种机器人能完成K个形态之间的语言翻译。问，利用这些机器人，能否实现1种群和N种群的形态变化。若可以，找到变化过程至少需要变多少次形态。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"> <span style="">第一行三个整数</span><span style="">N</span><span style="">，</span><span style="">K</span><span style="">和</span><span style="">M</span><span style="">，分别表示语言数，每个机器人能变化的形态数，机器人的数量。</span></p><p>接下来M行，每行K个整数。表示每个机器人可以变化的形态编号（编号从1到N）。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &#39;Times New Roman&#39;; font-size: 20px; line-height: 24px; text-indent: 28px; background-color: rgb(228, 240, 248);">输出最少转换形态的次数。如果无法完成翻译，输出-1。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: monospace;">9 3 5
1 2 3
1 4 5
3 6 7
5 6 7
6 8 9</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>&lt;font color="#333333" face="monospace"&gt;<span style="">4</span>&lt;/font&gt;</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>40%的数据N&lt;=100，1&lt;=K&lt;=20，M&lt;=40。</p><p><br style="font-family: 'Times New Roman';"></p><p>100%的数据1&lt;=N&lt;=100000，1&lt;=K&lt;=1000，1&lt;=M&lt;=1000。</p><p><br></p><p><span style="font-family: 'Times New Roman';">1-3-6-9或者1-5-6-9</span></p><p><br></p>
</div>
</div>