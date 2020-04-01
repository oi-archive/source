
# Description

<div class="content"><p>向Byteland的国王Bitolomew致敬！国王Bitolomew认为Byteland是一个独一无二的国家。它太小了，它所有的市民（包括国外）都只在农场或工厂之一工作，其中农场和工厂是两个不同的城市。因此每天早晨，每个城市的居民都在去这两个城市的路上通行。Byteland的交通网络包括一些连接两个不同城市的无向的道路，道路不会连向国家之外的城市（但是隧道和桥可能会这样）。两个城市间可能存在多条无向的道路。保证农场和工厂与所有城市连通。几个月前，为了改善交通状况，国王Bitolomew出台了过路费的政策，需要每个市民每次在通过相应道路时支付固定的费用Bitolomew希望这能引导市民重新考虑他们的上班路线，从而使得交通更加均匀畅通。国王的点子被他的谏者证明是不够完美的。每个Byteland的市民现在都开始走起了最便宜的上班路线。国王Bitolomew完全没想到会出现这种情况，然而过路费带来的收入着实提高了国家财政的收入。事实上，国王现在的经济状况实在是太好了，所以他准备在一个新的首都建一个新的城堡。新的首都必须和一些其他的城市通过无向的道路相连，这样才能从新首都到达每个城市。新建的道路可以设定非负的过路费（特别地，这里的过路费可以不是整数）。国王Bitolomew真的很讨厌车辆路过他的城堡所产生的噪声。他希望通过合理设定新道路的过路费使得从任意除了新首都之外的城市v到农场或工厂都不会经过新首都（注意这里v还包括农场和工厂）。另外，由于国王也要交过路费，所以他希望最小化从新首都到其他每个城市的平均过路费。请你帮助国王计算一下最小可能的平均值是多少吧。</p></div>

# Input

<div class="content"><p>第一行一个正整数T，表示有T组数据。</p>
<div>
<div>每组数据第一行两个正整数n和m，表示Byteland有n个城市和m条道路，2 &lt;= n &lt;= 10^5，1 &lt;= m &lt;= 3*10^5。</div>
<div>接下来m行，每行三个整数表示城市u和城市v之间有一条过路费为c的道路，1 &lt;= u, v &lt;= n，u ≠ v，0 &lt;= c &lt;= 10^6。两个城市间可能存在多条无向的道路。</div>
<div>农场所在的城市标号为1，工厂所在的城市标号为2。</div>
</div></div>

# Output

<div class="content"><p> 对于每组数据输出一行，最小可能的从新首都到其他点所需过路费的平均值。</p>
<div>
<div>你的答案应该和标准答案误差不超过10^-8。</div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
3 3<br/>
1 2 5<br/>
2 3 5<br/>
3 1 1 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1.833333333333<br/>
 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tjz">鸣谢Tjz</a></p></div>

