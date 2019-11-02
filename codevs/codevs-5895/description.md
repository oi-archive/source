<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">农夫约翰的奶牛不停地从他的农场中逃出来，导致了很多损害。为了防止它们再逃出来，他买了一只很大的号码锁以防止奶牛们打开牧场的门。</p><p style="">农夫约翰知道他的奶牛很聪明，所以他希望确保它们不会在简单地试了很多不同的号码组合之后就能轻易开锁。锁上有三个转盘，每个上面有数字1..N (1 &lt;= N &lt;= 100)，因为转盘是圆的，所以1和N是相邻的。有两种能开锁的号码组合，一种是农夫约翰设定的，还有一种“预设”号码组合是锁匠设定的。但是，锁有一定的容错性，所以，在每个转盘上的数字都与一个合法的号码组合中相应的数字相距两个位置以内时，锁也会打开。</p><p style="">比如说，如果农夫约翰的号码组合是(1,2,3)，预设号码组合是(4,5,6)，在转盘被设定为(1,4,5)（因为这和农夫约翰的号码组合足够接近）或(2,4,8)（因为这和预设号码组合足够接近）。注意，(1,5,6)并不会打开锁，因为它与任一号码组合都不够接近。</p><p style="">给出农夫约翰的号码组合和预设号码组合，请计算能够开锁的不同的号码组合的数目。号码是有序的，所以(1,2,3)与(3,2,1)不同。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">第一行：整数N。</p><p style="">第二行：三个以空格分隔的整数，为农夫约翰的号码组合。</p><p style="">第三行：三个以空格分隔的整数，为预设号码组合（可能与农夫约翰的号码组合相同）。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: 12.7px; line-height: 19.05px; background-color: rgb(255, 255, 255);">第一行：所有不同的能够开锁的号码组合的总数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="">50
1 2 3
5 6 7</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="">249</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">1 &lt;= N &lt;= 100</span></p>
</div>
</div>