# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;动物王国中有三类动物&nbsp;A,B,C，这三类动物的食物链构成了有趣的环形。A吃B，B吃C，C吃A。<BR>&nbsp;&nbsp;&nbsp;&nbsp;现有N个动物，以1－N编号。每个动物都是A,B,C中的一种，但是我们并不知道它到底是哪一种。<BR>&nbsp;&nbsp;&nbsp;&nbsp;有人用两种说法对这N个动物所构成的食物链关系进行描述：<BR>&nbsp;&nbsp;&nbsp;&nbsp;第一种说法是“1&nbsp;X&nbsp;Y”，表示X和Y是同类。<BR>&nbsp;&nbsp;&nbsp;&nbsp;第二种说法是“2&nbsp;X&nbsp;Y”，表示X吃Y。<BR>&nbsp;&nbsp;&nbsp;&nbsp;此人对N个动物，用上述两种说法，一句接一句地说出K句话，这K句话有的是真的，有的是假的。当一句话满足下列三条之一时，这句话就是假话，否则就是真话。<BR>&nbsp;&nbsp;&nbsp;&nbsp;1）&nbsp;当前的话与前面的某些真的话冲突，就是假话；<BR>&nbsp;&nbsp;&nbsp;&nbsp;2）&nbsp;当前的话中X或Y比N大，就是假话；<BR>&nbsp;&nbsp;&nbsp;&nbsp;3）&nbsp;当前的话表示X吃X，就是假话。<BR>&nbsp;&nbsp;&nbsp;&nbsp;你的任务是根据给定的N（1&lt;=N&lt;=50,000）和K句话（0&lt;=K&lt;=100,000），输出假话的总数。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行是两个整数N和K，以一个空格分隔。<BR>&nbsp;&nbsp;&nbsp;&nbsp;以下K行每行是三个正整数D，X，Y，两数之间用一个空格隔开，其中&nbsp;D&nbsp;表示说法的种类。<BR>&nbsp;&nbsp;&nbsp;&nbsp;若D=1，则表示X和Y是同类。<BR>&nbsp;&nbsp;&nbsp;&nbsp;若D=2，则表示X吃Y。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;只有一个整数，表示假话的数目。 

 
 # 提示 
输入文件&nbsp;&nbsp;&nbsp;对7句话的分析&nbsp;<BR>100&nbsp;7<BR>1&nbsp;101&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;假话&nbsp;<BR>2&nbsp;1&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;真话&nbsp;<BR>2&nbsp;2&nbsp;3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;真话&nbsp;<BR>2&nbsp;3&nbsp;3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;假话&nbsp;<BR>1&nbsp;1&nbsp;3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;假话&nbsp;<BR>2&nbsp;3&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;真话&nbsp;<BR>1&nbsp;5&nbsp;5&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;真话&nbsp;NOI&nbsp;2001&nbsp;食物链(eat) 
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
<tr><td>100 7
1 101 1 
2 1 2 
2 2 3 
2 3 3 
1 1 3 
2 3 1 
1 5 5</td><td>3</td></tr></table>
