
# Content

红人无数的红帽侠决定金盆洗手啦！  
由于红帽侠后继无人，按照祖祖辈辈的祖训，红帽侠要把位置传给这个王国里红帽最少的那个人。  
但是，红帽侠曾记得那个被红的晚上，而那个人，还在王国里潇潇洒洒。  
“当然是选择 不 原谅他啊！”  
于是红帽侠搬出了祖辈流传的神器：红帽自动机——对着一个人喊一声，“你将加冕为王”，除了他以外的所有人，都被戴上一顶红帽。  
红帽侠决定金盆洗手前，再干一票！  
不为别的，就为了让当初曾经红了他的人成为这个王国内唯一的红帽最多的人！  
“屏幕前的你，如果不想被我戴上红帽的话，就帮我算算，我最少需要喊多少次吧。这条咸鱼还没熟，我要再烤烤。”  
![title](/source/lutece/hong-mao-zi-dong-ji/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTgwMy8yMDE3MTEyNDE1MTkzNjIyNTE3LmdpZg==.gif)

# Standard Input

第一行两个整数$n,x(2\leq n\leq 100000 ,1\leq x\leq n)$，表示这个王国有$n$个人，红帽侠希望第$x$个人红帽最多。  
第二行包括$n$个整数，用空格隔开，第$i$个整数$g_i$表示第$i$个人头上有$g_i$顶红帽。($0\leq g_i \leq 10000)$

# Standard Output

输出一个整数$a$，表示红帽侠最少需要喊$a$次“你将加冕为王”。

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
1 1 3 4 4</td><td>4</td></tr><tr><td>4 2
0 3 2 1</td><td>0</td></tr></table>


# Constraints



# Note

Sample 1:  
第1次，对第4人喊“你将加冕为王”，整体红帽变为 [ 2 2 4 4 5 ]  
第2次，对第5人喊“你将加冕为王”，整体红帽变为 [ 3 3 5 5 5 ]  
第3次，对第4人喊“你将加冕为王”，整体红帽变为 [ 4 4 6 5 6 ]  
第4次，对第5人喊“你将加冕为王”，整体红帽变为 [ 5 5 7 6 6 ]  
此时，第3人红帽最多。  
可以证明，至少需要4次。  
Sample 2:  
第2人红帽最多，不需喊。

# Source


