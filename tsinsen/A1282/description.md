# 题面



<div class="pdcont"><b>题目描述</b><br/>
　　有一棵含N个结点的树，树上每条边(ai,bi)都有一个权值wi。树上每个结点涂有一个初始颜色ci。现在有很多次修改操作，第i次修改会将结点xi的颜色修改成yi。请在所有修改前和每次修改之后输出一个数，表示对应时刻最近的同色结点对的距离。<br/>
　　其中，距离定义为树上两点的最短路的距离。最短路按边的权值wi计算。<br/>
<b>输入格式</b><br/>
　　第一行一个数N。第二行N个数依次给出每个结点的初始颜色ci。<br/>
　　下面N-1行每行三个数ai,bi,wi，表示一条权值为wi的树边(ai,bi)。<br/>
　　下面一个数M表示修改次数。<br/>
　　下面M行每行两个数xi,yi，表示将结点xi的颜色修改为yi。<br/>
<b>输出格式</b><br/>
　　输出包含M+1行，第一行表示初始局面的最近同色结点对距离，下面M行依次表示每次修改后的最近同色结点对距离。如果某时刻没有同色点对，则在对应行输出-1。<br/>
<b>样例输入</b><br/>
　　5<br/>
　　2 2 3 2 3<br/>
　　3 5 9<br/>
　　1 3 1<br/>
　　2 1 2<br/>
　　4 1 8<br/>
　　4<br/>
　　2 3<br/>
　　2 1<br/>
　　1 1<br/>
　　2 2<br/>
　　样例输出<b></b><br/>
　　2<br/>
　　3<br/>
　　8<br/>
　　2<br/>
　　9<b></b><br/>
<b>样例说明</b><br/>
　　每行输出对应的解释为：<br/>
　　2 -&gt; 最近的是1和2，颜色均为2，距离为2<br/>
　　3 -&gt; 最近的是2和3，颜色均为3，距离为3<br/>
　　8 -&gt; 最近的是1和4，颜色均为2，距离为8<br/>
　　2 -&gt; 最近的是1和2，颜色均为1，距离为2<br/>
　　9 -&gt; 最近的是3和5，颜色均为3，距离为9<b></b><br/>
<b> </b><br/>
<b>数据范围</b><br/>
　　本题有十个测试点。十个测试点的数据规模如下：<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">编号<br/>
</td><td valign="top" style="border:solid 1.0pt">N<br/>
</td><td valign="top" style="border:solid 1.0pt">M<br/>
</td><td valign="top" style="border:solid 1.0pt">出现过的颜色的总数<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">1000<br/>
</td><td valign="top" style="border:solid 1.0pt">0<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=10<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">2000<br/>
</td><td valign="top" style="border:solid 1.0pt">0<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=2000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">5000<br/>
</td><td valign="top" style="border:solid 1.0pt">0<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=5000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">7000<br/>
</td><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=7000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">9000<br/>
</td><td valign="top" style="border:solid 1.0pt">10<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=9000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">6<br/>
</td><td valign="top" style="border:solid 1.0pt">10000<br/>
</td><td valign="top" style="border:solid 1.0pt">100<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=10000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">10000<br/>
</td><td valign="top" style="border:solid 1.0pt">10000<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=50<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">8<br/>
</td><td valign="top" style="border:solid 1.0pt">12000<br/>
</td><td valign="top" style="border:solid 1.0pt">10000<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=12000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">9<br/>
</td><td valign="top" style="border:solid 1.0pt">12000<br/>
</td><td valign="top" style="border:solid 1.0pt">12000<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=12000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">10<br/>
</td><td valign="top" style="border:solid 1.0pt">12000<br/>
</td><td valign="top" style="border:solid 1.0pt">12000<br/>
</td><td valign="top" style="border:solid 1.0pt">&lt;=12000<br/>
</td></tr></tbody></table>　　另外，对于所有数据，有：<br/>
　　1 &lt;= ai &lt;= N, 1 &lt;= bi &lt;= N, 1 &lt;= xi &lt;= N;<br/>
　　1&lt;=wi&lt;=10000<br/>
　　1 &lt;= ci &lt;= 10<sup>9</sup>, 1 &lt;= yi &lt;= 10<sup>9</sup></div>



