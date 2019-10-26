
# Content

柱爷很忙。

柱爷每天不仅要炒股，还要策划和实施抢银行，同时还要水群、回答IOI小朋友们问题，又或者要练习咸鱼神功。

为了能更快完成这些事，把时间拿来玩[BattleBlock Theater](http://store.steampowered.com/app/238460/)，柱爷把要做的$N$件事的类型$a_i$按**原本做的顺序**记录下来，计算最少要花费的时间。

万事冥冥之中俱有关联。假如柱爷做事$i$的前一件事是事$j$，所花费的时间为$(a\_i \|a\_j)-(a\_i\&a\_j)$，其中$\|，\&$是位运算符。若柱爷做事$i$前没有做事，则柱爷要花费的时间为$ai$。

但事情总有轻重缓急之分，按原本顺序的事$i$最多能推迟到做完**任意件**紧接着事$i$之后的事$j，i< j\leq i+b_i$后做，即原本顺序的事$k,k>i+b_i$不能在事$i$之前完成。

柱爷已经知道自己最少要花多少时间了，请问你知道吗。

# Standard Input

第一行一个数$N$，代表柱爷要做$N$件事。$1\leq N\leq 1000$

之后$N$行，每行两个数$a_i，b_i$，代表事情的类型和重要程度。$1\leq a_i\leq 1000，0\leq b_i\leq 7$

# Standard Output

输出一行一个数，即柱爷最少要花的时间。

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
5 0
4 0</td><td>6</td></tr><tr><td>2
5 1
4 0</td><td>5</td></tr></table>


# Constraints



# Note

对于样例2，柱爷可以先做**事2**再做**事1**，答案为$4+(4\|5)-(4\&5)=5$

# Source


