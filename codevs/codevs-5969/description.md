<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p> <span style=""><span style="">•</span></span><span style="">　在</span><span style="">FJOI2010</span><span style="">夏令营快要结束的时候，很多营员提出来要把整个夏令营期间的资料</span><span style="">刻录成一张光盘给大家，以便大家回去后继续学习。组委会觉得这个主意不错！可</span><span style="">是组委会一时没有足够的空光盘，没法保证每个人都能拿到刻录上资料的光盘，怎</span><span style="">么办呢？！ </span> <span style=""><span style="">•</span></span>　　<span style="">DYJ</span><span style="">分析了一下所有营员的地域关系，发现有些营员是一个城市的，其实他们只</span><span style="">需要一张就可以了，因为一个人拿到光盘后，其他人可以带着</span><span style="">U</span><span style="">盘之类的东西去拷贝</span><span style="">啊！ </span> <span style=""><span style="">•</span></span><span style="">　　他们愿意某一些人到他那儿拷贝资料，当然也可能不愿意让另外一些人到他那</span><span style="">儿拷贝资料，这与我们</span><span style="">FJOI</span><span style="">宣扬的团队合作精神格格不入！！！ </span> <span style=""><span style="">•</span></span><span style="">　　现在假设总共有</span><span style="">N</span><span style="">个营员（</span><span style="">2&lt;=N&lt;=200</span><span style="">），每个营员的编号为</span><span style="">1~N</span><span style="">。</span><span style="">DYJ</span><span style="">给每个</span><span style="">人发了一张调查表，让每个营员填上自己愿意让哪些人到他那儿拷贝资料。当然，</span><span style="">如果</span><span style="">A</span><span style="">愿意把资料拷贝给</span><span style="">B</span><span style="">，而</span><span style="">B</span><span style="">又愿意把资料拷贝给</span><span style="">C</span><span style="">，则一旦</span><span style="">A</span><span style="">获得了资料，则</span><span style="">B</span><span style="">，</span><span style="">C</span><span style="">都会获得资料。 </span> <span style=""><span style="">•</span></span><span style="">　　现在，请你编写一个程序，根据回收上来的调查表，帮助</span><span style="">DYJ</span><span style="">计算出组委会至少</span><span style="">要刻录多少张光盘，才能保证所有营员回去后都能得到夏令营资料？</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style=""><strong>先是一个数</strong></span><span style="font-family: 'Times New Roman';"><strong>N</strong></span><span style=""><strong>，接下来的</strong></span><span style="font-family: 'Times New Roman';"><strong>N</strong></span><span style=""><strong>行，分别表示各个营员愿意把自己获得的资料拷贝给其他哪些营员。即输入数据的第</strong></span><span style="font-family: 'Times New Roman';"><strong>i+1</strong></span><span style=""><strong>行表示第</strong></span><span style="font-family: 'Times New Roman';"><strong>i</strong></span><span style=""><strong>个营员愿意把资料拷贝给那些营员的编号，以一个</strong></span><span style="font-family: 'Times New Roman';"><strong>0</strong></span><span style=""><strong>结束。如果一个营员不愿意拷贝资料给任何</strong></span><span style=""><strong>人，则相应的行只有</strong></span><span style="font-family: 'Times New Roman';"><strong>1</strong></span><span style=""><strong>个</strong></span><span style="font-family: 'Times New Roman';"><strong>0</strong></span><span style=""><strong>，一行中的若干数之间用一个空格隔开。</strong></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;<span style="font-family: 宋体;font-size:20px;color:#002060"><strong>一个正整数，表示最少要刻录的光盘数。 </strong></span> &nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p> <span style=""><strong>5 </strong></span></p><p><span style=""><strong>2 4 3 0 </strong></span></p><p><span style=""><strong>4 5 0 </strong></span></p><p><span style=""><strong>0 </strong></span></p><p><span style=""><strong>0 </strong></span></p><p><span style=""><strong>1 0 </strong></span>  </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style=""><strong>1</strong></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">2&lt;=N&lt;=200</span></p>
</div>
</div>