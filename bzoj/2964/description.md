
# Description

<div class="content"><p><span style="font-size: medium">　　某RPG游戏中，最后一战是主角单挑Boss，将其简化后如下：<br/>
　　主角的气血值上限为HP，魔法值上限为MP，愤怒值上限为SP；Boss仅有气血值，其上限为M。<br/>
　　现在共有N回合，每回合都是主角先行动，主角可做如下选择之一：<br/>
　　1. 普通攻击：减少对方X的气血值，并增加自身DSP的愤怒值。（不超过上限）<br/>
　　2. 法术攻击：共有N1种法术，第i种消耗Bi的魔法值，减少对方Yi的气血值。（使用时要保证MP不小于Bi）<br/>
　　3. 特技攻击：共有N2种特技，第i种消耗Ci的愤怒值，减少对方Zi的气血值。（使用时要保证SP不小于Ci）<br/>
　　4. 使用HP药水：增加自身DHP的气血值。（不超过上限）<br/>
　　5. 使用MP药水：增加自身DMP的魔法值。（不超过上限）<br/>
　　之后Boss会攻击主角，在第i回合减少主角Ai的气血值。<br/>
　　刚开始时气血值，魔法值，愤怒值都是满的。当气血值小于等于0时死亡。<br/>
　　如果主角能在这N个回合内杀死Boss，那么先输出“Yes”，之后在同一行输出最早能在第几回合杀死Boss。（用一个空格隔开）<br/>
　　如果主角一定会被Boss杀死，那么输出“No”。<br/>
　　其它情况，输出“Tie”。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">　　输入的第一行包含一个整数T，为测试数据组数。<br/>
　　接下来T部分，每部分按如下规则输入：<br/>
　　第一行九个整数N, M, HP, MP, SP, DHP, DMP, DSP, X。<br/>
　　第二行N个整数Ai。<br/>
　　第三行第一个整数N1，接下来包含N1对整数Bi, Yi。<br/>
　　第四行第一个整数N2，接下来包含N2对整数Ci, Zi。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">　　输出共包含T行，每行依次对应输出一个答案。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
5 100 100 100 100 50 50 50 20<br/>
50 50 30 30 30<br/>
1 100 40<br/>
1 100 40<br/>
5 100 100 100 100 50 50 50 10<br/>
50 50 30 30 30<br/>
1 100 40<br/>
1 100 40<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Yes 4<br/>
Tie<br/>
样例说明<br/>
　　对于第一个样例，主角的策略是：第一回合法术攻击，第二回合使用HP药水，第三回合特技攻击，第四回合普通攻击。<br/>
</span></div>

# Hint

<div class="content"><p></p><p>　　对于100%的数据：1 ≤ N ≤ 1000，1 ≤ M ≤ 1000000，1 ≤ HP,MP,SP ≤ 1000，N1,N2 ≤ 10，DHP,Ai ≤ HP，DMP,Bi ≤ MP，DSP,Ci ≤ SP，X,Yi,Zi ≤ 10000，1 ≤ T ≤ 10。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=中国国家队清华集训 2012-2013 第三天
">中国国家队清华集训 2012-2013 第三天<br/>
</a></p></div>

