# 题目描述


<h3>
【题目描述】
</h3>
<p>
   有一个5*5的网格，其中恰好有一个格子是空的，其他格子各有一个字母。一共有4种指令：A，B，L,R,分别表示把空格上、下、左、右的相邻字母移到空格中。输入初始网格和指令序列（以数字0结束），输出指令执行完毕的网格。如果有非法指令，应先输出“This puzzle has no final configuration.”并且立即结束，然后输出当前网格。例如，图1中执行ARRBBL0后，效果如图2所示。
</p>
<p>
<img alt="" src="/upload/image/20181031/20181031101112_33169.png"/>               <img alt="" src="/upload/image/20181031/20181031101128_41957.png"/> 
</p>
<h3>
【输入格式】
</h3>
<p>
1，输入一个5*5的由字符构成的网格，其中有一个空格。
</p>
<p>
2，第6行是由A，B，L，R组成的由0结束的字符串。
</p>
<h3>
【输出格式】
</h3>
<p>
执行完毕之后的5*5的网格，中间用空格隔开。
</p>
<p>
如果非法，输出“This puzzle has no final configuration.”及当前网格。
</p>
<h3>
【样例输入】
</h3>
<p>
<span style="font-size:18px;">TRGSJ</span> 
</p>
<p>
<span style="font-size:18px;">XDOKI</span> 
</p>
<p>
<span style="font-size:18px;">M VLN</span> 
</p>
<p>
<span style="font-size:18px;">WPABE</span> 
</p>
<p>
<span style="font-size:18px;">UQHCF</span> 
</p>
<p>
<span style="font-size:18px;">ARRBBL0</span> 
</p>
<h3>
【样例输出】
</h3>
<p>
<span style="font-size:18px;">T R G S J</span> 
</p>
<p>
<span style="font-size:18px;">X O K L I</span> 
</p>
<p>
<span style="font-size:18px;">M D V B N</span> 
</p>
<p>
<span style="font-size:18px;">W P   A E</span> 
</p>
<p>
<span style="font-size:18px;">U Q H C F</span> 
</p>
<h3>
【提示】
</h3>
<pre>如果有非法指令，则立即结束，输出网格！！！
</pre>
<br/>
