# 题目描述


<p class="MsoNormal">
<strong></strong>
</p>
<h3>
<strong>题目描述</strong>
</h3>
<p>
<br/>
</p>
<p>
对于集合 N={1 ， 2 ，…， n} 的子集，定义一个称之为“小于”的关系：
</p>
<p>
设 S 1 ={X 1 ， X 2 ，…， X i } ， (x 1 &lt;x 2 &lt; … &lt;X i ) ，
</p>
<p>
   S 2 ={Y 1 ， Y 2  ，…， Y j } ， (Y 1 &lt;Y 2 &lt; … &lt;Y i ) ，
</p>
<p>
如果存在一个 k ， (O ≤ k ≤ min{i ， j)) ，使得 X  1 =Y 1 ，…， X k =Y k ，且 k=i 或 X (k+1) &lt;Y (k+1) ，则称 S 1 “小于” S 2 。
</p>
<p>
你的任务是，对于任意的 n(n ≤ 31) 及 k(k&lt;2^n ) ，求出第 k 小的子集。
</p>
<p>
</p><h3>【输入】</h3>
<p></p>
<p>
输入文件仅一行，包含两个用空格隔开的自然数， n 和 k 。
</p>
<p>
</p><h3>【输出】</h3>
<p></p>
<p>
输出文件仅一行，是该子集的元素，由小到大排列。空集输出 0 。
</p>
<p>
</p><h3>【样例】</h3>
<p></p>
<p>
sort.in
</p>
<p>
3 4
</p>
<p>
sort.out
</p>
<p>
1 2 3
</p>
