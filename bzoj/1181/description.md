
# Description

<div class="content"><p>在一个地区的选举中，共有V个人参加了投票，每一票只可能投给N个政党中的一个。当地的议会共有M个席位。不妨将N个政党编号为1到N，并且设编号为i的政党最终的得票为Vi，则议会中的席位按如下规则分配： 1、将得票数小于总选票的5%的政党剔除。 2、初始时议会为空，每个政党都只有0个席位。 3、对于每个政党P，计算一个参数Qp = Vp / (Sp + 1)，Vp为政党P的最终得票，Sp为政党P当前已经在议会拥有的席位。 4、给Qp最大的政党分配一个席位，如果有多个政党的Qp相同，则将席位分给其中编号最小的政党。 5、重复3和4，直到议会已满。 由于计票还没有结束，现在我们只知道一部分选票的投票结果。给出V、N、M以及每个政党当前的得票，请你计算每个政党最多以及最少能赢得多少个席位。</p></div>

# Input

<div class="content"></div>

# Output

<div class="content"></div>

# Sample Input

<div class="content"><span class="sampledata">20 4 5<br/>
4 3 6 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 3 3 2<br/>
1 0 1 0</span></div>

# Hint

<div class="content"><p></p><p></p><br/>
<div>14 votes have been tallied and 6 are yet to be counted. To illustrate one possible outcome, suppose that the first party receives 2 of those 6 votes, the second none, the third 1 vote and the fourth 3 votes. The parties&#39; totals are 6, 3, 7 and 4 votes. All parties exceeded the 5% threshold. Seats are allocated as follows: 1. The quotients are initially 6/1, 3/1, 7/1 and 4/1; the largest is 7/1 so party 3 wins a seat. 2. The quotients are 6/1, 3/1, 7/2 and 4/1; the largest is 6/1 so party 1 wins a seat. 3. The quotients are 6/2, 3/1, 7/2 and 4/1; the largest is 4/1 so party 4 wins a seat. 4. The quotients are 6/2, 3/1, 7/2 and 4/2; the largest is 7/2 so party 3 wins a seat. 5. The quotients are 6/2, 3/1, 7/3 and 4/2; parties 1 and 2 are tied with quotients 6/2 and 3/1, but party 1 is lower numbered so it wins the last seat. In this outcome, the numbers of seats won by the parties are 2, 0, 2 and 1. Since it is possible for the second party not to win any seats, the second number on the second line of output is zero.</div><br/>
<div><span style="color: rgb(255, 0, 0);">1 ≤ V ≤ 10,000,000, 1 ≤ N ≤ 100, 1 ≤ M ≤ 200</span></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

