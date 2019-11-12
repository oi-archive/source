# 题目描述


<h3>
	【题目描述】
</h3>
<p>
	</p><table height="0" border="0" cellpadding="0" cellspacing="0" bgcolor="#FFFFFF">
		<tbody>
			<tr>
				<td width="502" align="left" valign="top" style="font-family:Tahoma;color:#32656D;">
					　　在设计关系数据库的表格时，术语“函数依赖”（FD）被用来表示不同域之间的关系。函数依赖是描述一个集合中的域的值与另一个集合中的域的值之间的关系。记号X-&gt;Y被用来表示当集合X中的域被赋值后，集合Y的域就可以确定相应的值。例如，一个数据表格包含“社会治安编号”（S）、“姓名”（N）、“地址”（A）、“电话”（P）的域，并且每个人都与某个特定的互不相同的S值相对应，根据域S就可以确定域N、A、P的值。这就记作S-&gt;NAP。 <br/>
　　写一个程序以找出一组依赖中所有的冗余依赖。一个依赖是冗余的是指它可以通过组里的其他依赖得到。例如，如果组里包括依赖A-&gt;B、B-&gt;C和A-&gt;C，那么第三个依赖是冗余的，因为域C可以用前两个依赖得到（域A确定了域B的值，同样域B确定了域C的值)。在A-&gt;B、B-&gt;C、C-&gt;A、A-&gt;C、C-&gt;B和B-&gt;A中，所有的依赖都是冗余的。 <br/>
　　现在要求你编写一个程序，从给定的依赖关系中找出冗余的。 <br/>
				</td>
			</tr>
			<tr>
				<td width="14" height="14" style="font-family:Tahoma;color:#32656D;">
				</td>
				<td colspan="2" style="font-family:Tahoma;color:#32656D;">
				</td>
				<td width="14" height="14" style="font-family:Tahoma;color:#32656D;">
				</td>
			</tr>
		</tbody>
	</table>
<p></p>
<h3>
	【输入格式】
</h3>
<p>
	</p><table height="0" border="0" cellpadding="0" cellspacing="0" bgcolor="#FFFFFF" style="font-family:Tahoma;">
		<tbody>
			<tr>
				<td width="502" align="left" valign="top" style="font-family:Tahoma;color:#32656D;">
					　　输入第一行是一个不超过100的整数n，它表示文件中函数依赖的个数。从第二行起每一行是一个函数依赖且互不重复，每行包含用字符“-”和“&gt;”隔开的非空域列表。列表月包含大写的字母，函数依赖的数据行中不包括空格和制表符，不会出现“平凡”冗余依赖（如A-&gt;A）。虽然文件中没有对函数依赖编号，但其顺序就是编号1到n。
				</td>
			</tr>
			<tr>
			</tr>
		</tbody>
	</table>
<p></p>
<h3>
	【输出格式】
</h3>
<p>
	<span style="color:#32656D;font-family:Tahoma;background-color:#FFFFFF;">　　每一个冗余依赖，以及其他依赖的一个序列以说明该依赖是冗余的，先是一个FD，然后是依赖函数号，接着是&#34;is redundant using FDs：”最后是说明的序列号。 </span><br/>
<span style="color:#32656D;font-family:Tahoma;background-color:#FFFFFF;">　　如果许多函数依赖的序列都能被用来说明一个依赖是冗余的，则输出其中最短的证明序列。如果这些函数依赖中不包含冗余依赖，则输出“No redundant FDs”信息。 </span> 
</p>
<h3>
	【样例输入】
</h3>
<pre>6 
P-&gt;RST 
VRT-&gt;SQP
PS-&gt;T
Q-&gt;TR
QS-&gt;P
SR-&gt;V
<div>
	
</div>
<span></span></pre>
<h3>
	【样例输出】
</h3>
<pre>FD 3 is redundant using FDs: 1
FD 5 is redundant using FDs: 4 6 2
<div>
	
</div>
</pre>
<h3>
	<br/>
</h3>
