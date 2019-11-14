<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小J<span style="">是国家图书馆的一位图书管理员，他的工作是管理一个巨大的书架。虽然他很能吃苦耐劳，但是由于这个书架十分巨大，所以他的工作效率总是很低，以致他面临着被解雇的危险，这也正是他所郁闷的。</span></p>
<p>具体说来，书架由N<span style="">个书位组成，编号从1</span><span style="">到N</span><span style="">。每个书位放着一本书，每本书有一个特定的编码。</span></p>
<p>小J<span style="">的工作有两类：</span></p>
<p>1. 图书馆经常购置新书，而书架任意时刻都是满的，所以只得将某位置的书拿掉并换成新购的书。</p>
<p>2. 小J<span style="">需要回答顾客的查询，顾客会询问某一段连续的书位中某一特定编码的书有多少本。</span></p>
<p> </p>
<p>例如，共5<span style="">个书位，开始时书位上的书编码为1</span><span style="">，2</span><span style="">，3</span><span style="">，4</span><span style="">，5</span></p>
<p>一位顾客询问书位1<span style="">到书位3</span><span style="">中编码为“2</span><span style="">”的书共多少本，得到的回答为：1</span></p>
<p>一位顾客询问书位1<span style="">到书位3</span><span style="">中编码为“1</span><span style="">”的书共多少本，得到的回答为：1</span></p>
<p>此时，图书馆购进一本编码为“1<span style="">”的书，并将它放到2</span><span style="">号书位。</span></p>
<p>一位顾客询问书位1<span style="">到书位3</span><span style="">中编码为“2</span><span style="">”的书共多少本，得到的回答为：0</span></p>
<p>一位顾客询问书位1<span style="">到书位3</span><span style="">中编码为“1</span><span style="">”的书共多少本，得到的回答为：2</span></p>
<p>……</p>
<p> </p>
<p>你的任务是写一个程序来回答每个顾客的询问。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数N<span style="">，M</span><span style="">，表示一共N</span><span style="">个书位，M</span><span style="">个操作。</span></p>
<p>接下来一行共N<span style="">个整数数A1,A2</span>…AN<span style="">，Ai</span><span style="">表示开始时位置i</span><span style="">上的书的编码。</span></p>
<p>接下来M<span style="">行，每行表示一次操作，每行开头一个字符</span></p>
<p>若字符为‘C<span style="">’，表示图书馆购进新书，后接两个整数A(1&lt;=A&lt;=N)</span><span style="">，P</span><span style="">，表示这本书被放在位置A</span><span style="">上，以及这本书的编码为P</span><span style="">。</span></p>
<p>若字符为‘Q<span style="">’，表示一个顾客的查询，后接三个整数A</span><span style="">，B</span><span style="">，K(1&lt;=A&lt;=B&lt;=N)</span><span style="">，表示查询从第A</span><span style="">书位到第Ｂ书位（包含Ａ和Ｂ）中编码为Ｋ的书共多少本。</span></p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">对每一个顾客的查询，输出一个整数，表示顾客所要查询的结果。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 5</p>
<p>1 2 3 4 5</p>
<p>Q 1 3 2</p>
<p>Q 1 3 1</p>
<p>C 2 1</p>
<p>Q 1 3 2</p>
<p>Q 1 3 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>
<p>1</p>
<p>0</p>
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p>对于40%的数据，1&lt;=N,M&lt;=5000</p>
<p>对于100%的数据，1&lt;=N,M&lt;=100000</p>
<p>对于100%的数据，所有出现的书的编码为不大于2147483647的正数。</p>
</div>
</div>
</div>