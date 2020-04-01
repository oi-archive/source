
# Description

<div class="content"><div>小Q和小M最近发明了一种卡牌游戏，叫猴子大战。游戏最初小Q和小M各会取得一部分猴子牌。每局游戏，他们两个</div>
<div>需要分别等概率地从自己的猴子牌中抽取一张进行战斗。获胜的一方将获得双方的猴子牌。如果一方获得了所有的</div>
<div>猴子牌，则该方获得整场游戏的胜利。否则游戏将一直进行下去。 在进行了若干场比赛以后，小Q和小M算出了一</div>
<div>张胜率表，为每张猴子牌之间进行战斗双方获胜的概率。由于每场战斗一定会决出胜负，而且胜率不受先后顺序的</div>
<div>影响，因此对于任意的两张猴子牌A和B，A战胜B的概率加B战胜A的概率为1。 由于自己老是输给小M，小Q开始怀疑</div>
<div>自己每次拿到的猴子牌是否能获得胜利。他希望求出自己拿到的每种猴子牌组合的获胜的概率。 由于小Q接下来还</div>
<div>有在CD市体育中心数以万计的运动计划，因此这个问题只能交给你来解决了。</div></div>

# Input

<div class="content"><div>输入的第一行包含两个正整数n和m，表示猴子牌的总张数和需要求的猴子牌组合的个数。 </div>
<div>接下来有n行，每行包含n个实数，每个实数保留了两位小数。</div>
<div>这n行中，其中第i行第j列的数为Pi,j，表示第i张猴子牌战胜第j张猴子牌的概率。</div>
<div>保证Pi,j + Pj,i  =  1。特别地，Pi,j = 0.5，没有特殊意义。 最后又m行。</div>
<div>每行包含一个长度为n的无空格分隔的01串，表示一个猴子牌的组合。</div>
<div>其中第i个字符如果为0，表示最初第i张牌在小M处，否则表示在小Q处。</div></div>

# Output

<div class="content"><div>输出m行，每行一个实数，四舍五入保留八位小数（请强制输出八位浮点数），</div>
<div>一次表示每个给定的猴子牌组合下小Q获胜的概率。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4 <br/>
0.50 0.60 0.40 <br/>
0.40 0.50 0.70 <br/>
0.60 0.30 0.50 <br/>
110 <br/>
011 <br/>
111 <br/>
000 <br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.71304348 <br/>
0.66086957 <br/>
1.00000000 <br/>
0.00000000 </span></div>

# Hint

<div class="content"><p></p><div>【评分方法】 </div><br/>
<div>你的答案的每一行如果与我们给定的参考答案的差别均不超过2×10-6，则获得该测试点的得分，否则不得分。 </div><br/>
<div>参考答案保证与真实值的差别不超过10-8，因此如果你输出的答案保证与真实值差别不超过2×10^-6 — 2×10^-8，才能保证正确。</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=vfleaking提供spj">vfleaking提供spj</a></p></div>

