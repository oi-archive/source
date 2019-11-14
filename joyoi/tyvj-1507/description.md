# 

 
 # 题目背景 
夜幕降临，S国发现空中飘过几只飞碟，便立即组织专家进行分析。<BR>于是，专家们立即对飞碟排出物的初步检测，竟发现了DNA……<BR><BR> 

 
 # 题目描述 
为了进一步分析外星生物，专家们决定对DNA进行切割。<BR>限制性核酸内切酶是基因工程中的重要的工具酶。它会识别一段碱基序列（说白了就是只包含ATGC的序列）并且切割开。EcoRI是某种限制酶的名称，它识别有某种特性的DNA序列，即DNA序列双链反向排列相同的。（双链对应位碱基对要满足碱基互补配对原则）<BR>比如识别序列为&nbsp;G&nbsp;A&nbsp;A&nbsp;T&nbsp;T&nbsp;C<BR>&nbsp;&nbsp;互补链序列为&nbsp;C&nbsp;T&nbsp;T&nbsp;A&nbsp;A&nbsp;G<BR>第一条链从左读和第二条链从右读的是一样的。<BR>专家们想知道某一段DNA的序列中，具有这种特性的DNA子序列（连续）最长是多少，可限于智商，他们无法做出判断……于是，他们想到了你。<BR><BR><BR> 

 
 # 输入格式 
第一行，一个整数N，表示DNA序列的长度。<BR>第二行，一个字符串，表示DNA序列的某一条链的碱基序列。 

 
 # 输出格式 
输出只有一个数，为题目所求的最长特征DNA序列的长度。 

 
 # 提示 
【数据规模】<BR>	对于30%&nbsp;的数据&nbsp;N&lt;=500<BR>	对于90%&nbsp;的数据&nbsp;N&lt;=5000<BR>	对于100%的数据&nbsp;N&lt;=50000<BR>【友情提示】<BR>	A和T配对<BR>	G和C配对<BR>	题目描述不一定完全符合生物学原理，请不要轻易将此原理用于文化课学习！<BR>	大数据手下留情了……<BR> 
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
<tr><td>7
GAATTCA
</td><td>6

</td></tr></table>
