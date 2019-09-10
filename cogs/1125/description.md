# 题目描述


<h3>
	【题目描述】
</h3>
<p>
	<br/>
</p>
<p>
	有n根木棍，每根的长度l和重量w已知。这些木棍将被一台机器一根一根的加工。机器需要一些启动时间来做准备工作，启动时间与木棍被加工的具体情况有关。启动时间遵循以下规则：
</p>
<p>
	1加工第一根木棍的启动时间为1分钟。
</p>
<span style="font-size:10.5pt;font-family:" color:#323e32;"="">2加工完长度为<span style="font-size:10.5pt;font-family:" color:#323e32;"="">li，重量为<span style="font-size:10.5pt;font-family:" color:#323e32;"="">wi的木棍后，紧跟着加工长度<span style="font-size:10.5pt;font-family:" color:#323e32;"="">li+1，重量为<span style="font-size:10.5pt;font-family:" color:#323e32;"="">wi+1的木棍时，若<span style="font-size:10.5pt;font-family:" color:#323e32;"="">li≤li+1且<span style="font-size:10.5pt;font-family:" color:#323e32;"="">wi≤wi+1，则加工木棍<span style="font-size:10.5pt;font-family:" color:#323e32;"="">i+1时，不需要启动时间。例如：有<span style="font-size:10.5pt;font-family:" color:#323e32;"="">5根木棍，它们的长度和重量对为（<span style="font-size:10.5pt;font-family:" color:#323e32;"="">9,4），（<span style="font-size:10.5pt;font-family:" color:#323e32;"="">2,5），（<span style="font-size:10.5pt;font-family:" color:#323e32;"="">1,2），（<span style="font-size:10.5pt;font-family:" color:#323e32;"="">5,3），（<span style="font-size:10.5pt;font-family:" color:#323e32;"="">4,1），则最小总启动时间为<span style="font-size:10.5pt;font-family:" color:#323e32;"=""> 2分钟（加工序列为（<span style="font-size:10.5pt;font-family:" color:#323e32;"="">4,1），（<span style="font-size:10.5pt;font-family:" color:#323e32;"="">5,3），（<span style="font-size:10.5pt;font-family:" color:#323e32;"="">9,4），（<span style="font-size:10.5pt;font-family:" color:#323e32;"="">1,2），（<span style="font-size:10.5pt;font-family:" color:#323e32;"="">2,5）<span style="font-size:10.5pt;font-family:" color:#323e32;"="">）。
<p>
	<br/>
</p>
<h3>
	【输入格式】
</h3>
<p>
	<br/>
</p>
<p>
	输入文件wooden.in
</p>
<p>
	第一行一个整数n（1≤n≤5000），表示木棍的数量。
</p>
<p>
	第二行2 * n个整数，l1，w1，l2，w2，.......，ln，wn（1≤li,wi≤10000），为各根木棍的长度和重量，这2 * n个整数以若干个空格分隔。
</p>
<p>
	<br/>
</p>
<h3>
	【输出格式】
</h3>
<p>
	<br/>
</p>
<p>
	输出文件wooden.out仅一行，一个整数，即最小总启动时间。
</p>
<p>
	<br/>
</p>
<h3>
	【样例输入1】
</h3>
<p>
	<span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"="">5</span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span>
</p>
<p>
	<span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"="">
4 9 5 2 2 1 3 5 1 4</span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span>
</p>
<span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"="">
<h3>
	【样例输出1】
</h3>
2
<h3>
	【样例输入2】
</h3>
<p>
	<span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"="">3</span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span>
</p>
<p>
	<span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"="">
2 2 1 1 2 2</span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span>
</p>
<span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"="">
<h3>
	【样例输出2】
</h3>
<p>
	<span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"="">1</span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span>
</p>
<p>
	<span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""><span style="font-size:10.5pt;font-family:" color:#323e32;"=""></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span>
</p>
<h3>
</h3>
<h3>
	【来源】
</h3>
<p>
	冲刺NOIP2010模拟试题与解析（七）（提高组复赛）
</p>
<br/>
<p>
	<br/>
</p>
</span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span>
