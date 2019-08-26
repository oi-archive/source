
# Description

<div class="content"><p> 这里省略对游戏情节的剧透，有兴趣可以去Steam上搜索Quantum Break。你被请来帮助小Q同学决策一个游戏场景</p>
<div>的操作。假设主角位于三维空间的原点，有 n 个敌人向他射击，其中第 i 个敌人可以对主角产生 a_i 点伤害。</div>
<div>此外，空间中还有 m 个装有时元粒子的桶，其中引爆第 i 个桶可以使以第 i 个桶为中心，半径为 r_i 的球型区</div>
<div>域内部的时间静止一段时间，这也意味着子弹在球型区域内无法运动（不包括子弹轨迹与区域相切的情况）。主角</div>
<div>需要利用时光机器回到过去去拯救他的兄弟，现在时光机器正在原点启动，而他要在原地保护时光机器的启动过程</div>
<div>，这意味着他只能在原地使用时间能力来防御攻击。小Q可以操纵主角在这个场景使用两种时间能力，时间引爆和</div>
<div>时间护盾。一次时间引爆可以引爆一个桶，引爆不受到时间静止的影响，这意味着主角可以成功引爆一个已经在时</div>
<div>间静止区域内的桶。而时间护盾则是在以使用者本身为中心的一定区域内产生时间静止，从而抵御子弹的伤害。给</div>
<div>出每个敌人和桶的信息，假设杰克已经引爆所有的桶，但是其中 k (0≤k≤m) 个桶的时间静止效果即将消失，你</div>
<div>需要计算杰克在这种情况下要用时间护盾抵御的伤害之和的最大值 s(k) 。为了简化问题，你只需要输出sigma((i</div>
<div>+1)*s(i)),0&lt;=i&lt;=m,其对2^64取模的值而不是每个 s(k) 。时间是一种强大的力量，它也是头号杀手。注意时间限</div>
<div>制与空间限制。</div>
<div></div></div>

# Input

<div class="content"><p> 第一行包含一个正整数 T ，表示有 T 组数据，满足 T≤200 。</p>
<div>接下来是测试数据。对于每组测试数据：</div>
<div>第一行包含两个正整数 n 和 m ，满足 1≤n≤15,1≤m≤10^5 。</div>
<div>接下来 n 行给出敌人的信息，其中第 i 行包含四个整数 x_i,y_i,z_i,a_i ，表示第 i 个敌人的坐标是 (x_i,y_i,z_i)</div>
<div>其能对主角造成的伤害是 a_i ，满足 0≤|x_i |,|y_i |,|z_i |≤10^4,1≤a_i≤10^4 。</div>
<div>接下来 m 行给出桶的信息，其中第 i 行包含四个整数 x_i,y_i,z_i,r_i ，表示第 i 个桶的坐标是 (x_i,y_i,z_i) </div>
<div>其爆炸的半径是 r_i ，满足 0≤|x_i |,|y_i |,|z_i |≤10^4,1≤r_i≤10^4 。</div>
<div>保证所有给出的点（包括主角的位置）互不相同。</div>
<div>不超过 10 组数据满足 m≥100 ，不超过 2 组数据满足 m≥10^4 。</div></div>

# Output

<div class="content"><p>对于每组测试数据，输出一行一个非负整数，表示这组数据的答案。</p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
1 5<br/>
1 1 2 7<br/>
1 2 0 2<br/>
-1 8 -1 8<br/>
-2 -3 5 6<br/>
-2 1 3 3<br/>
-4 2 3 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">105</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供试题">鸣谢Tangjz提供试题</a></p></div>

