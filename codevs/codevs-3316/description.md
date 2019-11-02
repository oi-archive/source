<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>编写一个程序，输入一个正整数，并检查，使用下面描述的算法，看是否被11整除。这种特殊的测试于1897年由Charles L Dodgson (Lewis Carroll)提出。</p>
<p>算法：</p>
<p>    只要输入的数是两位以上的数，那么形成一个新的数字：</p>
<p>           •    删除个位数</p>
<p>           •    再减去删除的数字</p>
<p>        反复进行上面的运算，直到剩下的数是11的整数倍。</p>
<p>注：开头零的数量没有考虑在内，不应该被打印出来。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行输入一个正整数</span><span>n</span><span>（</span><span>n&lt;=50</span><span>），以下</span><span>n</span><span>行，每行一个正整数。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>由空行分隔为不同的正整数的输出。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1<br>12345678901234567900</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>12345678901234567900<br>1234567890123456790<br>123456789012345679<br>12345678901234558<br>1234567890123447<br>123456789012337<br>12345678901226<br>1234567890116<br>123456789005<br>12345678995<br>1234567884<br>123456784<br>12345674<br>1234563<br>123453<br>12342<br>1232<br>121<br>11<br>The number 12345678901234567900 is divisible by 11.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>为了地球的河蟹 社会的稳定 十二五计划的预期完成 全民奔小康的目标早日达到 请不要卡评测</p>
</div>
</div>