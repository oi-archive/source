# 题目描述


<h3>
<p>
【题目背景】
</p>
<p>
一排兽舍用钢丝网隔成了m间笼子,用来养老虎,由于老虎性格凶猛,隔着钢丝网也可能把隔壁老虎抓伤,所以不能连续两间笼子都圈养老虎.
</p>
<p>
第一问:求最多能养多少只老虎
</p>
<p>
第二问:给出圈养老虎的所有方案.
</p>
<p>
【输入文件】
</p>
<p>
输入文件 tiger.in 第一行是一个整数 m （ m&lt;=12 ）
</p>
<p>
【输出文件】
</p>
<p>
输出文件 tiger.out 的第一行包含一个整数 T ，下面接着有n行,每行是一种圈养老虎的方案。
</p>
<p>
【样例输入】
</p>
<pre>5
</pre>
<p>
【样例输出】
</p>
<pre>3
00000
00001
00010
00100
00101
01000
01001
01010
10000
10001
10010
10100
10101 
</pre>
<p>
【样例解释】            
</p>
<p>
长度为5的笼舍,最多养3只老虎,象下面最后一行的方案10101,表示1,3,5号笼子养老虎,2,4号笼子空着            
</p>
<p>
第1种方案00000,表示一只老虎也不养,第2种方案00001,表示1号笼(从右边开始编号)养老虎,其它的笼子不养,依此类推.            
</p>
<p>
输出方案按字典序排序.
</p>
</h3>
<p>
<br/>
</p>
