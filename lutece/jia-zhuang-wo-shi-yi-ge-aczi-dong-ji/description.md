
# Content

`帆宝`太菜了不懂什么是`AC自动机`，于是他积极地请教`乐爷`，`乐爷`以为`帆宝`在开玩笑，怎么可能菜到连这个都不会呢？

`乐爷`一本正经的说，显然AC自动机就是你字面理解的意思啊！就是把我写的一段代码扔到`AC自动机`里，`AC自动机`就能返还给我个能够AC的代码！

柱爷的代码很精炼，因此只有一个不含有空格和特殊字符字符串。

代码中可能出现的内容以及意义：

；         换行

\#          前面的代码写错了，把直到上一个分号的所有内容删除

@k@      重复的代码不想多写，把上往前数第k个句子（可能为空）的内容复制到这边$（k \ge 1）$

除了上面的字符，代码部分均为小写或大写字母，且保证输入合法。现在`帆宝`拿到了柱爷的一段代码，他想请教你写一个`AC自动机`，能够按照上面给出的要求将代码重构以便AC。

# Standard Input

一个字符串$S$，$1 \le |S| \le 100000$

# Standard Output

见题面

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
<tr><td>abccb;sc#ba;babc#;@1@ca;@1@;@3@bb;</td><td>abccb
ba

ca
ca
bb
</td></tr></table>


# Constraints



# Note



# Source


