
# Description

<div class="content"><p><span style="font-size: medium">Farmer John 想让她的奶牛准备郡级跳跃比赛，贝茜和她的伙伴们正在练习跨栏。她们很累，所以她们想消耗最少的能量来跨栏。 显然，对于一头奶牛跳过几个矮栏是很容易的，但是高栏却很难。于是，奶牛们总是关心路径上最高的栏的高度。 奶牛的训练场中有 N (1 ≤ N ≤ 300) 个站台，分别标记为1..N。所有站台之间有M (1 ≤ M ≤ 25,000)条单向路径，第i条路经是从站台Si开始，到站台Ei，其中最高的栏的高度为Hi (1 ≤ Hi ≤ 1,000,000)。无论如何跑，奶牛们都要跨栏。 奶牛们有 T (1 ≤ T ≤ 40,000) 个训练任务要完成。第 i 个任务包含两个数字 Ai 和 Bi (1 ≤ Ai ≤ N; 1 ≤ Bi ≤ N)，表示奶牛必须从站台Ai跑到站台Bi，可以路过别的站台。奶牛们想找一条路径从站台Ai到站台Bi，使路径上最高的栏的高度最小。 你的任务就是写一个程序，计算出路径上最高的栏的高度的最小值。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">行 1: 两个整数 N, M, T 行 </span></p>
<p><span style="font-size: medium">2..M+1: 行 i+1 包含三个整数 Si , Ei , Hi 行 M+2..M+T+1: 行 i+M+1 包含两个整数，表示任务i的起始站台和目标站台: Ai , Bi</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">行 1..T: 行 i 为一个整数，表示任务i路径上最高的栏的高度的最小值。如果无法到达，输出 -1。 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 6 3<br/>
1 2 12<br/>
3 2 8<br/>
1 3 5<br/>
2 5 3<br/>
3 4 4<br/>
2 4 8<br/>
3 4<br/>
1 2<br/>
5 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
8<br/>
-1<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

