
# Content

Littlte_Pro像很多学生一样生活在清水河畔，同时周围也住着大量的driver朋友们，总共有 n个drivers和Little_Pro生活在清水河畔，所有的driver都被Little_Pro用特殊的魔法祝福过，所以这些driver只能是good driver 或者 bad driver 这2个对立事件中的一个。

Littlte_Pro 是一个聪明的小司机。有一天，他想让所以的 drivers朋友们排成一个队列。然而作为一个与众不同的小司机，他想让这些队列的good driver、baddriver交替出现，从而为我校交通事业做出了巨大的贡献。我们的 Little_Pro 同时也是一位大魔法师. 每一次施法，他可以在一瞬间交换2个driver的在队列中的位置, 或者改变driver叔叔的性质(把一个good driver 变成 bad driver 或者把一个bad driver 变成 good driver)，无论是无所畏惧的Zhong大司机![title](/source/lutece/little-prode-driverpeng-you-men-he-ta-de-mo-fa/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTUxNC8yMDE2MTExNjE2NTk1NDg2NDgucG5n.png)，还是三金在手的cx大司机，Littlte_Pro都可以用魔法瞬间把他们变成坏司机 (偷笑)，搞怪结束了再把他们又变回来。

虽然Little_Pro是一位无所不能的小司机，但还是请你帮忙找到最少的施法次数，从而使这些driver朋友们在队列中good driver、bad driver交替出现。

**test 1即样例，如果出现本机通过样例，提交出现**`wrong answer on test 1`**的情况，请检查在gets或者scanf("%c")之前是否已经使用getchar()将上一行的空格吸收。**

# Standard Input

第一行输入一个 integer n (1 ≤ n ≤ 100,000) — 表示drivers的数量.

第二行输入一个包含n个元素的字符串, 其中包括字符'1' 和字符 '0'，其中’1’ 代表 bad driver、 ‘0’ 代表 good driver.

# Standard Output

输出一个 integer — Little_Pro 需要的最少的施法次数，从而使这些driver在队列中good driver、bad driver交替出现。

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
<tr><td>5
01100</td><td>1</td></tr><tr><td>5
11111</td><td>2</td></tr><tr><td>3
010</td><td>0</td></tr></table>


# Constraints



# Note

在样例1中,Little_Pro需要交换第三个和第四个drivers.所以他总共需要施法1次.
在样例2中,把第二和第四个driver变成good driver. 所以施法2次.
在样例3中,这些driver在队列中good driver、baddriver交替出现，所以施法0次.

# Source


