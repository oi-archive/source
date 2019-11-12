# 题目描述


<p>
	内存是计算机重要的资源之一，程序运行的过程中必须对内存进行分配。
</p>
<p>
	经典的内存分配过程是这样进行的：
</p>
<ol>
	<li>
		内存以内存单元为基本单位，每个内存单元用一个固定的整数作为标识，称为地址。地址从0开始连续排列，地址相邻的内存单元被认为是逻辑上连续的。我们把从地址i开始的s个连续的内存单元称为首地址为i长度为s的地址片。
	</li>
	<li>
		运行过程中有若干进程需要占用内存，对于每个进程有一个申请时刻T，需要内存单元数M及运行时间P。在运行时间P内（即T时刻开始，T+P时刻结束），这M个被占用的内存单元不能再被其他进程使用。
	</li>
	<li>
		假设在T时刻有一个进程申请M个单元，且运行时间为P，则：
		<ol>
			<li>
				若T时刻内存中存在长度为M的空闲地址片，则系统将这M个空闲单元分配给该进程。若存在多个长度为M个空闲地址片，则系统将首地址最小的那个空闲地址片分配给该进程。
			</li>
			<li>
				如果T时刻不存在长度为M的空闲地址片，则该进程被放入一个等待队列。对于处于等待队列队头的进程，只要在任一时刻，存在长度为M的空 闲地址片，系统马上将该进程取出队列，并为它分配内存单元。注意，在进行内存分配处理过程中，处于等待队列队头的进程的处理优先级最高，队列中的其它进程 不能先于队头进程被处理。
			</li>
		</ol>
	</li>
</ol>
<p>
	现在给出一系列描述进程的数据，请编写一程序模拟系统分配内存的过程。
</p>
<p>
	输入
</p>
<ul>
	<li>
		第一行是一个数N，表示总内存单元数（即地址范围从0到N-1）
	</li>
	<li>
		从第二行开始每行描述一个进程的三个整数T、M、P（M&lt;=N）。
	</li>
	<li>
		数据已按T从小到大排序。
	</li>
	<li>
		最后一行用三个0表示结束。
	</li>
	<li>
		输入文件最多10000行，且所有数据都小于10^9。
	</li>
	<li>
		输入文件中同一行相邻两项之间用一个或多个空格隔开。
	</li>
</ul>
<p>
	输出
</p>
<ul>
	<li>
		包括2行。
	</li>
	<li>
		第一行是全部进程都运行完毕的时刻。
	</li>
	<li>
		第二行是被放入过等待队列的进程总数。
	</li>
</ul>
<p>
	样例输入
</p>
<pre>10
1 3 10
2 4 3
3 4 4
4 1 4
5 3 4
0 0 0
</pre>
<p>
	样例输出
</p>
<pre>12
2
</pre>
<p>
	样例示例
