<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 'times new roman';">    考虑一个整数序列<em>A</em>，我们可以在<em>A</em>中相邻两个数字<em>A</em>[<em>i</em>]和A[<em>i</em>+1]间添加运算符“+”或“-”，使得该序列组成一个算式，比如，当<em>A</em>=｛17，5，-21，15｝时，可以添加运算符组成下列8个等式：</span></p><p style=""><span style="font-family: 'times new roman';"></span></p><p style=""><span style="font-family: 'times new roman';">17 + 5 + -21 + 15 = 16</span></p><p style=""><span style="font-family: 'times new roman';">17 + 5 + -21 - 15 = -14</span></p><p style=""><span style="font-family: 'times new roman';">17 + 5 - -21 + 15 = 58</span></p><p style=""><span style="font-family: 'times new roman';">17 + 5 - -21 - 15 = 28</span></p><p style=""><span style="font-family: 'times new roman';">17 - 5 + -21 + 15 = 6</span></p><p style=""><span style="font-family: 'times new roman';">17 - 5 + -21 - 15 = -24</span></p><p style=""><span style="font-family: 'times new roman';">17 - 5 - -21 + 15 = 48</span></p><p style=""><span style="font-family: 'times new roman';">17 - 5 - -21 - 15 = 18</span></p><p><span style="font-family: 'times new roman';">    我们称一个这样的整数序列能被<em>K</em>整除，当且仅当在该序列中添加运算符“+”和“-”，使得得到算式的得数能被<em>K</em>整除。比方说，上述序列能被7整除，却不能被5整除（因为没有任何一个添加方式能够使得其能够被5整除）。</span><br></p><p><span style="font-family: 'times new roman';">    现给出序列长度<em>N</em>和一个正整数<em>K</em>，以及序列中的每个元素，编程求出该序列能否被<em>K</em>整除。<br></span></p><p style=""><span style="font-family: 'times new roman';"></span><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'times new roman';">    输入为标准输入。</span><br></p><p><span style="font-family: 'times new roman';">    输入的第一行为一个正整数<em>T</em>，表示该测试点下共有<em>T</em>组子测试点。<br></span></p><p><span style="font-family: 'times new roman';">    接下来2<em>T</em>行，每2行描述一组子测试点，每一组子测试点第一行为两个正整数<em>N</em>和<em>K</em>，意义如题目描述所示；第2行为<em>N</em>个整数，描述序列<em>A</em>，每两个整数用一个空格隔开，第<em>i</em>个整数表示序列<em>A</em>中的第<em>i</em>个元素。<br></span></p><p><span style="font-family: 'times new roman';">    输入不含多余的空格和回车符。<br></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: &#39;times new roman&#39;;">&nbsp;&nbsp;&nbsp;&nbsp;输出为标准输出。<br/></span></p><p><span style="font-family: &#39;times new roman&#39;;">&nbsp;&nbsp;&nbsp;&nbsp;输出共<em>T</em>行，每行为一个子测试点的答案，如果序列能被K整除，输出“Divisible”，若不能，输出“Not divisible”。（所有输出均不含双引号）</span><br/></p><p><span style="font-family: &#39;times new roman&#39;;">&nbsp;&nbsp;&nbsp;&nbsp;输出不要包含多余的空格与回车符。<br/></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'times new roman';">2</span></p><p><span style="font-family: 'times new roman';">4 7</span></p><p><span style="font-family: 'times new roman';">17 5 -21 15</span></p><p><span style="font-family: 'times new roman';">4 5</span></p><p><span style="font-family: 'times new roman';">17 5 -21 15</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'times new roman';">Divisible</span></p><p><span style="font-family: 'times new roman';">Not divisible</span></p><p><span style="font-family: 'times new roman';"></span><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'times new roman';">对于30%的数据，1&lt;=<em>N</em>&lt;=16;<br></span></p><p><span style="font-family: 'times new roman';">对于60%的数据，1&lt;=<em>N</em>&lt;=1,000;</span></p><p><span style="font-family: 'times new roman';">对于100%的数据，1&lt;=<em>N</em>&lt;=10,000,1&lt;=<em>K</em>&lt;=100,|<em>A<sub>i</sub></em>|&lt;=10,000,1&lt;=<em>T</em>&lt;=20。</span></p><p><span style="font-family: times new roman;">【评分方式】</span></p><p><span style="font-family: times new roman;">    如果你的输出与标准输出完全一致，则得到该测试点的全部分数，任意一组子测试点的答案错误都会导致该测试点不得分。<br></span></p><p><span style="font-family: times new roman;"><br></span></p><p><span style="font-family: times new roman;">【限制】</span></p><p><span style="font-family: times new roman;">    时间限制为2s，空间限制为256MB。<br></span></p><p><br></p><p><span style="font-family: 'times new roman';">【Source】</span></p><p><span style="font-family: 'times new roman';">    UVa Online Judge</span><br></p>
</div>
</div>