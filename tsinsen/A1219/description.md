<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　浩浩荡荡的cg大军发现了一座矿产资源极其丰富的城市，他们打算在这座城市实施新的采矿战略。<br/>
　　这个城市可以看成一棵有n个节点的有根树，我们把每个节点用1到n的整数编号。为了方便起见，对于任何一个非根节点v，它任何一个祖先的编号都严格小于v。树上的每个节点表示一个矿点，每条边表示一条街道。<br/>
　　作为cg大军的一个小队长，你拥有m个部下。你有一张二维的动态信息表，用T<sub>i,j</sub>表示第i行第j列的数据。当你被允许开采某个区域时，你可以将你的部下分配至各个矿点。在第i个矿点安排j个人可以获得T<sub>i,j</sub>单位的矿产。<br/>
　　允许开采的区域是这样描述的：给你一对矿点(u,v)，保证v是u的祖先（这里定义祖先包括u本身）；u为你控制的区域，可以在以u为根的子树上任意分配部下；u到v的简单路径（不包括u但包括v，若u=v则包括u）为探险路径，在该路径上你可以选择至多一个矿点安排部下。你这次开采的收益为安排有部下的矿点的收益之和。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含5个正整数n、m、A、B、Q。n为矿点的个数，m为部下的数量。A、B、Q是与动态信息表有关的数据。<br/>
　　第二行包含n-1个正整数，第i个数为F<sub>i+1</sub>，表示节点i+1的父亲。<br/>
　　接下来需要你用下文的方法依次生成n组数据，每组数据共m个。其中第i组的m个数据为信息表中第i行的m个数据。<br/>
　　紧接着一行包含一个正整数C，表示事件的数量。<br/>
　　最后给出C行，每行描述一个事件。每个事件会先给出一个0或1的整数。如果该数为0，则后面有一个正整数p，表示动态信息表有更新，你需要生成一组m个数据，来替换信息表中第p行的m个数据。如果该数为1，则后面有两个正整数u、v，表示出现了一个你可以开采的区域，你需要回答这次开采的收益。<br/>
　　同一行的各个数之间均用一个空格隔开，没有多余的空格和换行。<br/>
　　数据的生成方法如下：<br/>
　　每次生成一组m个从小到大排列的数据，替换动态信息表的一行。其中，从小到大第j个数替换信息表中第j列的数。<br/>
　　调用以下代码m次并排序得到一组数据。（注意可能会出现重复的数）<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">函数GetInt<br/>
A←((A xor B)+(B div X)+(B * X))and Y<br/>
B←((A xor B)+(A div X)+(A * X))and Y<br/>
返回(A xor B)mod Q<br/>
</td></tr></tbody></table><br/>
　　其中A、B、Q均用32位有符号整数保存（C/C++的signed long int类型，pascal的longint类型），X=2<sup>16</sup>，Y=2<sup>31</sup>-1，xor为位异或运算，div为整除运算，and为位且运算，mod为取余运算。由于只保留了低31位，易得我们不用考虑数据的溢出问题。（注意每次A和B都会被改变）</div>
# 输出格式

<div class="pdcont">　　对于每个开采事件（开头为1的事件），输出一行一个整数，为每次的收益。</div>
# 样例输入

<div class="pddata">10 5 1 2 10<br/>
1 1 3 3 4 4 6 6 9<br/>
4<br/>
1 6 3<br/>
1 9 1<br/>
0 1<br/>
1 1 1</div>
# 样例输出

<div class="pddata">11<br/>
9<br/>
12</div>
# 样例说明

<div class="pdcont">　　最初的信息表如下<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt"><br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">5<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">0<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">0<br/>
</td><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">9<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">5<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">0<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">5<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">8<br/>
</td><td valign="top" style="border:solid 1.0pt">8<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">6<br/>
</td><td valign="top" style="border:solid 1.0pt">0<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">8<br/>
</td><td valign="top" style="border:solid 1.0pt">9<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">6<br/>
</td><td valign="top" style="border:solid 1.0pt">8<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">8<br/>
</td><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">8<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">9<br/>
</td><td valign="top" style="border:solid 1.0pt">0<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">9<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">10<br/>
</td><td valign="top" style="border:solid 1.0pt">0<br/>
</td><td valign="top" style="border:solid 1.0pt">0<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">4<br/>
</td></tr></tbody></table><br/>
　　变化后的第1行为<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">7<br/>
</td></tr></tbody></table><br/>
　　第一次开采可以在矿点6、8、9、10任意安排，可以在矿点3或4中选取一个安排开采。一种最优安排是在矿点6安排4人，在矿点8安排1人。第二次开采可以在矿点9安排，可以在矿点6、4、3、1中选择一个安排。一种最优安排是在矿点9安排1人，在矿点6安排4人。</div>
# 数据规模和约定

<div class="pdcont">　　对于60%的数据，1&lt;=n&lt;=500, 1&lt;=m&lt;=20, 1&lt;=C&lt;=500<br/>
<br/>
　　对于100%的数据，1&lt;=n&lt;=20000, 1&lt;=m&lt;=50, 1&lt;=C&lt;=2000<br/>
<br/>
<br/>
　　时限2s</div>

</div>