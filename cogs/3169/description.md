# 题目描述


<h3>
【题目描述】
</h3>
<p>
HS对包含n个点且每个连通块都是环的图很感兴趣，他给每个这样的图都打了一个1-m的分数。因为HS不能区分开本质相同的两个图，所以本质相同的图会被打上相同的分数。
</p>
<p>
当n=3的时候，HS会给如下三个图打可能不同的分数。
</p>
<p>
<img src="/upload/image/20190612/20190612085849_97872.png" alt=""/> 
</p>
<p>
HS想知道他有多少种不同的打分方法，因为结果太大了，所以只需要求出模1996488706(假设phi(1996488706)=998244353(虽然不是！))的答案就可以了。
</p>
<h3>
【输入格式】
</h3>
<p>
本有多组数据，故第一行有一个整数T，表示数据组数，
</p>
<p>
接下来T行，每行两个整数，表示n,m。
</p>
<h3>
【输出格式】
</h3>
<p>
T行，每行一个整数，表示答案。
</p>
<h3>
【样例输入】
</h3>
<pre>2
3 2
8 2
</pre>
<h3>
【样例输出】
</h3>
<pre>8
4194304
</pre>
<h3>
【提示】
</h3>
<p>
对于10%的数据，1&lt;=n，m&lt;=5，T=1。
</p>
<p>
对于20%的数据，1&lt;=n，m，T&lt;=1000。
</p>
<p>
对于50%的数据，1&lt;=n ，m&lt;=100000，T=1。
</p>
<p>
对于100%的数据，1&lt;=n，m，T &lt;=100000。
</p>
