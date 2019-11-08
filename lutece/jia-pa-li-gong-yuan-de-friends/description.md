
# Content

#### 我还有很多话想和她说，还有很多地方想和她去，把$Kaban$酱还给我！——$Sabaru$   

![](/source/lutece/jia-pa-li-gong-yuan-de-friends/img/bd68c1d204aaa2b37b9bb9cf3dc283ae.jpg)

薮猫酱为了从天蓝怪手里拯救小包，必须发现天蓝怪们的弱点所在。     
具体来说，$n$只天蓝怪组成了一个序列$A$，每一只有一个战斗力数值$A\_i$，    
之后会发生$m$个事件，事件共有两种类型，有可能是   
$1$、薮猫酱给你一个区间$[a,b]$，要你输出 $\max \{A_p+A_{p+1}+{\ldots}+A_q\}\ (a\leq p \leq q \leq b)$    
$2$、第$pos$只天蓝怪的战斗力变成了$X$

# Standard Input

第一行是两个整数$n$、$m$，    
第二行包含$n$个整数$A\_1,A\_2,{\ldots},A\_n$，    
接下来$m$行，每行三个整数，可能是    
$1\;a\;b$，代表薮猫酱的一次询问；    
$2\;pos\;X$，代表某只天蓝怪战斗力的变化。

# Standard Output

对于每次询问，单独输出一行，代表答案。

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
<tr><td>5 3
1 2 -3 4 5
1 2 3
2 2 -1
1 2 3</td><td>2
-1</td></tr></table>


# Constraints



# Note

$1{\leq}n{\leq}500000$，    
$1{\leq}m{\leq}100000$，    
$-1000{\leq}A\_i{\leq}1000$，    
$1{\leq}a{\leq}b{\leq}n$，    
$1{\leq}pos{\leq}n$，    
$-1000{\leq}X{\leq}1000$

# Source


