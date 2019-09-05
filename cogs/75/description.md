# 题目描述


<h3>
【问题描述】
</h3>
<p>
在一个果园里，多多已经将所有的果子打了下来，而且按果子的不同种类分成了不同的堆。多多决定把所有的果子合成一堆。
</p>
<p>
每一次合并，多多可以把两堆果子合并到一起，消耗的体力等于两堆果子的重量之和。可以看出，所有的果子经过 $n-1$ 次合并之后，就只剩下一堆了。多多在合并果子时总共消耗的体力等于每次合并所耗体力之和。
</p>
<p>
因为还要花大力气把这些果子搬回家，所以多多在合并果子时要尽可能地节省体力。假定每个果子重量都为 $1$，并且已知果子的种类数和每种果子的数目，你的任务是设计出合并的次序方案，使多多耗费的体力最少，并输出这个最小的体力耗费值。
</p>
<p>
例如有 $3$ 种果子，数目依次为 $1,2,9$。可以先将 $1,2$ 堆合并，新堆数目为 $3$，耗费体力为 $3$。接着，将新堆与原先的第三堆合并，又得到新的堆，数目为 $12$，耗费体力为 $12$。所以多多总共耗费体力为 $3+12=15$。可以证明 $15$ 为最小的体力耗费值。
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件fruit.in包括两行，第一行是一个整数 $n(1\le n\le 10000)$，表示果子的种类数。第二行包含 $n$ 个整数，用空格分隔，第 $i$ 个整数 $a_i(1\le a_i\le 20000)$ 是第 $i$ 种果子的数目。
</p>
<h3>
【输出格式】
</h3>
<p>
输出文件fruit.out包括一行，这一行只包含一个整数，也就是最小的体力耗费值。输入数据保证这个值小于 $231$。
</p>
<h3>
【样例输入】
</h3>
<pre>3
1 2 9
</pre>
<h3>
【样例输出】
</h3>
<pre>15
</pre>
<h3>
【数据规模】
</h3>
<p>
对于 30% 的数据，保证有 $n\le 1000$
</p>
<p>
对于 50% 的数据，保证有 $n\le 5000$
</p>
<p>
对于全部的数据，保证有 $n\le 10000$。
</p>