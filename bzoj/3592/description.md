
# Description

<div class="content"><div>奇葩建筑家Silly Hook受雇于某GFS，在GFS耗费巨资买下的郊外一块风水宝地上设计奇葩别墅，但令他震惊的是，</div>
<div>一群DSJ对GFS的富贵生活深恶痛绝，决定打洞以搞破坏。问题描述在上一次的Challenge中，DSJ大获全胜，风水宝</div>
<div>地上已是千疮百孔。Silly Hook只得合理利用资源，用已有的洞作为建筑的基点，同时，他还叫上了他的J友Shabb</div>
<div>y Hook来帮助填洞。现在我们简化一下这个问题，初始土地上有n个洞（从1开始编号），然后在这片土地上会按顺</div>
<div>序发生一系列事件。</div>
<div>1. H x d表示x号洞的深度变化了d。如果d≤0，说明Shabby Hook填平了一点这个洞，</div>
<div>深度变小或无明显变化。否则就是DSJ继续打洞导致深度变大。</div>
<div>2. A m xi表示Silly Hook设计的别墅的地基位置，即由给出的m个洞（第i个洞的编号为xi）</div>
<div>按顺时针顺序构成的多边形。同时他在设计后想知道当时这个多边形内（包括边界）洞的深度之和以及最大深度。</div>
<div>Silly Hook和Shabby Hook现在对DSJ已经忍无可忍了，请你帮他们回答这些询问。</div>
<div>建筑家Silly Hook尽管奇葩，但设计的多边形至少还是不会自交的（除相邻边有一个公共点外其他边之间都没有公共点）。</div>
<div>此外，为了降低难度，Silly Hook保证设计的多边形两两只会在洞处相交，同时所有洞都可以通过多边形的边到达其他的洞</div>
<div>（即所有询问组成连通的平面图）。</div></div>

# Input

<div class="content"><div>第一行一个整数Case表示数据点编号。</div>
<div>接下来一行一个整数n表示初始洞的个数。</div>
<div>接下来n行，每行三个整数xyd，表示坐标为(x,y)处有一个深度为d的洞。</div>
<div>接下来一行一个整数Q表示事件的数量。</div>
<div>接下来Q个事件，每个事件的格式如上所述。</div>
<div>n,Q的规模：n,Q≤50000</div>
<div>多边形（不含线段）点数和S的规模：S≤160000</div>
<div>|x|,|y|的规模：|x|,|y|≤10000000</div>
<p></p></div>

# Output

<div class="content"><p>对于每个A事件输出两个整数表示当时该多边形内的洞的深度之和以及最大深度</p></div>

# Sample Input

<div class="content"><span class="sampledata">0<br/>
6<br/>
1 1 1<br/>
2 2 1<br/>
2 3 1<br/>
2 4 1<br/>
2 5 1<br/>
4 1 1<br/>
6<br/>
A 3 1 2 6<br/>
A 3 1 3 6<br/>
A 3 1 4 6<br/>
A 3 1 5 6<br/>
A 3 1 3 2<br/>
A 3 2 3 6<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 1<br/>
4 1<br/>
5 1<br/>
6 1<br/>
3 1<br/>
3 1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2014年国家集训队十五人互测 By 佚名提供">2014年国家集训队十五人互测 By 佚名提供</a></p></div>

