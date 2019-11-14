
# Description

<div class="content"><p>　　你正在玩你最喜欢的电子游戏，并且刚刚进入一个奖励关。在这个奖励关里，系统将依次随机抛出k次宝物，<br/>
每次你都可以选择吃或者不吃（必须在抛出下一个宝物之前做出选择，且现在决定不吃的宝物以后也不能再吃）。<br/>
 宝物一共有n种，系统每次抛出这n种宝物的概率都相同且相互独立。也就是说，即使前k-1次系统都抛出宝物1（<br/>
这种情况是有可能出现的，尽管概率非常小），第k次抛出各个宝物的概率依然均为1/n。 获取第i种宝物将得到Pi<br/>
分，但并不是每种宝物都是可以随意获取的。第i种宝物有一个前提宝物集合Si。只有当Si中所有宝物都至少吃过<br/>
一次，才能吃第i种宝物（如果系统抛出了一个目前不能吃的宝物，相当于白白的损失了一次机会）。注意，Pi可<br/>
以是负数，但如果它是很多高分宝物的前提，损失短期利益而吃掉这个负分宝物将获得更大的长期利益。 假设你<br/>
采取最优策略，平均情况你一共能在奖励关得到多少分值？</p></div>

# Input

<div class="content"><p>　　第一行为两个正整数k和n，即宝物的数量和种类。以下n行分别描述一种宝物，其中第一个整数代表分值，随<br/>
后的整数依次代表该宝物的各个前提宝物（各宝物编号为1到n），以0结尾。</p></div>

# Output

<div class="content"><p>　　输出一个实数，保留六位小数，即在最优策略下平均情况的得分。</p></div>

# Sample Input

<div class="content"><span class="sampledata">1 2<br/>
1 0<br/>
2 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">1.500000</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">【数据规模】<br/><br/>
1&lt;=k&lt;=100,1&lt;=n&lt;=15，分值为[-10^6,10^6]内的整数。<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

