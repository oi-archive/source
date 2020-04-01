<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　求一个子树中的数的和.<br/>
　　要求支持以下操作:<br/>
　　1.Q x y 表示查询以x 为 根 y子树中的所有数的和.<br/>
　　2.R x y 将x-&gt;y的路径上的数翻转.<br/>
　　3.C x y 将x 的值 改为y.<br/>
　　4.L x y 将x,y相连.<br/>
　　5.U x y将以x为根,把y向其父亲的边删除.</div>
# 输入格式

<div class="pdcont">　　第一行两个数n,m,表示n个节点m个操作<br/>
　　下面m行,每行一个操作.</div>
# 输出格式

<div class="pdcont">　　对于每个询问,输出答案<br/>
　　1操作中,若x与y不连通则输出“Neroysq!”<br/>
　　2操作中,若x,y不连通则不操作<br/>
　　4操作中,若x,y已连通则不操作<br/>
　　5操作中,若x,y不连通或x == y则不操作</div>
# 样例输入

<div class="pddata">10 30<br/>
R 2 6<br/>
Q 7 1<br/>
U 1 7<br/>
Q 5 1<br/>
L 2 5<br/>
L 7 1<br/>
L 6 6<br/>
C 5 3<br/>
Q 1 5<br/>
C 3 1<br/>
Q 1 6<br/>
L 7 1<br/>
R 7 9<br/>
Q 1 9<br/>
L 2 7<br/>
R 8 7<br/>
Q 1 1<br/>
Q 9 6<br/>
R 9 7<br/>
L 5 3<br/>
Q 1 3<br/>
C 5 6<br/>
U 9 6<br/>
R 8 6<br/>
Q 7 7<br/>
L 7 6<br/>
Q 1 5<br/>
L 6 6<br/>
U 8 2<br/>
L 9 5</div>
# 样例输出

<div class="pddata">Neroysq!<br/>
Neroysq!<br/>
Neroysq!<br/>
Neroysq!<br/>
Neroysq!<br/>
3<br/>
Neroysq!<br/>
1<br/>
7<br/>
7</div>
# 数据规模和约定

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">1-4<br/>
</td><td valign="top" style="border:solid 1.0pt">N,m   &lt;= 100,权值均小于10000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">5-8<br/>
</td><td valign="top" style="border:solid 1.0pt">N,m   &lt;= 10000,权值均小于10000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">9-10<br/>
</td><td valign="top" style="border:solid 1.0pt">N,m   &lt;= 30000,且无2,5操作,权值均小于10000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">11-16<br/>
</td><td valign="top" style="border:solid 1.0pt">N,m   &lt;= 50000,且无2操作,权值均小于10000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">17-20<br/>
</td><td valign="top" style="border:solid 1.0pt">N,m   &lt;= 80000,操作无限制,权值均小于10000<br/>
</td></tr></tbody></table></div>

</div>