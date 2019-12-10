<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>你正在玩你最喜欢的电子游戏，并且刚刚进入一个奖励关。在这个奖励关里，系统将依次随机抛出k次宝物，每次你都可以选择吃或者不吃（必须在抛出下一个宝物之前做出选择，且现在决定不吃的宝物以后也不能再吃）。 宝物一共有n种，系统每次抛出这n种宝物的概率都相同且相互独立。也就是说，即使前k-1次系统都抛出宝物1（这种情况是有可能出现的，尽管概率非常小），第k次抛出各个宝物的概率依然均为1/n。 获取第i种宝物将得到Pi分，但并不是每种宝物都是可以随意获取的。第i种宝物有一个前提宝物集合Si。只有当Si中所有宝物都至少吃过一次，才能吃第i种宝物（如果系统抛出了一个目前不能吃的宝物，相当于白白的损失了一次机会）。注意，Pi可以是负数，但如果它是很多高分宝物的前提，损失短期利益而吃掉这个负分宝物将获得更大的长期利益。 假设你采取最优策略，平均情况你一共能在奖励关得到多少分值？</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行为两个正整数k和n，即宝物的数量和种类。以下n行分别描述一种宝物，其中第一个整数代表分值，随后的整数依次代表该宝物的各个前提宝物（各宝物编号为1到n），以0结尾。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>输出一个实数，保留六位小数，即在最优策略下平均情况的得分。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>1 2</span><br><span> 1 0</span><br><span> 2 0</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>1.500000</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>1&lt;=k&lt;=100,1&lt;=n&lt;=15，分值为[-10^6,10^6]内的整数。</span></p>
</div>
</div>