
# Description

<div class="content"><div>在有 N 座城市的国度．Alice希望可以开始一场充满传奇的旅行。TA 希望可以从一个城市出发开始旅行，每次前</div>
<div>往一个相邻的城市，途中不重复得经过恰好 K 座城市，最后抵达另外一个城市并结束旅行。需要注意的是，起点</div>
<div>与终点也被考虑为经过的城市，也就是说包括起点和终点在内经过的所有城市都是不能重复的。现在，Alice 希望</div>
<div>知道哪些城市对 &lt;u,v&gt; 可以作为合法的旅行起点与终点。</div>
<div></div></div>

# Input

<div class="content"><div>本题每一个测试点有多组测试数据。第一行给定正整数 T ，表示数据组数。</div>
<div>对于每一组数据来说，第一行给定三个整数 N，M 和 K，表示城市个数，城市之间的相邻关系个数，还有旅途应该</div>
<div>经过的城市个数。M 行．每一行给定两个整数 u 和 v ，表示标号为 u 的城市与标号为 v 的城市之间是相邻的．</div>
<div>即可以从其中一个城市出发前往另外一个。</div>
<div>N≤1000，M≤5000，2≤K≤7 且T*(k div 2)^(k div 2)&lt;=60</div>
<div style="font-size: 11.8181819915771px;"></div></div>

# Output

<div class="content"><div>对于每一组数据．输出 N 行．每行 N 个字符。</div>
<div>其中第 i 行第 j 个字符，或者为“Y”或者为“N”，分别表示是否存在从城市 i 出发到城市 j 结束的合法旅行方案。</div>
<div></div>
<div style="font-size: 11.8181819915771px;"></div></div>

# Sample Input

<div class="content"><span class="sampledata">1 <br/>
5 6 4 <br/>
1 2 <br/>
2 3 <br/>
3 5 <br/>
1 4 <br/>
4 5 <br/>
2 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">NYYYY <br/>
YNNYY <br/>
YNNYN <br/>
YYYNY <br/>
YYNYN</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

