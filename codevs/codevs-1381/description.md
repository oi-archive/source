<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>对于一群要互送礼物的朋友，你要确定每个人送出的礼物比收到的多多少<span style="font-family: 'Times New Roman';">(and vice versa for those who view gift giving with cynicism)</span>。<br>在这一个问题中，每个人都准备了一些钱来送礼物，而这些钱将会被平均分给那些将收到他的礼物的人。<br>然而，在任何一群朋友中，有些人将送出较多的礼物<span style="font-family: 'Times New Roman';">(</span>可能是因为有较多的朋友<span style="font-family: 'Times New Roman';">)</span>，有些人有准备了较多的钱。<br>给出一群朋友， 没有人的名字会长于 <span style="font-family: 'Times New Roman';">14 </span>字符，给出每个人将花在送礼上的钱，和将收到他的礼物的人的列表，<br>请确定每个人收到的比送出的钱多的数目。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<table border="1" cellpadding="0" style="">
<tbody>
<tr>
<td width="120"><span style="">第 <span style="font-family: 'Times New Roman';">1 </span>行<span style="font-family: 'Times New Roman';">:</span></span></td>
<td width="623">
<p>人数<span style="font-family: 'Times New Roman';">NP,2&lt;= NP&lt;=10 </span></p>
</td>
</tr>
<tr>
<td width="120">
<p>第 <span style="font-family: 'Times New Roman';">2</span>到 <span style="font-family: 'Times New Roman';">NP+1 </span>行<span style="font-family: 'Times New Roman';">: </span></p>
</td>
<td width="623">
<p>这<span style="font-family: 'Times New Roman';">NP</span>个在组里人的名字　一个名字一行</p>
</td>
</tr>
<tr>
<td width="120">
<p>第<span style="font-family: 'Times New Roman';">NP</span>＋<span style="font-family: 'Times New Roman';">2</span>到最后：</p>
</td>
<td width="623">
<p>这里的<span style="font-family: 'Times New Roman';">NP</span>段内容是这样组织的：<br>第一行是将会送出礼物人的名字。<br>第二行包含二个数字<span style="font-family: 'Times New Roman';">:</span>　第一个是原有的钱的数目（在<span style="font-family: 'Times New Roman';">0</span>到<span style="font-family: 'Times New Roman';">2000</span>的范围里），第二个<span style="font-family: 'Times New Roman';">NGi</span>是将收到这个送礼者礼物的人的个数 如果 <span style="font-family: 'Times New Roman';">NGi </span>是非零的<span style="font-family: 'Times New Roman';">, </span>在下面 <span style="font-family: 'Times New Roman';">NGi </span>行列出礼物的接受者的名字，一个名字一行。</p>
</td>
</tr>
</tbody>
</table>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出 <span style="font-family: 'Times New Roman';">NP </span>行<br />每行是一个的名字加上空格再加上收到的比送出的钱多的数目。<br />对于每一个人，他名字的打印顺序应和他在输入的<span style="font-family: 'Times New Roman';">2</span>到<span style="font-family: 'Times New Roman';">NP</span>＋<span style="font-family: 'Times New Roman';">1</span>行中输入的顺序相同。所有的送礼的钱都是整数。<br />每个人把相同数目的钱给每位要送礼的朋友，而且尽可能多给，不能给出的钱被送礼者自己保留。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Times New Roman';">5<br>dave<br>laura<br>owen<br>vick<br>amr<br>dave<br>200 3<br>laura<br>owen<br>vick<br>owen<br>500 1<br>dave<br>amr<br>150 2<br>vick<br>owen<br>laura<br>0 2<br>amr<br>vick<br>vick<br>0 0</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Times New Roman';">dave 302<br>laura 66<br>owen -359<br>vick 141<br>amr -150</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>测试系统是 <span style="font-family: 'Times New Roman';">Linux </span>符合标准的 <span style="font-family: 'Times New Roman';">Unix </span>的协定。<br>用<span style="font-family: 'Times New Roman';">'\n'</span>作为行的结束。<br>这和　<span style="font-family: 'Times New Roman';">Windows </span>系统用<span style="font-family: 'Times New Roman';">'\n' </span>和 <span style="font-family: 'Times New Roman';">'\r'</span>作为行的结束是不同的。<br>你的程序不要被这困住了</p>
</div>
</div>