<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>This question involves calculating the value of aromatic numbers which are a combination of Arabic digits and Roman numerals.</p>
<p>本题是关于计算芳香数数值的问题，芳香数是阿拉伯数字和罗马数字的组合。</p>
<p><span style="">An aromatic number is of the form ARARAR...AR, where each A is an Arabic digit, and each R is a Roman numeral. Each pair AR contributes a value described below, and by adding or subtracting these values together we get the value of the entire aromatic number.</span></p>
<p>芳香数的格式是ARARAR..ARA，其中A代表阿拉伯数字，R代表罗马数字。每一对AR按照下面的计算方式计算一个值，通过把这些数值加减起来，就得到了整个芳香数的数值。</p>
<p>An Arabic digit A can be 0, 1, 2, 3, 4, 5, 6, 7, 8 or 9. A Roman numeral R is one of the seven letters I, V, X, L, C, D, or M. Each Roman numeral has a base value:</p>
<p>阿拉伯数字是0,1,2..9，罗马数字是I,V,X,L,C,D,M。</p>
<p>Symbol I V X L C D M Base value 1 5 10 50 100 500 1000</p>
<p>符号I V X L C D M的值是1 5 10 50 100 500 1000。</p>
<p>The value of a pair AR is A times the base value of R. Normally, you add up the values of the pairs to get the overall value. However, wherever there are consecutive symbols ARA<sub>0</sub>R<sub>0</sub> with R<sub>0</sub> having a strictly bigger base value than R, the value of pair AR must be subtracted from the total, instead of being added.</p>
<p>一对AR的值计算为A乘以R。一般的，我们把所有的AR的值加起来就得到了芳香数的值。但是如果存在连续的两个数对ARA<sub>0</sub>R<sub>0，</sub>其中R<sub>0</sub>严格大于R的话，则需要减去AR的值，而不是加上。</p>
<p>For example, the number 3M1D2C has the value 3∗1000+1∗500+2∗100 = 3700 and 3X2I4X has the value 3 ∗ 10 − 2 ∗ 1 + 4 ∗ 10 = 68.</p>
<p>举个例子，3M1D2C 的值为3*1000+1*500+2*100=3700，而3X2I4X的值为3*10-2*1+4*10=68</p>
<p>Write a program that computes the values of aromatic numbers.</p>
<p>你的任务是写一个程序来计算一个给定的芳香数的值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p> The input is a valid aromatic number consisting of between 2 and 20 symbols.</p>
<p>输入是一个合法的芳香数，包含了2-20个字符。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;The output is the decimal value of the given aromatic number.</p>
<p>输出是一个十进制的整数代表这个芳香数的值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例输入 1： 3M1D2C</p>
<p>样例输入 2： 2I3I2X9V1X</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例输出 1： 3700</p>
<p>样例输出 2： -16</p>

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