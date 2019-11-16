<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">在虐各种最长公共子串、子序列的题虐的不耐烦了之后，你决定反其道而行之。</span></p><p><span style="">一个串的“子串”指的是它的连续的一段，例如</span>bcd<span style="">是</span>abcdef<span style="">的子串，但</span>bde<span style="">不是。</span></p><p><span style="">一个串的“子序列”指的是它的可以不连续的一段，例如</span>bde<span style="">是</span>abcdef<span style="">的子串，但</span>bdd<span style="">不是。</span></p><p style=""><span style="">下面，给两个小写字母串</span>A<span style="">，</span>B<span style="">，请你计算：</span></p><p>(1) A<span style="">的一个最短的子串，它不是</span>B<span style="">的子串</span></p><p>(2) A<span style="">的一个最短的子串，它不是</span>B<span style="">的子序列</span></p><p>(3) A<span style="">的一个最短的子序列，它不是</span>B<span style="">的子串</span></p><p>(4) A<span style="">的一个最短的子序列，它不是</span>B<span style="">的子序列</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">sus.in<span style="">中有两行，每行一个小写字母组成的字符串，分别代表</span>A<span style="">和</span>B<span style="">。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:28px">sus.out<span style="font-family:宋体">中输出</span>4<span style="font-family:宋体">行，每行一个整数，表示以上</span>4<span style="font-family:宋体">个问题的答案的长度。如果没有符合要求的答案，输出</span>-1.</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><strong><span style="">【样例输入</span>1</strong><strong><span style="">】</span></strong></p><p>aabbcc</p><p>abcabc</p><p> </p><p><strong><span style="">【样例输入</span>2</strong><strong><span style="">】</span></strong></p><p>aabbcc</p><p>aabbcc</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><strong><span style="">【样例输出</span>1</strong><strong><span style="">】</span></strong></p><p>2</p><p>4</p><p>2</p><p>4</p><p><strong><span style="">【样例输出</span>2</strong><strong><span style="">】</span></strong></p><p>-1</p><p>-1</p><p>2</p><p>-1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">对于</span>20%<span style="">的数据，</span>A<span style="">和</span>B<span style="">的长度都不超过</span>20</p><p><span style="">对于</span>50%<span style="">的数据，</span>A<span style="">和</span>B<span style="">的长度都不超过</span>500</p><p><span style="">对于</span>100%<span style="">的数据，</span>A<span style="">和</span>B<span style="">的长度都不超过</span>2000</p><p> </p><p><br></p>
</div>
</div>