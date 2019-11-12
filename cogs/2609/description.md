# 题目描述


<p>
【题目描述】
</p>
<p>
阿法汪和贝塔喵是两个绝顶聪明的AI，如今他们在玩一个很有趣的游戏。
</p>
<p>
游戏规则是这样的：有一棵有根树，这颗树的每个叶子上都有一个金币，每个金币都有各自的价值Wi。最开始，有一枚棋子在根节点，阿法汪和贝塔喵轮流走棋，每次可以将棋子从当前节点移动到它的某个儿子节点上，直到到达某个叶子，阿法汪就能获得叶子上的金币。
</p>
<p>
阿法汪希望自己获得的金币价值尽量大，而贝塔喵希望阿法汪获得的金币价值尽量小。由于两个AI都是非常聪明的，所以它们总会采用最优秀的策略。现在我们希望知道，阿法汪最终能获得价值为多少金币。
</p>
<p>
【输入格式】
</p>
<p>
第一行包含一个整数n，表示这颗树的节点数。
</p>
<p>
接下来n行中，第i行第一个整数Vi表示第i个节点有Vi个儿子。
</p>
<p>
如果Vi &gt; 0 则接下来有Vi个整数，表示第i个节点的Vi个儿子
</p>
<p>
如果Vi = 0则接下来还有一个整数，表示第i个节点上的金币的价值W
</p>
<p>
我们规定1号节点是这颗树的根节点
</p>
<p>
【输出格式】
</p>
<p>
输出一个整数，表示阿法汪最终能获得的金币的价值
</p>
<p>
【样例输入】
</p>
<p>
interesting.in
</p>
<p>
10
</p>
<p>
2 2 4
</p>
<p>
2 3 5
</p>
<p>
0 -100
</p>
<p>
3 6 7 9
</p>
<p>
0 -200
</p>
<p>
0 100
</p>
<p>
2 8 10
</p>
<p>
0 -50
</p>
<p>
0 200
</p>
<p>
0 50
</p>
<p>
【样例输出】
</p>
<p>
interesting.out
</p>
<p>
50
</p>
<p>
【样例说明】
</p>
<p>
 树的形态是这样的，最终棋子会走到10号节点
</p>
<p>
【提示】
</p>
<p>
</p><table style="border-collapse:collapse;width:50.0000%;">
<tbody>
<tr>
<td style="border:1.0000pt outset #000000;" width="27" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">编号</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="38" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">n</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="111" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">Wi</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="104" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">特殊限制</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:1.0000pt outset #000000;" width="27" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">1</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="38" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">=4</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="111" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">-1e9&lt;=Wi&lt;=1e9</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="104" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">叶子数&lt;=10</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:1.0000pt outset #000000;" width="27" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">2</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="38" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">=20</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="111" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">-1e9&lt;=Wi&lt;=1e9</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="104" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">叶子数&lt;=10</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:1.0000pt outset #000000;" width="27" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">3</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="38" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">=1e5</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="111" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">1&lt;=Wi&lt;=2</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="104" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">所有金币只有一个价值为2的叶子</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:1.0000pt outset #000000;" width="27" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">4</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="38" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">=1e5</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="111" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">1&lt;=Wi&lt;=2</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="104" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">所有金币只有一个价值为2的叶子</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:1.0000pt outset #000000;" width="27" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">5</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="38" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">=1e5</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="111" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">1&lt;=Wi&lt;=2</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="104" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">所有金币只有一个价值为2的叶子</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:1.0000pt outset #000000;" width="27" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">6</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="38" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">=1e5</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="111" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">-1e9&lt;=Wi&lt;=1e9</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="104" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">无</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:1.0000pt outset #000000;" width="27" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">7</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="38" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">=1e5</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="111" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">-1e9&lt;=Wi&lt;=1e9</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="104" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">无</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:1.0000pt outset #000000;" width="27" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">8</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="38" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">=1e5</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="111" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">-1e9&lt;=Wi&lt;=1e9</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="104" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">无</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:1.0000pt outset #000000;" width="27" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">9</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="38" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">=1e5</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="111" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">-1e9&lt;=Wi&lt;=1e9</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="104" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">无</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:1.0000pt outset #000000;" width="27" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">10</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="38" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">=1e5</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="111" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">-1e9&lt;=Wi&lt;=1e9</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
<td style="border:1.0000pt outset #000000;" width="104" valign="center">
<p class="MsoNormal" style="text-align:left;">
<span style="font-family:宋体;font-size:12.0000pt;">无</span><span style="font-family:Calibri;font-size:10.5000pt;"></span> 
</p>
</td>
</tr>
</tbody>
</table>
<p></p>
<p class="p">
<span style="font-family:Calibri;font-size:12.0000pt;"><span>以上是原题数据范围，鉴于该题当场</span>AC<span>人数过半（实际上是</span><span>Mike</span><span>太懒），本题数据范围的为</span><span>10</span><span>号描述的那样。</span></span><span style="font-family:Calibri;font-size:12.0000pt;"></span> 
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
【来源】
</p>
<p>
<br/>
</p>
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">2016河南省队集训，数据是Mike造的，如果数据有误请联系Mike，谁有官测直接刷掉就好。</span> 
</p>
<p>
<br/>
</p>
