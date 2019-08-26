
# Description

<div class="content"><div align="center"></div>
<div><span style="font-size: 12pt">    </span><span style="font-size: 12pt">条纹游戏是一个双人的游戏。所需要的物品有一个棋盘以及三种颜色的长方形条纹，这三种颜色分别是红色、绿色和蓝色。所有的红色条纹的尺寸是</span><span style="font-size: 12pt">c*1</span><span style="font-size: 12pt">，所有的绿色条纹的尺寸是</span><span style="font-size: 12pt">z*1</span><span style="font-size: 12pt">，所有的蓝色条纹的尺寸是</span><span style="font-size: 12pt">n*1</span><span style="font-size: 12pt">，这里</span><span style="font-size: 12pt">c,z,n</span><span style="font-size: 12pt">是正整数。每种颜色的条纹每个游戏者都拥有无限多个。</span></div>
<div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">一个棋盘是一个尺寸为</span><span style="font-size: 12pt">p*1</span><span style="font-size: 12pt">的长方形，由</span><span style="font-size: 12pt">p</span><span style="font-size: 12pt">个</span><span style="font-size: 12pt">1*1</span><span style="font-size: 12pt">的方格组成。</span></div>
<div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">游戏者轮流走，每一步都是由一个游戏者任选一种长方形条纹覆盖到棋盘上，并要求遵循以下规则：</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: -21pt"><span style="font-size: 12pt">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span style="font-size: 12pt">条纹不能伸出棋盘之外。</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: -21pt"><span style="font-size: 12pt">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span style="font-size: 12pt">不能覆盖在已有的条纹之上（即使部分也不行）。</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: -21pt"><span style="font-size: 12pt">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span style="font-size: 12pt">条纹的边缘必须与棋盘方格的边缘相重叠。谁不能再走，谁就输了。</span></div>
<div style="margin: 0cm 0cm 0pt 21pt"> </div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">先手是指在游戏中第一个走的游戏者。那么是否不管后手怎么走，先手都有必胜策略呢？</span></div>
<div><b><span style="font-size: 12pt">任务：</span></b></div>
<div><span style="font-size: 12pt">写一个程序：</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: -21pt"><span style="font-size: 12pt">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span style="font-size: 12pt">读入条纹的尺寸以及至少一个棋盘的尺寸。</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: -21pt"><span style="font-size: 12pt">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span style="font-size: 12pt">对每一个给出的棋盘判断先手是否必胜。</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: -21pt"><span style="font-size: 12pt">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span style="font-size: 12pt">将结果输出</span><span style="font-size: 12pt">。</span></div>
<div> </div></div>

# Input

<div class="content"><div> <span style="font-size: 12pt">第一行包含三个整数</span><span style="font-size: 12pt">c,z,n(1&lt;=c,z,,n&lt;=1000)</span><span style="font-size: 12pt">，表示三种条纹的长度，依次为红色，绿色以及蓝色。每两个数之间都用空格隔开。</span></div>
<div><span style="font-size: 12pt">       </span><span style="font-size: 12pt">文件的第二行包括一个整数</span><span style="font-size: 12pt">m</span><span style="font-size: 12pt">（</span>1 &lt;= m &lt;= 1000<span style="font-size: 12pt">）表示需要考虑的不同棋盘个数。以下</span><span style="font-size: 12pt">3</span><span style="font-size: 12pt">到</span><span style="font-size: 12pt">m+2</span><span style="font-size: 12pt">行每行包括一个整数</span><span style="font-size: 12pt">p</span><span style="font-size: 12pt">（</span><span style="font-size: 12pt">1&lt;=p&lt;=1000</span><span style="font-size: 12pt">）。第</span><span style="font-size: 12pt">i+2</span><span style="font-size: 12pt">行表示第</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">个棋盘的长度。</span></div>
<div> </div></div>

# Output

<div class="content"><div><span style="font-size: 12pt">   </span><span style="font-size: 12pt">应当包含</span><span style="font-size: 12pt">m</span><span style="font-size: 12pt">行。只有一个数字应当被写入文件的第</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">行：</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: -21pt"><span style="font-size: 12pt">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span style="font-size: 12pt">1</span><span style="font-size: 12pt">—如果对第</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">个棋盘先手有必胜策略。</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: -21pt"><span style="font-size: 12pt">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span style="font-size: 12pt">2</span><span style="font-size: 12pt">—其它。</span></div>
<div> </div></div>

# Sample Input

<div class="content"><span class="sampledata">1 5 1<br/>
<br/>
<br/>
3 <br/>
1 <br/>
5 <br/>
6 <br/>
<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> <br/>
1<br/>
1 <br/>
2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

