
# Content

基爷是一个笑口常开的人，不管是什么时候他都能保持一个好心态。一天，他发现在网络聊天时我们经常会用到很多表情符号，比如 Orz，TAT，QAQ，⊙﹏⊙，→\_→ $\ldots\ldots$但基爷觉得这些都太消极了，他更喜欢一些他喜欢的表情，比如 TOT，=\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_＝ ，^O^ $\ldots\ldots$

他意外的发现很多表情都有对称性。就拿TOT来说，如果把T，O都看成一个字符串，那么TOT也是个字符串，且它自身也拥有对称性。

基爷越想越开心，他开始在每个接触到的字符串里找形如TOT的子串，他现在拿到一个长度为$N$的字符串S，并采用枚举O串的长度的方法来进行排查。基爷脑子转的快，一下就完成了一大半任务。现在他准备开始排查O串长度为$K$的子串，但时间到了！他要开始组队训练了！要去拯救世界了！可谁来拯救这个问题呢？他决定交给你来办。

####给一个长度为$N$的字符串S，问S中有多少个子串满足TOT的形式，其中O串的长度为$K$，T串为非空字符串。

（基爷离开前留下了一句话：“`对了，两个子串，只要在母串中的位置不同，就算做不同。` 走啦，拜拜”）

# Standard Input

第一行输入一个字符串$S（1\leq |S|\leq 10^5）$，第二行输入一个整数$K（1\leq K< |S|）$，表示$O$串的长度。字符串只含有小写英文字母（a－z）

# Standard Output

输出一个整数，表示你帮基爷求出的答案。

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
<tr><td>bbaabaaaaa
1</td><td>7</td></tr><tr><td>abxxxxxab
5</td><td>1</td></tr><tr><td>aaaaaaaaaaa
2</td><td>20</td></tr><tr><td>gvgggfgcgcgagngmgogz
1</td><td>10</td></tr><tr><td>abbabaabbaababbabaababbaabbabaabbaababbaabbabaabab
4</td><td>63</td></tr></table>


# Constraints



# Note

#####下面对样例1进行解释：
>#####$S$=bbaabaaaaa，K=1，说明形如TOT的子串的|O|等于1。
>#####$S_{1...5}$=baaba，其中T=ba，O=a
>#####$S_{2...6}$=aabaa，其中T=aa，O=b
>#####$S_{3...5}$=aba，其中T=a，O=b
>#####$S_{5...7}$=aaa，其中T=a，O=a
>#####$S_{6...8}$=aaa，其中T=a，O=a
>#####$S_{7...9}$=aaa，其中T=a，O=a
>#####$S_{5...9}$=aaaaa，其中T=aa，O=a
>#####所以有7个子串形如TOT形式。
>#####T串是不可以为空字符串的，还有，别忘了基爷的话，"两个子串，只要在母串中的位置不同，就算做不同"。＝\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_＝

# Source


