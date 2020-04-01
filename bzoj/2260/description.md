
# Description

<div class="content"><p align="center"><font face="Times New Roman" size="3">Grant是一个个体户老板，他经营的小店因为其丰富的优惠方案深受附近居民的青睐，生意红火。小店的优惠方案十分简单有趣。Grant规定：在一次消费过程中，如果您在本店购买了精制油的话，您购买香皂时就可以享受2.00元/块的优惠价；如果您在本店购买了香皂的话，您购买可乐时就可以享受1.50元/听的优惠价……诸如此类的优惠方案就是说：如果您在本店购买了商品A的话，您就可以以P元/件的优惠价格购买商品B（购买的数量不限）。有趣的是，你需要购买同样一些商品，由于不同的购买顺序，Grant老板可能会叫你付不同数量的钱。比如你需要一块香皂（原价2.50元）、一瓶精制油（原价10.00元）、一听可乐(原价1.80元)，如果你按照可乐，精制油，香皂这样的顺序购买的话，Grant老板会问你要13.80元；而如果你按照精制油，香皂，可乐这样的顺序购买的话，您只需付13.50元。 <br/>
现在该村的居民请你编写一个程序，告诉你Grant小店商品的原价，所有优惠方案及所需的商品，计算至少需要花多少钱。不允许购买任何不需要的商品，即使这样做可能使花得钱更少。 <br/>
<br/>
</font></p></div>

# Input

<div class="content"><div><span style="font-size: 12pt">，第一行为一个整数</span><span style="font-size: 12pt">n</span><span style="font-size: 12pt">（</span><span style="font-size: 12pt">1&lt;=n&lt;=50</span><span style="font-size: 12pt">），表示</span><span style="font-size: 12pt">Grant</span><span style="font-size: 12pt">小店的商品种数。接下来是</span><span style="font-size: 12pt">n</span><span style="font-size: 12pt">行，其中第</span><span style="font-size: 12pt">(i+1)</span><span style="font-size: 12pt">行由一个实数</span><span style="font-size: 12pt">C<sub>i </sub>(0&lt;C<sub>i</sub>&lt;=1000)</span><span style="font-size: 12pt">和一个整数</span><span style="font-size: 12pt">M<sub>i </sub>(0&lt;=M<sub>i</sub>&lt;=100)</span><span style="font-size: 12pt">组成，其间由一个空格分隔，分别表示第</span><span style="font-size: 12pt">i</span><span style="font-size: 12pt">种商品的原价和所需数量。第</span><span style="font-size: 12pt">(n+2)</span><span style="font-size: 12pt">行又是一个整数</span><span style="font-size: 12pt">k</span><span style="font-size: 12pt">，表示</span><span style="font-size: 12pt">Grant</span><span style="font-size: 12pt">小店的优惠方案总数。接着</span><span style="font-size: 12pt">k</span><span style="font-size: 12pt">行，每行有二个整数</span><span style="font-size: 12pt">A</span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">B</span><span style="font-size: 12pt">（</span><span style="font-size: 12pt">1&lt;=A,B&lt;=n</span><span style="font-size: 12pt">）和一个实数</span><span style="font-size: 12pt">P</span><span style="font-size: 12pt">（</span><span style="font-size: 12pt"> 0&lt;=P&lt;1000</span><span style="font-size: 12pt">），表示一种优惠方案，即如果您购买了商品</span><span style="font-size: 12pt">A</span><span style="font-size: 12pt">，您就可以以</span><span style="font-size: 12pt">P</span><span style="font-size: 12pt">元</span><span style="font-size: 12pt">/</span><span style="font-size: 12pt">件的优惠价格购买商品</span><span style="font-size: 12pt">B</span><span style="font-size: 12pt">，</span><span style="font-size: 12pt">P</span><span style="font-size: 12pt">小于商品</span><span style="font-size: 12pt">B</span><span style="font-size: 12pt">的原价。所有优惠方案的（</span><span style="font-size: 12pt">A,B</span><span style="font-size: 12pt">）都是不同的。为了方便，</span><span style="font-size: 12pt">Grant</span><span style="font-size: 12pt">不收分币，所以所有价格都不会出现分。</span></div></div>

# Output

<div class="content"><p><font face="Times New Roman" size="3">只有一个实数，表示最少需要花多少钱。输出实数须保留两位小数。 <br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
10.00 1<br/>
1.80   1 <br/>
3.00   0<br/>
2.50   2<br/>
2<br/>
1 4 2.00<br/>
4 2 1.50<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">15.50<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

