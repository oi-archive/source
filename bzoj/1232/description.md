
# Description

<div class="content"><p><span style="font-size: medium">Farmer John变得非常懒, 他不想再继续维护供奶牛之间供通行的道路. 道路被用来连接N (5 &lt;= N &lt;= 10,000)个牧场, 牧场被连续地编号为1..N. 每一个牧场都是一个奶牛的家. FJ计划除去P(N-1 &lt;= P &lt;= 100,000)条道路中尽可能多的道路, 但是还要保持牧场之间的连通性. 你首先要决定那些道路是需要保留的N-1条道路. 第j条双向道路连接了牧场S_j和E_j (1 &lt;= S_j &lt;= N; 1 &lt;= E_j &lt;= N; S_j != E_j), 而且走完它需要L_j (0 &lt;= L_j &lt;= 1,000)的时间. 没有两个牧场是被一条以上的道路所连接. 奶牛们非常伤心, 因为她们的交通系统被削减了. 你需要到每一个奶牛的住处去安慰她们. 每次你到达第i个牧场的时候(即使你已经到过), 你必须花去C_i (1 &lt;= C_i &lt;= 1,000)的时间和奶牛交谈. 你每个晚上都会在同一个牧场(这是供你选择的)过夜, 直到奶牛们都从悲伤中缓过神来. 在早上起来和晚上回去睡觉的时候, 你都需要和在你睡觉的牧场的奶牛交谈一次. 这样你才能完成你的交谈任务. 假设Farmer John采纳了你的建议, 请计算出使所有奶牛都被安慰的最少时间. 对于你前10次的提交, 你的程序会在一部分正式的测试数据上运行, 并且返回运行的结果.</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第 1 行: 用空格隔开的两个整数N和P * 第 2..N+1 行: 第i+1行包含了一个整数: C_i * 第 N+2..N+P+1 行: 第 N+j+1 行包含用空格隔开的三个整数: S_j, E_j 和 L_j </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">第 1 行: 一个整数, 所需要的总时间(包含和在你所在的牧场的奶牛的两次谈话时间). </span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 7<br/>
10<br/>
10<br/>
20<br/>
6<br/>
30<br/>
1 2 5<br/>
2 3 5<br/>
2 4 12<br/>
3 4 17<br/>
2 5 15<br/>
3 5 6<br/>
4 5 12<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">176<br/>
</span></div>

# Hint

<div class="content"><p></p><p><img height="281" width="1065" alt="" src="/source/bzoj/1232/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS8yMigxNCkuanBn.jpg"/></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

