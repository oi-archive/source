# 题目描述


<h3>
【题目描述】
</h3>
<p>
AVL树是一种平衡二叉搜索树，除二叉搜索树的基本性质外，AVL树还满足一个性质：
</p>
<p>
每个节点的左子树与右子树的高度相差不超过1。
</p>
<p>
对高度的定义是：叶子节点的高度为1，其他节点的高度为左右子树高度的较大值+1。
</p>
<p>
现在，给定高度值h和模数p，你需要求出高度为h的AVL树最少包含的节点数模p的值。
</p>
<h3>
【输入格式】
</h3>
<p>
一行两个数，分别为h和p。
</p>
<h3>
【输出格式】
</h3>
<p>
一行一个数，表示答案。
</p>
<h3>
【样例输入】
</h3>
<pre>4 10007</pre>
<h3>
【样例输出】
</h3>
<pre>7</pre>
<h3>
【样例解释】
</h3>
<p>
一种符合要求的AVL树如图所示：
</p>
<p>
<img src="/upload/image/20160811/20160811064134_92986.png" alt=""/> 
</p>
<h3>
【数据范围】
</h3>
<p>
对于30%的数据，有n&lt;=$10^8$；
</p>
<p>
对于100%的数据，有n&lt;=$10^{18}$，p&lt;=$2*10^9$。
</p>
<h3>
【来源】
</h3>
<p>
HZOI 2016
</p>
