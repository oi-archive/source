# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
某山贼集团在绿荫村拥有强大的势力，整个绿荫村由 N 个连通的小村落组成，并且保证 对于每两个小村落有且仅有一条简单路径相连。小村落用阿拉伯数字编号为 1,2,3,4,…,n，
</p>
<p>
<br/>
</p>
<p>
山贼集团的总部设在编号为 1 的小村落中。山贼集团除了老大坐镇总部以外，其他的 P 个部 门希望在村落的其他地方建立分部。P 个分部可以在同一个小村落中建设，也可以分别建设 在不同的小村落中。每个分部到总部的路径称为这个部门的管辖范围，于是这 P 个分部的管 辖范围可能重叠，或者完全相同。在不同的村落建设不同的分部需要花费不同的费用。每个 部门可能对他的管辖范围内的小村落收取保护费，但是不同的分部如果对同一小村落同时收 取保护费，他们之间可能发生矛盾，从而损失一部分的利益，他们也可能相互合作，从而获 取更多的利益。现在请你编写一个程序，确定 P 个分部的位置，使得山贼集团能够获得最大 的收益。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
输入文件第一行包含一个整数 N 和 P，表示绿荫村小村落的数量以及山贼集团的部门数量。
</p>
<p>
接下来 N-1 行每行包含两个整数 X 和 Y，表示编号为 X 的村落与编号为 Y 的村落之间有 一条道路相连。(1&lt;=X,Y&lt;=N)
</p>
<p>
接下来 N 行，每行 P 个正整数，第 i 行第 j 个数表示在第 i 个村落建设第 j 个部门的分 部的花费 Aij。
</p>
<p>
然后有一个正整数 T，表示下面有 T 行关于山贼集团的分部门相互影响的代价。(0&lt;=T&lt;=2p)
</p>
<p>
<br/>
</p>
<p>
最后有 T 行，每行最开始有一个数 V，如果 V 为正，表示会获得额外的收益，如果 V 为负，则表示会损失一定的收益。然后有一个正整数 C，表示本描述涉及的分部的数量，接下来有 C 个数，Xi，为分部门的编号(Xi 不能相同)。表示如果 C 个分部 Xi 同时管辖某个小村落（可能同时存在其他分部也管辖这个小村落），可能获得的额外收益或者损失的收益为的|V|。T 行中可能存在一些相同的 Xi 集合，表示同时存在几种收益或者损失。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
输出文件要求第一行包含一个数 Ans，表示山贼集团设置所有分部后能够获得的最大收益。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
2 1
</p>

<p>
1 2
</p>

<p>
2   
</p>

<p>
1
</p>

<p>
1    
</p>

<p>
3 1 1    
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>5
</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
数据规模
</p>
<p>
<br/>
</p>
<p>
对于 40%的数据，1&lt;=P&lt;=6。
</p>
<p>
对于 100%的数据，1&lt;=N&lt;=100，1&lt;=P&lt;=12，保证答案的绝对值不超过 10^8。
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>