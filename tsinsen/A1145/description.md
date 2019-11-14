<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　栈是计算机中经典的数据结构，简单的说，栈就是限制在一端进行插入删除操作的线性表。栈有两种最重要的操作，即pop（从栈顶弹出一个元素）和push（将一个元素进栈）。<br/>
　　栈的重要性不言自明，任何一门数据结构的课程都会介绍栈。宁宁同学在复习栈的基本概念时，想到了一个书上没有讲过的问题，而他自己无法给出答案，所以需要你的帮忙。</div>
# 问题描述

<div class="pdcont"><img width="603" height="293" src="source/tsinsen/A1145/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9RlI0MzdMMjU=.do"/><br/>
　　宁宁考虑的是这样一个问题：一个操作数序列，从1，2，一直到n（图示为1到3的情况），栈A的深度大于n。<br/>
　　现在可以进行两种操作，<br/>
　　1.将一个数，从操作数序列的头端移到栈的头端（对应数据结构栈的push操作）<br/>
　　2. 将一个数，从栈的头端移到输出序列的尾端（对应数据结构栈的pop操作）<br/>
　　使用这两种操作，由一个操作数序列就可以得到一系列的输出序列，下图所示为由<br/>
　　1 2 3<br/>
　　生成序列<br/>
　　2  3 1<br/>
　　的过程。（原始状态如上图所示）<br/>
<img width="603" height="333" src="source/tsinsen/A1145/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9ZFJmcm1uN2c=.do"/><br/>
　　你的程序将对给定的n，计算并输出由操作数序列1，2，…，n经过操作可能得到的输出序列的总数。</div>
# 输入格式

<div class="pdcont">　　输入文件只含一个整数n（1≤n≤18）</div>
# 输出格式

<div class="pdcont">　　输出文件只有一行，即可能输出序列的总数目</div>
# 样例输入

<div class="pddata">3</div>
# 样例输出

<div class="pddata">5</div>

</div>