</p>
<table width="669" cellspacing="1" cellpadding="0" border="1" style="background:white none repeat scroll 0% 0%;width:501.7pt;">
	<tbody>
		<tr>
			<td width="4%" rowspan="2">
				<p align="center" style="text-align:center;">
					时
				</p>
				<p align="center" style="text-align:center;">
					刻
				</p>
				<p align="center" style="text-align:center;">
					<span style="font-family:System;">T</span>
				</p>
			</td>
			<td width="41%" colspan="12">
				<p align="center" style="text-align:center;">
					内存占用情况
				</p>
			</td>
			<td width="53%">
				<p align="center" style="text-align:center;">
					进程事件
				</p>
			</td>
		</tr>
		<tr>
			<td width="3%">
				<p align="center" style="text-align:center;">
					<span style="font-family:System;">0</span>
				</p>
			</td>
			<td width="3%" colspan="2">
				<p align="center" style="text-align:center;">
					<span style="font-family:System;">1</span>
				</p>
			</td>
			<td width="4%" colspan="2">
				<p align="center" style="text-align:center;">
					<span style="font-family:System;">2</span>
				</p>
			</td>
			<td width="3%">
				<p align="center" style="text-align:center;">
					<span style="font-family:System;">3</span>
				</p>
			</td>
			<td width="3%">
				<p align="center" style="text-align:center;">
					<span style="font-family:System;">4</span>
				</p>
			</td>
			<td width="3%">
				<p align="center" style="text-align:center;">
					<span style="font-family:System;">5</span>
				</p>
			</td>
			<td width="4%">
				<p align="center" style="text-align:center;">
					<span style="font-family:System;">6</span>
				</p>
			</td>
			<td width="3%">
				<p align="center" style="text-align:center;">
					<span style="font-family:System;">7</span>
				</p>
			</td>
			<td width="3%">
				<p align="center" style="text-align:center;">
					<span style="font-family:System;">8</span>
				</p>
			</td>
			<td width="5%">
				<p align="center" style="text-align:center;">
					<span style="font-family:System;">9</span>
				</p>
			</td>
			<td width="53%" rowspan="2">
				<p align="center" style="text-align:center;">
					进程<span style="font-family:System;">A</span>申请空间（<span style="font-family:System;">M=3,P=10</span>）<span>&lt;</span>成功<span>&gt;</span>
				</p>
			</td>
		</tr>
		<tr>
			<td width="4%">
				<p>
					<b><span>1</span></b>
				</p>
			</td>
			<td width="12%" style="background:#F3F3F3 none repeat scroll 0% 0%;" colspan="5">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;">A</span></b>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="4%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="5%">
				<p>
					<span> </span>
				</p>
			</td>
		</tr>
		<tr>
			<td width="4%">
				<p>
					<b><span>2</span></b>
				</p>
			</td>
			<td width="12%" style="background:#F3F3F3 none repeat scroll 0% 0%;" colspan="5">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;">A</span></b>
				</p>
			</td>
			<td width="15%" style="background:black none repeat scroll 0% 0%;" colspan="4">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;color:white;">B</span></b>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="5%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="53%">
				<p align="center" style="text-align:center;">
					进程<span style="font-family:System;">B</span>申请空间（<span style="font-family:System;">M=4,P=3</span>）<span>&lt;</span>成功<span>&gt;</span>
				</p>
			</td>
		</tr>
		<tr>
			<td width="4%">
				<p>
					<b><span>3</span></b>
				</p>
			</td>
			<td width="12%" style="background:#F3F3F3 none repeat scroll 0% 0%;" colspan="5">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;">A</span></b>
				</p>
			</td>
			<td width="15%" style="background:black none repeat scroll 0% 0%;" colspan="4">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;color:white;">B</span></b>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="5%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="53%">
				<p align="center" style="text-align:center;">
					进程<span style="font-family:System;">C</span>申请空间（<span style="font-family:System;">M=4,P=4</span>）<span>&lt;</span>失败进入等待队列<span>&gt;</span>
				</p>
			</td>
		</tr>
		<tr>
			<td width="4%">
				<p>
					<b><span>4</span></b>
				</p>
			</td>
			<td width="12%" style="background:#F3F3F3 none repeat scroll 0% 0%;" colspan="5">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;">A</span></b>
				</p>
			</td>
			<td width="15%" style="background:black none repeat scroll 0% 0%;" colspan="4">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;color:white;">B</span></b>
				</p>
			</td>
			<td width="3%" style="background:#CCCCCC none repeat scroll 0% 0%;">
				<p align="center" style="text-align:center;">
					<span style="font-family:System;">D</span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="5%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="53%">
				<p align="center" style="text-align:center;">
					进程<span style="font-family:System;">D</span>申请空间（<span style="font-family:System;">M=1,P=4</span>）<span>&lt;</span>成功<span>&gt;</span>
				</p>
			</td>
		</tr>
		<tr>
			<td width="4%">
				<p>
					<b><span>5</span></b>
				</p>
			</td>
			<td width="12%" style="background:#F3F3F3 none repeat scroll 0% 0%;" colspan="5">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;">A</span></b>
				</p>
			</td>
			<td width="15%" style="background:#E0E0E0 none repeat scroll 0% 0%;" colspan="4">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;">C</span></b>
				</p>
			</td>
			<td width="3%" style="background:#CCCCCC none repeat scroll 0% 0%;">
				<p align="center" style="text-align:center;">
					<span style="font-family:System;">D</span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="5%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="53%">
				<p align="center" style="text-align:center;">
					进程<span style="font-family:System;">B</span>结束，释放空间
				</p>
				<p align="center" style="text-align:center;">
					进程<span style="font-family:System;">C</span>从等待队列取出，分配空间
				</p>
				<p align="center" style="text-align:center;">
					进程<span style="font-family:System;">E</span>申请空间（<span style="font-family:System;">M=3,P=4</span>）<span>&lt;</span>失败进入等待队列<span>&gt;</span>
				</p>
			</td>
		</tr>
		<tr>
			<td width="4%">
				<p>
					<b><span>6</span></b>
				</p>
			</td>
			<td width="12%" style="background:#F3F3F3 none repeat scroll 0% 0%;" colspan="5">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;">A</span></b>
				</p>
			</td>
			<td width="15%" style="background:#E0E0E0 none repeat scroll 0% 0%;" colspan="4">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;">C</span></b>
				</p>
			</td>
			<td width="3%" style="background:#CCCCCC none repeat scroll 0% 0%;">
				<p align="center" style="text-align:center;">
					<span style="font-family:System;">D</span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="5%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="53%">
				<p>
					<span> </span>
				</p>
			</td>
		</tr>
		<tr>
			<td width="4%">
				<p>
					<b><span>7</span></b>
				</p>
			</td>
			<td width="12%" style="background:#F3F3F3 none repeat scroll 0% 0%;" colspan="5">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;">A</span></b>
				</p>
			</td>
			<td width="15%" style="background:#E0E0E0 none repeat scroll 0% 0%;" colspan="4">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;">C</span></b>
				</p>
			</td>
			<td width="3%" style="background:#CCCCCC none repeat scroll 0% 0%;">
				<p align="center" style="text-align:center;">
					<span style="font-family:System;">D</span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="5%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="53%">
				<p>
					<span> </span>
				</p>
			</td>
		</tr>
		<tr>
			<td width="4%">
				<p>
					<b><span>8</span></b>
				</p>
			</td>
			<td width="12%" style="background:#F3F3F3 none repeat scroll 0% 0%;" colspan="5">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;">A</span></b>
				</p>
			</td>
			<td width="15%" style="background:#E0E0E0 none repeat scroll 0% 0%;" colspan="4">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;">C</span></b>
				</p>
			</td>
			<td width="12%" style="background:#A6A6A6 none repeat scroll 0% 0%;" colspan="3">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;">E</span></b>
				</p>
			</td>
			<td width="53%">
				<p align="center" style="text-align:center;">
					进程<span style="font-family:System;">D</span>结束，释放空间
				</p>
				<p align="center" style="text-align:center;">
					进程<span style="font-family:System;">E</span>从等待队列取出，分配空间
				</p>
			</td>
		</tr>
		<tr>
			<td width="4%">
				<p>
					<b><span>9</span></b>
				</p>
			</td>
			<td width="12%" style="background:#F3F3F3 none repeat scroll 0% 0%;" colspan="5">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;">A</span></b>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="4%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="12%" style="background:#A6A6A6 none repeat scroll 0% 0%;" colspan="3">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;">E</span></b>
				</p>
			</td>
			<td width="53%">
				<p align="center" style="text-align:center;">
					进程<span style="font-family:System;">C</span>结束，释放空间
				</p>
			</td>
		</tr>
		<tr>
			<td width="4%">
				<p>
					<b><span>10</span></b>
				</p>
			</td>
			<td width="12%" style="background:#F3F3F3 none repeat scroll 0% 0%;" colspan="5">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;">A</span></b>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="4%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="12%" style="background:#A6A6A6 none repeat scroll 0% 0%;" colspan="3">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;">E</span></b>
				</p>
			</td>
			<td width="53%">
				<p>
					<span> </span>
				</p>
			</td>
		</tr>
		<tr>
			<td width="4%">
				<p>
					<b><span>11</span></b>
				</p>
			</td>
			<td width="5%" colspan="2">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%" colspan="2">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="4%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="12%" style="background:#A6A6A6 none repeat scroll 0% 0%;" colspan="3">
				<p align="center" style="text-align:center;">
					<b><span style="font-family:System;">E</span></b>
				</p>
			</td>
			<td width="53%">
				<p align="center" style="text-align:center;">
					进程<span style="font-family:System;">A</span>结束，释放空间
				</p>
			</td>
		</tr>
		<tr>
			<td width="4%">
				<p>
					<b><span>12</span></b>
				</p>
			</td>
			<td width="5%" colspan="2">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%" colspan="2">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="4%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="3%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="5%">
				<p>
					<span> </span>
				</p>
			</td>
			<td width="53%">
				<p align="center" style="text-align:center;">
					进程<span style="font-family:System;">E</span>结束，释放空间
				</p>
			</td>
		</tr>
	</tbody>
</table>
