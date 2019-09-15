# 题目描述


<p>
<span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">【</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">题目描述</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">给定一个包含</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> N </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">个点，</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">M </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">条边的无向图，每条边的边权均为</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> 1</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">。</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">再给定</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> K </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">个三元组（</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">A</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">B</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">C</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">）</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">，表示从</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> A </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">点走到</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> B </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">点后不能往</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> C </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">点走。注意三元组是有序的，如可</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">以从</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> B </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">点走到</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> A </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">点再走到</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> C</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">。</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">现在你要在</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> K </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">个三元组的限制下，找出</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> 1 </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">号点到</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> N </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">号点的最短路径，并输出任意一条合法路径，会有</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> spj (Special Judge) </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">检查你的输出。</span> 
</p>
<p>
<span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">【输人格式】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;">    </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">输入文件第一行有三个数</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> N</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">M</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">K</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">，意义如题目所述。</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">接下来</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> M </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">行每行两个数</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> A</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">B</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">，表示</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> A</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">B </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">间有一条边。</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">再下面</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> K </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">行，每行三个数（</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">A</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">B</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">C</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">）描述一个三元组。</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">【输出格式】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">输出文件共两行数，第一行一个数</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> S </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">表示最短路径长度。</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">第二行</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> S+1 </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">个数，表示从</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> 1 </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">到</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> N </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">所经过的节点。</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">【输入样例】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">4 4 2 </span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">1 2</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">2 3</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">3 4 </span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">1 3 </span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">1 2 3 </span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">1 3 4</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">【输出样例】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">4</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">1 3 2 3 4</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">【</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">数据规模</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">】</span><span style="color:#000000;font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">对于</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> 40%</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">的数据满足</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> N</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">≤</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">10</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">M</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">≤</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">20</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">K</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">≤</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">5</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">。</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> </span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">对于</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> 100%</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">的数据满足</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"> N</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">≤</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">3000</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">M</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">≤</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">20000</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">K</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">≤</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;">100000</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">。</span><span style="font-size:12.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
