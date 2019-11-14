
# Description

<div class="content"><div style="line-height: 20pt"><span style="font-size: 12pt">SJF</span><span style="font-size: 12pt">最近经常在机房打</span><span style="font-size: 12pt">PES</span><span style="font-size: 12pt">，由于</span><span style="font-size: 12pt">SJF</span><span style="font-size: 12pt">过于扭曲的心灵，他总是让自己的队员自动申请黄牌，可是由于其技术有限</span><span style="font-size: 12pt">(</span><span style="font-size: 12pt">比如乌龙</span><span style="font-size: 12pt">T</span><span style="font-size: 12pt">不进</span><span style="font-size: 12pt">)</span><span style="font-size: 12pt">或</span><span style="font-size: 12pt">RP</span><span style="font-size: 12pt">太低，有时连犯规都没机会，有时甚至犯了规裁判也不判，这让</span><span style="font-size: 12pt">SJF</span><span style="font-size: 12pt">很郁闷。</span></div>
<div style="line-height: 20pt"><span style="font-size: 12pt">       </span><span style="font-size: 12pt">我们把球场抽象成一个长</span><span style="font-size: 12pt">w</span><span style="font-size: 12pt">宽</span><span style="font-size: 12pt">h</span><span style="font-size: 12pt">的矩形，其四个顶点分别为</span><span style="font-size: 12pt">(w, 0)</span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">(w,h)</span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">(0,h)</span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">(0,0)</span><span style="font-size: 12pt">，而裁判位于点</span><span style="font-size: 12pt">(w0,0)</span><span style="font-size: 12pt">。场上有</span><span style="font-size: 12pt">n</span><span style="font-size: 12pt">名球员，第</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">名球员坐标为</span><span style="font-size: 12pt">(x<i><sub>i</sub>,y<sub>i</sub></i>)</span><span style="font-size: 12pt">，活动区域为半径为</span><span style="font-size: 12pt">r<sub>i</sub></span><span style="font-size: 12pt">的圆，每名球员的活动区域不可能到球场之外并且不会有两名球员的活动区域有公共点。若</span><span style="font-size: 12pt">SJF</span><span style="font-size: 12pt">位于某球队员的活动区域内或被某名球员的活动区域挡住了裁判的视线，那么即使</span><span style="font-size: 12pt">SJF</span><span style="font-size: 12pt">的动作再恶劣裁判都会以看不清为由拒绝判罚，否则</span><span style="font-size: 12pt">SJF</span><span style="font-size: 12pt">就能如其扭曲的心灵所愿从而吃牌。假设</span><span style="font-size: 12pt">SJF</span><span style="font-size: 12pt">出现在球场上每个点概率都相等，</span><span style="font-size: 12pt">SJF</span><span style="font-size: 12pt">想知道自己有多大的概率吃牌。</span></div>
<div style="line-height: 20pt"> </div></div>

# Input

<div class="content"><div style="line-height: 20pt"><span style="font-size: 12pt">       </span><span style="font-size: 12pt">第一行</span><span style="font-size: 12pt">4</span><span style="font-size: 12pt">个非负数，</span><span style="font-size: 12pt">n</span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">w</span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">h</span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">w0</span><span style="font-size: 12pt">，如题中所述，其中只有</span><span style="font-size: 12pt">n</span><span style="font-size: 12pt">为整数。</span></div>
<div style="line-height: 20pt"><span style="font-size: 12pt">       </span><span style="font-size: 12pt">接下来</span><span style="font-size: 12pt">n</span><span style="font-size: 12pt">行，每行三个浮点数</span><span style="font-size: 12pt">x<sub>i</sub></span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">y<sub>i</sub></span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">r<sub>i</sub></span><span style="font-size: 12pt">，如题中所述。</span></div>
<div style="line-height: 20pt"> </div></div>

# Output

<div class="content"><div style="line-height: 20pt"><span style="font-size: 12pt">       </span><span style="font-size: 12pt">一个数</span><span style="font-size: 12pt">ans</span><span style="font-size: 12pt">，表示</span><span style="font-size: 12pt">SJF</span><span style="font-size: 12pt">吃牌的概率。</span></div>
<div style="line-height: 20pt"><span style="font-size: 12pt">       ans</span><span style="font-size: 12pt">精度任意，但你的答案与标准答案的误差不能超过</span><span style="font-size: 12pt">10<sup>-5</sup></span><span style="font-size: 12pt">。</span></div>
<div style="line-height: 20pt"> </div></div>

# Sample Input

<div class="content"><span class="sampledata">       0 2 2 0<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
       1<br/>
 <br/>
数据说明<br/>
       无论SJF在哪里犯规裁判都看得见，所以SJF的黄牌是吃定了。<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p>存在精度误差，不要提交!</p><br/>
<p>对于100%的数据 0≤n≤1000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

