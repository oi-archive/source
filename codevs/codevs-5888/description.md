<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">   当整个oi界陷入黑暗的时候，身为附中oi希望的f[j][k]大佬</span><span style="">想要用自己多年收藏的若干个妹子和若干个汉子将这些妹子和汉子并成一个最大的基因库，这样他就可以和他们一起造出世界上最厉害的人来拯救世界。（不要问我冯学怎么同时和妹子还有汉子造人）</span></p><p><span style="">   具体地来说每个妹子可以直接给给汉子Ei的基因</span><span style="">。而每个汉子含有两个接受端口和一个输出端口。汉子有两种：</span>A<span style="">类和</span>B<span style="">类。</span>A<span style="">类是喜欢冯学的，可以将两个接收端口的基因叠加并合成。</span>B<span style="">类是冯学喜欢的，可以将两个接受端口的基因量较大那个给冯学。</span></p><p><span style="">   现在有</span>n-1<span style="">个汉子，</span>n<span style="">个妹子。</span>f[j][k]<span style="">给出了汉子的连接方式，他想知道怎样放置妹子，能够使最后的基因量最大化。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">  第一行是一个字符串，表示连接的方式。给出的形式是这样的：</span>X<span style="">，表示一个单独的妹子的放置处；</span>AS1S2<span style="">，其中</span>S1<span style="">和</span>S2<span style="">表示两个输出基因，</span>A<span style="">表示使用A类汉子将基因并成一个，然后这本身也成为一个新的假妹子（和妹子功能一样）；</span>BS1S2<span style="">也是同理，只不过是使用B类汉子。并且保证</span>A<span style="">和</span>B<span style="">的个数为</span>n-1<span style="">个。</span>X<span style="">的个数为</span>n<span style="">个。</span></p><p><span style="">  第二行是</span>n<span style="">个正整数，表示这几个妹子。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family:宋体">&nbsp; &nbsp;一个数，表示最大的输出基因。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>Case 1：</p><p>BXBXX</p><p>8 2 3</p><p>Case 2：</p><p>AXBXX</p><p><span style="font-family: Calibri, sans-serif;">8  2  3</span></p><p><br></p><p><br></p><p><br></p><p><br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Case 1：</p><p>8</p><p>Case 2：</p><p>11</p><p>Case 2的说明：<br></p><p><img src="/source/codevs/codevs-5888/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy01ODg4L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvYmxvYl8yMDE3MDMyMTIwMTMwNV83ODIucG5n.png" title=""></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">对于</span>20%<span style="">的数据</span> n&lt;10</p><p><span style="">对于</span>60%<span style="">的数据</span> n&lt;=3000</p><p><span style="">对于</span>100%<span style="">的数据</span> n&lt;=200000 Ei&lt;=10000</p><p><br></p>
</div>
</div>