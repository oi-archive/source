# 题目描述


<h3>
【题目描述】
</h3>
<p>
随着小F能力的增强，他开始尝试在各大OJ上刷题。
</p>
<p>
然而最近小F碰到了一个垃圾出题人出的题，这个题对他来说太难了，他想了半天也没有什么思路。
</p>
<p>
题目是这样的，小F面前摆着一个长度为N的序列，每个元素为不超过M的正整数。
</p>
<p>
为了整做题的小F，垃圾出题人会进行Q次修改，每次修改的内容为一对不超过M的正整数a,b，表示将序列中所有为a的数改写为b。
</p>
<p>
所有修改操作进行完之后，要求小F把最后的序列算出来。
</p>
<p>
渣渣小F又不会了...然而...他又没忘掉向你求助...
</p>
<h3>
【输入格式】
</h3>
<p>
第一行，包含三个整数N,M,Q，意义如上所述。
</p>
<p>
第二行，包含 N 个整数 A1,A2......AN，表示初始序列。接下来的Q行，每行两个整数a,b，意义如上所述。
</p>
<h3>
【输出格式】
</h3>
<p>
输出一行，包含N个整数，表示最后序列的形态。
</p>
<h3>
【样例输入】
</h3>
<pre>5 5 3
1 2 3 4 5
3 1
4 3
1 5
</pre>
<h3>
【样例输出】
</h3>
<pre>5 2 5 3 5</pre>
<h3>
【数据范围】
</h3>
<p>
对于20%的数据，1&lt;=N,M,Q&lt;=1000。
</p>
<p>
对于另外40%的数据，1&lt;=N,Q&lt;=100000，1&lt;=M&lt;=20。
</p>
<p>
对于100%的数据，1&lt;=N,M,Q&lt;=1000000，1&lt;=a,b,Ai&lt;=M。
</p>
<h3>
【来源】
</h3>
<p>
搬运 by HZOI 2016
</p>
