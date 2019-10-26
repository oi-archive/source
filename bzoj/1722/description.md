
# Description

<div class="content"><p><span style="font-size: medium; ">Farmer John&#39;s N (1 &lt;= N &lt;= 500) cows are trying to select the milking team for the world-famous Multistate Milking Match-up (MMM) competition. As you probably know, any team that produces at least X (1 &lt;= X &lt;= 1,000,000) gallons of milk is a winner.  Each cow has the potential of contributing between -10,000 and 10,000 gallons of milk. (Sadly, some cows have a tendency to knock over jugs containing milk produced by other cows.)  The MMM prides itself on promoting family values. FJ&#39;s cows have no doubt that they can produce X gallons of milk and win the contest, but to support the contest&#39;s spirit, they want to send a team with as many parent-child relationships as possible (while still producing at least X gallons of milk). Not surprisingly, all the cows on FJ&#39;s farm are female.  Given the family tree of FJ&#39;s cows and the amount of milk that each would contribute, compute the maximum number of parent-child relationships that can exist in a winning team. Note that a set of cows with a grandmother-mother-daughter combination has two parent-child relationships (grandmother-mother, mother-daughter).</span></p>
<p></p><p class="MsoNormal"><span style="font-size: medium; "><br/>
</span></p>
<p class="MsoNormal"><span style="font-size: medium; "><span lang="EN-US">    </span><span style="font-family: 宋体; ">约翰的</span><span lang="EN-US">N(1</span><span style="font-family: 宋体; ">≤</span><span lang="EN-US">N</span><span style="font-family: 宋体; ">≤</span><span lang="EN-US">500)</span><span style="font-family: 宋体; ">头奶牛打算组队去参加一个世界级的产奶比赛</span><span lang="EN-US">(Multistate Milking</span></span></p>
<p class="MsoNormal"><span style="font-size: medium; "><span lang="EN-US">Match-up</span><span style="font-family: 宋体; ">，缩写为</span><span lang="EN-US">MMM)</span><span style="font-family: 宋体; ">．她们很清楚其他队的实力，也就是说，她们派出的队只要能产出至少</span><span lang="EN-US">X(I</span><span style="font-family: 宋体; ">≤</span><span lang="EN-US">X</span><span style="font-family: 宋体; ">≤</span><span lang="EN-US">1000000)</span><span style="font-family: 宋体; ">加仑牛奶，就能赢得这场比赛．</span><span lang="EN-US">    </span><span style="font-family: 宋体; ">每头牛都能为集体贡献一定量的牛奶，数值在</span><span lang="EN-US">-10000</span><span style="font-family: 宋体; ">到</span><span lang="EN-US">10000</span><span style="font-family: 宋体; ">之间（有些奶牛总是想弄翻装着其他奶牛产的奶的瓶子）．</span></span></p>
<p class="MsoNormal"><span style="font-size: medium; "><span lang="EN-US">    MMM</span><span style="font-family: 宋体; ">的举办目的之一，是通过竞赛中的合作来增进家庭成员之间的默契．奶牛们认为她们总是能赢得这场比赛，但为了表示对比赛精神的支持，她们希望在选出的队伍里能有尽可能多的牛来自同一个家庭，也就是说，有尽可能多对的牛有直系血缘关系（当然，这支队伍必须能产出至少</span><span lang="EN-US">X</span><span style="font-family: 宋体; ">加仑牛奶）．当然了，所有的奶牛都是女性，所以队伍里所有直系血亲都是母女关系．</span><span lang="EN-US">    </span><span style="font-family: 宋体; ">约翰熟知所有奶牛之间的血缘关系．现在他想知道，如果在保证一支队伍能赢得比赛的情况下，队伍中最多能存在多少对血缘关系．注意，如果一支队伍由某头奶牛和她的母亲、她的外祖母组成，那这支队伍里一共有</span><span lang="EN-US">2</span><span style="font-family: 宋体; ">对血缘关系（这头奶牛外祖母与她的母亲，以及她与她的母亲）．</span></span></p>
<p class="MsoNormal"></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium; ">* Line 1: Two space-separated integers, N and X.  * Lines 2..N+1: Line i+1 contains two space-separated integers         describing cow i. The first integer is the number of gallons         of milk cow i would contribute. The second integer (range         1..N) is the index of the cow&#39;s mother. If the cow&#39;s mother is         unknown, the second number is 0. The family information has no         cycles: no cow is her own mother, grandmother, etc. </span></p>
<p></p><div><span style="font-size: medium; "><br/>
</span></div>
<div>
<p class="MsoNormal"><span style="font-size: medium; "><span lang="EN-US">    </span><span style="font-family: 宋体; ">第</span><span lang="EN-US">1</span><span style="font-family: 宋体; ">行：两个用空格隔开的整数</span><span lang="EN-US">N</span><span style="font-family: 宋体; ">和</span><span lang="EN-US">X.</span></span></p>
<p class="MsoNormal"><span style="font-size: medium; "><span lang="EN-US">    </span><span style="font-family: 宋体; ">第</span><span lang="EN-US">2</span><span style="font-family: 宋体; ">到</span><span lang="EN-US">N+1</span><span style="font-family: 宋体; ">行：每行包括两个用空格隔开的整数，第一个数为一只奶牛能贡献出的牛奶的加仑数，第二个数表示她的母亲的编号．如果她的母亲不在整个牛群里，那第二个数为</span><span lang="EN-US">0</span><span style="font-family: 宋体; ">．并且，血缘信息不会出现循环，也就是说一头奶牛不会是自己的母亲或祖母，或者更高代的祖先．</span></span></p>
<p class="MsoNormal"></p>
<p class="MsoNormal"><span style="font-size: medium; "><span lang="EN-US">   </span></span></p>
<p class="MsoNormal"><span style="font-size: medium; "><span style="font-family: 宋体; "><br/>
</span></span></p>
</div>
<p></p></div>

