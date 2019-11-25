
# Content

在京州电子科技大学，AMC集训队开始招新了。听完老师的数据结构授课，秦二茼想出了一道题，他希望实现一个队列，这个队列可以实现三种操作：首元素出队、新元素入队、询问整个队列内所有的元素的乘积mod  P的结果。秦二茼拿这道题问老师，老师一下就做出来了，现在秦二茼准备问问你，看看你会不会做。

# Standard Input

第一行两个数$n,P(1 \le n,P \le 10^6)$表示操作次数和$P$  
接下来$n$行，每行一个操作符  
若操作符为+后面的还有一个数字$x(0 \le x < P)$表示加数字x加入队列  
若操作符为- 表示队首元素出队  
若操作符为? 表示询问整个队列内所有元素的乘积mod P的结果

# Standard Output

对于每个?对应一行输出表示:整个队列内所有元素的乘积mod P的结果**(若队内无元素则答案为0)**

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>4 10
+ 2
?
-
?</td><td>2
0</td></tr></table>


# Constraints



# Note

数据在windows下生成，可能混合有\r，注意读入处理

# Source


