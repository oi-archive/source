# 

 
 # 题目描述 
<p style="line-height: 20.8px;">大家都知道，基因可以看作一个碱基对序列。它包含了4种核苷酸，简记作A,C,G,T。生物学家正致力于寻找人类基因的功能，以利用于诊断疾病和发明药物。</p>

<p style="line-height: 20.8px;">在一个人类基因工作组的任务中，生物学家研究的是：两个基因的相似程度。因为这个研究对疾病的治疗有着非同寻常的作用。两个基因的相似度的计算方法如下：</p>

<p style="line-height: 20.8px;">对于两个已知基因，例如AGTGATG和GTTAG，将它们的碱基互相对应。当然，中间可以加入一些空碱基-，例如：</p>

<table align="center" border="1" cellpadding="0" cellspacing="0" style="line-height: 20.8px;">
	<tbody>
		<tr>
			<td style="width: 19px;">
			<p>A</p>
			</td>
			<td style="width: 19px;">
			<p>G</p>
			</td>
			<td style="width: 19px;">
			<p>T</p>
			</td>
			<td style="width: 19px;">
			<p>G</p>
			</td>
			<td style="width: 19px;">
			<p>A</p>
			</td>
			<td style="width: 19px;">
			<p>T</p>
			</td>
			<td style="width: 19px;">
			<p>-</p>
			</td>
			<td style="width: 19px;">
			<p>G</p>
			</td>
		</tr>
		<tr>
			<td style="width: 19px;">
			<p>-</p>
			</td>
			<td style="width: 19px;">
			<p>G</p>
			</td>
			<td style="width: 19px;">
			<p>T</p>
			</td>
			<td style="width: 19px;">
			<p>-</p>
			</td>
			<td style="width: 19px;">
			<p>-</p>
			</td>
			<td style="width: 19px;">
			<p>T</p>
			</td>
			<td style="width: 19px;">
			<p>A</p>
			</td>
			<td style="width: 19px;">
			<p>G</p>
			</td>
		</tr>
	</tbody>
</table>

<div style="line-height: 20.8px; clear: both;">&nbsp;</div>

<p style="line-height: 20.8px;">&nbsp;</p>

<p style="line-height: 20.8px;">这样,两个基因之间的相似度就可以用碱基之间相似度的总和来描述，碱基之间的相似度如下表所示：</p>

<p align="center" style="line-height: 20.8px;"><img src="/source/joyoi/tyvj-4486/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotNDQ4Ni9maWxlOi8vL0c6XEppYW5nU2hhbmdwdVzmoYzpnaJcUHJvYmxlbSUyMERlc2NyaXB0aW9uMTAyNy5maWxlc1wxMDI3LmdpZg==.gif" /><img alt="" src="data:image/jpeg;base64,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" style="width: 229px; height: 165px;" /><img src="/source/joyoi/tyvj-4486/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotNDQ4Ni9maWxlOi8vL0c6XEppYW5nU2hhbmdwdVzmoYzpnaJcUHJvYmxlbSUyMERlc2NyaXB0aW9uMTAyNy5maWxlc1wxMDI3LmdpZg==.gif" /></p>

<p style="line-height: 20.8px;">那么相似度就是：(-3)+5+5+(-2)+(-3)+5+(-3)+5=9。因为两个基因的对应方法不唯一，例如又有：</p>

<table align="center" border="1" cellpadding="0" cellspacing="0" style="line-height: 20.8px;">
	<tbody>
		<tr>
			<td style="width: 19px;">
			<p>A</p>
			</td>
			<td style="width: 19px;">
			<p>G</p>
			</td>
			<td style="width: 19px;">
			<p>T</p>
			</td>
			<td style="width: 19px;">
			<p>G</p>
			</td>
			<td style="width: 19px;">
			<p>A</p>
			</td>
			<td style="width: 19px;">
			<p>T</p>
			</td>
			<td style="width: 19px;">
			<p>G</p>
			</td>
		</tr>
		<tr>
			<td style="width: 19px;">
			<p>-</p>
			</td>
			<td style="width: 19px;">
			<p>G</p>
			</td>
			<td style="width: 19px;">
			<p>T</p>
			</td>
			<td style="width: 19px;">
			<p>T</p>
			</td>
			<td style="width: 19px;">
			<p>A</p>
			</td>
			<td style="width: 19px;">
			<p>-</p>
			</td>
			<td style="width: 19px;">
			<p>G</p>
			</td>
		</tr>
	</tbody>
</table>

<div style="line-height: 20.8px; clear: both;">&nbsp;</div>

<p style="line-height: 20.8px;">&nbsp;</p>

<p style="line-height: 20.8px;">相似度为：(-3)+5+5+(-2)+5+(-1)+5=14。规定两个基因的相似度为所有对应方法中，相似度最大的那个。<img src="file:///C:\Users\Administrator\Documents\Tencent Files\798700808\Image\C2C\Z6VW_71%~`WUW`NZ@`@_N4X.png" /></p> 

 
 # 输入格式 
<p>共两行。每行首先是一个整数，表示基因的长度；隔一个空格后是一个基因序列，序列中只含A,C,G,T四个字母。</p> 

 
 # 输出格式 
<p>仅一行，即输入基因的相似度。</p> 

 
 # 提示 
<p><span style="line-height: 1.6em;">1&lt;=序列的长度&lt;=100</span></p> 
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
5 GTTAG</td><td>14</td></tr></table>
