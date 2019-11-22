<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在幻想乡，帕秋莉•诺蕾姬是以宅在图书馆闻名的魔法使。这一天帕秋莉又在考虑如何加强魔法咒语的威力。帕秋莉的魔法咒语是一个仅有大写字母组成的字符串，我们考虑从’A’到’Z’分别表示0到25的数字，于是这个魔法咒语就可以看作一个26进制数。帕秋莉通过研究发现，如果一个魔法咒语所代表的数能够整除10进制数M的话，就能够发挥最大的威力。若当前的魔法咒语并不能整除M，帕秋莉只会将其中两个字符的位置交换，尽量让它能够被M整除，当然由于某些咒语比较特殊，无论怎么改变都不能达到这个目的。请你计算出她能否只交换两个字符就让当前咒语被M整除。(首位的’A’为前导0) 第1行：1个字符串，长度不超过L。 第2行：1个正整数，M 第1行：用空格隔开的2个整数，输出时先输位置靠前的那个。 如果存在多种交换方法，输出字典序最小的，比如1 3和1 5都可以达到目的，就输出1 3；1 3和2 4都行时也输出1 3。注意字符串下标从左到右依次为1到L开始。如果初始魔法咒语已经能够整除M，输出”0 0”；若无论如何也不能到达目的输出”-1 -1”。 PATCHOULI 16 4 9 对于30%的数据：1 &lt;= L &lt;= 10, 1 &lt;= M &lt;= 100 对于50%的数据：除前面30%外，1 &lt;= L &lt;= 500, M = 5或25或26 对于100%的数据：1 &lt;= L &lt;= 2,000, 1 &lt;= M &lt;= 200,000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：1个字符串，长度不超过L。 第2行：1个正整数，M</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第1行：用空格隔开的2个整数，输出时先输位置靠前的那个。 如果存在多种交换方法，输出字典序最小的，比如1 3和1 5都可以达到目的，就输出1 3；1 3和2 4都行时也输出1 3。注意字符串下标从左到右依次为1到L开始。如果初始魔法咒语已经能够整除M，输出&rdquo;00&rdquo;；若无论如何也不能到达目的输出&rdquo;-1-1&rdquo;。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>PATCHOULI 16</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4 9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据：1 &lt;= L &lt;= 10, 1 &lt;= M &lt;= 100 对于50%的数据：除前面30%外，1 &lt;= L &lt;= 500, M = 5或25或26 对于100%的数据：1 &lt;= L &lt;= 2,000, 1 &lt;= M &lt;= 200,000</p>
</div>
</div>