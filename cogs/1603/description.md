# 题目描述


<h3>
【题目描述】
</h3>
<p style="background:#FFFFFF;line-height:18pt;text-indent:35pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="letter-spacing:0.4pt;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">由于施惠国的统治极其残暴，每年从13个区中每个区中选出2名“贡品”参加饥饿游戏，而参加游戏的人必须在险恶的自然环境中杀死其余的人才能存活。游戏只会有一个人活下来 </span><span style="letter-spacing:0.4pt;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">凯特尼斯·伊夫狄恩</span><span style="letter-spacing:0.4pt;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">和同区的</span><span style="letter-spacing:0.4pt;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">皮塔·麦拉克</span><span style="letter-spacing:0.4pt;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">在历经千难万阻后活了下来，然而残忍的游戏只允许一人存活，正当两人准备同时吃下有毒的果实自杀的时候，统治者被打动了，他说：你们两个人跟我玩一个游戏，你赢了，我就让你们两个都活下来。女主角</span><span style="letter-spacing:0.4pt;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">凯特尼斯·伊夫狄恩接受了挑战</span><span style="letter-spacing:0.4pt;font-family:&#34;font-size:12pt;mso-spacerun:&#34;">。</span><span style="letter-spacing:0.4pt;font-family:&#34;font-size:12pt;font-weight:bold;mso-spacerun:&#34;"><!--?xml:namespace prefix = o ns = "urn:schemas-microsoft-com:office:office" /--><o:p></o:p></span> 
</p>
<p style="background:#FFFFFF;line-height:18pt;text-indent:22.5pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="letter-spacing:0.4pt;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">这个游戏是这样的，有n(n&lt;=20)个箱子，每个箱子里面有ai（ai&lt;=1000000000）个石头（怎么放进去的我就不知道了），两个人轮流进行操作（女主角先手），每一次操作可以将任意个（大于0个）</span><span style="letter-spacing:0.4pt;font-family:&#34;font-size:14pt;font-weight:bold;background-color:#E53333;mso-spacerun:&#34;">未打开的箱子</span><span style="letter-spacing:0.4pt;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">打开（一开始所有的箱子都是关闭的），或者在</span><span style="letter-spacing:0.4pt;font-family:&#34;font-size:14pt;font-weight:bold;background-color:#009900;mso-spacerun:&#34;">已经打开</span><span style="letter-spacing:0.4pt;font-family:&#34;font-size:14pt;background-color:#009900;mso-spacerun:&#34;">的</span><span style="letter-spacing:0.4pt;font-family:&#34;font-size:14pt;font-weight:bold;background-color:#009900;mso-spacerun:&#34;">一个</span><span style="letter-spacing:0.4pt;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><span style="background-color:#009900;">箱子里拿走任意个（大于0个）石头（不能超过这个箱子现有的石头数）</span>。最后谁无法操作谁就输了。</span><span style="letter-spacing:0.4pt;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="background:#FFFFFF;line-height:18pt;text-indent:22.5pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="letter-spacing:0.4pt;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">现在给出n，和这n个箱子里的石头数ai，女主角想知道她是否有绝对的把握取得胜利（很明显她的对手“统治者”是绝顶聪明的）。<img alt="" src="/upload/image/20140419/20140419161527_99553.jpg"/></span><span style="letter-spacing:0.4pt;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<!--EndFragment-->
<h3>
【输入格式】
</h3>
<p style="background:#FFFFFF;line-height:18pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="letter-spacing:0.4pt;font-family:&#34;font-size:12pt;mso-spacerun:&#34;"> </span><span style="letter-spacing:0.4pt;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">第一行有一个正整数T（表示有T组测试数据），对于每组测试数据有两行，第一行为一个正整数n，接下来有 n个数，第 i 个数表示ai.</span><span style="letter-spacing:0.4pt;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<!--EndFragment-->
<h3>
【输出格式】
</h3>
<p style="margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="letter-spacing:0.4pt;font-family:&#34;font-size:14pt;font-weight:bold;mso-spacerun:&#34;"> </span><span style="letter-spacing:0.4pt;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">有T行：对于每一个测试数据，如果先手可以必胜则输出“Yes”，否则输出“No”（没有引号）。</span> 
</p>
<!--EndFragment-->
<h3>
【样例输入】
</h3>
<pre>5
5
18 11 16 19 15
5
18 12 17 10 18
5
17 7 1 10 1
5
19 5 16 19 8
5
18 18 7 4 9</pre>
<h3>
【样例输出】
</h3>
<pre>No
Yes
Yes
Yes
Yes</pre>
<h3>
【提示】
</h3>
<p style="text-indent:7pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#34;font-size:14pt;mso-spacerun:&#34;">40%的数据：n&lt;=5, T&lt;=5, ai不超过20</span><span style="font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="text-indent:7pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="font-family:&#34;font-size:14pt;mso-spacerun:&#34;">100%的数据：n&lt;=20，T&lt;=10,ai不超过1，000，000，000；</span><span style="font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<!--EndFragment-->
<h3>
【来源】
</h3>
<p>
HZOI
</p>
