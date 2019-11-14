
# Description

<div class="content"><p><span style="font-size: medium">可怕的洪水在夏天不期而至，兔子王国遭遇了前所未有的饥荒，它们不得不去外面的森林里寻找食物。<br/>
为了简化起见，我们假设兔子王国中有n只兔子，编号为1n。在救济粮到来之前的m天中，每天恰好有k只兔子需要去森林里寻找粮食。森林里居住着可怕的大灰狼，所幸兔子已经摸清了大灰狼捕食习惯，即狼们在每一天只会捕食特定编号的兔子。为了安全起见，兔子们需要保证每次出去觅食的k只兔子都不会被狼捕食。由于每天出去捕食的兔子都不尽相同，它们为每一天定义了一个生疏度pi，即第i天出来寻找食物，但是第i1天却没有出来觅食的兔子个数。规定第1天的生疏度为0.现在兔子们希望在保证安全的前提下，每天的生疏度不能超过L，请为兔子们构造一个合法的方案。</span></p></div>

# Input

<div class="content"><p> </p>
<p><span style="font-size: medium">第一行包括四个整数n,m,k和L.<br/>
接下来n行，每行一个长度为m的01串。其中第i行第j个字符若为0，则表示狼在第j天会捕食编号为i的兔子，为1则表示不捕食。<br/>
</span></p></div>

# Output

<div class="content"><p><font size="4">m行，每行k个1-n之间互不相同的整数，代表这一天出去寻找食物的兔子编号。如果没有合法方案，则输出一行1即可。</font></p>
<p><span style="font-size: medium"><br/>
</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 4 3 1<br/>
1001<br/>
1101<br/>
1111<br/>
1110<br/>
0111<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 3 4<br/>
2 3 4<br/>
3 4 5<br/>
2 3 5<br/>
<br/>
 </span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">对于 100% 的测试数据，1 &lt;= n;m &lt;= 800; 1 &lt;= k &lt;= n; 1 &lt;= l &lt;= k<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

