<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在幻想乡，稗田乙女是负责书写《幻想乡缘起》的家族。由于需要代代相传关于幻想乡的记忆，稗田乙女采用了一些特殊的记录方式。对于相同重复的文字，稗田乙女会用一个数字来代替，然后用一个数列来表示一个段文字。比如1代表"A"，2代表"C"，那么{1,2}就代表"AC"，{2,1,2}就代表"CAC"。不过由于年代过于久远，到阿求时已经是第九代稗田乙女，所以难免会出现错误。现在阿求有N个数字(1..N)和N个字符('A'..第N个字母)，以及一些以前传承下来的M组文字段和对应的数列。每一组文字段和数列相互对应，文字的第i个字符对应着数列的第i项。阿求想要知道怎样安排N个数字和字符的对应关系，能够使组数尽可能多的文字段和数列组合满足该对应关系。数字和字符间一一对应，不会出现多对一或一对多的情况。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：2个正整数N, M<br> 　　第2..2*M+1行：每2行为一组，第1行为文字段落，第2行为数列。保证文字段落的字符数L等于数列数字个数L，且均在1..N。文字段落只包含大写字母</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第1行：最多能够匹配的文字段落和数列组合数量</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3<br> ACCA<br> 1 3 3 1 <br> AAC<br> 2 2 1<br> BCBC<br> 3 1 3 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于60%的数据： 1 ≤ N ≤ 10，1 ≤ M ≤ 20<br> 　　对于100%的数据：1 ≤ N ≤ 26，1 ≤ M ≤ 60<br> 　　对于100%的数据：1 ≤ L ≤ 100<br>　提示<br>　　样例解释：<br> 　　当A=2,B=3,C=1时第2、3字符串和数列组合满足对应关系。<br><br> 　　注意：<br> 　　保证每一组文字段和数列组合均合法；<br> 　　在一组文字段和数列组合里面不会出现多个字符对一个数字，或是一个字符对多个数字的情况。</p>
</div>
</div>