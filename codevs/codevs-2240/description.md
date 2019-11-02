<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给出一个由小写英文字母组成的字符串S，再给出q个询问，要求回答S某个子串的最短循环节。<br>如果字符串B是字符串A的循环节，那么A可以由B重复若干次得到。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个正整数n ，表示S的长度。<br>第二行n个小写英文字母，表示字符串S。<br>第三行一个正整数q ，表示询问个数。<br>下面q行每行两个正整数a,b (1&lt;=a&lt;=b&lt;=n)，表示询问字符串S[a..b]的最短循环节长度。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-align: left;" align="center"><span style="font-size: 10px;">依次输出q行正整数，第i行的正整数对应第i个询问的答案。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>8<br>aaabcabc<br>3<br>1 3<br>3 8<br>4 8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1<br>3<br>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">n&lt;=500,000</span></p>
<p style=""><span style="">q&lt;=2,000,000</span></p>
<p style=""><span style="">测试的第一个点是样例</span></p>
</div>
</div>