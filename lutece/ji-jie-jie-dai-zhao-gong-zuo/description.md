
# Content

- 又到了一年一度的泥电学子找工作的日子，大家都在各大网站上投了不少的简历，却是收到了寥寥可数的offer。
- 然而，预料之中的是，佳浩姐姐又收到了数不胜数的offer，这些offer来自n家公司，并且没家公司都给佳浩姐姐寄出了至少一封offer（是的，许多公司给佳浩姐姐寄出了很多offer，这些offer涵盖各个不同的岗位，他们希望佳浩姐姐能选择其中一个或者多个岗位）。
- 由于佳浩姐姐收到的offer实在是太多了，以至于佳浩姐姐已经忘记了一共有多少offer了！现在佳浩姐姐只记得一些公司寄出的offer数量与其他公司的offer数量之间的关系，例如A公司比B公司给出的offer少，而C公司比D公司给出的offer多，E公司与F公司给出的offer一样多。
- 佳浩姐姐非常的忙，因此没有时间来详细的整理这些offer，我们希望你能根据佳浩姐姐的回忆想想佳浩姐姐至少收到了多少封offer，当然，佳浩姐姐可能记错了一些东西，以至于这些关系之间可能存在矛盾。

# Standard Input

第一行包含两个整数n，m，表示一共有n家公司，佳浩姐姐一共记得m个关系（1≤n≤1000，0≤m≤5000）  
接下来的m行每行包含三个整数，o，a，b，当o为1时表示a公司给出offer比b公司多，当o为2时表示a公司给出offer比b公司少，当o为3时表示a公司给出offer与b公司的一样多。

# Standard Output

若佳浩姐姐的记忆不存在矛盾，则输出佳浩姐姐最少收到了多少封offer，否则输出-1

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
<tr><td>2 2
1 2 1
1 1 2</td><td>-1</td></tr><tr><td>3 2
1 1 2
2 3 1</td><td>4</td></tr></table>


# Constraints



# Note

在样例2中，1公司比2公司的给出的多，3公司比1公司给出的少，因此，1公司2封，2、3公司各一封的情况为最少收到的offer数量，共4封。

# Source


