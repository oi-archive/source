
# Description

<div class="content"><div>小强在解一个关于x[1..n]的同余方程组，每个的形式都是：</div>
<div>x[i]=k[i]*x[p[i]]+b[i]   mod  m</div>
<div>其中 m=10007。然而，小强还想要让这个方程组不停地变化。每次，它可能更改</div>
<div>a[i]、b[i]、p[i]的值，而你要动态地回答当前方程组中x[i]的值。</div>
<p></p></div>

# Input

<div class="content"><div>第一行是一个整数 N。接下来N 行，每行三个整数</div>
<div>k[i]、p[i]、b[i]。下面Q行，每行一个操作，格式是以下两种：</div>
<div>A a   表示询问x[a]的解。</div>
<div>C a k[a] p[a] b[a] 表示把第a个方程修改成x[a]=k[a]*x[p[a]]+b[a]。</div>
<div>输入数据保证：所有的 k都是介于1~10006 之间的正整数，b 都是介于0~10006 之间</div>
<div>的正整数，p是介于1~N之间的正整数。</div>
<p></p></div>

# Output

<div class="content"><div>对于询问操作，你要输出一个介于0~10006之间的整数，表示x[a]的解。注意：</div>
<div>方程组中可能有相互矛盾的等式。如果 x[a]有唯一解，或者你通过删除方程中若干个等式</div>
<div>之后，可以使得x[a]有唯一解，那么你要输出这个唯一解。否则，输出-1。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1 1 1<br/>
2 3 1<br/>
3 2 1<br/>
4<br/>
A 2<br/>
C 1 2 2 3<br/>
C 3 2 1 5<br/>
A 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">8005 <br/>
2857</span></div>

# Hint

<div class="content"><p></p><div>【样例解释】</div><br/>
<div>一开始，方程是（模10007意义下的）：</div><br/>
<div>x[1]=x[1]+1;</div><br/>
<div>x[2]=2*x[3]+1;</div><br/>
<div>x[3]=3*x[2]+1;</div><br/>
<div>第一个等式是自相矛盾的，删去它之后，这个方程的解是</div><br/>
<div>x[2]=8005，x[3]=4002，x[3]=0..10006</div><br/>
<div>两次修改之后，方程变成：</div><br/>
<div>x[1]=2*x[2]+3;</div><br/>
<div>x[2]=2*x[3]+1;</div><br/>
<div>x[3]=2*x[1]+5;</div><br/>
<div>这个方程的解是：x[1]=1426;x[2]=5715;x[3]=2857;</div><br/>
<div></div><br/>
<div>100%的数据保证：N&lt;=50000，Q&lt;=100000</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

