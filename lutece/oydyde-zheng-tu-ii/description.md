
# Content

尊贵的`oydy`想要踏遍这片土地上的所有道路!于是就开始了他的征途。  
这片土地上有$n$个城市和$m$条路,每条路**单向**连接城市$u$和城市$v$($u$和$v$可能是相同的),在`oydy`征途中,并且每当他到达一个城市,他的小弟`FoolishMe`就会帮他把这个城市的编号记录下来(即按顺序记录了整个征途经过的城市,包括起点),好在`oydy`完成征途时将他的伟大征程写入史记。    
由于`oydy`是尊贵的,他可以选择任意一个城市作为自己征途的起点。他希望在史记中自己的征程是完美的,也就是经过每条道路**恰好一次**,并且这段征程在所有可能的征程中拥有**最小的字典序**。如果无法满足以上条件,在这片土地上的这段征程将不会被写入史记。  
由于`FoolishMe`想偷懒,于是他想让聪明的你帮他预估一下`oydy`的征程是否会被写入史记,如果会的话这段完美征程是什么样的,这样一来`FoolishMe`就可以预先写好然后在路上摸鱼了。

# Standard Input

第一行两个数字$n$和$m$表示这片土地上有n个点和m条路 $(1\leq n \leq 10^6, 1 \leq m \leq 2 \times 10^6)$    
接下来$m$行,每行两个数字$u,v$,表示有一条道路连接了城市$u$和城市$v$ $(1 \leq u, v \leq n, u和v可能相同)$

# Standard Output

输出一行,如果`oydy`的征程会被写入史记,那么输出这段完美征程,相邻的城市编号用空格隔开。如果征程不会被写入史记,则输出"What a shame!"(不带引号)。

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
<tr><td>5 7
5 1
1 1
1 2
2 3
3 1
1 1
1 5</td><td>1 1 1 2 3 1 5 1</td></tr><tr><td>3 4
1 1
1 2
1 3
2 3</td><td>What a shame!</td></tr></table>


# Constraints



# Note

注意有重边和自环哦  
单向连接$u$和$v$指的是从$u$指向$v$  
经过每条边恰好一次,但是可以经过一个点若干次  
不一定每个城市都能到达  
数据量较大建议用scanf读入  
  
序列A的字典序比序列B的小当且仅当A是B的一个前缀或者存在i <= n使得A[j] == B[j] (j < i) 且 A[i] < B[i]

# Source


