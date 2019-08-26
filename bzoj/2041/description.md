
# Description

<div class="content"><p>陶陶最近开始玩红警了，他玩的是自己MOD的一个红警版本。这个版本是这样的：你只能造两样东西，战车工厂和坦克。最初你有一个战车工厂，然后在接下来的每一秒内你可以有两种选择(假设当前有k个战车工厂)：1，建造一个战车工厂；2，建造k辆坦克。注意，战车工厂和坦克是不能同时建造的。 陶陶在玩了一个月红警后，认为自己红警水平很厉害了。于是他向curimit发了一份挑战书，他还嚣张地说他会对curimit发动N次攻击。第i次攻击在第time[i]秒末，陶陶会使用num[i]辆坦克来进攻，消灭掉curimit家里同等数量的坦克。如果此时curimit家里没有这么多的坦克的话，那么curimit就死翘翘了。 curimit接到战书后看到看到陶陶如此强大的攻势，被吓得不轻。他想请你帮帮忙，帮他制定一份作战计划（什么时候造战车工厂，什么时候造坦克）：curimit希望在抵挡了陶陶的N轮进攻之后，在第final秒末发动最终的总攻击，一举歼灭陶陶的老家。他希望你的作战计划能够在第final秒末造出最多数量的坦克。</p></div>

# Input

<div class="content"><p>第1行为两个整数N，final，含义如题目中所述。 接下来N行，第i行有两个数time[i]和num[i]，含义如题目中所述。</p></div>

# Output

<div class="content"><p>如果curimit无法抵挡陶陶的进攻，那么输出“No Answer!”；否则输出第final秒末curimit最多能拥有多少辆坦克。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 10<br/>
5 3<br/>
7 13<br/>
9 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
</span></div>

# Hint

<div class="content"><p></p><p>第1秒：造战车工厂。 第2秒：造战车工厂。 第3秒：造战车工厂。 第4秒：造坦克，当前坦克数：4。 第5秒：造坦克，当前坦克数：8。 第5秒：陶陶带了3辆坦克冲了进来，当前坦克数：5。 第6秒：造坦克，当前坦克数：9。 第7秒：造坦克，当前坦克数：13。 第7秒：陶陶带了13辆坦克冲了进来，当前坦克数：0。 第8秒：造坦克，当前坦克数：4。 第9秒：造坦克，当前坦克数：8。 第9秒：陶陶带了4辆坦克冲了进来，当前坦克数：4。 第10秒：造坦克，当前坦克数：8。 在第10秒末，curimit家里最多有8辆坦克。【数据规模和约定】 10%的数据中N≤5，final≤10； 30%的数据中N≤1000，final≤1000； 100%的数据中N≤100000，final≤10^ 9，0≤num[i]≤10^ 18； 100%的数据中1≤time[1]</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=版权所有者： 宋文杰">版权所有者： 宋文杰</a></p></div>

