
# Content

Silentsky是花仙子魔法学校的学生，他很聪明，可是却很懒很调皮。他大半个学期都没有上课，只有到期末考试临近时，他才终于意识到了自己必须开始学习了。花仙子老师的课可不是那么容易通过的。如果这门课Silentsky没过的话，lcy就可能会很生气甚至会不见他了。

![.*](/source/lutece/kan-shu/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTYzLzIwMTQwMjAyMjIzMDQ3NTE2MjMucG5n.png)

Silentsky可没有那么多的时间用来学习，因为他还有很多其他事情要做，和lcy出去逛街就需要很多很多的时间。为了不至于裸考，Silentsky必须啃完厚厚的书本。可同时Silentsky又要尽快看完以保证lcy不生气。可怜的Silentsky只好只看课本上的教学内容而不得不放弃每一章后面的习题。教材的页码从1开始，每章的习题都放在了教学内容的后面。

要看完花仙子老师的教材是一项无比艰巨的任务，而Silentsky每天只能看固定页数的书，所以虽然他跳过了课后的习题，可是要看完依然需要很多天。焦急的Silentsky想知道在一些天结束的时候，他第二天应该从哪一页开始看呢，你能告诉他吗？

# Standard Input

输入的第一行是$T$（不超过$30$）。$T$表示测试部分的个数，每一部分都要求单独计算并按照要求输出结果。

每一组数据的第一行有两个整数$n$, $m$，分别表示课本的章数为$n$($0 < n\leq 100000$), Silentsky每天能够看$m$页课本($0\leq m\leq 1000000000$，跳过习题)。

之后一行有$n$个整数，第$i$个数代表第$i$章Silentsky必须看的教学内容的页数。接下来的一行也有$n$个整数，第$i$个数代表第i章的习题的页数。($0\leq$页数$\leq 1000000000$)。

接下来的一行有一个整数$q$，表示有$q$个询问($0< q\leq 1000$)。之后的$q$行的每一行都是一个整数$d$，表示Silentsky询问在$d+1$天的时候他应该开始看的那一页的页码（$0\leq d\leq 1000000000$)。

# Standard Output

对于每个询问，如果在那天结束的时候Silentsky已经学完课本，输出`Our beautiful girl won't be angry.^ ^`；如果还没有学到任何内容，输出`Stupid boy learned nothing so far.`；否则输出在$d+1$天Silentsky应该开始看的那一页的页码。

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
<tr><td>2
3 10
17 18 19
20 30 40
3
1
2
6
2 1
1 2
1000000000 1000000000
3
0
1
2</td><td>11
41
Our beautiful girl won't be angry.^ ^
Stupid boy learned nothing so far.
1000000002
1000000003</td></tr></table>


# Constraints



# Note

**为了避免发生不必要的错误，请把结果需要的输出文字直接拷贝。计算中可能会超出int范围，请使用long long。**

# Source


