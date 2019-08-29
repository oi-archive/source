<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　艾利斯顿商学院篮球队要参加一年一度的市篮球比赛了。拉拉队是篮球比赛的一个看点，好的拉拉队往往能帮助球队增加士气，赢得最终的比赛。所以作为拉拉队队长的楚雨荨同学知道，帮助篮球队训练好拉拉队有多么的重要。<br/>
　　拉拉队的选拔工作已经结束，在雨荨和校长的挑选下，<b><i>n</i></b><b>位</b>集优秀的身材、舞技于一体的美女从众多报名的女生中脱颖而出。这些女生将随着篮球队的小伙子们一起，和对手抗衡，为艾利斯顿篮球队加油助威。<br/>
　　一个阳光明媚的早晨，雨荨带领拉拉队的队员们开始了排练。<i>n</i>个女生从左到右排成一行，每个人手中都举了一个写有<b>26</b><b>个小写字母</b>中的某一个的牌子，在比赛的时候挥舞，为小伙子们呐喊、加油。<br/>
　　雨荨发现，如果<b>连续的一段</b>女生，有<b>奇数</b>个，并且他们手中的牌子所写的字母，从左到右和从右到左读起来一样，那么这一段女生就被称作<b>和谐小群体</b>。<br/>
　　现在雨荨想找出所有<b>和谐小群体</b>，并且按照女生的个数<b>降序</b>排序之后，<b>前</b><b>K</b><b>个</b>和谐小群体的女生个数<b>的乘积</b>是多少。由于答案可能很大，雨荨只要你告诉她，答案除以<b>19930726</b>的余数是多少就行了。</div>
# 输入格式

<div class="pdcont">　　输入为标准输入。<br/>
　　第一行为两个正整数<i>n</i>和<i>K</i>，代表的东西在题目描述中已经叙述。<br/>
　　接下来一行为<i>n</i>个字符，代表从左到右女生拿的牌子上写的字母。</div>
# 输出格式

<div class="pdcont">　　输出为标准输出。<br/>
　　输出一个整数，代表题目描述中所写的乘积除以19930726的余数，如果总的和谐小群体个数小于<i>K</i>，输出一个整数-1。</div>
# 样例输入

<div class="pddata">5 3<br/>
ababa</div>
# 样例输出

<div class="pddata">45</div>
# 样例说明

<div class="pdcont">　　和谐小群体女生所拿牌子上写的字母从左到右按照女生个数降序排序后为ababa, aba, aba, bab, a, a, a, b, b，前三个长度的乘积为 。</div>
# 数据规模和约定

<div class="pdcont">　　总共20个测试点，数据范围满足：<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">测试点<br/>
</td><td valign="top" style="border:solid 1.0pt"><i>n</i><br/>
</td><td valign="top" style="border:solid 1.0pt">K<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">10<br/>
</td><td valign="top" style="border:solid 1.0pt">10<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">100<br/>
</td><td valign="top" style="border:solid 1.0pt">100<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">100<br/>
</td><td valign="top" style="border:solid 1.0pt">100<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">1,000<br/>
</td><td valign="top" style="border:solid 1.0pt">1,000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">1,000<br/>
</td><td valign="top" style="border:solid 1.0pt">1,000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">6<br/>
</td><td valign="top" style="border:solid 1.0pt">1,000<br/>
</td><td valign="top" style="border:solid 1.0pt">1,000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">1,000<br/>
</td><td valign="top" style="border:solid 1.0pt">1,000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">8<br/>
</td><td valign="top" style="border:solid 1.0pt">100,000<br/>
</td><td valign="top" style="border:solid 1.0pt">= 1<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">9<br/>
</td><td valign="top" style="border:solid 1.0pt">100,000<br/>
</td><td valign="top" style="border:solid 1.0pt">100,000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">10<br/>
</td><td valign="top" style="border:solid 1.0pt">100,000<br/>
</td><td valign="top" style="border:solid 1.0pt">100,000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">11<br/>
</td><td valign="top" style="border:solid 1.0pt">100,000<br/>
</td><td valign="top" style="border:solid 1.0pt">100,000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">12<br/>
</td><td valign="top" style="border:solid 1.0pt">100,000<br/>
</td><td valign="top" style="border:solid 1.0pt">1,000,000,000,000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">13<br/>
</td><td valign="top" style="border:solid 1.0pt">100,000<br/>
</td><td valign="top" style="border:solid 1.0pt">1,000,000,000,000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">14<br/>
</td><td valign="top" style="border:solid 1.0pt">100,000<br/>
</td><td valign="top" style="border:solid 1.0pt">1,000,000,000,000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">15<br/>
</td><td valign="top" style="border:solid 1.0pt">500,000<br/>
</td><td valign="top" style="border:solid 1.0pt">1,000,000,000,000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">16<br/>
</td><td valign="top" style="border:solid 1.0pt">500,000<br/>
</td><td valign="top" style="border:solid 1.0pt">1,000,000,000,000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">17<br/>
</td><td valign="top" style="border:solid 1.0pt">500,000<br/>
</td><td valign="top" style="border:solid 1.0pt">1,000,000,000,000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">18<br/>
</td><td valign="top" style="border:solid 1.0pt">1,000,000<br/>
</td><td valign="top" style="border:solid 1.0pt">= 1<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">19<br/>
</td><td valign="top" style="border:solid 1.0pt">1,000,000<br/>
</td><td valign="top" style="border:solid 1.0pt">1,000,000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">20<br/>
</td><td valign="top" style="border:solid 1.0pt">1,000,000<br/>
</td><td valign="top" style="border:solid 1.0pt">1,000,000,000,000<br/>
</td></tr></tbody></table></div>

</div>