<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>USACO 2015 December Contest, Platinum<br>Problem 3. Counting Haybales</p><p><br></p><p>农夫约翰打算重修他的农场。他有 N 块土地，连续排列成一行，标号为 1…N。在每块土地上有任意数量的草堆。他可以发出三种指令：</p><p>1) 对一个连续区间的土地，每块土地增加相同数量的草堆。</p><p>2) 对一个连续区间的土地，输出其中最少的草堆数量。</p><p>3) 对一个连续区间的土地，输出草堆数量总数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个正整数，N (1≤N≤200,000) 和 Q (1≤Q≤100,000)。</p><p>下一行是N个非负整数，最大100,000，表示每块土地上有多少个草堆。</p><p>以下Q行，每行一单个大写字母开头(M，P或S)，空格后跟随两个正整数 A 和 B (1≤A≤B≤N), 或者三个正整数 A, B, 和 C (1≤A≤B≤N; 1≤C≤100,000)。当且仅当第一个字母是 P 时，是三个正整数。<br>当该字母是M，输出区间A…B的最小草堆数。</p><p>当该字母是P，在区间A…B，每块土地增加C堆草。</p><p>当该字母是M，输出区间A…B的草堆数之和。<br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>每行一个数字，用于响应&#39;M&#39; 或 &#39;S&#39; 命令。</p><p><br/>
</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 5<br>3 1 2 4<br>M 3 4<br>S 1 3<br>P 2 3 1<br>M 3 4<br>S 1 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2<br>6<br>3<br>8<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1≤N≤200,000</p><p>1≤Q≤100,000<br></p><p>1≤A≤B≤N; 1≤C≤100,000</p>
</div>
</div>