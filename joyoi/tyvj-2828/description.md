# 

 
 # 题目描述 
<p>
Larkin 收到了来自Stone 的信息。作为一个世界一流的密码学家，Stone 喜欢加密他给Larkin 的信息。这一次，他决定使用OTP(One Time Pad) 加密法。OTP 加密法在运用得当的情况下是不能被破解的，而Stone 深知这一点。但是，他不想让Larkin 在一个不可能完<br>成的任务面前绞尽脑汁，所以他附带给了Larkin 一些暗示。<br>Larkin 知道Stone 给的信息的原始文本只包含小写的英文字母(‘a’ - ‘z’)、句点‘.’ 和空格‘ ’(ASCII 码为32)。而且，他知道Stone 只会用数字‘0’ 到‘9’ 作为密钥。在深思熟虑之后，他意识到他可以确定所有的空格和句点的位置。他现在请求你写一个程序完成这个工作。<br>通过以往与Stone 的接触，Larkin 知道OTP 加密法是如何工作的。让我们来看一个简单的例子。假设你想要用密钥“0120123” 加密字符串“abc efg”。<br><br><center><img src="/source/joyoi/tyvj-2828/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjgyOC9wcm9ibGVtc19pbWFnZXMvMzM2Mi9wZy5qcGc=.jpg"></img></center><br>首先，你先将密钥和文本转换成十六进制的ASCII 码形式。接下来对上下两行相对应的数进行异或操作。这样得到的序列就是加密后的信息。</p> 

 
 # 输入格式 
<p>
输入文件decrypt.in 第一行包含一个数N，表示加密后的信息中的字符的个数。<br>接下来一行包含N 个整数，使用十六进制的形式，范围为010 到12710，表示加密后的信息。</p> 

 
 # 输出格式 
<p>
<br>img src="problems_images/3362/pg2.jpg"></img></p> 

 
 # 提示 
<p>
<br><img src="/source/joyoi/tyvj-2828/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjgyOC9wcm9ibGVtc19pbWFnZXMvMzM2Mi9wZzQuanBn.jpg"></img></p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>7
51 53 51 10 54 54 54</td><td><br><img src="/source/joyoi/tyvj-2828/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjgyOC9wcm9ibGVtc19pbWFnZXMvMzM2Mi9wZzMuanBn.jpg"></img></td></tr></table>
