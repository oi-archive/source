<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>【问题描述】<br>在初赛普及组的“阅读程序写结果”的问题中，我们曾给出一个字符串展开的例子：如果在输<br>入的字符串中，含有类似于“d-h”或“4-8”的子串，我们就把它当作一种简写，输出时，用连续<br>递增的字母或数字串替代其中的减号，即，将上面两个子串分别输出为“defgh”和“45678”。在<br>本题中，我们通过增加一些参数的设置，使字符串的展开更为灵活。具体约定如下：<br>（1）遇到下面的情况需要做字符串的展开：在输入的字符串中，出现了减号“-”，减号两侧<br>同为小写字母或同为数字，且按照ASCII 码的顺序，减号右边的字符严格大于左边的字符。<br>（2）参数p1：展开方式。p1=1 时，对于字母子串，填充小写字母；p1=2 时，对于字母子串，</p>
<p>填充大写字母。这两种情况下数字子串的填充方式相同。p1=3 时，不论是字母子串还是数字子串，<br>都用与要填充的字母个数相同的星号“*”来填充。<br>（3）参数p2：填充字符的重复个数。p2=k 表示同一个字符要连续填充k 个。例如，当p2=3<br>时，子串“d-h”应扩展为“deeefffgggh”。减号两侧的字符不变。<br>（4）参数p3：是否改为逆序：p3=1 表示维持原有顺序，p3=2 表示采用逆序输出，注意这时<br>仍然不包括减号两端的字符。例如当p1=1、p2=2、p3=2 时，子串“d-h”应扩展为“dggffeeh”。<br>（5）如果减号右边的字符恰好是左边字符的后继，只删除中间的减号，例如：“d-e”应输出<br>为“de”，“3-4”应输出为“34”。如果减号右边的字符按照ASCII码的顺序小于或等于左边字符，<br>输出时，要保留中间的减号，例如：“d-d”应输出为“d-d”，“3-1”应输出为“3-1”。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第 1 行为用空格隔开的3 个正整数，依次表示参数p1，p2，p3。<br>第 2 行为一行字符串，仅由数字、小写字母和减号“-”组成。行首和行末均无空格。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只有一行，为展开后的字符串。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【输入输出样例1】<br>1 2 1<br>abcs-w1234-9s-4zz</p>
<p>【输入输出样例2】<br>2 3 2<br>a-d-d</p>
<p>【输入输出样例3】<br>3 4 2<br>di-jkstra2-6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【输入输出样例1】</p>
<p>abcsttuuvvw1234556677889s-4zz</p>
<p>【输入输出样例2】</p>
<p>aCCCBBBd-d</p>
<p>【输入输出样例3】</p>
<p>dijkstra2************6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【限制】<br>40%的数据满足：字符串长度不超过5<br>100%的数据满足：1&lt;=p1&lt;=3, 1&lt;=p2&lt;=8, 1&lt;=p3&lt;=2。字符串长度不超过100</p>
</div>
</div>