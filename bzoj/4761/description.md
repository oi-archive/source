
# Description

<div class="content"><div>Bessie has gotten herself stuck on the wrong side of Farmer John&#39;s barn again, and since her vision </div>
<div>is so poor, she needs your help navigating across the barn.The barn is described by an N×N grid of </div>
<div>square cells (2≤N≤20), some being empty and some containing impassable haybales. Bessie starts in </div>
<div>the lower-left corner (cell 1,1) and wants to move to the upper-right corner (cell N,N). You can gui</div>
<div>de her by telling her a sequence of instructions, each of which is either &#34;forward&#34;, &#34;turn left 90 d</div>
<div>egrees&#34;, or &#34;turn right 90 degrees&#34;. You want to issue the shortest sequence of instructions that wi</div>
<div>ll guide her to her destination. If you instruct Bessie to move off the grid (i.e., into the barn wa</div>
<div>ll) or into a haybale, she will not move and will skip to the next command in your sequence.Unfortun</div>
<div>ately, Bessie doesn&#39;t know if she starts out facing up (towards cell 1,2) or right (towards cell 2,1</div>
<div>). You need to give the shortest sequence of directions that will guide her to the goal regardless o</div>
<div>f which case is true. Once she reaches the goal she will ignore further commands.</div>
<div></div>
<div>给定一个N*N的网格(N&lt;=20)，你从左下角出发，要到达右上角，网格中会有障碍物你要给定一个长度最短的行为序</div>
<div>列（往前走，左转，右转），使得无论Bessie处于左下角时是头朝向上还是朝向左都可以在执行完这个序列后到达</div>
<div>右上角如果当前的行为会导致Bessie走到障碍物上或者越界，则Bessie会忽视这个行为</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains N.</div>
<div>第一行为N表示网格大小</div>
<div>Each of the NN following lines contains a string of exactly N characters, representing the barn. The</div>
<div> first character of the last line is cell 1,1. The last character of the first line is cell N, N.Eac</div>
<div>h character will either be an H to represent a haybale or an E to represent an empty square.</div>
<div></div>
<div>接下来N行每行N列，描述这个网格，H表示障碍物，E表示空地</div>
<div></div>
<div>It is guaranteed that cells 1,1 and N,N will be empty, and furthermore it is guaranteed that there i</div>
<div>s a path of empty squares from cell 1,1 to cell N,N</div>
<div></div>
<div>数据保证左下角和右上角一定是空地，且一定有解</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>On a single line of output, output the length of the shortest sequence of directions that will guide</div>
<div> Bessie to the goal, irrespective whether she starts facing up or right.</div>
<div>输出最短命令序列的长度</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
EHE<br/>
EEE<br/>
EEE</span></div>

# Sample Output

<div class="content"><span class="sampledata">9<br/>
In this example, the instructions &#34;Forward, Right, Forward, Forward, Left, Forward, Left, Forward, F<br/>
orward&#34; will guide Bessie to the destination irrespective of her starting orientation.<br/>
当Bessie在左下角的时候，执行前进，右转，前进，前进，左转，前进，左转，前进，前进无论Bessie一开始是朝<br/>
向上还是朝向下，都可以到达右上角。</span></div>

# Hint

<div class="content"><p></p><p> <span style="font-family: arial, verdana, helvetica, sans-serif;">1.“无论Bessie处于左下角时是头朝向上还是朝向左”根据英文原文“Bessie doesn&#39;t know if she starts out facing up (towards cell 1,2) or right (towards cell 2,1).”应为无论Bessie处于左下角时是头朝向上还是朝向右</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/><br/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">2.漏了原题很重要的一点:&#34;Once she reaches the goal she will ignore further commands.&#34;即如果Bessie已经到达终点，她会忽视以后的所有行为</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

