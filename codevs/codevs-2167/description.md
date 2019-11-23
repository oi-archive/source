<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>奶牛们灰常享受在牛栏中牟叫，因為她们可以听到她们牟声的回音。虽然有时候并不能完全听到完整的回音。Bessie曾经是一个出色的秘书，所以她精确地纪录了所有的牟叫声及其回声。她很好奇到底两个声音的重复部份有多长。</p>
<p>输入两个字符串（长度為1到80个字母），表示两个牟叫声。你要确定最长的重复部份的长度。两个字符串的重复部份指的是同时是一个字符串的前缀和另一个字符串的后缀的字符串。</p>
<p>我们通过一个例子来理解题目。考虑下面的两个牟声：</p>
<p>moyooyoxyzooo<br> yzoooqyasdfljkamo</p>
<p>第一个串的最后的部份"yzooo"跟第二个串的第一部份重复。第二个串的最后的份"mo"跟第一个串的第一部份重复。所以"yzooo"跟"mo"都是这2个串的重复部份。其中，"yzooo"比较长，所以最长的重复部份的长度就是5。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入格式:</p>
<p>* 前两行: 每一行是1个字符串表示奶牛的牟声或它的回声。</p>
<p> </p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出格式:</p>
<p>* 第一行: 包含一个单独的整数表示输入的2个字符串中，一个字符串的前缀和另一个字符串的后<br /> 缀的最长的重复部份的长度。</p>
<p>&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>abcxxxxabcxabcd<br>abcdxabcxxxxabcx</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>11</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>"abcxxxxabcx"是第一个字符串的前缀和第二个字符串的后缀。</p>
</div>
</div>