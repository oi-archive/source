# 题目描述


<span></span> 
<p>
	【问题描述】
</p>
<p>
	有<span>2n</span><span>个棋子（</span><span>n</span><span>≥</span><span>4</span><span>）排成一行，开始为位置白子全部在左边，黑子全部在右边，如下图为</span><span>n=5</span><span>的情况：</span> 
</p>
<p>
	○○○○○●●●●●
</p>
<p>
	移动棋子的规则是：每次必须同时移动相邻的两个棋子，颜色不限，可以左移也可以右移到空位上去，但不能调换两个棋子的左右位置。每次移动必须跳过若干个棋子（不能平移），要求最后能移成黑白相间的一行棋子。如<span>n=5</span><span>时，成为：</span> 
</p>
<p>
	○●○●○●○●○●
</p>
<p>
	任务：编程打印出移动过程。
</p>
<p>
	<br/>
</p>
<h3>
	【样例输入】
</h3>
<pre>7</pre>
<h3>
	【样例输出】
</h3>
<pre>step 0:ooooooo*******--
step 1:oooooo--******o*
step 2:oooooo******--o*
step 3:ooooo--*****o*o*
step 4:ooooo*****--o*o*
step 5:oooo--****o*o*o*
step 6:oooo****--o*o*o*
step 7:ooo--***o*o*o*o*
step 8:ooo*o**--*o*o*o*
step 9:o--*o**oo*o*o*o*
step10:o*o*o*--o*o*o*o*
step11:--o*o*o*o*o*o*o*
</pre>
