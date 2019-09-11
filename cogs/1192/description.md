# 题目描述


<p>
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">这个题目要求你编写一个程序来解决一个纵横填字游戏。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    这个游戏比我们在报纸上见到的通常的填字游戏要简单。游戏仅给出单词的起始位置，方面</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">横向或纵向</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">以及单词的长度。只要单词的长度正好，游戏中能填入任何一个来自词典的单词。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    在游戏中单词相交处的字母必须相同，当然，任何单词只准使用一次。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    思考一下以下这个游戏。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">例如，假定从上到下有<span>5</span><span>行，用</span><span>0</span><span>到</span><span>4</span><span>来表示，从左到右有</span><span>5</span><span>列，用</span><span>0</span><span>到</span><span>4</span><span>来表示。我们用</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">X, Y</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">来表示填字游戏中第<span>X</span><span>列和第</span><span>Y</span><span>行的字母。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;" align="center">
<tbody>
<tr>
<td style="border:0.5000pt solid #000000;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid #000000;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid #000000;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid #000000;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid #000000;background:#737373;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid #000000;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid #000000;background:#737373;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid #000000;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid #000000;background:#737373;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid #000000;background:#737373;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid #000000;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid #000000;background:#737373;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid #000000;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid #000000;background:#737373;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid #000000;background:#737373;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid #000000;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid #000000;background:#737373;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid #000000;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid #000000;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid #000000;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid #000000;background:#737373;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid #000000;background:#737373;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid #000000;background:#737373;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid #000000;background:#737373;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid #000000;background:#737373;" valign="top" width="18">
<p style="text-align:center;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<br/>
</td>
</tr>
</tbody>
</table>
<p style="text-indent:21.7500pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">在这个游戏中，我们需填入<span>5</span><span>个单词：在</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0, 0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">的右边填入一个<span>4</span><span>个字母的单词，在</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0, 0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">的下方填入一个<span>4</span><span>个字母的单词，在</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2, 0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">的下方填入一个<span>4</span><span>个字母的单词，在</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0, 2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">的右边填入一个<span>3</span><span>个字母的单词，最后在</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2, 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">的右边填入一个<span>3</span><span>个字母的单词。字典上所有的单词都能使用但最多只能使用一次。例如，以下是一个可能的解决方案。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">（<span>0, 0</span><span>）右边，</span><span>LATE</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">（<span>0, 0</span><span>）下面，</span><span>LIED</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">（<span>2, 0</span><span>）下面，</span><span>TELL</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">（<span>2, 3</span><span>）右边，</span><span>LOW</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    输入文件的第一行是作为字典使用的—个文本文件名，你可以假定这个文件存在，是可读的并且包含最多不超过<span>100000</span><span>个单词，并且按词典顺序存储，每行一个单词。字典中所有的单词所含的字母可以是大写或小写</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">在这个问题中字母的大小写是无关紧要的</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">。你可以假设字典中所有单词的长度不超过<span>20</span><span>个字符。输入文件的下一行包含一个整数</span><span>n</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">n<span>≤</span><span>15</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，表示要填的单词的数量。接下来的<span>n</span><span>行中每行给出关于一个单词的提示，在每个提示中分别给出单词的首字母在填字游戏中的列和行的位置，后面根据单词的方向是横向还是纵向，相应跟字符</span><span>A</span><span>或字符</span><span>D</span><span>，最后一个数表示该单词的长度，以上数据之间均用空格隔开。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    你能作以下的进一步的假设。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    （<span>1</span><span>）填字游戏的尺寸不超过</span><span>10</span><span>×</span><span>10</span><span>。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    （<span>2</span><span>）游戏盘中放得下所有的单词。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    （<span>3</span><span>）用给定的词典是能够破解出该游戏的。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    输出文件应该包含<span>n</span><span>行，输出游戏中可填入的所有单词。单词应该每行出现一个，并且按输入文件中提示的顺序输出。每个单词中所有的字母必须是大写的。所有的单词必须来自给定的词典文件</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">忽略大小写</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">。任何单词只能使用一次。对于给定输入文件可能有大量的正确解决方案，你只须输出其中的任意一个解决方案。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【样例】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">puzzle.in</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">puzzle.out</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">words.txt</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">LATE</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">LIED</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0 0 A 4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">TELL</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0 0 D 4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">EEL</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2 0 D 4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">LOW</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0 2 A 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2 3 A 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<br/>
</p>
