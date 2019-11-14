<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    某电视台在每一个星期天都有一个福利彩票节目，在该节目中有一个考察幸运观众记忆力的节目。节目的安排是这样的：首先由节目主持人说出一串诸如“左1右2左2左3右4左1”的数值串，然后由幸运观众重复该数值串；如果幸运观众能全部记忆出节目主持人说的所有数值串，该观众将获得一笔数目可观的奖金。为了确保节目的质量，节目导演希望这种数值串中不含连续的2个以上相同子串，这样数值串就不易记忆。他们称这种有连续相同子串的数值串为“易数值串”，而这种相同子串称为重复子串；无重复子串的数值串称为“难数值串”。</p>
<p>    例如，下列字符串是“易数值串”：</p>
<p>   （1）<span style="text-decoration: underline;">左1</span>左1 （2）左1<span style="text-decoration: underline;">右2</span><span style="text-decoration: underline;">左3</span>右2左3右2（3）<span style="text-decoration: underline;">左1右2左4</span>左1右2左4右2</p>
<p>    而下列字符串是“难字符串”：</p>
<p>（1）左1（2）左1右2（3）左1右2左1右1（4）左1右2右4左1右2</p>
<p>    现假设：</p>
<p>（1）数值前只有“左”和“右”2个方向，分别用L和R代替“左”和“右”。</p>
<p>（2）数字范围为1，2，3，4，5，6，7，8，9。</p>
<p>（3）所有子串指的是“左”或“右”开始的子串，以诸如“1右2左”的连续重复子串不计算为重复子串。</p>
<p>你的任务是：对于给定一个数值串（串的长度&lt;=100000）,请你编程求出第一次出现的最长重复子串。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入：输入文件为1行，它是一串数值串。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出：输出文件为1行，它是输入文件中数值串的第一次出现的最长重复子串。如果无重复子串则输出字符串&ldquo;NO&rdquo;。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>string.in :</p>
<p>L1R2L2L4R5L3L4R5L3R4R5L3R4R5R6L1              </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>String.out:</p>
<p>L4R5L3</p>

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