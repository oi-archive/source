<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">为了庆祝元旦，J市决定举办全市小学足球联赛。各学校积极响应，共有N支球队报名参加，爱好足球的小W也参加了。为了活动的开展和不影响学生学习，只能安排K场比赛，每支球队最多参加两场比赛，至少参加零场比赛。因球队水平不同，每支球队都拥有一个和其他球队不同的水平等级（用一个正整数来表示）。在比赛中，等级高的球队必须作为客场，等级低的球队必须作为主场。每个球队最多只能做一次主场和一次客场。为了增加比赛的观赏度，观众希望K场比赛中球队水平差距的总和最小。比如有7支球队，他们的等级分别是30、17、26、41、19、38、18，要进行3场比赛。那么最好安排是球队2  vs 球队7, 球队7 vs 球队5 ,球队6 vs 球队4，此时等级差的总和等于(18-17) + (19-18) + (41-38) = 5达到最小。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">第一行两个正整数N ，K。 </span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">接下来有N 行，第i行表示第i 支球队的等级。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px; background-color: rgb(255, 255, 255);">共一行，输出最小的等级差的总和。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">7 3
30
17
26
41
19
38
18</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">对于20%的数据，1≤N≤300  <br style=""></p><p><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"></p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><br style="">对于80%的数据，1≤N≤5000<br style=""></p><p><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"></p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><br style="">对于100%的数据，1≤N≤10000  <br style=""></p><p><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">保证所有输入数据中等级的值小于32000，1 ≤K≤ N-1</span></p><p><br></p>
</div>
</div>