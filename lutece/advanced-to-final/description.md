
# Content

/* ----------------------------------------------------------------------------------

厦门大学程序设计竞赛预选赛晋级规则


预选赛晋级规则如下：

$T = 20$。 
$A = 10$。 

1. 预选赛晋级决赛总名额为 $T$ 人。
2. 每次预选赛的有$A$个晋级名额。
3. 只有正式报名成功的选手（以下简称正式选手）才有晋级资格。
4. 每次预选赛的正式选手中的前$A$名有直接晋级权。
5. 在两次或者两次以上预选赛里取得晋级权的选手有权选择在哪次预选赛晋级， 并同时失去其他
预选赛的直接晋级权，失去的直接晋级权不再往下递补。在选手未做选择的情况下，默认从其第一次
获得直接晋级权的预选赛中晋级。
6. 在确定所有直接晋级选手后， 如果某个预选赛晋级人数不足$A$人， 则在同一次预选赛中未晋级
的正式选手中按排名往下递补选择晋级选手， 一次预选赛总共最多晋级$A$人。获得递补资格的选手从
其最早获得递补资格的预选赛中晋级。

---------------------------------------------------------------------------------- */

Now, you are one of the finalists of $4$_th Xiamen University Programming Contest.

But don't forget how you got advanced to this Final. In general, we have $k$ preliminary contests.

Given the lists of the registered contestants , the ranklists of the $k$ preliminary contest and the decision of some contestant after the preliminary stage, you are to determine the finalists of out contest.

# Standard Input

The input contains only one test case.

The test case begin with an integer $A (0 \leq A \leq 20)$ as mentioned above.

The rest of the test case consists of three blocks -- Contestant List Block, Ranklist Block, Decisions Block.

The Contestant List Block begins with an integer $n (0 \leq n \leq 1000)$ indicating the number of the registered contestants. Then $n$ lines follows, which represents the $n$ distinct IDs of contestant with no more than ten characters.

You can assume that there are no two lines of the same ID.

The Ranklist Block begins with an integer $k (0 \leq k \leq 1000)$ means there are $k$ sub-blocks, the $i$_th sub-block begins with an integer $n\_i (0 < n\_i \leq 100)$ indicating the number of IDs participated in the $i$_th preliminary contest and is followed by $n\_i$ lines presenting the ranklist from top to bottom. You can assume that there are no two lines of the same ID in a sub-block.

The Decisions Block begins with an integer $q (0 \leq q \leq 1000)$, which means that there will be q Emails about advancing deicision from contestant to judge team.
Each the rest $q$ lines is in the form of "ID $x$" (without quotation), ID is the contest ID of the sender with no more than ten characters, $x (0 \leq x < k)$ is the preliminary contest index he chooses to advance from. Some contestant may send more than one Email to judges, only the last Email sent takes effect.

All IDs are case-sensitive.

# Standard Output

You should output the finalists if any, one per line, in lexicographic order.

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
<tr><td>4
9
ArXoR
Loneknight
TheBeet
aaa
bbb
ccc
ddd
eee
fff
3
9
ArXoR
Loneknight
TheBeet
aaa
bbb
ccc
ddd
eee
fff
4
Loneknight
ArXoR
TheBeet
bbb
3
TheBeet
Loneknight
ArXoR
2
ArXoR 0
arxor 1</td><td>ArXoR
Loneknight
TheBeet
aaa
bbb</td></tr></table>


# Constraints



# Note



# Source


