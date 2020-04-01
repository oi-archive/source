
# Description

<div class="content"><div>九条可怜在玩一个很好玩的策略游戏：Slay the Spire，一开始九条可怜的卡组里有2n张牌，每张牌上都写着一个</div>
<div>数字wi，一共有两种类型的牌，每种类型各n张：1.攻击牌：打出后对对方造成等于牌上的数字的伤害。2.强化牌</div>
<div>：打出后，假设该强化牌上的数字为x，则其他剩下的攻击牌的数字都会乘上x。保证强化牌上的数字都大于1。现</div>
<div>在九条可怜会等概率随机从卡组中抽出m张牌，由于费用限制，九条可怜最多打出k张牌，假设九条可怜永远都会采</div>
<div>取能造成最多伤害的策略，求她期望造成多少伤害。</div>
<div>假设答案为y，你只需要输出</div>
<div>（2n）!*y / (m!*(2n-m)!) Mod 998244353</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行一个正整数T表示数据组数</div>
<div>接下来对于每组数据：</div>
<div>第一行三个正整数n,m,k</div>
<div>第二行n个正整数wi，表示每张强化牌上的数值。</div>
<div>第三行n个正整数wi，表示每张攻击牌上的数值。</div>
<div>1&lt;=k&lt;=m&lt;=2n&lt;=3e3</div>
<div>1&lt;=wi&lt;=1e8</div>
<div>Σ2n &lt;= 3e4</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出T行，每行一个非负整数表示每组数据的答案。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
2 3 2<br/>
2 3<br/>
1 2<br/>
10 16 14<br/>
2 3 4 5 6 7 8 9 10 11<br/>
1 2 3 4 5 6 7 8 9 10</span></div>

# Sample Output

<div class="content"><span class="sampledata">19<br/>
253973805</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Qingyu上传">鸣谢Qingyu上传</a></p></div>

