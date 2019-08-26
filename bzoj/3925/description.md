
# Description

<div class="content"><p> 傲娇少女幽香是一个很萌很萌的妹子，而且她非常非常地有爱心，很喜欢为幻想乡的人们做一些自己力所能及的事情来帮助他们。 这不，幻想乡突然发生了地震，所有的道路都崩塌了。现在的首要任务是尽快让幻想乡的交通体系重新建立起来。幻想乡一共有n个地方，那么最快的方法当然是修复n-1条道路将这n个地方都连接起来。 幻想乡这n个地方本来是连通的，一共有m条边。现在这m条边由于地震的关系，全部都毁坏掉了。每条边都有一个修复它需要花费的时间，第i条边所需要的时间为ei。地震发生以后，由于幽香是一位人生经验丰富，见得多了的长者，她根据以前的经验，知道每次地震以后，每个ei会是一个0到1之间均匀分布的随机实数。并且所有ei都是完全独立的。 现在幽香要出发去帮忙修复道路了，她可以使用一个神奇的大魔法，能够选择需要的那n-1条边，同时开始修复，那么修复完成的时间就是这n-1条边的ei的最大值。当然幽香会先使用一个更加神奇的大魔法来观察出每条边ei的值，然后再选择完成时间最小的方案。 幽香在走之前，她想知道修复完成的时间的期望是多少呢？ </p></div>

# Input

<div class="content"><div>第一行两个数n,m，表示地方的数量和边的数量。其中点从1到n标号。 </div>
<div>接下来m行，每行两个数a,b，表示点a和点b之间原来有一条边。 </div>
<div>这个图不会有重边和自环。 </div></div>

# Output

<div class="content"><div>一行输出答案，四舍五入保留6位小数。 </div></div>

# Sample Input

<div class="content"><span class="sampledata">5 4<br/>
1 2<br/>
1 5<br/>
4 3<br/>
5 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.800000</span></div>

# Hint

<div class="content"><p></p><div>提示： </div><br/>
<div><br/>
<div>（以下内容与题意无关，对于解题也不是必要的。） </div><br/>
<div>对于n个[0,1]之间的随机变量x1,x2,...,xn，第k小的那个的期望值是k/(n+1)。 </div><br/>
<div></div><br/>
<div>样例解释： </div><br/>
<div>对于第一个样例，由于只有4条边，幽香显然只能选择这4条，那么答案就是4条边的ei中最大的数的期望，由提示中的内容，可知答案为0.8。 </div><br/>
<div></div><br/>
<div>数据范围： </div><br/>
<div>对于所有数据：n&lt;=10, m&lt;=n(n-1)/2, n,m&gt;=1。 </div><br/>
<div>对于15%的数据：n&lt;=3。 </div><br/>
<div>另有15%的数据：n&lt;=10, m=n。 </div><br/>
<div>另有10%的数据：n&lt;=10, m=n(n-1)/2。 </div><br/>
<div>另有20%的数据：n&lt;=5。 </div><br/>
<div>另有20%的数据：n&lt;=8。</div><br/>
</div><br/>
<div></div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

