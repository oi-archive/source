# 题目描述


<h3>
【题目描述】
</h3>
<p>
排序是生活中最常见的操作之一，计算机科学对此大有用武之地。稍有常识的人都知道，基于交换的排序时间复杂度下界是O(nlogn)。这意味着可能设计出的最好排序算法将用至少O(nlog(n))次交换操作来给n个整数排序。虽然如此，对给定的n个整数，如果你知道每个数在排序后的位置，那么你总能找到一个包含至多n-1次交换的操作序列来将它们按升序排列。考虑四个元素&lt;1 2 3 4&gt;，有24种可能的排列，并且你知道每个元素在排序后的位置。
</p>
<p>
如果排列是&lt;2 1 4 3&gt;，至少需要进行2次交换来让它有序（分别交换1,2和4,3）。如果排列是&lt;2 3 4 1&gt;，就至少需要进行3次交换。&lt;4 2 3 1&gt;需要1次交换，&lt;1 2 3 4&gt;不需要交换。用这种方法，我们可以找到包含N个不同整数，并且至少交换K次才能排序的排列数。
</p>
<h3>
【输入格式】
</h3>
<p>
输入包含最多250组数据。
</p>
<p>
每组数据占1行，含2个正整数N(1&lt;=N&lt;=21)和K(0&lt;=K&lt;N)。
</p>
<p>
输入结束标志为N=K=0.
</p>
<h3>
【输出格式】
</h3>
<p>
对于每组数据，输出至少交换K次才能排序的排列数。
</p>
<h3>
【样例输入】
</h3>
<pre>3 1
3 0
3 2
0 0</pre>
<h3>
【样例输出】
</h3>
<pre>3
1
2</pre>
<h3>
【来源】
</h3>
<p>
<a href="http://uva.onlinejudge.org/index.php?option=com_onlinejudge&amp;Itemid=8&amp;category=485&amp;page=show_problem&amp;problem=2018" target="_blank">UVa 11077 Find the Permutations</a> 
</p>
<p>
刘汝佳，《算法竞赛入门经典训练指南》表2-10
</p>
<p>
Problemsetter: Md. Kamruzzaman
</p>
<p>
Special Thanks: Abdullah-al-Mahmud
</p>
