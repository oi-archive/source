
# Description

<div class="content"><div>ls和他的妹子sl都进入了青春期，额头上长出了雀斑。他们分别把雀斑的图案描成了一个矩阵，由&#34;.&#34;和&#34;*&#34;组成，</div>
<div>&#34;.&#34;代表无雀斑，&#34;*&#34;代表有雀斑。他们幻想着未来结婚生子，定义了他们的孩子的额头前的雀斑的生成规则：可以</div>
<div>选择sl的雀斑图案然后进行平行移动，然后他们的儿子的某一个位置有雀斑当且仅当他们中恰好有一人该位置有雀</div>
<div>斑。例如：如果不进行平行移动，则ls的矩阵a[i][j]就对应sl的矩阵b[i][j]，如果将sl的矩阵向右平移x，那么l</div>
<div>s的矩阵a[i+x][j]就对应着sl的矩阵b[i][j]。那么这就可能存在a[i][j]与b[i][j]之间无法对应（因为ls和sl的</div>
<div>矩阵大小不一定相同，也就是可能a[i][j]有字符而b[i][j]没有），于是定义如果某矩阵对应位置没有字符，则与</div>
<div>&#34;.&#34;对应。例如：</div>
<div>ls的矩阵：</div>
<div>.x.x</div>
<div>xx..</div>
<div>..xx</div>
<div>sl的矩阵：</div>
<div>xx.</div>
<div>.xx</div>
<div>x.x</div>
<div>.xx</div>
<div>那么孩子的矩阵：</div>
<div>x..x</div>
<div>x.x.</div>
<div>x..x</div>
<div>.xx.</div>
<div>现给出ls的矩阵，sl的矩阵和孩子的矩阵，问能不能找到一种平行变换方式</div>
<div>使得sl平行变换矩阵后与ls的矩阵生成的儿子的矩阵经过平行变换</div>
<div>（此处的平行变换允许随便移动）后与给出的儿子的矩阵完全重合。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行两个数n1,m1,表示ls的矩阵的大小。</div>
<div>接下来n1行，每行字符串长m1，表示ls的矩阵。</div>
<div>接下来一行两个数n2,m2,表示sl的矩阵的大小。</div>
<div>接下来n2行，每行字符串长m2，表示sl的矩阵。</div>
<div>接下来一行两个数n3,m3,表示他们的孩子的矩阵的大小。</div>
<div>接下来n3行，每行字符串长m3，表示孩子的矩阵。</div>
<div>1&lt;=n1,m1,n2,m2,n3,m3&lt;=1000。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>第一行输出一个字符串&#34;YES&#34;或&#34;NO&#34;。</div>
<div>如果第一行输出&#34;YES&#34;，那么第二行再输出两个数x,y，</div>
<div>表示平行变换的方式为向右移x格，向下移y格（x&lt;0则表示向左移-x格，y&lt;0则表示向上移-y格）。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
..*<br/>
.*.<br/>
*.*<br/>
3 3<br/>
**.<br/>
..*<br/>
.*.<br/>
5 2<br/>
.*<br/>
*.<br/>
**<br/>
.*<br/>
*.</span></div>

# Sample Output

<div class="content"><span class="sampledata">YES<br/>
0 2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

