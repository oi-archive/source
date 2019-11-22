
# Content

#### 你这快乐的王子，我难道不可以做你的小燕子吗？——$Hishikawa\,Rikka$    

![](/source/lutece/rikkade-fan-nao/img/aHR0cDovL2kyNDkucGhvdG9idWNrZXQuY29tL2FsYnVtcy9nZzIyNC9ha2k5NjExMDMvUHJlY3VyZS9MZW9wYXJkLVJhd3NEb2tpZG9raVByZWN1cmUtMDFSQVdFWDEyODB4NzIweDI2NEFBQzE4LTQ3LTQ4X3pwczE4ZTlhZjIwLmpwZw==.jpg)

$Rikka$想要和$Mana$在一起，然而$Mana$依然到处收着她的后宫。即使$Rikka$是$Cure\,Diamond$，钻石之心也是会受伤的！$Rikka$只得玩卡片游戏暂时缓解心中的烦恼。     
然而今天$Rikka$在玩卡片游戏时遇到了麻烦，需要你的帮助。    
所有卡片构成了一个序列，每张卡片上最开始有一个整数。    
$Rikka$有时候会修改某张卡片上的数字。    
还会询问某一段**下标是等差数列**的子序列的最大值。

# Standard Input

第一行是一个整数$n$，    
第二行是一个长度为$n$的整数序列$a$，第$i$个数代表第$i$张卡片上初始的数字，    
第三行是一个整数$m$，    
接下来$m$行，每行首先有一个整数$op$，    
然后，若$op=0$，则之后有两个整数$p$，$v$，代表将$a_p$的值加上$v$，    
若$op=1$，则之后有两个整数$x_0$，$d$，代表询问$\max \{a_{x_0},a_{x_0+d},a_{x_0+2d},{\ldots},a_{x_0+kd}\}(x_0+(k+1)d>n)$。

# Standard Output

对每个$op=1$，单独输出一行，代表该**下标是等差数列**的子序列的最大值。

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
<tr><td>10
1 6 1 4 9 4 8 2 8 5
10
1 3 3
0 5 4
0 3 8
1 2 5
1 4 8
1 7 5
1 3 6
0 1 2
1 5 3
1 4 9</td><td>8
8
4
8
9
13
4</td></tr><tr><td>10
-9 -6 2 -10 -2 -6 10 6 -4 -2
10
1 2 3
1 6 3
0 7 8
0 4 -6
0 10 -5
1 10 4
0 3 -8
1 2 4
0 10 -5
1 1 2</td><td>6
-4
-7
-6
18</td></tr></table>


# Constraints



# Note

$1{\leq}n{\leq}70000$，    
$1{\leq}m{\leq}70000$，    
保证任何时刻$abs(a_i){\leq}2147483647(1{\leq}i{\leq}n)$，    
$0{\leq}op{\leq}1$，    
$1{\leq}p{\leq}n$，    
$abs(v){\leq}2147483647$，    
$1{\leq}x_0{\leq}n$，    
$1{\leq}d{\leq}n$，    
保证涉及的所有数在$C++$的$int$内。

# Source


