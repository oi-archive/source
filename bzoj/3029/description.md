
# Description

<div class="content"><p><span style="font-size: medium">　　打开了黑魔法师Vani的大门，队员们在迷宫般的路上漫无目的地搜寻着关押applepi的监狱的所在地。突然，眼前一道亮光闪过。“我，Nizem，是黑魔法圣殿的守卫者。如果你能通过我的挑战，那么你可以带走黑魔法圣殿的地图……”瞬间，队员们被传送到了一个擂台上，最初身边有一个容量为K的包包。<br/>
　　擂台赛一共有N项挑战，各项挑战依次进行。第i项挑战有一个属性ai，如果ai&gt;=0，表示这次挑战成功后可以再获得一个容量为ai的包包；如果ai=-1，则表示这次挑战成功后可以得到一个大小为1 的地图残片。地图残片必须装在包包里才能带出擂台，包包没有必要全部装满，但是队员们必须把 【获得的所有的】地图残片都带走（没有得到的不用考虑，只需要完成所有N项挑战后背包容量足够容纳地图残片即可），才能拼出完整的地图。并且他们至少要挑战成功L次才能离开擂台。<br/>
　　队员们一筹莫展之时，善良的守卫者Nizem帮忙预估出了每项挑战成功的概率，其中第i项挑战成功的概率为pi%。现在，请你帮忙预测一下，队员们能够带上他们获得的地图残片离开擂台的概率。</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">　　第一行三个整数N,L,K。<br/>
　　第二行N个实数，第i个实数pi表示第i项挑战成功的百分比。<br/>
　　第三行N个整数，第i个整数ai表示第i项挑战的属性值.</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">　　一个整数，表示所求概率，四舍五入保留6 位小数。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">样例输入1<br/>
3 1 0<br/>
10 20 30<br/>
-1 -1 2<br/>
<br/>
样例输入2<br/>
5 1 2<br/>
36 44 13 83 63<br/>
-1 2 -1 2 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例输出1<br/>
0.300000<br/>
<br/>
样例输出2<br/>
0.980387<br/>
</span></div>

# Hint

<div class="content"><p></p><p>　　若第三项挑战成功，如果前两场中某场胜利，队员们就有空间来容纳得到的地图残片，如果挑战失败，根本就没有获得地图残片，不用考虑是否能装下；若第三项挑战失败，如果前两场有胜利，没有包来装地图残片，如果前两场都失败，不满足至少挑战成功次（）的要求。因此所求概率就是第三场挑战获胜的概率。</p><br/>
<p>　　对于 100% 的数据，保证0&lt;=K&lt;=2000，0&lt;=N&lt;=200，-1&lt;=ai&lt;=1000，0&lt;=L&lt;=N，0&lt;=pi&lt;=100。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Poetize1">Poetize1</a></p></div>