# Output

<div class="content"><p>* Line 1: The maximum number of parent-child relationships possible on         a winning team. Print -1 if no team can win.</p>
<p></p>
<p class="MsoNormal"><span style="font-size: medium; "><span lang="EN-US">    </span><span style="font-family: 宋体; ">输出在一个能获胜的队伍中，最多可能存在的有血缘关系的牛的对数．如果任何一支队伍都不可能获胜，输出</span><span lang="EN-US">-1.</span></span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 8<br/>
-1 0   //第一个数字代表这头奶的产量,第二个数字代表其父亲点是哪一个.<br/>
3 1<br/>
5 1<br/>
-3 3<br/>
2 0<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
There are 5 cows. Cow 1 can produce -1 gallons and has two daughters, cow<br/>
2 and 3, who can produce 3 and 5 gallons, respectively. Cow 3 has a<br/>
daughter (cow 4) who can produce -3 gallons. Then there&#39;s cow 5, who can<br/>
produce 2 gallons.<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p> </p><br/>
<div></div><br/>
<div><br/>
<p class="MsoNormal"><span style="font-size: medium; "><span lang="EN-US">    </span><span style="font-family: 宋体; ">约翰一共有</span><span lang="EN-US">5</span><span style="font-family: 宋体; ">头奶牛．第</span><span lang="EN-US">1</span><span style="font-family: 宋体; ">头奶牛能提供</span><span lang="EN-US">-1</span><span style="font-family: 宋体; ">加仑的牛奶，且她是第</span><span lang="EN-US">2</span><span style="font-family: 宋体; ">、第</span><span lang="EN-US">3</span><span style="font-family: 宋体; ">头奶牛的母亲．第</span><span lang="EN-US">2</span><span style="font-family: 宋体; ">、第</span><span lang="EN-US">3</span><span style="font-family: 宋体; ">头奶牛的产奶量务别为</span></span><st1:chmetcnv tcsc="0" numbertype="1" negative="False" hasspace="False" sourcevalue="3" unitname="加仑" w:st="on"></st1:chmetcnv><span style="font-size: medium; "><st1:chmetcnv tcsc="0" numbertype="1" negative="False" hasspace="False" sourcevalue="3" unitname="加仑" w:st="on"><span lang="EN-US">3</span><span style="font-family: 宋体; ">加仑</span></st1:chmetcnv><span style="font-family: 宋体; ">和</span></span><st1:chmetcnv tcsc="0" numbertype="1" negative="False" hasspace="False" sourcevalue="5" unitname="加仑" w:st="on"></st1:chmetcnv><span style="font-size: medium; "><st1:chmetcnv tcsc="0" numbertype="1" negative="False" hasspace="False" sourcevalue="5" unitname="加仑" w:st="on"><span lang="EN-US">5</span><span style="font-family: 宋体; ">加仑</span></st1:chmetcnv><span style="font-family: 宋体; ">．第</span><span lang="EN-US">4</span><span style="font-family: 宋体; ">头奶牛是第</span><span lang="EN-US">3</span><span style="font-family: 宋体; ">头奶牛的女儿，她能提供</span><span lang="EN-US">-3</span><span style="font-family: 宋体; ">加仑牛奶．还有与其他牛都没有关系的第</span><span lang="EN-US">5</span><span style="font-family: 宋体; ">头奶牛，她的产奶量是</span></span><st1:chmetcnv tcsc="0" numbertype="1" negative="False" hasspace="False" sourcevalue="2" unitname="加仑" w:st="on"></st1:chmetcnv><span style="font-size: medium; "><st1:chmetcnv tcsc="0" numbertype="1" negative="False" hasspace="False" sourcevalue="2" unitname="加仑" w:st="on"><span lang="EN-US">2</span><span style="font-family: 宋体; ">加仑</span></st1:chmetcnv><span style="font-family: 宋体; ">．</span></span></p><br/>
<p class="MsoNormal"><span style="font-size: medium; "><span lang="EN-US">    </span><span style="font-family: 宋体; ">最好的一支队伍包括第</span><span lang="EN-US">1</span><span style="font-family: 宋体; ">，</span><span lang="EN-US">2</span><span style="font-family: 宋体; ">，</span><span lang="EN-US">3</span><span style="font-family: 宋体; ">，</span><span lang="EN-US">5</span><span style="font-family: 宋体; ">头奶牛．她们一共能产出（</span><span lang="EN-US">-1</span><span style="font-family: 宋体; ">）</span><span lang="EN-US">+3+5+2=9</span><span style="font-family: 宋体; ">≥</span><span lang="EN-US">8</span><span style="font-family: 宋体; ">加仑牛奶，</span></span></p><br/>
<p class="MsoNormal"><span style="font-size: medium; "><span style="font-family: 宋体; ">并且这支队伍里有</span><span lang="EN-US">2</span><span style="font-family: 宋体; ">对牛有血缘关系（</span><span lang="EN-US">1</span><span style="font-family: 宋体; ">—</span><span lang="EN-US">2</span><span style="font-family: 宋体; ">和</span><span lang="EN-US">1-3</span><span style="font-family: 宋体; ">）．如果只选第</span><span lang="EN-US">2</span><span style="font-family: 宋体; ">，</span><span lang="EN-US">3</span><span style="font-family: 宋体; ">，</span><span lang="EN-US">5</span><span style="font-family: 宋体; ">头奶牛，虽然总产奶量会更高（</span></span><st1:chmetcnv tcsc="0" numbertype="1" negative="False" hasspace="False" sourcevalue="10" unitname="加仑" w:st="on"></st1:chmetcnv><span style="font-size: medium; "><st1:chmetcnv tcsc="0" numbertype="1" negative="False" hasspace="False" sourcevalue="10" unitname="加仑" w:st="on"><span lang="EN-US">10</span><span style="font-family: 宋体; ">加仑</span></st1:chmetcnv><span style="font-family: 宋体; ">），但这支队伍里包含的血缘关系的对数比上一种组合少（队伍里没有血缘关系对）．</span></span></p><br/>
</div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

