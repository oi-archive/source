<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>所谓角谷猜想，即给定一个正整数 n，对 n 反复进行下列两种变换：</span><br><span>1）如果n是偶数，就除以2；</span><br><span>2）如果n是奇数，就乘以3加1。</span><br><span>最后的结果总是1。</span><br><br><span>我们把从 n 变换到 1 所需要进行的变换次数称做 n 的变换长度，如数字 7 的变换为：</span><br><br><span>7-22-11-34-17-52-26-13-40-20-10-5-16-8-4-2-1</span><br><br><span>共进行了 16 次变换，因而 7 的变换长度为 16。</span></p>
<p><span><span>Wish 现在对一个给定区间内的最长变换长度比较感兴趣，但是手算起来计算量太大，于是他又找到了参加信息学竞赛的你，你可以帮助他吗？</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>每个测试点包含多组数据，第一行一个数 t，表示数据个数。</span><br><span>第二行至第 t+1 行，每行两个数 a、b，表示求 a 和 b 之间数（包含 a、b）的最长变换长度。</span><br><br><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>输出格式</span><br /><span>t 行，每行输出对应输入数据的各个区间的最长变换长度。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2<br>1 7<br>9 20</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>16<br>20</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据范围<br>1 &lt;= t &lt;= 100<br>1 &lt;= a, b &lt;= 10^8<br>区间长度不超过 10^5</p>
</div>
</div>