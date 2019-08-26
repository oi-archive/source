
# Description

<div class="content"><div>你被给定一系列关于重要的历史事件的演讲，每件事一场演讲，它们不按顺序排列。每件历史事件持续一个时间段[ai，bi]。如果两件事的时间有共同区间，我们说它们是有关联的。把关于有关联的历史事件的演讲排的彼此靠近能使课程更便于理解。此外，不相关的演讲必须按历史事件的发生时间排序（如果A在B之前发生，且AB不相关，那么关于A的演讲必须在B之前进行） </div>
<div>找出最小的整数k&gt;=0和一个演讲的顺序，使得排序后任意两场相关的演讲之间的间隔不超过k（第i场演讲和第j场演讲之间的间隔是|i-j|）。 </div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包括数据组数T。每组数据包含以下内容： </div>
<div>每组数据的第一行是一个数n，1&lt;=n&lt;=50000。接下来n行包括两个整数ai和bi，-10^9&lt;=ai&lt;=bi&lt;=10^9。区间两两不相同。 </div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>每组数据答案的第一行是一个最小值k，接下来n行按顺序列举排列后的演讲的历史事件的区间（与输入中的格式一样），使得任意两个相关的演讲相隔不超过k。切记将不相关的演讲按时间顺序排列！ </div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1 <br/>
3 <br/>
1 6 <br/>
2 3 <br/>
4 5 </span></div>

# Sample Output

<div class="content"><span class="sampledata">1 <br/>
2 3 <br/>
1 6 <br/>
4 5 </span></div>

# Hint

<div class="content"><p></p><p>共有三个历史事件，其中1,2；1,3是相关的，2,3不相关，且2在3之前发生，所以2应该排在3的前面。对于相关的历史事件，1与2在排列后的位置是2和1，间隔为1,1与3在排列后的位置为2与3，间隔为1,所以此时k最小为1，该排法最优。 </p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

