<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>W教授在T大学计算机系里开了一门“数字逻辑”课，主要讲授如何设计逻辑电路。这一天，W教授布置了一个实验：设计并实现一个4端输入、4端输出的逻辑译码电路。设计这样的电路原本并不困难，但是，教授给出了如下的要求：</p>
<p>1．只允许使用2端输入、1端输出的门电路作为实现电路的组件，而且可用门电路的种类和数目都已给定；</p>
<p>2．使用最少数目的门电路。</p>
<p> </p>
<p>这两个要求难倒了全系的同学，于是，Q同学找到了正在参加CTSC（中国队选拔赛）的你，希望你能帮忙编写一个程序，自动找出符合要求的连接方式。</p>
<p> </p>
<p>在数字逻辑中，所有信号都可以看作只有两个值：“高电平”和“低电平”，分别用“1”和“0”来表示。</p>
<p>一个门电路元件的特性由其输入/输出功能表唯一给出，所谓功能表，就是输入信号电平与输出信号电平之间的关系表。比如，“与门”的符号和功能表如下图所示：</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="66">
<p>X</p>
</td>
<td valign="top" width="66">
<p>Y</p>
</td>
<td valign="top" width="66">
<p>S</p>
</td>
</tr>
<tr>
<td valign="top" width="66">
<p>0</p>
</td>
<td valign="top" width="66">
<p>0</p>
</td>
<td valign="top" width="66">
<p>0</p>
</td>
</tr>
<tr>
<td valign="top" width="66">
<p>1</p>
</td>
<td valign="top" width="66">
<p>0</p>
</td>
<td valign="top" width="66">
<p>0</p>
</td>
</tr>
<tr>
<td valign="top" width="66">
<p>0</p>
</td>
<td valign="top" width="66">
<p>1</p>
</td>
<td valign="top" width="66">
<p>0</p>
</td>
</tr>
<tr>
<td valign="top" width="66">
<p>1</p>
</td>
<td valign="top" width="66">
<p>1</p>
</td>
<td valign="top" width="66">
<p>1</p>
</td>
</tr>
</tbody>
</table>
<p> </p>
<p>如果“与门”的两个输入端X和Y都是高电平“1”，则输出端S也是高电平“1”，否则，输出端S是低电平“0”。</p>
<p>假定，本次实验提供的门电路都具有输入对称性，即交换两个输入端的信号，输出不变。但是，如果门电路的输入端悬空（即没有加输入信号），则输出无意义。</p>
<p> </p>
<p>在连接电路的过程中，一个门电路的输出端可以将信号送到其他多个元件的输入端；而门电路的一个输入端则只能接收来自一个输出端的信号。</p>
<p><br> 另外，规定信号必须单向传输，即一个门电路的输出不能直接或间接通过其他门电路回到同一门电路的输入端。如下图所示即为两种不允许的连接方式：</p>
<p> </p>
<p><br> 要求你设计的译码电路是一个有四个输入端和四个输出端的逻辑电路，该译码电路的输入和输出关系通过功能表给出，即给出每种输入组合下的四个输出端的情况。显然，一共有16种输入组合。比如，一个由前述“与门”构成的2输入，2输出的简单译码电路如下表所示（其中，A1, A2是输入端，Y1, Y2是输出端）：</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="66">
<p>A1</p>
</td>
<td valign="top" width="66">
<p>A2</p>
</td>
<td valign="top" width="66">
<p>Y1</p>
</td>
<td valign="top" width="66">
<p>Y2</p>
</td>
</tr>
<tr>
<td valign="top" width="66">
<p>0</p>
</td>
<td valign="top" width="66">
<p>0</p>
</td>
<td valign="top" width="66">
<p>0</p>
</td>
<td valign="top" width="66">
<p>0</p>
</td>
</tr>
<tr>
<td valign="top" width="66">
<p>1</p>
</td>
<td valign="top" width="66">
<p>0</p>
</td>
<td valign="top" width="66">
<p>0</p>
</td>
<td valign="top" width="66">
<p>0</p>
</td>
</tr>
<tr>
<td valign="top" width="66">
<p>0</p>
</td>
<td valign="top" width="66">
<p>1</p>
</td>
<td valign="top" width="66">
<p>0</p>
</td>
<td valign="top" width="66">
<p>0</p>
</td>
</tr>
<tr>
<td valign="top" width="66">
<p>1</p>
</td>
<td valign="top" width="66">
<p>1</p>
</td>
<td valign="top" width="66">
<p>1</p>
</td>
<td valign="top" width="66">
<p>1</p>
</td>
</tr>
</tbody>
</table>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>其中第一行为一个正整数，表示元件的种类数，其后有连续的行，每行描述一种元件。对正整数：</p>
<p>文件的第行有四个以空格隔开的整数，依次为：</p>
<p> </p>
<p>其中，正整数表示第<em>k</em>种元件的数目（<em>k</em>即这种元件的种类编号），所有元件的数目之和不会超过10（用于实验的经费并不充足）。表示两个输入端分别为和时的输出，即是三个非0即1的数，分别表示在两个输入端均为0；两个输入端一个为0另一个为1；以及两个输入端均为1的时候，该元件的输出。</p>
<p>输入文件的第到第行，表示需组成的集成电路的功能表，每行有8个数，分别为0或1。其中，前四个数依次对应四个输入端（编号为1～4）的信号，不存在两行的前四个数完全相同；而后面四个数则对应在各输入端信号为前四个数时，四个输出端依次应输出的信号。</p>
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

