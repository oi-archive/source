
# Description

<div class="content"><p><span style="font-size: medium">与很多奶牛一样，Farmer John那群养尊处优的奶牛们对食物越来越挑剔，随便拿堆草就能打发她们午饭的日子自然是一去不返了。现在，Farmer John不得不去牧草专供商那里购买大量美味多汁的牧草，来满足他那N(1 &lt;= N &lt;= 100,000)头挑剔的奶牛。 所有奶牛都对FJ提出了她对牧草的要求：第i头奶牛要求她的食物每份的价钱不低于A_i(1 &lt;= A_i &lt;= 1,000,000,000)，并且鲜嫩程度不能低于B_i(1 &lt;= B_i &lt;= 1,000,000,000)。商店里供应M(1 &lt;= M &lt;= 100,000)种不同的牧草，第i 种牧草的定价为C_i(1 &lt;= C_i &lt;= 1,000,000,000)，鲜嫩程度为D_i (1 &lt;= D_i &lt;= 1,000,000,000)。 为了显示她们的与众不同，每头奶牛都要求她的食物是独一无二的，也就是说，没有哪两头奶牛会选择同一种食物。 Farmer John想知道，为了让所有奶牛满意，他最少得在购买食物上花多少钱。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第1行: 2个用空格隔开的整数：N 和 M </span></p>
<p><span style="font-size: medium">* 第2..N+1行: 第i+1行包含2个用空格隔开的整数：A_i、B_i * 第N+2..N+M+1行: 第j+N+1行包含2个用空格隔开的整数：C_i、D_i</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第1行: 输出1个整数，表示使所有奶牛满意的最小花费。如果无论如何都无法 满足所有奶牛的需求，输出-1 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 7<br/>
1 1<br/>
2 3<br/>
1 4<br/>
4 2<br/>
3 2<br/>
2 1<br/>
4 3<br/>
5 2<br/>
5 4<br/>
2 6<br/>
4 4<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">12<br/>
<br/>
输出说明:<br/>
<br/>
    给奶牛1吃价钱为2的2号牧草，奶牛2吃价钱为4的3号牧草，奶牛3分到价钱<br/>
为2的6号牧草，奶牛4选择价钱为4的7号牧草，这种分配方案的总花费是12，为<br/>
所有方案中花费最少的。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

