
# Content

伊卡洛斯很爱吃西瓜。一次，他来到一个西瓜摊旁，发现水果摊有N个西瓜，但只有红色和黄色两种颜色。

伊卡洛斯很想知道知道一些信息，便于老板交谈了起来。

当老板的话的第一个字符为”A”时，老板会告诉伊卡洛斯一些信息，格式如下：

$A\ x\ y\ 1$ 这句话表示第$x$个西瓜和第$y$个西瓜是同一种颜色的。

$A\ x\ y\ 2$ 这句话表示第$x$个西瓜和第$y$个西瓜是不同种颜色的。

当然，为了考验伊卡洛斯有没有认真听， 老板也会时不时问伊卡洛斯一些问题，格式如下：

$Q\ x\ y$ 这句话表示询问第$x$个西瓜和第$y$个西瓜是不是同一种颜色，如果确定为同一种颜色，伊卡洛斯需要回答`1`；确定为不同种颜色，伊卡洛斯需要回答`2`；无法确定时伊卡洛斯回答`3`。

注意，伊卡洛斯是根据已获得的信息来回答的。也就是只有这个问题之前的信息才为已知信息。

老板说，只有回答对他全部的问题，伊卡洛斯才能吃到瓜，他聪明的想到了让你来帮助他。

# Standard Input

第一行包含两个整数$N$和$M$，$N$是西瓜总数，$M$是以$A$或$Q$开头的老板的话总和。  
以下$M$行，每行包含一条老板的话。形式有$A\ x\ y\ 1$或$A\ x\ y\ 2$或$Q\ x\ y$。
$1 \le N \le 100000\ 1 \le M \le 200000\ 1 \le X, Y \le N$
数据保证没有矛盾

# Standard Output

对于每一条$Q$指令，输出`1`/`2`/`3`代表两个西瓜颜色的关系。

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
<tr><td>6 9  
A 1 2 1  
A 1 3 1  
A 1 4 2  
Q 2 4  
Q 1 6  
A 3 6 1  
A 4 5 2  
Q 1 5  
Q 1 6</td><td>2
3
1 
1</td></tr></table>


# Constraints



# Note

西瓜的颜色有且仅有两种！

# Source


