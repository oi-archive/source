<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>CG同学又弄到一批新牛，新牛到了农场以后，首先要学习汉语，数的朗读成为新牛的一个难题，朗读绝对值小于10亿的数。 新牛门知道汉语中有如下的读书规则： 1.首先读符号位，然后读整数部分，整数部分之后可能出现小数点，如果有小数部分则小数点一定出现，并且读出小数点之后读小数部分。 2.符号位的读法是： （1）正数，不论是正号“+”是否出现，都不必读出符号位； （2）负数的最左边的符号是“—”，都城“负”（以“F”来表示负） 3.整数部分的读法是： （1）如果整数部分不存在或者整数部分全是零则直接读成“零”（以“0”来表示“零”） （2）否则从整数部分中最左边的非零数字开始读起，然后以十、百、千、万、亿（分别以“S”、“B”、“Q”、“W”、“Y”来表示）等数量单位来拼读整数部分。 4.整数部分中： （1）每一个非零数字都必须结合各个相应的数量单位读出来； （2）每一段连续的“零”只能读成一个零，但是某一段连续的零的左侧或者右侧不存在非零数字（这里只考虑整数部分）则这一段“零”不应该读出来； 5.如果有小数部分，则首先读“点”（以“D”来表示“点”），然后从左至右有顺序的读出各个小数位。在读出小数部分的时候不可以使用十、百、千、万、亿等数量单位；但是小数部分的每一个数字都需要读出来，连续的零不可以读成一个“零”，而应该分别读出。 6.如果数中有小数点而没有小数部分，则不应该把小数点读出来。 例如，—0020030004.567应该读成“F2Q03W04D567”，000.89应该读成“0D89”。    请你编写程序帮助新牛把给定的数正确的读出来。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入仅一行，存放了一个数（不超过50个字符），其绝对值小于10亿。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出仅一行，输出这个数的正确读法</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>—0020030004.567</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>F2Q03W04D567</p>

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