<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>某山贼集团在绿荫村拥有强大的势力，整个绿荫村由N个连通的小村落组成，并且保证对于每两个小村落有且仅有一条简单路径相连。小村落用阿拉伯数字编号为1,2,3,4,…,n，山贼集团的总部设在编号为1的小村落中。山贼集团除了老大坐镇总部以外，其他的P个部门希望在村落的其他地方建立分部。P个分部可以在同一个小村落中建设，也可以分别建设在不同的小村落中。每个分部到总部的路径称为这个部门的管辖范围，于是这P个分部的管辖范围可能重叠，或者完全相同。在不同的村落建设不同的分部需要花费不同的费用。每个部门可能对他的管辖范围内的小村落收取保护费，但是不同的分部如果对同一小村落同时收取保护费，他们之间可能发生矛盾，从而损失一部分的利益，他们也可能相互合作，从而获取更多的利益。现在请你编写一个程序，确定P个分部的位置，使得山贼集团能够获得最大的收益。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行包含一个整数N和P，表示绿荫村小村落的数量以及山贼集团的部门数量。</p>
<p>接下来N-1行每行包含两个整数X和Y，表示编号为X的村落与编号为Y的村落之间有一条道路相连。(1&lt;=X,Y&lt;=N)</p>
<p>接下来N行，每行P个正整数，第i行第j个数表示在第i个村落建设第j个部门的分部的花费Aij。</p>
<p>然后有一个正整数T，表示下面有T行关于山贼集团的分部门相互影响的代价。(0&lt;=T&lt;=2p)</p>
<p>最后有T行，每行最开始有一个数V，如果V为正，表示会获得额外的收益，如果V为负，则表示会损失一定的收益。然后有一个正整数C，表示本描述涉及的分部的数量，接下来有C个数，Xi，为分部门的编号(Xi不能相同)。表示如果C个分部Xi同时管辖某个小村落（可能同时存在其他分部也管辖这个小村落），可能获得的额外收益或者损失的收益为的|V|。T行中可能存在一些相同的Xi集合，表示同时存在几种收益或者损失。</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件要求第一行包含一个数Ans，表示山贼集团设置所有分部后能够获得的最大收益。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 1</p>
<p>1 2</p>
<p>2 1</p>
<p>1</p>
<p>3 1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于40%的数据，1&lt;=P&lt;=6。</p>
<p>对于100%的数据，1&lt;=N&lt;=100，1&lt;=P&lt;=12，保证答案的绝对值不超过108。</p>
</div>
</div>