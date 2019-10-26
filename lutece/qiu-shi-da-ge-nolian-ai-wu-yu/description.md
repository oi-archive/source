
# Content

传说有这么一个故事！

在一个月白风清的晚上，秋实大哥约一位他心仪的妹子一起逛校园，浪漫的秋实大哥决定在当晚对妹子表白。“XXXXX...”，秋实大哥温情地说完了准备已久的话。而妹子决定用一种浪漫的方式接受秋实大哥（其实妹子早已对秋实大哥动心，这一刻她早已迫不及待了，但还是决定考秋实大哥最后一关，再委婉地接受）。妹子拿出了她心爱的口琴，吹出了一首迷人的曲子...... “你能把我的曲子重复一遍么？”，但考虑到万一秋实大哥没有做到而失去了赢得人赢的心的机会，妹子又说到，“只要你能吹出我的一部分旋律，我就答应你，从今以后，我就是你的一部分”。

#####好奇心重的你，真的很想知道秋实大哥最终有没有抱得美人归，除此之外，你还想知道秋实大哥吹出的曲子的旋律有多少次符合妹子的旋律。

![title](/source/lutece/qiu-shi-da-ge-nolian-ai-wu-yu/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTA2Ny8yMDE1MDQwOTEyNTI1ODM2NjUuanBn.jpg)

####将两个相邻的音符连起来，则妹子吹出的音符可以画出一条折线$A$，同样，秋实大哥吹出的音符也可以画出一条折线$B$，如果折线$B$已经与折线$A$的某一段完全重合，或者能够经过上下左右平移与折线$A$的某一段完全重合，则表示秋实大哥吹出了妹子的一部分旋律。

# Standard Input

第一行输入一个整数$N(2 \leq N \leq 2 \cdot 10^6)$，表示妹子吹了$N$个音符。

第二行输入$N$个音符，每个音符都是整数，且在32位整数范围内，每两个音符用一个空格隔开。

第三行输入一个整数$M(2 \leq M \leq 2 \cdot 10^6)$，表示秋实大哥吹了$M$个音符。

最后一行输入$M$个音符，每个音符都是整数，且在32位整数范围内，每两个音符用一个空格隔开。

# Standard Output

如果秋实大哥抱得美人归了，第一行输出`Wow! Life Winner!`，第二行再输出一个整数，表示秋实大哥的曲子的旋律有多少次符合妹子的。

如果秋实大哥没有做到，输出`Oh. That's impossible. I must have had a dream.`

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
<tr><td>14
1 1 5 5 6 6 5 4 4 3 3 2 2 1
14
0 0 4 4 5 5 4 3 3 2 2 1 1 0</td><td>Wow! Life Winner!
1</td></tr><tr><td>20
1 2 1 2 1 2 1 2 1 1 0 1 3 2 3 2 7 6 7 2
3
6 5 6</td><td>Wow! Life Winner!
6</td></tr><tr><td>25
2 3 2 3 3 2 3 3 3 2 3 2 2 3 3 2 2 2 3 3 3 3 2 3 3
3
2 3 3</td><td>Wow! Life Winner!
5</td></tr><tr><td>29
6 6 7 5 5 6 4 4 5 3 3 4 2 2 3 1 1 2 0 0 1 -1 -1 0 -2 -2 -1 -3 -3
8
6 6 7 5 5 6 4 4</td><td>Wow! Life Winner!
8</td></tr><tr><td>26
1 1 0 1 0 1 0 1 0 1 1 0 1 0 1 0 1 1 0 1 0 1 1 0 1 0
5
1 1 0 1 1</td><td>Oh. That's impossible. I must have had a dream.</td></tr></table>


# Constraints



# Note



# Source


