
# Description

<div class="content"><div>我们假设小T有一个人体耐力上限E，在月初的时候，小T有E的体力。</div>
<div>接下来每一天有一个任务，这个任务小T可以付出任意的非负整数体力去完成，并且，每一天的结束的时候，小T会增加R的体力。当然体力是不可能超出E的，也就是说，如果当前体力+R大于E，那么恢复完之后的体力依旧是E。毫无疑问，体力是不可能小于0的。</div>
<div>每个任务会有一个价值V[]，一个任务的收获就是这个任务的价值乘上付出的体力。</div>
<div>你要帮帮小T，使他最大化 “所有任务的收获之和”， 方便他继续的高富帅！</div>
<div>最后，我们的口号是“烧死GFS~”。</div>
<div></div></div>

# Input

<div class="content"><div>
<div>第一行一个正整数case，表示数据的组数。</div>
<div>对于每一组数据，第一行有三个正整数E，R，N，表示的是能量上限，恢复值，和这个月的天数。第二行有N个非负整数表示V[1]-V[N]。</div>
<div></div>
</div>
<div>
<p class="MsoNormal" style="text-indent: 21pt;"></p>
</div>
<div>
<div></div>
<div></div>
<p></p>
</div></div>

# Output

<div class="content"><div>
<div>对于一组数据，一行输出最大化的收获之和。</div>
<div></div>
</div>
<div></div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
5 2 2<br/>
2 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">12</span></div>

# Hint

<div class="content"><p></p><div>第一天用5的体力，接下来恢复2点体力，再用光。</div><br/>
<div>Can&lt;=10,N&lt;=500000,E&lt;=10^6.所有的输入非负，并且，V&lt;=10^6。</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名提供">By 佚名提供</a></p></div>

