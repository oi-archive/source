
# Description

<div class="content"><div>没头脑 和不高兴 是一对形影不离的好朋友，他们一起上学也一起玩耍。这天，这对好朋友聚在一起玩纸牌游戏。</div>
<div>他们所玩的纸牌总共有N张，每一张上面都有一个1N 的数组，任意两张纸牌上的数字都不相同。根据他们制定的游</div>
<div>戏规则，在每局游戏的开始，所有的牌需要按照从1N 的顺序排好。在开心地完了一局牌之后，他们发现牌的顺序</div>
<div>被弄得乱七八遭，将它们排好序是 一件挺麻烦的事情。他们讲凌乱的纸牌在桌面上排成一排，然后开始了排序工</div>
<div>作。不高兴 由于在上一局游戏中输了牌，非常不高兴。他只将其中((奇数位置)) 的牌排成了升序，然后把剩下的</div>
<div>任务推给了没头脑。没头脑 非常没头脑，他采取了一个有些 笨的排序方式。每次，他找到两张相邻并且顺序不对</div>
<div>的牌交换他们，直到整个 序列被排好序为止。乐于探究的你，想要研究在初始排列随机的情况下没头脑 花在交换</div>
<div>纸牌上的时间。假设没头脑 每交换一对纸牌花费的时间为 1，你希望求出他排序时间的期望。此外，为了更好地</div>
<div>分析这个问题，你还希望能够计算出所花时间的方差。更进一步地，如果((被不高兴排好序的位置发生了变化))，</div>
<div>你是否还能求出没头脑 用来排序的时间期望呢？</div></div>

# Input

<div class="content"><div>输入文件共 M+1 行。</div>
<div>第一行包含两个正整数 N,M。</div>
<div>接下来M行，每行包含三个整数l,r,v。其中 1 &lt;=_l&lt;= r&lt;= N,?v属于{1,N}</div>
<div>若v=0则表示不高兴不再对l 到r之间的位置排序；反之若v=1则表示被不高兴 排序的位置将涵盖 l到r。</div>
<div>输出文件共M+2行。每行输出一个形如p/q的有理数，其中gcd(p,q )=1, q&gt;=1,p,q为整数。</div></div>

# Output

<div class="content"><div>第一行输出在初始条件下没头脑 排序时间的期望。 </div>
<div>第二行输出在初始条件下没头脑 排序时间的方差。</div>
<div>接下来Ｍ行，每行分别输出在对不高兴 排序的位置进行了前若干次修改之 后没头脑 排序时间的期望。</div></div>

# Sample Input

<div class="content"><span class="sampledata">33<br/>
230 221 131<br/>
2.5 </span></div>

# Sample Output

<div class="content"><span class="sampledata">2/3<br/>
2/9<br/>
3/2<br/>
1/1<br/>
0/1</span></div>

# Hint

<div class="content"><p></p><p><img width="668" height="215" alt="" src="/source/bzoj/3148/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwNC8xKDgpLmpwZw==.jpg"/></p><br/>
<p>N&lt;=100000, M=10^5</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

