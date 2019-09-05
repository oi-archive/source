# 题目描述


<h3>
【题目描述】
</h3>
<p>
Treap是一种平衡二叉搜索树，除二叉搜索树的基本性质外，Treap还满足一个性质：
</p>
<p>
每个节点都有一个确定的优先级，且每个节点的优先级都比它的两个儿子小(即它的优先级满足堆性质)。
</p>
<p>
不难证明在节点的优先级都事先给定且互不相同时，对应的Treap有且仅有一个。
</p>
<p>
现在，给定n个数和每个数对应的优先级，求出对应的以数的大小作为二叉搜索树比较依据的Treap的先序遍历结果。
</p>
<p>
对先序遍历的定义是：先访问根节点，再访问左子树，最后访问右子树。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行一个数n表示数的个数。
</p>
<p>
第二行n个数表示每个数的大小。
</p>
<p>
第三行n个数表示每个数对应的优先级。
</p>
<h3>
【输出格式】
</h3>
<p>
一行n个数，表示Treap的先序遍历结果(对于每个节点，输出对应的数)。
</p>
<h3>
【样例输入】
</h3>
<pre>7
2 11 5 9 1 4 3
2 10 1 8 4 6 5
</pre>
<h3>
【样例输出】
</h3>
<pre>5 2 1 3 4 9 11</pre>
<h3>
【样例解释】
</h3>
<p>
对应的Treap如图所示，其中圈内的数是给出的数，圈外的数是节点的优先级。
</p>
<p>
<img src="/upload/image/20160807/20160807190522_51607.png" alt=""/> 
</p>
<h3>
【数据范围】
</h3>
<p>
n&lt;=500000。
</p>
<p>
所有的数和优先级都互不相同且在int(C++)/longint(Pascal)范围内。
</p>
<h3>
【提示】
</h3>
<p>
为了给不想用栈模拟递归的孩纸们偷懒的机会，C++选手请在main函数的开头加入以下代码：
</p>
<p>
int __size__=128&lt;&lt;20;
</p>
<p>
char *__p__=(char*)malloc(__size__)+__size__;
</p>
<p>
__asm__(&#34;movl %0, %%esp\n&#34;::&#34;r&#34;(__p__));
</p>
<p>
注意上述代码会占用你128MB的空间，请自行调整代码。
</p>
<h3>
【来源】
</h3>
<p>
HZOI 2016
</p>