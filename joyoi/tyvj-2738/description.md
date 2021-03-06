# 

 
 # 题目描述 
<p>
分子生物学家要对基因序列进行比较，以发现它们之间的相似之处。在这个问题里面，我们只考虑由‘A’、‘T’、‘C’、‘G’四种符号组成的核酸序列。一般来说，这种比较的过程就是先把两个序列按照一定的方式进行配对，再逐对符号依次比较，从而确定它们之间的相似程度值。给定一个目标序列和存储在基因数据库里的若干序列，要求你编写程序，找出基因数据库中跟目标序列最相似的序列，也就是使相似程度值达到最大值的序列。<br>对于给定序列和一个数据库之间的某种配对方式，其相似程度值就是在这种配对方式下各对符号的相似程度值之和。如果配对的两个符号相同，那么该对符号的相似程度值为5，如果配对的两个符号不同，那么相似程度值就为－4。在配对的过程中，还可以添加空格，如果某一符号与空格配对，则相应的相似程度值为－7。比如给定序列M＝‘GAAGGCA’，和一个数据库序列N＝‘GCAGAGCA’，如果按下面的配对方式进行配对，那么两序列的相似程度值为5＋（－4）＋5＋5＋（－7）＋5＋5＋5＝19。<br>序列M：　G A A G ？G C A<br>序列N：　G C A G A G C A<br>注意在上面的配对方式中添加的空格用？表示。<br></p> 

 
 # 输入格式 
<p>
输入文件第一行为给定的目标序列，第2行为一个正整数N，即数据库序列的数目，其大小不超过1000，从第3行到第N+2行，每行为一个数据库序列。所有序列都是由A、T、C、G四种符号组成的字符串，全部字母均为大写，而且字符串长度不超过100。</p> 

 
 # 输出格式 
<p>
输出文件包含两行，第一行输出最大相似程度值，第二行输出与给定目标序列最相似的数据序列，如果有多个序列满足，则输出按照字典顺序排列最小的一个序列。</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>ACGGG
5
ACGGT
ACGGGG
ACCGGTT
TCGGG
AACGGG</td><td>18
AACGGG</td></tr></table>
