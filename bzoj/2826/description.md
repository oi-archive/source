
# Description

<div class="content"><div><span style="font-size: medium">邪恶的PureDark星球的居民把曾经美丽的草原、森林、海洋、高山、沙漠变成了由工业MOD驱动</span></div>
<div><span style="font-size: medium">的各类机器所构成的钢铁城市。可惜，这些居民或是因为水平不足，亦或是抱着一种不负责任的心态，</span><span style="font-size: medium">无数次核弹的爆炸以及各类核电事故，加之植被被毁、空气污染，整个星球的环境已经恶化到了不可挽</span><span style="font-size: medium">回的地步。就在这个时候，平日里被各种OI题目虐得死去活来的沙茶，突然人品爆发，发明出一种机器，这种</span><span style="font-size: medium">机器能够把环境中的污染物转变成一种特殊的粒子——沙茶粒子(Sandy-tea Particle，简称STP)，也可以</span><span style="font-size: medium">将这种粒子放出重新变成污染物。PureDark星球的居民发现，这是收集这种危险污染物的唯一方式。而</span><span style="font-size: medium">由于污染物的量过于巨大，通过收集污染物的方式无法阻止环境恶化，因此人们并不重视这台机器，也</span><span style="font-size: medium">没有人愿意协同沙茶完成自己的伟大设计，因此沙茶来到地球，找到了身为OI大牛的你。</span><span style="font-size: medium">因为Minecraft世界中没有任何物理可言，沙茶可以通过一种叫做Redstone的物质无限地获取能源</span><span style="font-size: medium">供机器运转而不需要付出任何费用或是高能的STP，同时物质的转化也不再满足质量守恒的规律。也就是</span><span style="font-size: medium">说，在某一天将污染物转化为STP，在另一天可能可以以不同的比例转化回污染物。沙茶准备利用这种转</span><span style="font-size: medium">化的比例差来产生更多的STP，因为他预感到这种粒子可以起到拯救世界的作用，虽然他不知道如何用</span><span style="font-size: medium">STP来拯救世界。很可惜沙茶终究是沙茶，他的机器能力非常有限，每天最多只能够转化污染物 Gi</span><span style="font-size: medium"> mol或是释放污染</span><span style="font-size: medium">物 Di mol（这些值能事先被预测出来），转化和释放污染物不能在同一天进行，且转化的污染物的物质</span><span style="font-size: medium">的量必须是整数。机器每次进行物质转化后，需要等待T天使设备冷却，冷却过程中不能再进行物质转</span><span style="font-size: medium">化。沙茶的机器有一个用于存储污染物的大仓，它的容积当然不是无限大的，最多能存储C mol 污染物。</span><span style="font-size: medium">每次实验结束时，机器中的污染物必须被清空，沙茶可不愿意冒机器爆炸的险。也是因为Minecraft世界</span><span style="font-size: medium">没有任何物理可言，STP粒子可以以任意的密度存在，也就是说机器中的STP粒子可以无限多。同时，</span><span style="font-size: medium">机器中STP粒子的物质的量可以为0、为正整数，甚至可以为负整数。</span><span style="font-size: medium">现在，沙茶想做M次实验来测试机器的稳定性。在每次实验开始时，他拥有的STP的物质的量为</span><span style="font-size: medium">0。他预感到了第i天每摩尔污染物需要STP的物质的量Ai</span><span style="font-size: medium">以及这一天每摩尔污染物能转化成的STP的物</span><span style="font-size: medium">质的量Bi</span><span style="font-size: medium">，以及前文提到的 Gi</span><span style="font-size: medium">和Di</span><span style="font-size: medium"> 。请帮他算出他每次实验能获得的STP的最大值。</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium"> </span><span style="font-size: medium">第1行是一个正整数M，表示实验的次数。</span></p>
<div><span style="font-size: medium">对于每次实验，第1行是三个正整数N，T，C，分别表示实验的天数、设备冷却时间和污染物存储</span><span style="font-size: medium">器的容量。第2~5行分别有N个正整数，每行分别是A1、A2……AN，B1、B2……BN，G1、G2……</span><span style="font-size: medium">GN，D1、D2……DN，意义如前文所述。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">M行，每行一个整数，第i行的整数表示沙茶在第i次实验中能获得的最大STP的物质的量。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata"> <br/>
1<br/>
10 1 10<br/>
1 1 1 5 5 10 10 10 10 10<br/>
1 2 3 3 4 5 6 7 8 9<br/>
1 1 1 1 1 1 1 1 1 1<br/>
1 1 1 1 1 1 1 1 1 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">14<br/>
样例解释<br/>
一个最优方案为：在第1、3天各消耗1 mol STP转化为1 mol 污染物，在第7、9天分别将1 mol<br/>
污染物转化为7、9 mol STP，整个实验结束时有STP (7+9-1-1) mol=14 mol。<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><div style="text-align: left; line-height: normal; font-family: arial, verdana, sans-serif; font-size: medium"><span style="line-height: 21px; font-family: 黑体; font-size: 14px">0≤Ai,Bi,Gi,Di≤100</span></div><br/>
<p>有M≤10，O≤T＜N≤3000，1≤C≤3000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=湖北省队互测">湖北省队互测</a></p></div>

