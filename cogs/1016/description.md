# 题目描述


<p align="center" style="text-align:center;">
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">守卫者的挑战</span><span></span></b> 
</p>
<p align="center" style="text-align:center;">
	<br/>
</p>
<p>
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">题目描述</span><span></span></b> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">打开了黑魔法师</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Vani</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">的大门，队员们在迷宫般的路上漫无目的地搜寻着关押</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">applepi</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">的监狱的所在地。突然，眼前一道亮光闪过。“我，</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Nizem</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，是黑魔法圣殿的守卫者。如果你能通过我的挑战，那么你可以带走黑魔法圣殿的地图……”瞬间，队员们被传送到了一个擂台上，最初身边有一个容量为K</span><span></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">的包包。</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">擂台赛一共有N</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">项挑战，各项挑战依次进行。第</span><span style="font-size:16px;">i</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">项挑战有一个属性</span><span style="font-size:16px;">ai</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，如果</span><span style="font-size:16px;">ai&gt;=0</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，表示这次挑战成功后可以再获得一个容量为</span><span style="font-size:16px;">ai</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">的包包；如果</span><span style="font-size:16px;">ai=-1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，则表示这次挑战成功后可以得到一个大小为</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">的地图残片。地图残片必须装在包包里才能带出擂台，包包没有必要全部装满，但是队员们必须把</span><b><u><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">获得的所有的</span></u></b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">地图残片都带走（没有得到的不用考虑，只需要完成所有</span><span style="font-size:16px;">N</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">项挑战后背包容量足够容纳地图残片即可），才能拼出完整的地图。并且他们至少要挑战成功</span><span style="font-size:16px;">L</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">次才能离开擂台。</span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">队员们一筹莫展之时，善良的守卫者</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Nizem</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">帮忙预估出了每项挑战成功的概率，其中第</span><span style="font-size:16px;">i</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">项挑战成功的概率为</span><span style="font-size:16px;">Pi/100</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">。现在，请你帮忙预测一下，队员们能够带上他们获得的地图残片离开擂台的概率。</span> 
</p>
<p>
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入格式</span><span></span></b> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第一行三个整数</span><span style="font-size:16px;">N</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">,</span><span style="font-size:16px;">L</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">,</span><span style="font-size:16px;">K</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">。</span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第二行</span><span style="font-size:16px;">N</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">个实数，第</span><span style="font-size:16px;">i</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">个实数</span><span style="font-size:16px;">Pi</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">表示第</span><span style="font-size:16px;">i</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">项挑战成功的百分比。</span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第三行</span><span style="font-size:16px;">N</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">个整数，第</span><span style="font-size:16px;">i</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">个整数</span><span style="font-size:16px;">ai</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">表示第</span><span style="font-size:16px;">i</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">项挑战的属性值</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">.</span> 
</p>
<p>
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出格式</span><span></span></b> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">一个整数，表示所求概率，四舍五入保留</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">6 </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">位小数。</span><span></span> 
</p>
<p>
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">样例输入</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1</span></b> 
</p>
<pre><span>3 1 0</span></pre>
<pre><span>10 20 30</span></pre>
<pre><span>-1 -1 2</span></pre>
<p>
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">样例输出</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1</span></b> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">0.300000</span> 
</p>
<p>
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">样例输入</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span></b> 
</p>
<pre><span>5 1 2</span></pre>
<pre><span>36 44 13 83 63</span></pre>
<pre><span>-1 2 -1 2 1</span></pre>
<p>
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">样例输出</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span></b> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">0.980387</span> 
</p>
<p>
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">样例说明</span><span></span></b> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">在第一个样例中，若第三项挑战成功，如果前两场中某场胜利，队员们就有空间来容纳得到的地图残片，如果挑战失败，根本就没有获得地图残片，不用考虑是否能装下；若第三项挑战失败，如果前两场有胜利，没有包来装地图残片，如果前两场都失败，不满足至少挑战成功</span><span style="font-size:16px;">L</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">次（</span><span style="font-size:16px;">L=1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">）的要求。因此所求概率就是第三场挑战获胜的概率。</span> 
</p>
<p>
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">数据范围与约定</span><span></span></b> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 100% </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">的数据，保证</span><span style="font-size:16px;">0&lt;=K&lt;=2000</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，</span><span style="font-size:16px;">0&lt;=N&lt;=200</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，</span><span style="font-size:16px;">-1&lt;=ai&lt;=1000</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，</span><span style="font-size:16px;">0&lt;=L&lt;=N</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，</span><span style="font-size:16px;">0&lt;=Pi&lt;=100</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">。</span> 
</p>
