
# Content

潘爷精通火柴人的构造，他认为一个完整的火柴人必须是下面这个样子的  
![1](/source/lutece/zhe-ye-shi-yi-dao-bao-li-ti/img/aHR0cHM6Ly9oZS1zMy5zMy5hbWF6b25hd3MuY29tL21lZGlhL3VwbG9hZHMvY2E2NjI5Yy5wbmc=.png)    
潘爷曾经遇到过一棵树，这棵树有$n$个点，标号分别为$1,2,3,\dots n$，但是现在潘爷记不得树的样子了，只知道每个点的度数  
潘爷还知道这棵树上有很多很多的火柴人图形……但是由于记不得树的样子了，所以他想知道火柴人的期望个数是多少……  
潘爷把这个问题交给了你……请你求出这棵树上的火柴人图形的个数的期望值

# Standard Input

第一行有一个数$n$,表示树的大小$(n \leq 1e5)$  
第二行有$n$个数,第$i$个数表示第$i$个点的度数   
保证至少存在一棵树满足这些度数

# Standard Output

输出一个数,火柴人图形个数的期望值……请输出$\%1e9+7$后的结果

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
<tr><td>9
4 3 3 1 1 1 1 1 1</td><td>428571433</td></tr></table>


# Constraints



# Note

![2](/source/lutece/zhe-ye-shi-yi-dao-bao-li-ti/img/aHR0cHM6Ly9oZS1zMy5zMy5hbWF6b25hd3MuY29tL21lZGlhL3VwbG9hZHMvMWNiYzViZi5wbmc=.png)    
有$90$棵树满足这种样子，这种树上有$2$个火柴人图形     
![3](/source/lutece/zhe-ye-shi-yi-dao-bao-li-ti/img/aHR0cHM6Ly9oZS1zMy5zMy5hbWF6b25hd3MuY29tL21lZGlhL3VwbG9hZHMvNTY0YTE5MS5wbmc=.png)     
有$60$棵树满足这种样子，这种树上有$1$个火柴人图形    
![4](/source/lutece/zhe-ye-shi-yi-dao-bao-li-ti/img/aHR0cHM6Ly9oZS1zMy5zMy5hbWF6b25hd3MuY29tL21lZGlhL3VwbG9hZHMvNmU0ZGY0Yy5wbmc=.png)    
有$60$棵树满足这种样子，这种树上有$1$个火柴人图形     
所以期望值为$\frac{10}{7}$，在模$1e9+7$意义下为$428571433$

# Source


