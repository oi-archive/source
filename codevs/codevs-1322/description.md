<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>对于包含字母A到Y各一次的单词S，将其从上到下从左到右写在一个5*5的矩阵中，如单<br>词ADJPTBEKQUCGLRVFINSWHMOXY写出来如下： <br>A D J P T <br>B E K Q U <br>C G L R V <br>F I N S W <br>H M O X Y <br>若该矩阵满足每一行每一列的字母都是字典序递增的则称S为优美的，如上述单词就是<br>优美的，而ADJPTBEGQUCKLRVFINSWHMOXY则不是（第二列不满足要求）。 <br>Your Task <br>将所有优美的单词按字典序列出，从小到大编号1,2,…… <br>请你完成以下两种任务： <br>1. 给定一个优美的单词，求其编号。 <br>2. 给定一个编号，求对应的优美的单词。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个字母，W表示任务1，N表示任务2 <br>若是任务1，第二行是一个优美的单词，否则第二行是一个正整数，表示某个优美的单<br>词的编号，保证该数不超过优美的单词的总数</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行，若是任务1，输出对应编号，否则输出对应的优美的单词&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>W <br>ABCDEFGHIJKLMNOPQRSUTVWXY</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例输入二 <br>N <br>20 <br>样例输出二 <br>ABCDEFGHIJKLMNOPQSUWRTVXY</p>
</div>
</div>