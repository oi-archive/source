
# 题目描述

** 译自 BalticOI 2011 Day2 T1「Meetings」**

有 $N$ 人需达成一项计划。每人都花 $P\min$ 陈述自己的提案，所有人陈述完毕后再花 $V\min$ 表决出最佳提案。例如，如果有 $100$ 人，$P=V=1\min$，总共需要 $1\times 100 + 1=101\min$ 来达成计划。  
为了加快进度，他们想分成小组，每个小组表决出一份最佳议案，再由全部人一起表决各小组选出的议案。注意小组内可以再分组。小组内表决的方式类似，也是每人陈述自己的提案后再表决。例如，$100$ 人分成两组，一组 $60$ 人，一组 $40$ 人，那么过程如下（与前面相同，$P=V=1\min$）：
* $60$ 人组花 $61\min$ 选出最佳议案，同时 $40$ 人组花 $41\min$ 选出最佳议案（自然，他们要等待 $60$ 人组）；
* 两组再花 $2\min$ 陈述，然后花 $1\min$ 表决。

总用时 $61 + 2 + 1 = 64\min$。  
试求：他们至少要多久才能达成计划。

The Society for Saving the World has called their N members to an emergency congress to finally agree on a plan for saving the world. To reach a common decision in any meeting at the congress, the meeting participants proceed as follows:
1. Each of them has a proposal and takes P minutes to present it to the others.
2. After all participants have made their presentations, they vote for the best proposal, which takes V minutes.

For example, if each proposal takes one minute (P = 1) and voting also takes one minute (V = 1), a meeting with 100 participants would reach a decision in 101 minutes.
To speed up the overall decision-making process, the participants of the congress have decided to split into groups and work in parallel. Each group selects the best proposal among themselves using the procedure described above. Then the representatives of the groups meet and pick the final plan among the proposals voted best in each group.
For example, if the 100 participants would split into two groups of 40 and 60, respectively, the process could work as follows (again, P = V = 1):
* the larger group takes 61 minutes to select their best proposal;
* the smaller group takes 41 minutes to do the same and then has to wait for the larger group to finish;
* then the two representatives of the groups meet and spend 2 minutes presenting to each other and 1 minute to vote.

The total time spent is thus 61 + 2 + 1 = 64 minutes.
But the groups might further divide themselves into subgroups and sometimes it could be useful to split into more than two groups. As a special case, a subgroup of 1 member can decide in no time, as there is no need to present one’s own proposal to oneself.
Write a program that, given presentation and voting times P and V , computes the minimal time needed for the N participants of the congress to reach a common decision, assuming they organize their meetings and groups optimally.

# 输入格式

仅一行，包括三个整数 $N, P, V$。

The first and only line of input contains the three integers N, P, and V : N is the number of participants of the congress, P is the presentation time (in minutes), and V is the voting time (in minutes).

# 输出格式

输出共一行，表示他们至少需要多少分钟才能达成计划。

The first and only line of output should contain the integer M, the minimal number of minutes needed for the congress to reach a decision.

# 样例

|Sample Input|Sample Output|
|-|-|
|`9 1 1`|`8`|
|`6 1 2`|`8`|
|`6 2 1`|`12`|
在第一组样例中，$9$ 人应分成 $3$ 组，一组 $3$ 人。

# 数据范围与提示

对于 $40\%$ 的数据，$1 ≤ N ≤ 5000$。  
对于 $70\%$ 的数据，$1 ≤ N ≤ 5\times 10^4$。  
对于所有数据，$1 ≤ N ≤ 10^{15}, 1 ≤ P,V ≤ 1000$。

