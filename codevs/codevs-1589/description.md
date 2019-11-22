<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Siruseri 政府建造了一座新的会议中心。许多公司对租借会议中心的会堂很<br>感兴趣，他们希望能够在里面举行会议。<br>对于一个客户而言，仅当在开会时能够独自占用整个会堂，他才会租借会堂。<br>会议中心的销售主管认为：最好的策略应该是将会堂租借给尽可能多的客户。显<br>然，有可能存在不止一种满足要求的策略。<br>例如下面的例子。总共有4 个公司。他们对租借会堂发出了请求，并提出了<br>他们所需占用会堂的起止日期（如下表所示）。<br>开始日期结束日期<br>公司1 4 9<br>公司2 9 11<br>公司3 13 19<br>公司4 10 17<br>上例中，最多将会堂租借给两家公司。租借策略分别是租给公司1 和公司3，<br>或是公司2 和公司3，也可以是公司1 和公司4。注意会议中心一天最多租借给<br>一个公司，所以公司1 和公司2 不能同时租借会议中心，因为他们在第九天重合<br>了。<br>销售主管为了公平起见，决定按照如下的程序来确定选择何种租借策略：首<br>先，将租借给客户数量最多的策略作为候选，将所有的公司按照他们发出请求的<br>顺序编号。对于候选策略，将策略中的每家公司的编号按升序排列。最后，选出<br>其中字典序最小1的候选策略作为最终的策略。<br>例中， 会堂最终将被租借给公司1 和公司3 ： 3 个候选策略是<br>{(1,3),(2,3),(1,4)}。而在字典序中(1,3)&lt;(1,4)&lt;(2,3)。<br>你的任务是帮助销售主管确定应该将会堂租借给哪些公司。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行有一个整数N，表示发出租借会堂申请的公司的个数。第2 到<br>第N+1 行每行有2 个整数。第i+1 行的整数表示第i 家公司申请租借的起始和终<br>止日期。对于每个公司的申请，起始日期为不小于1 的整数，终止日期为不大于<br>109 的整数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出的第一行应有一个整数M，表示最多可以租借给多少家公司。第二行应列出M 个数，表示最终将会堂租借给哪些公司。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4<br>4 9<br>9 11<br>13 19<br>10 17</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2<br>1 3 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于50%的输入，N≤3000。在所有输入中，N≤200000。</p>
</div>
</div>