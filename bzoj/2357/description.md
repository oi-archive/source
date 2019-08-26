
# Description

<div class="content"><div style="text-indent: 24.1pt; line-height: 200%"><span style="font-size: 12pt; line-height: 200%">给定</span><span style="font-size: 12pt; line-height: 200%">K</span><span style="font-size: 12pt; line-height: 200%">种化学物质和</span><span style="font-size: 12pt; line-height: 200%">N</span><span style="font-size: 12pt; line-height: 200%">种反应类型。每个反应都有一些反应物和生成物，且反应需要一定的时间。假设每次反应后的若干生成物都可以完全分离。而每次反应的生成物，可以立即用于其他反应的生成物。每种物质的数量都是无限的。</span></div>
<div style="text-indent: 24.1pt; line-height: 200%"><span style="font-size: 12pt; line-height: 200%">给出一些已有的物质，求得到一种指定物质至少要多少时间。</span></div></div>

# Input

<div class="content"><div style="text-indent: 24.1pt; line-height: 200%"><span style="font-size: 12pt; line-height: 200%">第一行包含</span><span style="font-size: 12pt; line-height: 200%">4</span><span style="font-size: 12pt; line-height: 200%">个整数，分别为</span><span style="font-size: 12pt; line-height: 200%">K</span><span style="font-size: 12pt; line-height: 200%">、</span><span style="font-size: 12pt; line-height: 200%">N</span><span style="font-size: 12pt; line-height: 200%">、已有物质数量</span><span style="font-size: 12pt; line-height: 200%">M</span><span style="font-size: 12pt; line-height: 200%">和所求物质的编号；</span></div>
<div style="text-indent: 24.1pt; line-height: 200%"><span style="font-size: 12pt; line-height: 200%">下面依次是</span><span style="font-size: 12pt; line-height: 200%">N</span><span style="font-size: 12pt; line-height: 200%">种反应的描述。每种反应的描述有三行。第一行包含一个正整数，表示该反应的时间；第二行第一个数是这个反应的反应物的数量，接着是这些反应物的编号；第三行第一个数是生成物的数量，接着是生成物的编号。</span></div>
<div style="text-indent: 24.1pt; line-height: 200%"><span style="font-size: 12pt; line-height: 200%">已有物质的编号总是</span><span style="font-size: 12pt; line-height: 200%">1</span><span style="font-size: 12pt; line-height: 200%">到</span><span style="font-size: 12pt; line-height: 200%">M</span><span style="font-size: 12pt; line-height: 200%">，编号为</span><span style="font-size: 12pt; line-height: 200%">M+1</span><span style="font-size: 12pt; line-height: 200%">到</span><span style="font-size: 12pt; line-height: 200%">K</span><span style="font-size: 12pt; line-height: 200%">的为开始时没有的物质。</span></div></div>

# Output

<div class="content"><div style="text-indent: 24.1pt; line-height: 200%"><span style="font-size: 12pt; line-height: 200%">包含一个非负整数，表示生成指定的物质需要的最短的时间。如果无法生成指定物质，则输出</span><span style="font-size: 12pt; line-height: 200%">-1</span><span style="font-size: 12pt; line-height: 200%">。</span></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3 1 4<br/>
8<br/>
1 1<br/>
1 4<br/>
3<br/>
1 1<br/>
2 2 3<br/>
2<br/>
2 1 3<br/>
1 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
</span></div>

# Hint

<div class="content"><p></p><p>【样例说明】<br/><br/>
依次进行反应二和反应三，可以得到所有种类的物质，耗时为5.<br/><br/>
【数据规模】<br/><br/>
 <br/><br/>
30%的数据满足，1&lt;=K,N&lt;=10；<br/><br/>
100%的数据满足，1&lt;=K&lt;=250，1&lt;=N&lt;=500.</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

