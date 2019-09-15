# 题目描述


<p align="center" style="text-align:center;">
<b><span style="font-size:16pt;font-family:&#39;Microsoft YaHei&#39;;">终极装备</span><span style="color:red;font-family:&#39;Microsoft YaHei&#39;;">(besta.pas/c/cpp)</span></b> 
</p>
<p>
<b><span style="font-family:&#39;Microsoft YaHei&#39;;">题目描述：</span><span></span></b> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;">近日</span><span style="font-family:&#39;Microsoft YaHei&#39;;">DT</span><span style="font-family:&#39;Microsoft YaHei&#39;;">中的</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Henry</span><span style="font-family:&#39;Microsoft YaHei&#39;;">和</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Geer</span><span style="font-family:&#39;Microsoft YaHei&#39;;">两人沉迷于仙剑</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;">这款经典的游戏中（都怪</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Michael</span><span style="font-family:&#39;Microsoft YaHei&#39;;">，是他把这个游戏推荐给他们的，才让他们如此沉迷，无心学习！不过这款游戏的确不错，想当年</span> <span style="font-family:&#39;Microsoft YaHei&#39;;">……哦，对不起，扯远了，回正题）。</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;">Henry</span><span style="font-family:&#39;Microsoft YaHei&#39;;">和</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Geer</span><span style="font-family:&#39;Microsoft YaHei&#39;;">经过一段复杂的迷宫（游戏里的迷宫多得很，有不好走！苦了两位啊），并且在</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Michael</span><span style="font-family:&#39;Microsoft YaHei&#39;;">的帮助之下，他们终于到了女娲遗迹这个地方，并且各自学会了一套终极魔法！同时还得到了一批终极装备！（晕！一批终极装备！真不知道编游戏的人怎么想的，既然是终极装备，为何弄那么多出来啊！）问题来了，在他们得到这些终极装备之前他们还有一些能和终极装备媲美的装备，并且数量和终极装备的数量一样，他们得到这些终极装备后就想让自己操控的游戏人物变得更强，但是一个人物最大负重为</span><span style="font-family:&#39;Microsoft YaHei&#39;;">M</span><span style="font-family:&#39;Microsoft YaHei&#39;;">，每个装备可提升人物</span><span style="font-family:&#39;Microsoft YaHei&#39;;">V[i]</span><span style="font-family:&#39;Microsoft YaHei&#39;;">能量值，自身重量为</span><span style="font-family:&#39;Microsoft YaHei&#39;;">W[i]</span><span style="font-family:&#39;Microsoft YaHei&#39;;">（我们把这两个值称为该装备的属性），</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Henry</span><span style="font-family:&#39;Microsoft YaHei&#39;;">和</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Geer</span><span style="font-family:&#39;Microsoft YaHei&#39;;">想让自己操控的人物在最大负重的范围内获得最大的能量值，（并且同一种装备只能选择一样或者不选）</span><span style="font-family:&#39;Microsoft YaHei&#39;;">{A</span><span style="font-family:&#39;Microsoft YaHei&#39;;">：什么叫同一种装备？</span><span style="font-family:&#39;Microsoft YaHei&#39;;"> B</span><span style="font-family:&#39;Microsoft YaHei&#39;;">：这个，这个…</span><span style="font-family:&#39;Microsoft YaHei&#39;;">     </span><span style="font-family:&#39;Microsoft YaHei&#39;;">晕</span> <span style="font-family:&#39;Microsoft YaHei&#39;;">！</span><span style="font-family:&#39;Microsoft YaHei&#39;;">    </span><span style="font-family:&#39;Microsoft YaHei&#39;;">就是如果</span><span style="font-family:&#39;Microsoft YaHei&#39;;">V1[i]</span><span style="font-family:&#39;Microsoft YaHei&#39;;">和</span><span style="font-family:&#39;Microsoft YaHei&#39;;"> V2[i]</span><span style="font-family:&#39;Microsoft YaHei&#39;;">就是同一种装备，就是</span><span style="font-family:&#39;Microsoft YaHei&#39;;">i</span><span style="font-family:&#39;Microsoft YaHei&#39;;">相同</span><span style="font-family:&#39;Microsoft YaHei&#39;;">}</span><span style="font-family:&#39;Microsoft YaHei&#39;;">于是作为</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Oier</span><span style="font-family:&#39;Microsoft YaHei&#39;;">的他们编写了一个程序来帮他们来选择装备！（学习这个就是安逸，打游戏都要轻松一点！）</span><span></span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;"> </span> 
</p>
<p>
<b><span style="font-family:&#39;Microsoft YaHei&#39;;">输入数据：</span></b><span></span> 
</p>
<p style="margin-left:10.5pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;">第一行</span><span style="font-family:&#39;Microsoft YaHei&#39;;">3</span><span style="font-family:&#39;Microsoft YaHei&#39;;">个数：</span><span style="font-family:&#39;Microsoft YaHei&#39;;">M</span><span style="font-family:&#39;Microsoft YaHei&#39;;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">N</span><span style="font-family:&#39;Microsoft YaHei&#39;;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">T</span><span style="font-family:&#39;Microsoft YaHei&#39;;">。</span><span style="font-family:&#39;Microsoft YaHei&#39;;">M</span><span style="font-family:&#39;Microsoft YaHei&#39;;">代表人物的最大负重，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">N</span><span style="font-family:&#39;Microsoft YaHei&#39;;">为得到的终极装备数量，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">T</span><span style="font-family:&#39;Microsoft YaHei&#39;;">为人物不带任何装备的能量值。</span><span></span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;"> </span> 
</p>
<p style="margin-left:94.5pt;text-indent:-94.5pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;">  </span><span style="font-family:&#39;Microsoft YaHei&#39;;">接下来</span><span style="font-family:&#39;Microsoft YaHei&#39;;">N</span><span style="font-family:&#39;Microsoft YaHei&#39;;">行，一行</span><span style="font-family:&#39;Microsoft YaHei&#39;;">4</span><span style="font-family:&#39;Microsoft YaHei&#39;;">个数，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">V1[i],W1[i],V2[i],W2[i]    </span> 
</p>
<p style="margin-left:94.5pt;text-indent:-26.25pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;">V1[i],W1[i]</span><span style="font-family:&#39;Microsoft YaHei&#39;;">：表示原来装备的属性（</span><span style="font-family:&#39;Microsoft YaHei&#39;;">V1[i]</span><span style="font-family:&#39;Microsoft YaHei&#39;;">：能量值；</span><span style="font-family:&#39;Microsoft YaHei&#39;;">W1[i]</span><span style="font-family:&#39;Microsoft YaHei&#39;;">：物品重量）；</span><span></span> 
</p>
<p style="text-indent:68.25pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;">V2[i],W2[i]</span><span style="font-family:&#39;Microsoft YaHei&#39;;">：表示得到的终极装备属性（</span><span style="font-family:&#39;Microsoft YaHei&#39;;">V2[i]</span><span style="font-family:&#39;Microsoft YaHei&#39;;">：能量值；</span><span style="font-family:&#39;Microsoft YaHei&#39;;">W2[i]</span><span style="font-family:&#39;Microsoft YaHei&#39;;">：物品重量）；</span><span></span> 
</p>
<p style="margin-left:94.5pt;text-indent:-94.5pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;"> </span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;"> </span> 
</p>
<p>
<b><span style="font-family:&#39;Microsoft YaHei&#39;;">输出数据：</span><span></span></b> 
</p>
<p style="text-indent:10.5pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;">一个数，就是人物能够达到的最大能量值。</span><span></span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;"> </span> 
</p>
<p>
<b><span style="font-family:&#39;Microsoft YaHei&#39;;">样例：</span><span></span></b> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;">INPUT</span><span style="font-family:&#39;Microsoft YaHei&#39;;">：</span><span></span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;">  50  3  20</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;">  12  18  23  19</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;">  17  10  30  24</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;">  20  20  17  20</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;">OUTPUT</span><span style="font-family:&#39;Microsoft YaHei&#39;;">：</span><span></span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;"> 80</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;"> </span> 
</p>
<p>
<b><span style="font-family:&#39;Microsoft YaHei&#39;;">时间限制：</span><span></span></b> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;">  </span><span style="font-family:&#39;Microsoft YaHei&#39;;">每测试点时间</span><span style="font-family:&#39;Microsoft YaHei&#39;;">&lt;=1S</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;">数据范围：</span><span></span> 
</p>
<p style="text-indent:10.5pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;">（</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1&lt;=M,T&lt;=10000,1&lt;=N&lt;=200</span><span style="font-family:&#39;Microsoft YaHei&#39;;">）</span><span></span> 
</p>
<p style="text-indent:15.75pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;">(1&lt;=W[i],V[i]&lt;=10000)</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;">  </span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;"> </span> 
</p>
<p>
<b><span style="font-family:&#39;Microsoft YaHei&#39;;color:red;">温馨提示</span></b><span style="font-family:&#39;Microsoft YaHei&#39;;">：本次比赛比较简单，大家不要见外，不要</span><span style="font-family:&#39;Microsoft YaHei&#39;;">BS</span><span style="font-family:&#39;Microsoft YaHei&#39;;">。重在找回你的比赛信心。</span><span></span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;">    </span> 
</p>
<p style="text-indent:31.5pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;"> </span> 
</p>
<p style="text-indent:31.6pt;">
<b><span style="font-family:&#39;Microsoft YaHei&#39;;color:#0070C0;">感谢大家的参与！！！</span><span style="color:#0070C0;"></span></b> 
</p>
<p style="text-indent:42.15pt;">
<b><span style="font-family:&#39;Microsoft YaHei&#39;;color:red;">预祝大家在</span><span style="color:red;font-family:&#39;Microsoft YaHei&#39;;">2007noip</span></b><b><span style="font-family:&#39;Microsoft YaHei&#39;;color:red;">中取得优异成绩！！！！！！</span><span style="color:red;"></span></b> 
</p>
<p style="text-indent:58.0pt;">
<b><span style="font-family:&#39;Microsoft YaHei&#39;;color:#00B0F0;">大家共同努力，为</span><span style="color:#00B0F0;font-family:&#39;Microsoft YaHei&#39;;">noip</span></b><b><span style="font-family:&#39;Microsoft YaHei&#39;;color:#00B0F0;">奋进！！！！！！！！！</span><span style="color:#00B0F0;"></span></b> 
</p>
