<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<ul style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><li><p>描述</p></li><li><p style="">MFY最近对回文串产生了非常浓厚的兴趣。</p><p style="">如果一个字符串从左往右看和从右往左看完全相同的话，那么就认为这个串是一个回文串。例如，“abcaacba”是一个回文串，“abcaaba”则不是一个回文串。</p><p style="">MFY现在强迫症发作，看到什么字符串都想要把它变成回文的。MFY可以通过切割字符串，使得切割完之后得到的子串都是回文的。</p><p style="">现在MFY想知道他最少切割多少次就可以达到目的。例如，对于字符串“abaacca”，最少切割一次，就可以得到“aba”和“acca”这两个回文子串。<span style="font-family: sans-serif;"></span></p></li></ul>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<ul><li><p>输入</p></li><li><p>输入的第一行是一个整数 T (T &lt;= 20) ，表示一共有 T 组数据。<br>接下来的 T 行，每一行都包含了一个长度不超过的 1000 的字符串，且字符串只包含了小写字母。</p></li></ul><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<ul class=" list-paddingleft-2"><li><p>输出</p></li><li><p>对于每组数据，输出一行。该行包含一个整数，表示阿福最少切割的次数，使得切割完得到的子串都是回文的。</p></li></ul><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3<br></p><p>abaacca</p><p>abcd</p><p>abcba</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1<br></p><p>3</p><p>0</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">对于第一组样例，MFY最少切割 1 次，将原串切割为“aba”和“acca”两个回文子串。</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">对于第二组样例，MFY最少切割 3 次，将原串切割为“a”、“b”、“c”、“d”这四个回文子串。</span><br style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;"><span style="font-family: 'Lucida Grande', Verdana, 'Bitstream Vera Sans', Arial, sans-serif;">对于第三组样例，MFY不需要切割，原串本身就是一个回文串。</span></p>
</div>
</div>