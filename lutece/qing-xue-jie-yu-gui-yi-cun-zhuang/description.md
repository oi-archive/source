
# Content

日复一日，年复一年，春去秋来。

卿学姐终于从天行廖那里毕业啦。出山的卿学姐首先来到了一个诡异的村庄。

在这个村庄中，只有两种人，一种是好人，一种是坏人。

好人只说真话，坏人只说假话。

村庄虚伪的平静由于卿学姐的到来，终于被打破了。

人们开始互相指控，每个人都会说另外一个人是否是好人。

卿学姐修行途中只学会了膜法，却不谙世事，所以卿学姐无法确认哪些人是好人，哪些人是坏人。

但是机智的卿学姐意识到可以通过这些人的指控来分辨。

现在告诉你村庄中每个人指控谁是否为好人，请问是否有个合理的分类能够符合所有的指控。

# Standard Input

第一行一个整数$N$，表示村庄总共有$N$个人，村民从$1$开始编号到$N$

$1\le N \le 100000$

接下来$N$行，每行两个整数，$a_i,t$，如果$t$是$1$，那么说明第$i$个人认为第$a_i$个人是好人。如果$t$是$2$，那么说明第$i$个人认为第$a_i$个人是坏人。

$1\le a_i \le N$

# Standard Output

如果存在一个好人坏人的分类能够满足所有的指控，那么输出"Time to show my power"，否则输出"One face meng bi"

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
<tr><td>3
2 2
3 1
1 2</td><td>Time to show my power</td></tr><tr><td>3
2 2
3 2
1 2</td><td>One face meng bi</td></tr></table>


# Constraints



# Note

第一组样例中，如果1是好人，2和3都是坏人，就能解释得通这些指控

# Source


