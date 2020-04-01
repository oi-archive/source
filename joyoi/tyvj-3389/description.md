# 

 
 # 题目描述 
<p>
相似基因（GENE.pas\c\cpp）<br><br>【题目描述】<br>　　大家都知道，基因可以看作一个碱基对序列。它包含了4种核苷酸，简记作A,C,G,T。生物学家正致力于寻找人类基因的功能，以利用于诊断疾病和发明药物。<br>　　在一个人类基因工作组的任务中，生物学家研究的是：两个基因的相似程度。因为这个研究对疾病的治疗有着非同寻常的作用。两个基因的相似度的计算方法如下：<br>　　对于两个已知基因，例如AGTGATG和GTTAG，将它们的碱基互相对应。当然，中间可以加入一些空碱基-，例如：<br><br><center><img src="/source/joyoi/tyvj-3389/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzM4OS9wcm9ibGVtc19pbWFnZXMvMjE4MC8xLmpwZw==.jpg"></img></center><br>　　这样,两个基因之间的相似度就可以用碱基之间相似度的总和来描述，碱基之间的相似度如下表所示：<br><br><center><img src="/source/joyoi/tyvj-3389/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzM4OS9wcm9ibGVtc19pbWFnZXMvMjE4MC8yLmpwZw==.jpg"></img></center><br>　　那么相似度就是：(-3)+5+5+(-2)+(-3)+5+(-3)+5=9。因为两个基因的对应方法不唯一，例如又有：<br><br><center><img src="/source/joyoi/tyvj-3389/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzM4OS9wcm9ibGVtc19pbWFnZXMvMjE4MC8zLmpwZw==.jpg"></img></center><br>　　相似度为：(-3)+5+5+(-2)+5+(-1)+5=14。规定两个基因的相似度为所有对应方法中，相似度最大的那个。</p> 

 
 # 输入格式 
<p>
　　输入文件GENE.IN共两行。每行首先是一个整数，表示基因的长度；隔一个空格后是一个基因序列，序列中只含A,C,G,T四个字母。1<=序列的长度<=100。</p> 

 
 # 输出格式 
<p>
　　输出文件GENE.OUT仅一行，即输入基因的相似度。</p> 
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
<tr><td>7 AGTGATG
5 GTTAG
</td><td>14</td></tr></table>
