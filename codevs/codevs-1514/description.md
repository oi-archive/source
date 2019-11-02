<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    小 T有一个很大的书柜。这个书柜的构造有些独特，即书柜里的书是从上至下堆放成一列。她用 1 到 n 的正整数给每本书都编了号。 <br>    小 T 在看书的时候，每次取出一本书，看完后放回书柜然后再拿下一本。由于这些书太有吸引力了，所以她看完后常常会忘记原来是放在书柜的什么位置。不过小 T 的记忆力是非常好的，所以每次放书的时候至少能够将那本书放在拿出来时的位置附近，比如说她拿的时候这本书上面有 X 本书，那么放回去时这本书上面就只可能有 X-1、X或 X+1 本书。 <br>    当然也有特殊情况，比如在看书的时候突然电话响了或者有朋友来访。这时<br>候粗心的小 T 会随手把书放在书柜里所有书的最上面或者最下面，然后转身离<br>开。 <br>    久而久之，小 T 的书柜里的书的顺序就会越来越乱，找到特定的编号的书就变得越来越困难。于是她想请你帮她编写一个图书管理程序，处理她看书时的一些操作，以及回答她的两个提问：(1)编号为 X 的书在书柜的什么位置；(2)从上到下第 i 本书的编号是多少。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有两个数 n，m，分别表示书的个数以及命令的条数；第二行为 n 个正整数：第i个数表示初始时从上至下第i个位置放置的书的编号；第三行到m+2行，每行一条命令。命令有 5 种形式： <br>1． Top S——表示把编号为S的书房在最上面。 <br>2． Bottom S——表示把编号为 S的书房在最下面。 <br>3． Insert S T——T∈{-1，0，1}，若编号为S的书上面有 X本书，则这条命令表示把这本书放回去后它的上面有X+T本书； <br>4． Ask S——询问编号为S的书的上面目前有多少本书。 <br>5． Query S——询问从上面数起的第S本书的编号。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每一条 Ask 或 Query 语句你应该输出一行，一个数，代表询问的答案。 &nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 10 <br>1 3 2 7 5 8 10 4 9 6 <br>Query 3 <br>Top 5 <br>Ask 6 <br>Bottom 3 <br>Ask 3 <br>Top 6 <br>Insert 4 –1 <br>Query 5 <br>Query 2 <br>Ask 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 <br>9 <br>9 <br>7 <br>5 <br>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%的数据，n,m&lt;=10000 <br> 100%的数据，n,m&lt;=80000</p>
</div>
</div>