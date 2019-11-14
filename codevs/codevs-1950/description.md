<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    小 W 喜欢读书，尤其喜欢读《约翰克里斯朵夫》。最近小 W 准备读一本新书，这本书一共有p页，页码范围为0..p-1。 <br>    小 W 很忙，所以每天只能读一页书。为了使事情有趣一些，他打算使用NOI2012 上学习的线性同余法生成一个序列，来决定每天具体读哪一页。 我们用 Xi来表示通过这种方法生成出来的第 i 个数，也即小 W 第 i 天会读哪一页。这个方法需要设置 3 个参数 a，b，X<sub>1</sub>，满足 0≤a，b，X<sub>1</sub>≤p-1，且 a，b，X<sub>1</sub>都是整数。按照下面的公式生成出来一系列的整数。 <br>X<sub>i</sub>+1 = (aX<sub>i</sub> + b) mod p <br>    其中 mod p 表示前面的数除以 p的余数。 <br>    可以发现，这个序列中下一个数总是由上一个数生成的，而且每一项都在0..p-1 这个范围内，是一个合法的页码。同时需要注意，这种方法有可能导致某两天读的页码完全一样。 <br>    小W非常急切地想去读这本书的第t页。 所以他想知道， 对于一组给定的a，b，X<sub>1</sub>，如果使用线性同余法来生成每一天读的页码，最早读到第 t 页是在哪一天，或者指出他永远不会读到第 t 页。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入含有多组数据，第一行一个正整数 T，表示这个测试点内的数据组数。 <br>    接下来 T行，每行有五个整数p，a，b，X<sub>1</sub>，t，表示一组数据。保证 X<sub>1</sub>和t 都是合法的页码。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; 共 T行，每行一个整数表示他最早读到第 t 页是哪一天。如果他永远不会读到第t 页，输出-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 <br>7 1 1 3 3 <br>7 2 2 2 0 <br>7 2 2 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 <br>3 <br>-1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例解释】<br>对于第一组数据，生成的序列为：3，4，5，6，0… <br>对于第二、三组数据，生成的序列为：2，6，0，2…<br><br>【数据范围】</p>
<table border="0">
<tbody>
<tr>
<td>测试点编号</td>
<td>a</td>
<td>b</td>
<td>p</td>
</tr>
<tr>
<td>1</td>
<td>0≤a≤p-1</td>
<td>0≤b≤p-1</td>
<td>2≤p≤100</td>
</tr>
<tr>
<td>2</td>
<td>0≤a≤p-1</td>
<td>0≤b≤p-1</td>
<td>2≤p≤100</td>
</tr>
<tr>
<td>3</td>
<td>a=1</td>
<td>0≤b≤p-1</td>
<td>2≤p≤10<sup>9</sup></td>
</tr>
<tr>
<td>4</td>
<td>a=1</td>
<td>0≤b≤p-1</td>
<td>2≤p≤10<sup>9</sup></td>
</tr>
<tr>
<td>5</td>
<td>a=1</td>
<td>0≤b≤p-1</td>
<td>2≤p≤10<sup>9</sup></td>
</tr>
<tr>
<td>6</td>
<td>0≤a≤p-1</td>
<td>b=0</td>
<td>2≤p≤10<sup>9</sup></td>
</tr>
<tr>
<td>7</td>
<td>0≤a≤p-1</td>
<td>b=0</td>
<td>2≤p≤10<sup>9</sup></td>
</tr>
<tr>
<td>8</td>
<td>0≤a≤p-1</td>
<td>0≤b≤p-1</td>
<td>2≤p≤10<sup>9</sup></td>
</tr>
<tr>
<td>9</td>
<td>0≤a≤p-1</td>
<td>0≤b≤p-1</td>
<td>2≤p≤10<sup>9</sup></td>
</tr>
<tr>
<td>10</td>
<td>0≤a≤p-1</td>
<td>0≤b≤p-1</td>
<td>2≤p≤10<sup>9</sup></td>
</tr>
</tbody>
</table>
</div>
</div>