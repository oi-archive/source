<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">Mr.Li</span><span style="">开了一家钢笔公司，他致力于拥有无穷种钢笔，他是</span><span style="">Mr.Li</span><span style="">，所以他做到了！这个世界上有</span><span style="">T</span><span style="">个平行宇宙，他在每个宇宙的</span><span style="">M</span><span style="">个不同的城市开了钢笔店，并且每个城市有</span><span style="">N</span><span style="">条街，每条街上开了两家钢笔店。其中每条街上的两家钢笔店的钢笔种类总数为</span><span style="">N+1</span><span style="">种。每条街上钢笔店中的钢笔都不同！！！</span></p><p style=""><span style="">且</span><span style="">Mr.Li</span><span style="">对于每一条街编号：</span><span style="">1,2,3,L,N-1,N</span><span style="">。且每条街上两个钢笔店中的种类为：（</span><span style="">1</span><span style="">，</span><span style="">N</span><span style="">），（</span><span style="">2</span><span style="">，</span><span style="">N-1</span><span style="">），（</span><span style="">3</span><span style="">，</span><span style="">N-2</span><span style="">），</span><span style="">L</span><span style="">，（</span><span style="">N</span><span style="">，</span><span style="">1</span><span style="">）。</span></p><p style=""><span style="">Mr.Li</span><span style="">的同学要在同一条街的不同店中买一共两支钢笔（即在一条街的两个店中各买一支钢笔），可以选择任意街道和城市。</span><span style="">Mr.Li</span><span style="">很好奇，到底有多少种方案。由于方案太多，</span><span style="">Mr.Li</span><span style="">希望你对求得的答案模上</span><span style="">100000007</span><span style="">。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行一个数</span><span style="">T</span><span style="">，表示有</span><span style="">T</span><span style="">个宇宙。</span></p><p style=""><span style="">第二行一个数</span><span style="">ADD</span><span style="">。</span></p><p style=""><span style="">以下一行，有两个数</span><span style="">N</span><span style="">，</span><span style="">M</span><span style="">。之间有一个空格，后有一个回车。</span></p><p style=""><span style="">每行无多余空格和回车。</span></p><p style=""><span style="">以后的数据</span><span style="">N(k)=N(k-1)+add*k; M(k)=M(k-1)+add*(k-1);</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:53px"><span style="font-size:27px;font-family:宋体">输出一行表示所有</span><span style="font-size:27px">T</span><span style="font-size:27px;font-family: 宋体">个宇宙的答案相加之后模上</span><span style="font-size:27px">100000007</span><span style="font-size: 27px;font-family:宋体">的值。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">【样例输入</span><span style="">1</span><span style="">】</span></p><p style=""><span style="">1</span></p><p style=""><span style="">0</span></p><p style=""><span style="">2 2</span></p><p><span style="">【样例输入</span><span style="">2</span><span style="">】</span></p><p style=""><span style="">3</span></p><p style=""><span style="">1</span></p><p style=""><span style=""><span style="font-family: sans-serif;"><span style="">2</span></span><span style="">  </span></span><span style="">2</span></p><p><span style="">【样例输入</span><span style="">3</span><span style="">】</span></p><p style=""><span style="">3</span></p><p style=""><span style="">12345678987654321</span></p><p style=""><span style="">98765432123456789 98765432123456789</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">【样例输出</span><span style="">1</span><span style="">】</span></p><p style=""><span style="">16</span></p><p style=""><span style=""><br></span></p><p><span style="">【样例输出</span><span style="">2</span><span style="">】</span></p><p style=""><span style="">82127153</span></p><p style=""><span style=""><br></span></p><p><span style="">【样例输出</span><span style="">3</span><span style="">】</span></p><p style=""><span style="">40716496</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">对于</span><span style="">10%</span><span style="">的数据：</span><span style="">0&lt;n , m , t , add&lt;100</span><span style="">。</span></p><p style=""><span style="">对于</span><span style="">10%</span><span style="">的数据：</span><span style="">0&lt;n , m , t , add&lt;3000</span><span style="">。</span></p><p style=""><span style="">对于</span><span style="">10%</span><span style="">的数据：</span><span style="">0&lt;n , t , add&lt;3000</span><span style="">。</span><span style="">0&lt; m &lt;100000007</span><span style="">。</span></p><p style=""><span style="">对于</span><span style="">100%</span><span style="">的数据：</span><span style="">0&lt; t &lt;=100000</span><span style="">。</span></p><p style=""><span style="">0&lt;N , M , add&lt;=10^999999</span><span style="">。</span></p><p style=""><span style="">注意：</span><span style="">codevs</span><span style="">上读入一个提行是两个字符：</span><span style="">\n</span><span style="">，</span><span style="">\r</span><span style="">。</span></p><p><br></p>
</div>
</div>