<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　小Q和小M最近发明了一种卡牌游戏，叫猴子大战。<br/>
　　游戏最初小Q和小M各会获得一部分猴子牌。每局游戏，他们两个需要分别等概率地从自己的猴子牌中抽取一张进行战斗。获胜的一方将获得双方的猴子牌。如果一方获得了所有的猴子牌，则该方获得整场游戏的胜利。否则游戏将一直进行下去。<br/>
　　在进行了若干场比赛以后，小Q和小M算出了一张胜率表，为每两张猴子牌之间进行战斗双方获胜的概率。由于每场战斗一定会决出胜负，而且胜率不受先后顺序影响，因此对于任意的两张猴子牌A和B，A战胜B的概率加B战胜A的概率为1。<br/>
　　由于自己老是输给小M，小Q开始怀疑自己每次拿到的猴子牌是否能获得胜利。他希望求出自己拿到的每种猴子牌组合的获胜的概率。<br/>
　　由于小Q接下来还有在CD市体育中心数以万计的运动计划，因此这个问题只能交给你来解决了。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含两个正整数 n 和 m，表示猴子牌的总张数和需要求的猴子牌组合的个数。<br/>
　　接下来有 n 行，每行包含 n 个实数，每个实数保留了两位小数。这 n 行中，其中第 i 行第 j 列的数为 P_(i,j)，表示第 i 张猴子牌战胜第 j 张猴子牌的概率。保证P_(i,j)+P_(j,i)=1。特别地，P_(i,i)=0.5，没有特殊意义。<br/>
　　最后有 m 行。每行包含一个长度为 n 的无空格分隔的01串，表示一个猴子牌的组合。其中第 i 个字符如果为0，表示最初第 i 张牌在小M处，否则表示在小Q处。</div>
# 输出格式

<div class="pdcont">　　输出 m 行，每行一个实数，四舍五入保留八位小数，依次表示每个给定的猴子牌组合下小Q获胜的概率。</div>
# 样例输入

<div class="pddata">3 4<br/>
0.50 0.60 0.40<br/>
0.40 0.50 0.70<br/>
0.60 0.30 0.50<br/>
110<br/>
011<br/>
111<br/>
000</div>
# 样例输出

<div class="pddata">0.71304348<br/>
0.66086957<br/>
1.00000000<br/>
0.00000000</div>
# 评分方法

<div class="pdcont">　　你的答案的每一行如果与我们给定的参考答案的差别均不超过2×10^(-6)，则获得该测试点的得分，否则不得分。<br/>
　　参考答案保证与真实值的差别不超过10^(-8)，因此如果你输出的答案保证与真实值差别不超过2×10^(-6)-10^(-8)，才能保证正确。</div>
# 数据规模及约定

<div class="pdcont">　　对于每组数据，n的取值如下<br/>
<table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">测试点编号<br/>
</td><td style="border:solid 1.0pt"><i>n</i><br/>
</td><td style="border:solid 1.0pt">测试点编号<br/>
</td><td style="border:solid 1.0pt"><i>n</i><br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">1<br/>
</td><td style="border:solid 1.0pt"><i>n</i> = 2<br/>
</td><td style="border:solid 1.0pt">6<br/>
</td><td style="border:solid 1.0pt"><i>n</i> = 20<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">2<br/>
</td><td style="border:solid 1.0pt"><i>n</i> = 5<br/>
</td><td style="border:solid 1.0pt">7<br/>
</td><td style="border:solid 1.0pt"><i>n</i> = 40<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">3<br/>
</td><td style="border:solid 1.0pt"><i>n</i> = 7<br/>
</td><td style="border:solid 1.0pt">8<br/>
</td><td style="border:solid 1.0pt"><i>n</i> = 60<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">4<br/>
</td><td style="border:solid 1.0pt"><i>n</i> = 8<br/>
</td><td style="border:solid 1.0pt">9<br/>
</td><td style="border:solid 1.0pt"><i>n</i> = 80<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">5<br/>
</td><td style="border:solid 1.0pt"><i>n</i> = 10<br/>
</td><td style="border:solid 1.0pt">10<br/>
</td><td style="border:solid 1.0pt"><i>n</i> = 100<br/>
</td></tr></tbody></table><br/>
　　对于100%的数据，保证1≤n≤100，1≤m≤n^2。0≤P_(i,j)≤1，P_(i,j)  恰好包含2位小数，且 P_(i,j)+P_(j,i)=1。表示猴子牌组合的01串长度均为 n，且不含其它字符。<br/>
　　P_(i,j )的生成方式为：在某个环境下，使用某个随机数种子，持续调用某语言生成整数的伪随机函数直到时钟函数达到1秒，接下来取连续的若干个随机函数值对101取模再除以100，作为输入数据中的满足 i&lt;j 的 P_(i,j)。该生成过程只启动一次，即不会出现看到数据以后重新生成数据的情况。以上操作的目的是希望P_(i,j)的每个取值几乎等概率且不受人控制，你可以不必理会这段话。</div>

</div>