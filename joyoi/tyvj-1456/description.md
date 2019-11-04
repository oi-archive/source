# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;当小精灵们把贺卡都书写好了之后。礼品准备部的小精灵们已经把所有的礼品都制作好了。可是由于精神消耗的缘故，他们所做的礼品的质量越来越小，也就是说越来越不让圣诞老人很满意。可是这又是没有办法的事情。<BR>&nbsp;&nbsp;&nbsp;&nbsp;于是圣诞老人把礼品准备部的小精灵们聚集起来，说明了自己的看法：“现在你们有n个礼品，其质量也就是降序排列的。那么为了使得这个礼品序列保持平均，不像现在这样很有规律的降序，我这里有一个列表。”<BR>&nbsp;&nbsp;&nbsp;&nbsp;“列表共有m行，这m行都称作操作（不是序列），每一行有n个数字，这些数字互不相同而且每个数字都在1到n之间。一开始，礼品的序列就是现在礼品所处的位置，也就是说，一开始礼品的序列就是1、2、3、4……n；那么然后，我们看列表的第一行操作，设这一行操作的第i个数字为a[i]，那么就把原来序列中的第a[i]个礼物放到现在这个序列的第i的位置上，然后组成新的礼物序列。然后，看列表的第二行操作……、第三行操作……一直到最后一行操作，重复上面的操作。当最后一行的操作结束，组成了的序列又按照第一行来操作，然后第二行操作……第三行操作……一直循环下去，直到一共操作了k行为止。最后生成的这个序列就是我们最终礼品送给孩子们的序列了。大家明白了吗？”<BR>&nbsp;&nbsp;&nbsp;&nbsp;“明白了！”<BR>&nbsp;&nbsp;&nbsp;&nbsp;等圣诞老人一个微笑走后，大家却开始忙碌了。因为k值可能很大很大，而小精灵们的操作速度有限。所以可能在圣诞老人去送礼物之前完成不了这个任务。让他们很是恼火……<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行三个数，n，m和k。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来m行，每行n个数。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;一行，一共n个数，表示最终的礼品序列。n个数之间用一个空格隔开，行尾没有空格，需要回车。<BR> 

 
 # 提示 
1&lt;=n&lt;=100；1&lt;=m&lt;=10；1&lt;=k&lt;=2^31-1。 
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
<tr><td>7 5 8
6 1 3 7 5 2 4
3 2 4 5 6 7 1
7 1 3 4 5 2 6
5 6 7 3 1 2 4
2 7 3 4 6 1 5
</td><td>2 4 6 3 5 1 7
</td></tr></table>