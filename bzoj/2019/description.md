
# Description

<div class="content"><p><span style="font-size: medium">奶牛们没钱了，正在找工作。农夫约翰知道后，希望奶牛们四处转转，碰碰运气。而且他还加了一条要求：一头牛在一个城市最多只能赚D(1 &lt;= D &lt;= 1,000)美元，然后它必须到另一座城市工作。当然，它可以在别处工作一阵后又回来原来的城市再最多赚D美元。而且这样往往返返的次数没有限制。 城市间有P (1 &lt;= P &lt;= 150)条单向路径连接，共有C(2 &lt;= C &lt;= 220)座城市，编号1..C. 贝希当前处在城市S (1 &lt;= S &lt;= C)。路径 i 从城市A_i 到城市B_i (1 &lt;= A_i &lt;= C; 1 &lt;= B_i &lt;= C)，在路径上行走不用花任何费用。为了帮助贝希，约翰让它使用他的私人飞机服务。这项服务有F条(1 &lt;= F &lt;= 350)航线，每条航线是从城市J_i飞到另一座城市K_i (1 &lt;=J_i &lt;= C; 1 &lt;= K_i &lt;= C)，费用是T_i (1 &lt;= T_i &lt;= 50,000)美元。如果贝希手中如果没有现钱，可以用以后赚的钱来付机票钱。贝希可以选择任何时候，在任何城市退休。如果在工作时间上不作限制，贝希总共可以赚多少钱呢？ 如果赚的钱也不会出现限制，就输出-1。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第1行: 5个空格分开的整数 D, P, C, F, S </span></p>
<p><span style="font-size: medium">第2..P+1行: 第 i+1行包含2个空格分开的整数，表示一条从A_i 到 B_i的单向路径 </span></p>
<p><span style="font-size: medium">第P+2..P+F+1行: 第P+i 包含3个空格分开的整数，表示一条从J_i到K_i的单向航线，费用为T_i</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">第1行: 在上述规则下的最多可赚的钱数。 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">100 3 5 2 1<br/>
1 5<br/>
2 3<br/>
1 4<br/>
5 2 150<br/>
2 5 120<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">250<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">样例说明：贝希可以从城市 1 到 5 再到 2 ，最后到 3, 总共赚 4*100 - 150 = 250 美元。 </span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

