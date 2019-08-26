
# Description

<div class="content"><div style="text-indent: 24pt"><span style="font-size: medium">Bytetel公司想改进它们生产的计算机，它们想用一些特殊的汇编电路门系统来替代汇编程序。汇编程序由许多单独的任务组成，每个任务有四个元素。</span></div>
<div style="margin: 0cm 0cm 0pt 45pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span>两个寄存器作为输入</span></div>
<div style="margin: 0cm 0cm 0pt 45pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span>一个运算符</span></div>
<div style="margin: 0cm 0cm 0pt 45pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span>一个寄存器作为输出</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">我们假设最多有26个寄存器，分别用小写字母a～z表示。此外有四种运算，用大写字母A，B，C，D表示。</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">一个汇编电路包括：</span></div>
<div style="margin: 0cm 0cm 0pt 45pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span>输入端映射到寄存器，该寄存器的初值作为电路的输入</span></div>
<div style="margin: 0cm 0cm 0pt 45pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span>输出端同样映射到寄存器，电路的输出作为给寄存器的值</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">一个电路由许多门组成，每个门包括两个输入和一个输出，它将输入的值进行一个基本运算，并将结果输出。门的输入和整个电路的输出要么与其它门的输出端相连，要么和整个电路的输出端相连。门的输出和整个电路的输入要么与其它门的输入端相连，要么和整个电路的输出端相连。电路门之间不会形成回路。</span></div>
<div style="text-indent: 24pt"><span style="font-size: medium">如果一个电路门系统和一个汇编程序对于任意的输入，它们的输出都相同，那么我们就称它们是等效的。</span></div>
<div><span style="font-size: medium">任务：</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -18pt"><span style="font-size: medium">1、读入一个汇编程序的描述</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -18pt"><span style="font-size: medium">2、计算最少要几个门可以组成与汇编程序等效的电路系统</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -18pt"><span style="font-size: medium">3、输出</span></div></div>

# Input

<div class="content"><div> </div>
<div style="text-indent: 24pt"><span style="font-size: medium">第一行包含一个整数n，(1&lt;=n&lt;1000)，表示汇编程序的指令数。以后n行每行包含4个字母表示一条指令，第一个字母为A,B,C,D中的一个，表示操作的类型，第二和第三个字母为小写字母，表示输入的寄存器，第四个字母也是小写字母，表示输出的寄存器。</span></div></div>

# Output

<div class="content"><p> </p>
<div style="text-indent: 24pt"><span style="font-size: medium">包含一个整数，表示与给汇编程序等效的电路门系统中最少需要几个电路门。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">8<br/>
Afbc<br/>
Bfbd<br/>
Cddd<br/>
Bcbc<br/>
Afcc<br/>
Afbf<br/>
Cfbb<br/>
Dfdb<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
6</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

