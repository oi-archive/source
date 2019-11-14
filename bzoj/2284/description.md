
# Description

<div class="content"><div> </div>
<div> </div>
<div> </div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">相信大家都玩过贪食蛇游戏，现在有一个改版贪食蛇游戏，跟传统的贪食蛇游戏一样，贪食蛇在活动区域内运动，吃食物，但是这个改版的贪食蛇游戏有着一些特别的规则。</span></div>
<div style="text-indent: 24pt"> </div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">活动区域：</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">贪食蛇的活动区域是一个</span><span style="font-size: 12pt">R</span><span style="font-size: 12pt">行</span><span style="font-size: 12pt">C</span><span style="font-size: 12pt">列的网格</span><span style="font-size: 12pt">A</span><span style="font-size: 12pt">，贪食蛇活动不能超过这个网格的范围。第</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">行第</span><span style="font-size: 12pt">j</span><span style="font-size: 12pt">列的方格用</span><span style="font-size: 12pt">A<sub>i,j</sub></span><span style="font-size: 12pt">表示。每个方格有一个整数权值，记作</span><span style="font-size: 12pt">w(A<sub>ij</sub>)</span><span style="font-size: 12pt">。</span><span style="font-size: 12pt">0&lt;=w(A<sub>ij</sub>)&lt;=8</span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">w(A<sub>ij</sub>)=0</span><span style="font-size: 12pt">时，</span><span style="font-size: 12pt">A<sub>ij</sub></span><span style="font-size: 12pt">禁止进入；</span><span style="font-size: 12pt">w(A<sub>ij</sub>)&gt;0</span><span style="font-size: 12pt">时，</span><span style="font-size: 12pt">A<sub>ij</sub></span><span style="font-size: 12pt">允许进入。</span></div>
<div style="text-indent: 24pt"> </div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">方向：</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">对于</span><span style="font-size: 12pt">P=(X<sub>0</sub>,Y<sub>0</sub>)</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">Q=(X<sub>1</sub>,Y<sub>1</sub>)</span><span style="font-size: 12pt">，有以下四种基本方向：</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -21pt"><span style="font-size: 12pt">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span style="font-size: 12pt">正左</span><span style="font-size: 12pt">(L)</span><span style="font-size: 12pt">：</span><span style="font-size: 12pt">X<sub>0</sub>=X<sub>1</sub></span><span style="font-size: 12pt">且</span><span style="font-size: 12pt">Y<sub>0</sub>=Y<sub>1</sub>-1</span><span style="font-size: 12pt">，则称</span><span style="font-size: 12pt">P</span><span style="font-size: 12pt">位于</span><span style="font-size: 12pt">Q</span><span style="font-size: 12pt">的正左方向。</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -21pt"><span style="font-size: 12pt">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span style="font-size: 12pt">正右</span><span style="font-size: 12pt">(R)</span><span style="font-size: 12pt">：</span><span style="font-size: 12pt">X<sub>0</sub>=X<sub>1</sub></span><span style="font-size: 12pt">且</span><span style="font-size: 12pt">Y<sub>0</sub>=Y<sub>1</sub>+1</span><span style="font-size: 12pt">，则称</span><span style="font-size: 12pt">P</span><span style="font-size: 12pt">位于</span><span style="font-size: 12pt">Q</span><span style="font-size: 12pt">的正右方向。</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -21pt"><span style="font-size: 12pt">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span style="font-size: 12pt">正上</span><span style="font-size: 12pt">(U)</span><span style="font-size: 12pt">：</span><span style="font-size: 12pt">X<sub>0</sub>=X<sub>1</sub>-1</span><span style="font-size: 12pt">且</span><span style="font-size: 12pt">Y<sub>0</sub>=Y<sub>1</sub></span><span style="font-size: 12pt">，则称</span><span style="font-size: 12pt">P</span><span style="font-size: 12pt">位于</span><span style="font-size: 12pt">Q</span><span style="font-size: 12pt">的正上方向。</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -21pt"><span style="font-size: 12pt">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span style="font-size: 12pt">正下</span><span style="font-size: 12pt">(D)</span><span style="font-size: 12pt">：</span><span style="font-size: 12pt">X<sub>0</sub>=X<sub>1</sub>+1</span><span style="font-size: 12pt">且</span><span style="font-size: 12pt">Y<sub>0</sub>=Y<sub>1</sub></span><span style="font-size: 12pt">，则称</span><span style="font-size: 12pt">P</span><span style="font-size: 12pt">位于</span><span style="font-size: 12pt">Q</span><span style="font-size: 12pt">的正下方向。</span></div>
<div style="text-indent: 24pt"> </div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">贪食蛇：</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">贪食蛇</span><span style="font-size: 12pt">B</span><span style="font-size: 12pt">是占据若干方格的图形，占据的方格数为贪食蛇的长度，记为</span><span style="font-size: 12pt">m</span><span style="font-size: 12pt">，则贪食蛇从头到尾，用</span><span style="font-size: 12pt">B<sub>1</sub></span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">B<sub>2</sub></span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">……</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">B<sub>m</sub></span><span style="font-size: 12pt">表示。记</span><span style="font-size: 12pt">p</span><span style="font-size: 12pt">为贪食蛇的形态，若</span><span style="font-size: 12pt">Bi</span><span style="font-size: 12pt">位于第</span><span style="font-size: 12pt">X<sub>i</sub></span><span style="font-size: 12pt">行第</span><span style="font-size: 12pt">Y<sub>i</sub></span><span style="font-size: 12pt">列，则</span><span style="font-size: 12pt">p(B<sub>i</sub>)=(X<sub>i</sub>,Y<sub>i</sub>)</span><span style="font-size: 12pt">。初始情况下，</span><span style="font-size: 12pt">m=4</span><span style="font-size: 12pt">，且运动过程中始终需要满足以下限制：</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -21pt"><span style="font-size: 12pt">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span style="font-size: 12pt">对于</span><span style="font-size: 12pt">B<sub>i</sub></span><span style="font-size: 12pt">和</span><span style="font-size: 12pt">B<sub>i+1</sub>(1&lt;=i&lt;m)</span><span style="font-size: 12pt">，就是贪食蛇的前、后相邻两部分，必须满足</span><span style="font-size: 12pt">B<sub>i</sub></span><span style="font-size: 12pt">位于</span><span style="font-size: 12pt">B<sub>i+1</sub></span><span style="font-size: 12pt">的</span><span style="font-size: 12pt">L</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">R</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">U</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">D</span><span style="font-size: 12pt">四个方向之一。</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -21pt"><span style="font-size: 12pt">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span style="font-size: 12pt">对于</span><span style="font-size: 12pt">B<sub>i</sub></span><span style="font-size: 12pt">和</span><span style="font-size: 12pt">B<sub>j</sub>(1&lt;=i&lt;j&lt;=m)</span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">p(B<sub>i</sub>)=(X<sub>i</sub>,Y<sub>i</sub>)</span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">p(B<sub>j</sub>)=(X<sub>j</sub>,Y<sub>j</sub>)</span><span style="font-size: 12pt">，需要满足</span><span style="font-size: 12pt">X<sub>i</sub>!=X<sub>j</sub></span><span style="font-size: 12pt">或</span><span style="font-size: 12pt">Y<sub>i</sub>!=Y<sub>j</sub></span><span style="font-size: 12pt">。也就是说，贪食蛇身体的任意一部分不能相交。</span></div>
<div style="text-indent: 24pt"> </div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">食物：</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">贪食蛇的活动区域内存在一些食物。每个食物位于一个允许进入的方格上，食物不会重叠。每个食物只能被吃一次。</span></div>
<div style="text-indent: 24pt"> </div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">贪食蛇的运动：</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">如果贪食蛇的头部</span><span style="font-size: 12pt">B<sub>1</sub></span><span style="font-size: 12pt">的</span><span style="font-size: 12pt">L</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">R</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">U</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">D</span><span style="font-size: 12pt">四个方向之一的</span><span style="font-size: 12pt">A<sub>ij</sub></span><span style="font-size: 12pt">能进入，且</span><span style="font-size: 12pt">A<sub>ij</sub></span><span style="font-size: 12pt">上不存在食物，则贪食蛇可以向该方向运动，新的头部位于</span><span style="font-size: 12pt">A<sub>ij</sub></span><span style="font-size: 12pt">上。记</span><span style="font-size: 12pt">p’</span><span style="font-size: 12pt">为贪食蛇新的形态，则：</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -21pt"><span style="font-size: 12pt">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span style="font-size: 12pt">p’(B<sub>k</sub>)=p(B<sub>k-1</sub>)</span><span style="font-size: 12pt">，当</span><span style="font-size: 12pt">2&lt;=k&lt;=m</span><span style="font-size: 12pt">。</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -21pt"><span style="font-size: 12pt">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span style="font-size: 12pt">p’(B<sub>k</sub>)=(i,j)</span><span style="font-size: 12pt">，当</span><span style="font-size: 12pt">k=1</span></div>
<div style="text-indent: 24pt"> </div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">贪食蛇的进食：</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">如果贪食蛇的头部</span><span style="font-size: 12pt">B<sub>1</sub></span><span style="font-size: 12pt">的</span><span style="font-size: 12pt">L</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">R</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">U</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">D</span><span style="font-size: 12pt">四个方向之一的</span><span style="font-size: 12pt">A<sub>ij</sub></span><span style="font-size: 12pt">能进入，且</span><span style="font-size: 12pt">A<sub>ij</sub></span><span style="font-size: 12pt">上存在食物，则贪食蛇可以向该方向进食，新的头部位于</span><span style="font-size: 12pt">A<sub>ij</sub></span><span style="font-size: 12pt">上，蛇的新长度</span><span style="font-size: 12pt">m’=m+1</span><span style="font-size: 12pt">。记</span><span style="font-size: 12pt">p’</span><span style="font-size: 12pt">为贪食蛇新的位置，则：</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -21pt"><span style="font-size: 12pt">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span style="font-size: 12pt">p’(B<sub>k</sub>)=p(B<sub>k-1</sub>)</span><span style="font-size: 12pt">，当</span><span style="font-size: 12pt">2&lt;=k&lt;=m’</span><span style="font-size: 12pt">。</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -21pt"><span style="font-size: 12pt">l<span style="font: 7pt &#39;Times New Roman&#39;">        </span></span><span style="font-size: 12pt">p’(B<sub>k</sub>)=(i,j)</span><span style="font-size: 12pt">，当</span><span style="font-size: 12pt">k=1</span></div>
<div style="text-indent: 24pt"> </div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">注意：运动或进食后的贪食蛇形态，仅仅需要考虑变换后的形态是否满足限制，不需要考虑变换的过程。也就是说，原来形态合法的贪食蛇的头部可以运动到尾部的位置，因为在变换后头部和尾部仍不会重叠。</span></div>
<div style="text-indent: 24pt"> </div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">运动或进食所需要的时间：</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">贪食蛇运动或进食，需要消耗时间。设运动或进食前头部所在的方格是</span><span style="font-size: 12pt">P</span><span style="font-size: 12pt">，运动或进食后头部所在的方格是</span><span style="font-size: 12pt">Q</span><span style="font-size: 12pt">，则此次运动或进食的所消耗的时间为</span><span style="font-size: 12pt">|w(P)-w(Q)|+1</span><span style="font-size: 12pt">。</span></div>
<div style="text-indent: 24pt"> </div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">游戏的会在开始前给出贪食蛇的初始位置和所有食物的位置。你的任务是，以最少的时间令贪食蛇吃完所有食物。</span></div></div>

