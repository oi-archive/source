<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>读入一个长度为 n 的由小写英文字母组成的字符串，请把这个字符串的所有非空后缀按字典序从小到大排序，然后按顺序输出后缀的第一个字符在原串中的位置。位置编号为 1 到 n。</p><p>本题是一道经典的模板问题，本题数据只是为了测试你的代码是否正确，所以范围较小，请不要暴力或打表或骗分。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Times New Roman', Times, 'Microsoft YaHei', 'WenQuanYi Micro Hei', 'Microsoft YaHei UI', serif;">输入包括一个长度为 n</span><span style="font-family: 'Times New Roman', Times, 'Microsoft YaHei', 'WenQuanYi Micro Hei', 'Microsoft YaHei UI', serif;"> 的仅包含小写英文字母的字符串。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出包括 n 个整数，第 i 个整数<span style="color: rgb(51, 51, 51); font-family: &#39;Times New Roman&#39;, Times, &#39;Microsoft YaHei&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft YaHei UI&#39;, serif; font-size: 14px; line-height: 20px; text-indent: 28px; background-color: rgb(255, 255, 255);">表示排名为 i 的<span style="color: rgb(51, 51, 51); font-family: &#39;Times New Roman&#39;, Times, &#39;Microsoft YaHei&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft YaHei UI&#39;, serif; font-size: 14px; line-height: 20px; text-indent: 28px; background-color: rgb(255, 255, 255);">后缀的第一个字符在原串中的位置。</span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>ababa</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5 3 1 4 2<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据范围：</p><p>1 &lt;= n &lt;= 100。（请勿暴力）</p><p>----------------------------------------------------------</p><p>样例解释：</p><p>排序后的结果为：</p><ol style=""><li><p>a</p></li><li><p>aba</p></li><li><p>ababa</p></li><li><p>ba</p></li><li><p>baba<br></p></li></ol>
</div>
</div>