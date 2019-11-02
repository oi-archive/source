# 

 
 # 题目背景 
Stone为了保证自己PC数据的安全，设置了一个密码，因为依赖于抑或运算，所以他把这个密码叫做抑或密码。 

 
 # 题目描述 
Stone的密码是这样的：密码有一组原码，每个密码对应着两个数，而密码的值就是这两个数所围起来对应原码的闭区间的抑或和。具体来说，假如说原码组是{1&nbsp;2&nbsp;3&nbsp;4&nbsp;5}，而一个密码的对应数是2和4，那么这个密码的值就是2&nbsp;xor&nbsp;3&nbsp;xor&nbsp;4&nbsp;=&nbsp;5。防止歧义，这里声明一下，两个对应数指的是原码组的位置，而不是原码组里的数。再举一个例子，如果原码组是{123&nbsp;423&nbsp;45&nbsp;23&nbsp;654&nbsp;1333&nbsp;234}，对应数是2和5，那么密码的值就是&nbsp;423&nbsp;xor&nbsp;45&nbsp;xor&nbsp;23&nbsp;xor&nbsp;654。<BR>比较有用的是，Stone采用了类似一次一密的方法，每次会随机出两个对应数，也就是说，每一次查询的时候，密码都会变，甚至有时候会修改原码组，好在，Stone比较沙茶，他做的密码系统每次修改原码组只会修改一个值。但是他的PC经常会需要输入密码，如果我说，他随便打开一个文件夹都需要输入一次密码，是不是很纠结。<BR>你的任务就是，我们给出原码组，以及每次查询的对应数和修改情况，希望你可以给出每次密码的值。<BR> 

 
 # 输入格式 
第一行两个整数n，m。分别表示原码组的大小，和查询或修改次数。<BR>以下m行，每行三个整数，p，x，y。<BR>如果p=1，那么表示修改原码组x修改成y。<BR>如果p=0，那么表示请输出对应数是x，y的时候，密码的值。<BR> 

 
 # 输出格式 
对每个p=0的情况输出一行，即密码的值。 

 
 # 提示 
题目数据范围：<BR>对于50%的数据，n,m&lt;=500<BR>对于100%的数据，n&lt;=50000&nbsp;&nbsp;&nbsp;m&lt;=100000<BR>对于100%的数据，0&lt;=a[i]&lt;=maxlongint<BR>且所有输入均合法 
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
<tr><td>5 3
3 9 6 0 3
0 2 2
1 1 2
0 2 4
</td><td>9
15
</td></tr></table>