<p align="left"><span style="font-size: 10px;">文件的第一行为一个单词，&ldquo;Yes&rdquo;或&ldquo;No&rdquo;&mdash;&mdash;如果存在符合要求的设计方案，则为&ldquo;Yes&rdquo;，否则为&ldquo;No&rdquo;。</span></p>
<p align="left">如果第一行是&ldquo;No&rdquo;，则文件结束，否则&mdash;&mdash;</p>
<p align="left">第二行只有一个非负整数<em>p</em>，表示最少需要的门电路数目。下面<em>p</em>行分别给出每个门电路在电路中的连接情况的描述。每行有四个以空格隔开的正整数：S K A B，其中S表示该门电路的编号（所有用到的门电路按5~<em>p</em>+4编号，1~4的编号用来表示四个输入端）；K表示该元件的种类编号（按照输入文件中的顺序由1~编号）；A和B分别表示接入该元件的两个输入端的门电路或译码电路输入端的编号（其中，A&lt;S，B&lt;S）。</p>
<p align="left">最后一行有四个正整数，表示组成的译码电路的四个输出端分别所接的元件的编号（在1~<em>p</em>之间）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1</p>
<p>5 0 1 0</p>
<p>0 0 0 0 0 0 0 0</p>
<p>1 0 0 0 1 0 0 0</p>
<p>0 1 0 0 1 1 0 0</p>
<p>1 1 0 0 0 1 0 0</p>
<p>0 0 1 0 0 1 1 0</p>
<p><span style="">0 1 1 0 1 0 1 0</span></p>
<p>1 0 1 0 1 1 1 0</p>
<p>1 1 1 0 0 0 1 0</p>
<p>0 0 0 1 0 0 1 1</p>
<p>1 0 0 1 1 0 1 1</p>
<p>0 1 0 1 1 1 1 1</p>
<p>1 1 0 1 0 1 1 1</p>
<p>0 0 1 1 0 1 0 1</p>
<p>1 0 1 1 1 1 0 1</p>
<p>0 1 1 1 1 0 0 1</p>
<p>1 1 1 1 0 0 0 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<div>
<table cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top">
<p>Yes</p>
<p>3</p>
<p>5 1 2 1</p>
<p>6 1 3 2</p>
<p>7 1 4 3</p>
<p>5 6 7 4</p>
</td>
</tr>
</tbody>
</table>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>实际上，每个数据的限时是不一样的。</p>
</div>
</div>