# Input

<div class="content"><div style="text-indent: 24pt"><span style="font-size: 12pt">第一行，两个正整数</span><span style="font-size: 12pt">R</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">C</span><span style="font-size: 12pt">。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">接下来</span><span style="font-size: 12pt">R</span><span style="font-size: 12pt">行，每行</span><span style="font-size: 12pt">C</span><span style="font-size: 12pt">个没有空格分隔的数字。其中第</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">行第</span><span style="font-size: 12pt">j</span><span style="font-size: 12pt">个数字为</span><span style="font-size: 12pt">w(A<sub>ij</sub>)</span><span style="font-size: 12pt">。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">接下来</span><span style="font-size: 12pt">4</span><span style="font-size: 12pt">行，每行</span><span style="font-size: 12pt">2</span><span style="font-size: 12pt">个正整数。第</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">行的两个整数</span><span style="font-size: 12pt">X<sub>i</sub></span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">Y<sub>i</sub></span><span style="font-size: 12pt">，表示</span><span style="font-size: 12pt">p(B<sub>i</sub>)=(X<sub>i</sub>,Y<sub>i</sub>)</span><span style="font-size: 12pt">。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">接下来一个正整数</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">，表示食物的数量。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">接下来</span><span style="font-size: 12pt">N</span><span style="font-size: 12pt">行，每行</span><span style="font-size: 12pt">2</span><span style="font-size: 12pt">个正整数</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">、</span><span style="font-size: 12pt">j</span><span style="font-size: 12pt">，表示</span><span style="font-size: 12pt">A<sub>ij</sub></span><span style="font-size: 12pt">上存在一个食物。</span></div></div>

# Output

<div class="content"><div style="margin: 13pt 0cm"> </div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">如果贪食蛇不能吃到所有的食物，输出</span><span style="font-size: 12pt">“No solution.”</span><span style="font-size: 12pt">（不包括引号）。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">否则，输出：</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">第一行，一个整数，表示所需花费的时间；</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
11011<br/>
11011<br/>
11011<br/>
11011<br/>
11411<br/>
1 1<br/>
2 1<br/>
3 1<br/>
4 1<br/>
4<br/>
5 5<br/>
4 4<br/>
2 5<br/>
1 4<br/>
【样例输出】<br/>
21<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p><p>对于20%的数据，N &lt;= 1。<br/><br/>
对于40%的数据，N &lt;= 2。<br/><br/>
对于60%的数据，N &lt;= 3。<br/><br/>
对于100%的数据，N &lt;= 4。<br/><br/>
 <br/><br/>
对于30%的数据，R * C &lt;= 36。<br/><br/>
对于100%的数据，R &lt;= 12，C &lt;= 12。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Stage2 day2">Stage2 day2</a></p></div>

