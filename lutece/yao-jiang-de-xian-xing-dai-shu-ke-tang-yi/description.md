
# Content

![o_千曜2.jpg](/source/lutece/yao-jiang-de-xian-xing-dai-shu-ke-tang-yi/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMTEvMjEvaWRKMzRyYXo3blhTQ1BrLmpwZw==.jpg)

千歌是浦之星女子学院高中二年级的学生，虽然她是广受欢迎的学园偶像，然而她的数学很差。   
这天，在线性代数课堂上，老师教给了她们如何求一个矩阵的**逆矩阵**，笨蛋千歌怎么也学不会。     
于是，她的青梅竹马，曜，决定在放学以后给她单独辅导。  
曜酱出了这样一道题目：给定一个n×n的矩阵，如果其可逆，求其逆矩阵；否则给出“NO”的答复。   
千歌当然不会啦，于是聪明的你能帮一下她吗？

# Standard Input

输入包含多组数据，以EOF结尾。    
对于每组数据，第一行是一个整数n，代表矩阵大小；   
接下来n行，每行n个浮点数，代表这个矩阵。

# Standard Output

对于每组数据，如果该矩阵可逆，接下来输出n行n列的矩阵，代表输入矩阵的逆矩阵（每个元素保留小数点后三位）。    
如果不可逆，输出“NO”（不含引号）。

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
<tr><td>2
0.0 1.0
1.0 2.0
3
0.0 2.0 -1.0
1.0 1.0 2.0
-1.0 -1.0 -1.0
3
0.0 2.0 -1.0
-1.0 -1.0 -1.0
-1.0 -1.0 -1.0</td><td>-2.000 1.000
1.000 0.000
-0.500 -1.500 -2.500
0.500 0.500 0.500
0.000 1.000 1.000
NO
</td></tr></table>


# Constraints



# Note

n<=100   
请不要输出-0.000这样的东西

# Source


