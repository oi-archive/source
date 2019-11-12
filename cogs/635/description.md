# 题目描述


<p>
	<strong>题目描述</strong>：<strong> </strong><br/>
大家对GIF这种图形格式一定不陌生，现在我们用字符串压缩来解释GIF压缩图形的基本原理。<br/>
GIF压缩的基础是一个数字编码与字符串映射关系的字典。字典只包含可能出现在待压缩字符串中的字符或子串的映射关系，且数字编码长度相同。例如，假如要压缩的字符串可能包含所有26个大写字母，那么字典可初始化为（A,00），（B,01），（C,02），…，（Z,25），注意数字编码长度都是2。假如我们只是想压缩DNA序列，那么字典可初始化为（A,0），（T,1），（G,2），（C,3）。<br/>
压缩算法如下：<br/>
1.在字典中查找字串未压缩部分最长的前缀，将这个前缀替换成字典对应的数字编码。<br/>
2.如果字串尚有未完成压缩的部分，则在字典中添加一个映射关系（s,n），s是上一步骤找到的前缀加紧接其后的字符，n是字典中尚未使用的最小的编码。<br/>
我们以压缩字符串ABABBAABB为例说明，由于字串只包含A和B，字典初始只有两项（A,0）和（B,1）。
</p>
<table border="1" cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td valign="top" width="142">
				<br/>
待压缩字串
			</td>
			<td valign="top" width="142">
				<p>
					最长前缀
				</p>
			</td>
			<td valign="top" width="142">
				<p>
					替换成编码
				</p>
			</td>
			<td valign="top" width="142">
				<p>
					新增字典条目
				</p>
			</td>
		</tr>
		<tr>
			<td valign="top" width="142">
				<p>
					ABABBAABB
				</p>
			</td>
			<td valign="top" width="142">
				<p>
					A
				</p>
			</td>
			<td valign="top" width="142">
				<p>
					0
				</p>
			</td>
			<td valign="top" width="142">
				<p>
					(AB,2)
				</p>
			</td>
		</tr>
		<tr>
			<td valign="top" width="142">
				<p>
					0BABBAABB
				</p>
			</td>
			<td valign="top" width="142">
				<p>
					B
				</p>
			</td>
			<td valign="top" width="142">
				<p>
					1
				</p>
			</td>
			<td valign="top" width="142">
				<p>
					(BA,3)
				</p>
			</td>
		</tr>
		<tr>
			<td valign="top" width="142">
				<p>
					01ABBAABB
				</p>
			</td>
			<td valign="top" width="142">
				<p>
					AB
				</p>
			</td>
			<td valign="top" width="142">
				<p>
					2
				</p>
			</td>
			<td valign="top" width="142">
				<p>
					(ABB,4)
				</p>
			</td>
		</tr>
		<tr>
			<td valign="top" width="142">
				<p>
					012BAABB
				</p>
			</td>
			<td valign="top" width="142">
				<p>
					BA
				</p>
			</td>
			<td valign="top" width="142">
				<p>
					3
				</p>
			</td>
			<td valign="top" width="142">
				<p>
					(BAA,5)
				</p>
			</td>
		</tr>
		<tr>
			<td valign="top" width="142">
				<p>
					0123ABB
				</p>
			</td>
			<td valign="top" width="142">
				<p>
					ABB
				</p>
			</td>
			<td valign="top" width="142">
				<p>
					4
				</p>
			</td>
			<td valign="top" width="142">
				<p>
					---
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	最终的压缩结果是01234。<br/>
还有一点要特别注意，当字典中不断添加新的映射关系，数字编码长度在某个步骤将突破初始化时的长度。由于字典所有数字编码长度要保持一致，这时要将字典中原有的数字编码前补0，之后的压缩按新的数字编码进行替换，而原有已替换的数字编码则不受影响。例如，ABABBAABBAABAABAB将压缩成01234027301，而不是0123402731。<br/>
请对输入的初始字典和压缩后的编码进行解压。<br/>
<strong>输入格式</strong>（GIF.in）：<br/>
第一行的字符串是压缩后的数字编码。第二行是初始的字典，由一个正整数n开始，n(1&lt;=n&lt;=100)是字典初始的条目数，后面接着n个字符串，字典中的第一个字符串编码为0（如n&gt;10则是00），第二个字符串编码为1，以此类推。<br/>
<strong>输出格式</strong>（GIF.out）：<br/>
输出只有一行，是解压后的字符串。我们保证所有输入都是可以解压的。<br/>
<strong>样例 </strong>
</p>
<table border="1" cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td valign="top" width="284">
				<br/>
GIF.in
			</td>
			<td valign="top" width="284">
				<p>
					GIF.out
				</p>
			</td>
		</tr>
		<tr>
			<td valign="top" width="284">
				<p>
					01234<br/>
2 A B
				</p>
			</td>
			<td valign="top" width="284">
				<p>
					ABABBAABB
				</p>
			</td>
		</tr>
		<tr>
			<td valign="top" width="284">
				<p>
					01234027301<br/>
2 A B
				</p>
			</td>
			<td valign="top" width="284">
				<p>
					ABABBAABBAABAABAB
				</p>
			</td>
		</tr>
		<tr>
			<td valign="top" width="284">
				<p>
					21104<br/>
3 BA A C
				</p>
			</td>
			<td valign="top" width="284">
				<p>
					CAABAAA
				</p>
			</td>
		</tr>
		<tr>
			<td valign="top" width="284">
				<p>
					01<br/>
2 JA VA
				</p>
			</td>
			<td valign="top" width="284">
				<p>
					JAVA
				</p>
			</td>
		</tr>
	</tbody>
</table>
