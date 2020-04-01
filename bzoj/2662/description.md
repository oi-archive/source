
# Description

<div class="content"><p><span style="font-size: medium">  “我要成为魔法少女！”   <br/>
  “那么，以灵魂为代价，你希望得到什么？” <br/>
“我要将有关魔法和奇迹的一切，封印于卡片之中„„”   <br/>
   <br/>
  在这个愿望被实现以后的世界里，人们享受着魔法卡片（SpellCard，又名符<br/>
卡）带来的便捷。 <br/>
 <br/>
现在，不需要立下契约也可以使用魔法了！你还不来试一试？ <br/>
  比如，我们在魔法百科全书（Encyclopedia  of  Spells）里用“freeze”作为关<br/>
键字来查询，会有很多有趣的结果。 <br/>
例如，我们熟知的Cirno，她的冰冻魔法当然会有对应的 SpellCard 了。 当然，<br/>
更加令人惊讶的是，居然有冻结时间的魔法，Cirno 的冻青蛙比起这些来真是小<br/>
巫见大巫了。 <br/>
这说明之前的世界中有很多魔法少女曾许下控制时间的愿望，比如 Akemi <br/>
Homura、Sakuya Izayoi、„„ <br/>
当然，在本题中我们并不是要来研究历史的，而是研究魔法的应用。 <br/>
 <br/>
我们考虑最简单的旅行问题吧：  现在这个大陆上有 N 个城市，M 条双向的<br/>
道路。城市编号为 1~N，我们在 1 号城市，需要到 N 号城市，怎样才能最快地<br/>
到达呢？ <br/>
  这不就是最短路问题吗？我们都知道可以用 Dijkstra、Bellman-Ford、<br/>
Floyd-Warshall等算法来解决。 <br/>
  现在，我们一共有 K 张可以使时间变慢 50%的 SpellCard，也就是说，在通<br/>
过某条路径时，我们可以选择使用一张卡片，这样，我们通过这一条道路的时间<br/>
就可以减少到原先的一半。需要注意的是： <br/>
  1. 在一条道路上最多只能使用一张 SpellCard。 <br/>
  2. 使用一张SpellCard 只在一条道路上起作用。 <br/>
  3. 你不必使用完所有的 SpellCard。 <br/>
   <br/>
  给定以上的信息，你的任务是：求出在可以使用这不超过 K 张时间减速的<br/>
SpellCard 之情形下，从城市1 到城市N最少需要多长时间。 </span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium"><br/>
第一行包含三个整数：N、M、K。 <br/>
接下来 M 行，每行包含三个整数：Ai、Bi、Timei，表示存在一条 Ai与 Bi之<br/>
间的双向道路，在不使用 SpellCard 之前提下，通过它需要 Timei的时间。 </span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">输出一个整数，表示从1 号城市到 N号城市的最小用时。 </span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4 1 <br/>
1 2 4 <br/>
4 2 6 <br/>
1 3 8 <br/>
3 4 8 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7 <br/>
【样例1 解释】 <br/>
  在不使用 SpellCard 时，最短路为 1à2à4，总时间为 10。现在我们可<br/>
以使用 1 次 SpellCard，那么我们将通过 2à4 这条道路的时间减半，此时总<br/>
时间为7。 <br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据：1  ≤  K  ≤  N ≤  50，M  ≤  1000。 <br/><br/>
  1≤  Ai，Bi ≤  N，2 ≤  Timei  ≤  2000。 <br/><br/>
为保证答案为整数，保证所有的 Timei均为偶数。 <br/><br/>
所有数据中的无向图保证无自环、重边，且是连通的。   <br/><br/>
 </p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

