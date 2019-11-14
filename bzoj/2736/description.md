
# Description

<div class="content"><div id="pres" style="text-align: center; font-size: 14px; vertical-align: middle">
<div style="margin: 8px 0px 6px; font-weight: bold"></div>
</div>
<div id="pcont1" style="margin-top: 20px; display: block">
<div class="pdcont"><span style="font-size: medium">　　感谢HQ提供题目描述<br/>
　　一场暴雨过后，Q国遭受到了巨大的灾难，无数建筑被冲毁，城市中也积存了大量洪水，为了应对这场严重的灾难，Q国主席QQ决定立即启动紧急预案，修建多条运河以疏导洪水。<br/>
　　很不幸的是，Q国位于山区，地形复杂，运河的修建困难重重，所以我们要尽量修建数量最少的运河将所有城市的洪水疏导出去。而且，位于山区地貌的市海拔两两不同，这导致修建的运河只能把洪水由较高的城市导向较低的城市。但是若两个城市的高度差过大，洪水沿运河流下时可能冲毁河两岸的堤坝，如果处理不当可能会产生更严重的后果。经过统计，QQ测出了每个城市的海拔，还通过计算得出：如果某条道路连接的两个城市海拔差超过K，较低的城市会被洪水摧毁。于是QQ决定：每个城市要通过运河连接唯一一个海拔比它低的城市，这样到达该城市所有的洪水都可以通过它被疏导到更低的城市。特别的，海拔最低的城市靠近海边，可以直接把洪水排入海中，所以不必连接这样一条运河。另外，对于某一个城市可能有很多更高的城市向它输送洪水，所以它要从中选择一条进行重点处理。<br/>
　　现在QQ要制定疏导洪水的计划，一个合法的计划包括若干条运河以及每一个城市选择的重点治理的运河（可以选择任意一条流入它的运河，而对于没有洪水通过运河流入的城市不必选择），而且要满足QQ的决定，且不能摧毁任何一个城市。两个计划被认为是相同的，当且仅当将城市连接起来的运河的集合相同且每个城市的重点处理的选择也相同。QQ想知道这样的方案有多少个，于是他把这个任务交给了神犇你。<br/>
</span></div>
</div></div>

# Input

<div class="content"><div class="pdsec"> </div>
<div class="pdcont"><span style="font-size: medium">　　第一行两个整数N、K。<br/>
　　第二行N个整数，用空格分隔，表示每个城市的海拔。<br/>
</span></div>
<div class="pdcont"><span style="font-size: medium">　　</span></div></div>

# Output

<div class="content"><p><font size="4">仅一行，包含一个整数，表示方案数。由于这个数可能很大，你只需要输出方案数对1000000007取模的结果即可。</font><br/>
</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
1 2 4 5<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
<br/>
样例说明<br/>
　　不考虑重点处理的运河的选取，共有4种方案，数字表示QQ测得的海拔，箭头方向表示水流方向。<br/>
　　(1) 1&lt;-2 2&lt;-4 4&lt;-5<br/>
　　(2) 1&lt;-2 1&lt;-4 4&lt;-5<br/>
　　(3) 1&lt;-2 2&lt;-4 2&lt;-5<br/>
　　(4) 1&lt;-2 1&lt;-4 2&lt;-5<br/>
　　其中(2)(3)(4)都只存在一个城市上方有两条运河且别的城市上方至多有一条运河，所以重点处理的运河的选取方法只有两种，而(1)每个城市上方都至多有一条运河，选取方法只有一种，所以最终方案数是1+2+2+2=7种。<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据规模和约定<br/><br/>
　　对于20%的数据 N &lt;= 20, K &lt;= 10<br/><br/>
　　对于40%的数据 N &lt;= 40, K &lt;= 12<br/><br/>
　　对于100 %的数据 2 &lt;= N &lt;= 50, 1 &lt;= K &lt;= 16, 1 &lt;= V &lt;= 200,<br/><br/>
　　输入数据保证至少有一种合法方案。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

