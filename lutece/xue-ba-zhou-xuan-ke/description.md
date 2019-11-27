
# Content

![](/source/lutece/xue-ba-zhou-xuan-ke/img/aHR0cHM6Ly9zczMuYmRzdGF0aWMuY29tLzcwY0Z2OFNoX1ExWW54R2twb1dLMUhGNmhoeS9pdC91PTE0ODAzMjMxOTgsMjY4NDQ2OTY3NSZmbT0yNyZncD0wLmpwZw==.jpg)
           
众所周知`周大爷`不仅编程了得，专业课成绩更是名列前茅，恰巧又到了选课的季节，神秘的`zin`作为`周大爷`的好朋（基）友，给了`周大爷`一份课表，这个课 表和一般的课表有些不同，它是一个有向无环图，图中每个节点表示一门课程，如果课程A有一条通向课程B的有向边，那么意味着，如果选了课程A，就能选课程B ，对于没有前驱的课程可以直接选择。

`周大爷`看了课表后，发现自己非常想学课程$k$,但是`周大爷`又不想花太多精力去学别的课程，现在请你帮助`周大爷`计算为了选上课程$k$最少一共要选多少门课程（$k$包含在内）。

# Standard Input

一个正整数$n$（$1\le n\le 200000$）,$k$ ($1\le k\le n$)  ，$m$（$1\le m\le \min(1000000 , \frac{n(n-1)}{2})$） 表示图中有$m$条边.接下来$m$行，每一行输入两个整数$a$，$b$（$1\le a,b\le n$）表示如果选了课程$a$就能选择课程$b$。

# Standard Output

周大爷最少要选多少门课程

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
<tr><td>3 2 1
1 2</td><td>2</td></tr></table>


# Constraints



# Note

样例不是test1

# Source


