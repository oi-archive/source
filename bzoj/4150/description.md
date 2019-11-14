
# Description

<div class="content"><div>在舞台上有n个枪手，第i个枪手瞄准了第p[i]个枪手，将于第u[i]秒开枪。一个枪手如果成功开枪，</div>
<div>那么被瞄准的枪手会立刻死亡。</div>
<div>现在给出q次修改操作，请在一开始和每次修改操作后统计出最后存活的枪手个数。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个正整数n(1&lt;=n&lt;=200000)，表示枪手的个数。</div>
<div>第二行包含n个互不相同的正整数p[1],p[2],...,p[n](1&lt;=p[i]&lt;=n,p[i]!=i)，依次表示每个枪手的目标。</div>
<div>第三行包含n个正整数u[1],u[2],...,u[n](1&lt;=u[i]&lt;=10^9)，依次表示每个枪手的开枪时间。</div>
<div>接下来一行包含一个正整数q，表示修改操作的个数。</div>
<div>接下来q行，每行包含两个正整数k,v(1&lt;=k&lt;=n,1&lt;=v&lt;=10^9)，表示把u[k]修改为v。</div>
<div>数据保证任何时刻任意两个枪手的开枪时间都不同。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>第一行包含一个正整数，即在进行修改之前最后存活的枪手个数。</div>
<div>接下来q行，每行包含一个正整数，第i行输出在第i次修改之后最后存活的枪手个数。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
2 3 4 1<br/>
1 2 3 4<br/>
3<br/>
1 8<br/>
2 7<br/>
3 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
2<br/>
1<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris上传">鸣谢Claris上传</a></p></div>

