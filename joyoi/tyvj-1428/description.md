# 

 
 # 题目背景 
经典题目 

 
 # 题目描述 
起初一串大写字母A~Z按顺序排列，有一串由互不相同的26个大写字母组成的密码，分别对应A~Z的加密方法。现在已知一串由互不相同的26个大写字母组成的密文，问它能否通过某种密码将原串加密两次后形成，若能，输出Yes并打印出字典序最小的密码，否则输出No。<BR><BR>比如：<BR>原串：ABCDEFGHIJKLMNOPQRSTUVWXYZ（所有数据原串都是这样的）<BR>密码：CDBAEFGHIJKLMNOPQRSTUVWXYZ（待求，这是输出数据）<BR>密文：BADCEFGHIJKLMNOPQRSTUVWXYZ（加密两次后的密文，这是输入数据）<BR>这里边A第一次被换成了C，第二次又换成了C的密码B。对于每个字母都是这样的加密方法。<BR><BR> 

 
 # 输入格式 
一串由互不相同的26个大写字母组成的密文 

 
 # 输出格式 
问输入的密文能否通过某种密码将原串A~Z加密两次后形成，若能，第一行输出Yes，第二行打印出字典序最小的密码，否则输出No。 
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
<tr><td>BADCEFGHIJKLMNOPQRSTUVWXYZ</td><td>Yes
CDBAEFGHIJKLMNOPQRSTUVWXYZ</td></tr></table>
