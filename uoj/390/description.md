# 题目描述

<p>在UOJ管理员群里一共有$N$个管理员，为了容纳这些管理员，vfk准备了$N + 1$个鸽笼。</p>
<p>为了节省空间，vfk把这些鸽笼堆了起来，共有$n$列，第$i$列放了$a_i$个鸽笼，满足 $\sum a_i = N+1$。</p>
<p>每当UR结束，管理员们就会按照编号从小到大的顺序回到鸽笼里，每个管理员回来的时候，会先等概率的在所有还有剩余的鸽笼的列中随机一个列，然后住到这列剩下的鸽笼里编号最小的一个中。</p>
<p>现在$N$个管理员都回笼了之后，还有一列会空出一个鸽笼。你能对于每一列，求出这一列有空鸽笼的概率吗？</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/390/Shenzhen_Metro_Baigelong.jpg" alt="百鸽笼"/></p>

# 输入格式


<p>第一行一个整数$n$。</p>
<p>第二行$n$个正整数$a_i$。</p>

# 输出格式


<p>一行$n$个整数表示答案对$998244353$取模的结果。</p>

# 样例一


<h4>input</h4>
<pre>3
1 1 1

</pre>

<h4>output</h4>
<pre>332748118 332748118 332748118

</pre>

<h4>explanation</h4>
<p>都是$\frac{1}{3}$。</p>

# 样例二


<h4>input</h4>
<pre>3
1 2 3

</pre>

<h4>output</h4>
<pre>771790773 824938042 399759892

</pre>



# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<p>对于所有数据，均满足 $1\le a_i \le 30,1 \le n \le 30,\sum a_i \ge 1$。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th><th>分值</th><th>限制</th></tr></thead><tbody><tr><td>1</td><td>$10$</td><td>$1 \leq a_i \leq 3, n \leq 10$</td></tr><tr><td>2</td><td>$10$</td><td>$1 \leq a_i \leq 5. n \leq 30$</td></tr><tr><td>3</td><td>$20$</td><td>$1 \leq a_i \leq 30, n \leq 10$</td></tr><tr><td>4</td><td>$20$</td><td>$1 \leq a_i \leq 30, n \leq 20$</td></tr><tr><td>5</td><td>$40$</td><td>$1 \leq a_i \leq 30, n \leq 30$</td></tr></tbody></table></div>

<p><strong>时间限制</strong>：$1\texttt{s}$</p>
<p><strong>空间限制</strong>：$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=390">样例数据下载</a></p>
