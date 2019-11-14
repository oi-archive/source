<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给出N个单词（均仅由小写英文字母构成，长度至少为1且不超过S）与Q次询问，每次询问给定一组L_i,R_i，请你回答：从第L_i个单词到第R_i个单词是否两两不同。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，为一个整数N。<br>接下来N行，每行一个单词。<br>接下来一行，为一个整数Q。<br>接下来Q行，每行两个整数L_i,R_i。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">共Q行，每行对应一个询问的答案。<br />如果此区间内的单词两两不同，输出一行YES，否则输出一行NO。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6</p>
<p>asdfjkl</p>
<p>asdfjkl</p>
<p>asbfjkl</p>
<p>lkjfdsa</p>
<p>asdfjkl</p>
<p>asbfjkl</p>
<p>4</p>
<p>1 2</p>
<p>2 5</p>
<p>3 5</p>
<p>1 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>NO</p>
<p>NO</p>
<p>YES</p>
<p>NO</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p>对于20%的数据，N≤1000,Q≤1000,S≤1；</p>
<p>对于50%的数据，N≤1000,Q≤1000；</p>
<p>对于100%的数据，N≤100000,Q≤100000,S≤10。</p>
</div>
</div>
</div>