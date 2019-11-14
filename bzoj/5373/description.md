
# Description

<div class="content"><div>九条可怜是一个爱玩游戏的女孩子。</div>
<div>最近她在玩一个无双割草类的游戏，平面上有n个敌人，每一个敌人的坐标为xi,yi</div>
<div>可怜有一个技能是在平面上画一个m个点的简单多边形，并消灭所有严格在多边形内部的敌人。</div>
<div>不难发现如果想要快速的消灭敌人的话，只要画一个足够大的简单多边形就行了。</div>
<div>但是这样的游戏性就太差了。于是可怜打算为游戏增加一定的随机性。</div>
<div>可怜在平面上随便画了一个m个点的简单多边形(ai,bi)。</div>
<div>接下来可怜打算按照[-π,π)上的均匀分布随机选取数字α（可以理解为等概率选取），并把这个简单多边形绕原点逆时针旋转α的角度（弧度制）。</div>
<div>现在可怜给你了每一个点的坐标，多边形的坐标，你的任务是帮助可怜计算在随机旋转后她期望可以消灭多少个敌人。</div></div>

# Input

<div class="content"><div>第一行四个整数n,m</div>
<div>接下来n行每行两个整数xi,yi,描述了一个敌人的坐标。</div>
<div>接下来m行每行两个整数ai,bi,按照逆时针的顺序描述了简单多边形的每一个顶点。</div>
<div>n≤200,m≤500,∣x∣,∣y∣≤10^6</div></div>

# Output

<div class="content"><div>输出一行一个整数表示期望值，保留五位小数。同时保证所有数据的小数点后第6位在舍入前不会是4和5。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
0 0<br/>
1 0<br/>
-1 -1<br/>
0 1<br/>
0 0<br/>
1 0<br/>
1 1<br/>
0 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.50000</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

