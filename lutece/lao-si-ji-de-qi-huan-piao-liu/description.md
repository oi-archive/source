
# Content

老司机在救出了女票之后，就和她在全世界旅游，有一天，他们来到了一个神奇的小岛上。       
这个小岛上有三种动物，他们互相克制，就像~~虚空追猎凤凰~~石头剪刀布一样，他们形成了一个食物环。  
热爱小动物的老司机女票已经对这个岛上的N只动物进行了细致的研究，对他们所属的族群也了如指掌，并对他们的行为做了记录。     
第一种记录方式是`1 X Y`，表示X和Y关系密切（是同类）。   
第二种记录方式是`2 X Y`，表示X对Y有攻击性行为（X克制Y）。   
不过很不凑巧，这些记录被毛手毛脚的JJ给打乱了，使得其中一些记录出现了错误。   
为了安慰着急的女票，老司机急忙来帮忙查看是哪些记录出现了错误，当一条记录满足以下三种可能***之一***时，这就是一条错误的记录。     
1）这条记录中的X或者Y比N大     
2）攻击性记录中的X攻击了X     
3）这条记录与前面的记录相悖    
老司机说是来帮忙，但是还要忙着跑去和wyy踢fifa，所以就让你来完成这个任务，找出这些记录中哪些错了。

# Standard Input

第一行两个整数N和M，为记录的动物数量和记录条数
接下来M行，每行代表一条记录。

# Standard Output

一行n个数字，表示哪几条记录有误，用空格隔开      
按编号升序输出

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
<tr><td>100 7
1 101 1 
2 1 2
2 2 3 
2 3 3 
1 1 3 
2 3 1 
1 5 5</td><td>1 4 5
</td></tr></table>


# Constraints



# Note

数据范围：     
1<= N <= 50,000      
1<= M <=100,000

# Source


