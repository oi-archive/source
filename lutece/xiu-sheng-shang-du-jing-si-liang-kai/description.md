
# Content

陆伯言军陷八卦阵之中，分明只是一条直路，却怎的也走不到尽头。阵中尽是石堆，以某一石堆为参考，无论向走还是向右，总是会回到出发的石堆,最后幸得一黄姓老翁带路才得脱出。

陆伯言逃离八卦阵后，来到山顶观察此阵，记从左往右第i堆石堆的高度为$A_i$，发现任何两堆较矮的石堆都能和它们之间的一座较高的石堆形成"八卦锁"，将其中之人牢牢锁住，无从逃脱。

根据石堆的情况，陆伯言大致计算了“八卦锁”的数量（即 $A_i < A_j > A_k,i<j<k$ 的组合数），不禁心中一惊,对孔明惊为天人，遂放弃追击，收兵回吴。

“有劳岳父了。” “为何将其放走？” “...一表人才，何必浪费于此。”

# Standard Input

第一行一个整数$n$，表示石堆堆数。

接下来一行，$n$个整数，第$i$个数表示从左到右第$i$堆石堆的高度$A_i$。

$1 \leq n \leq 50000,1 \leq A_i \leq 32768$

# Standard Output

一个整数，“八阵锁”的数目。

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
1 2 3 4 1</td><td>6</td></tr></table>


# Constraints



# Note



# Source


