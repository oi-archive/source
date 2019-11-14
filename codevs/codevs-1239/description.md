<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">T 公司发现其研制的一个软件中有 n 个错误，随即为该软件发放了一批共 m 个补丁程</span><span style="">序。每一个补丁程序都有其特定的适用环境，某个补丁只有在软件中包含某些错误而同时又</span><span style="">不包含另一些错误时才可以使用。一个补丁在排除某些错误的同时，往往会加入另一些错误。</span><span style="">换句话说，对于每一个补丁 i，都有 2 个与之相应的错误集合 B1[i]和 B2[i]，使得仅当软件</span><span style="">包含 B1[i]中的所有错误，而不包含 B2[i]中的任何错误时，才可以使用补丁 i。补丁 i 将修复</span><span style="">软件中的某些错误 F1[i]，而同时加入另一些错误 F2[i]。另外，每个补丁都耗费一定的时间。 </span><br><span style="">试设计一个算法，利用 T 公司提供的 m 个补丁程序将原软件修复成一个没有错误的软</span><span style="">件，并使修复后的软件耗时最少。</span></p>
<p><span style="">对于给定的 n 个错误和 m 个补丁程序，找到总耗时最少的软件修复方案。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第 1 行有 2 个正整数 n 和 m，n 表示错误总数，m</span><span style="">表示补丁总数，1&lt;=n&lt;=20, 1&lt;=m&lt;=100。接下来 m 行给出了 m个补丁的信息。每行包括一</span><span style="">个正整数，表示运行补丁程序 i 所需时间，以及 2 个长度为 n 的字符串，中间用一个空格符</span><span style="">隔开。第 1 个字符串中，如果第 k 个字符 bk 为“+” ，则表示第 k 个错误属于 B1[i]，若为“-”，</span><span style="">则表示第 k 个错误属于 B21[i]，若为“0” ，则第 k 个错误既不属于 B1[i]也不属于 B2[i]，即</span><span style="">软件中是否包含第 k 个错误并不影响补丁 i 的可用性。第 2 个字符串中，如果第 k 个字符 bk</span><span style="">为“+” ，则表示第 k 个错误属于 F1[i]，若为“-”，则表示第 k 个错误属于 F2[i]，若为“0” ，</span><span style="">则第 k 个错误既不属于 F1[i]也不属于 F2[i]，即软件中是否包含第 k 个错误不会因使用补丁</span><span style="">i 而改变。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: large;">将总耗时数输出。如果问题无解，则输出 0。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">3 3 </span></p>
<p><span style="">1 000 00- </span></p>
<p><span style="">1 00- 0-+ </span></p>
<p><span style="">2 0-- -++</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">8</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>