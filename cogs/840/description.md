# 题目描述


<p>
	<span style="font-family:宋体;">【问题描述】</span><span style="font-family:;" "=""></span> 
</p>
<p>
	<span style="font-family:;" "=""><span>    </span></span><span style="font-family:宋体;">小</span>x<span style="font-family:宋体;">在学习了加法和乘法之后，想到了一个问题。</span><span style="font-family:;" "=""></span> 
</p>
<p>
	<span style="font-family:;" "=""><span>    </span></span><span style="font-family:宋体;">给定一个很长的数字</span><span style="font-family:;" "="">N</span><span style="font-family:宋体;">，能不能在中间加上<code>*</code><span style="font-family:宋体;">和<code>+</code><span style="font-family:;" "="">,</span><span style="font-family:宋体;">进行相应的乘法和加法运算，得到自己预期的结果整数</span><span style="font-family:;" "="">T</span><span style="font-family:宋体;">。</span><span style="font-family:;" "=""></span> </span></span> 
</p>
<p>
	<span style="font-family:;" "=""><span>    </span></span><span style="font-family:宋体;">我们约定：<code>*</code><span style="font-family:宋体;">的优先级高于<code>+</code><span style="font-family:宋体;">，且运算数可以有任意个前导</span><span style="font-family:;" "="">0.</span> </span></span> 
</p>
<p>
	<span style="font-family:宋体;">【输入】</span><span></span> 
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:宋体;">输入数据会有多组。</span><span></span> 
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:宋体;">每组数据包含两行。</span><span></span> 
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:宋体;">第一行：一个长度为</span><span>N</span><span style="font-family:宋体;">的只包含</span><span>0~9</span><span style="font-family:宋体;">的数字字符串；</span><span></span> 
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:宋体;">第二行：一个整数</span><span>T</span><span style="font-family:宋体;">。</span><span></span> 
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:宋体;">如果</span><span>T&lt;0</span><span style="font-family:宋体;">表示输入结束。</span><span></span> 
</p>
<p>
	<span style="font-family:宋体;">【输出】</span><span></span> 
</p>
<p>
	<span><span>       </span></span><span style="font-family:宋体;">每组数据输出一个数字单独占一行，表示最少需要添加的运算符（</span><code>*</code><span style="font-family:宋体;">和<code>+</code><span style="font-family:宋体;">），无解输出</span><span style="font-family:;" "="">-1</span><span></span> </span> 
</p>
<p>
	<span style="font-family:宋体;">【输入输出样例</span><span>1</span><span style="font-family:宋体;">】</span><span></span> 
</p>
<table style="border-collapse:collapse;border:none;" border="1" cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="283">
				<p>
					<span style="font-family:;" "="">puzzle.in</span> 
				</p>
			</td>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="283">
				<p>
					<span>puzzle</span><span style="font-family:;" "="">.out</span> 
				</p>
			</td>
		</tr>
		<tr>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="283">
<pre class="prettyprint">032057
5
333
8
00
-1</pre>
			</td>
			<td style="border:solid windowtext 1.0pt;" valign="top" width="283">
				<p>
					<br/>
				</p>
<pre class="prettyprint">3
-1</pre>
				<p>
					<br/>
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	<span style="font-family:宋体;">【样例解释】第一组</span><span> 03+2+0*57=5<span>  </span></span><span style="font-family:宋体;">第二组无解</span><span></span> 
</p>
<p>
	<span style="font-family:宋体;">【数据范围】</span><span> </span> 
</p>
<p>
	<span><span>   </span>30%</span><span style="font-family:宋体;">数据保证</span><span> 1&lt;=N&lt;=10<span>  </span>0&lt;=T&lt;=50</span> 
</p>
<p>
	<span><span>  </span><span> </span>50%</span><span style="font-family:宋体;">数据保证</span><span> 1&lt;=N&lt;=15<span>  </span>0&lt;=T&lt;=200</span> 
</p>
<p>
	<span><span>   </span></span><span style="font-family:宋体;">对于全部数据</span><span><span>  </span></span><span style="font-family:宋体;">测试数据不超过</span><span>5</span><span style="font-family:宋体;">组</span><span><span>  </span>1&lt;=N&lt;=20<span>  </span>0&lt;=T&lt;=200</span> 
</p>
<p>
	<span style="font-size:16.0pt;"> </span> 
</p>
