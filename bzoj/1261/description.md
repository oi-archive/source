
# Description

<div class="content">
张老师根据自己工作的需要，设计了一种特殊的二叉搜索树。他把这种二叉树起名为zh_tree，对于具有n个结点的zh_tree，其中序遍历恰好为(1，2，3，…，n)，其中数字1，2，3，…，n 是每个结点的编号。n个结点恰好对应于一组学术论文中出现的n个不同的单词。第j个单词在该组论文中出现的次数记为dj，例如，d2=10表示第2个结点所对应的单词在该组论文中出现了10次。设该组论文中出现的单词总数为S，显然，S=d1+d2+…+dn。记fj=dj/S为第j个单词在该组论文中出现的概率（频率）。
张老师把根结点深度规定为0，如果第j个结点的深度为r，则访问该结点的代价hj为hj=k(r+1)+c，其中k，c为已知的不超过100的正常数。
则zh_tree是满足以下条件的一棵二叉树：它使
h1f1+h2f2+…+hnfn
达到最小。我们称上式为访问zh_tree的平均代价。
请你根据已知数据为张老师设计一棵zh_tree。
</div>

# Input

<div class="content">第1行：3个用空格隔开的正数：
n k c
其中n&lt;30，为整数，k，c为不超过100的正实数。
第2行：n个用空格隔开的正整数，为每个单词出现的次数(次数&lt;200)。
</div>

# Output

<div class="content">第1行：(5分)一个正实数，保留3位小数，为访问Zh_tree的最小平均代价。
第2行：（5分）n个用空格隔开的整数，为该树的前序遍历。一般地，作为最优解的前序遍历不一定唯一，只输出一个解。
</div>

# Sample Input

<div class="content"><span class="sampledata">4 2 3.5<br/>
20 30 50 20<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7.000<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

