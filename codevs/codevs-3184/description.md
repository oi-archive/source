<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>SYY虽然中了500W，但他依然喜欢玩GAME.</p>
<p>一天，他看到了一个GAME叫（找不同）。</p>
<p><span>给出N个单词（均仅由小写英文字母构成，长度至少为1且不超过S）与Q次询问，每次询问给定一组L_i,R_i，请你回答：从第L_i个单词到第R_i个单词是否两两不同。</span></p>
<p><span>他想玩到第一名，也就是所有回答全对。他能实现吗？</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行，为一个整数N。</span><br><span>接下来N行，每行一个单词。</span><br><span>接下来一行，为一个整数Q。</span><br><span>接下来Q行，每行两个整数L_i,R_i。</span></p>
<p><span><br></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>共Q行，每行对应一个询问的答案。</span><br /><span>如果此区间内的单词两两不同，输出一行YES，否则输出一行NO。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>6
asdfjkl
asdfjkl
asbfjkl
lkjfdsa
asdfjkl
asbfjkl
4
1 2
2 5
3 5
1 6</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>NO
NO
YES
NO</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<ul>
<li>对于20%的数据，N≤1000,Q≤1000,S≤1；</li>
<li>对于50%的数据，N≤1000,Q≤1000；</li>
<li>对于100%的数据，N≤100000,Q≤100000,S≤10。</li>
<li>对于100%的数据，输入数据很弱，骗分算法会非常有用。注：题目为转载</li>
</ul>
</div>
</div>