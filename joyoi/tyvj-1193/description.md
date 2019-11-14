# 

 
 # 题目描述 
<p>&nbsp;&nbsp;定义如下规则序列(字符串)：<br />
1．空序列是规则序列；<br />
2．如果S是规则序列，那么(S)和[S]也是规则序列；<br />
3．如果A和B都是规则序列，那么AB也是规则序列。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;例如，下面的字符串都是规则序列：<br />
()，[]，(())，([])，()[]，()[()]<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;而以下几个则不是：<br />
(，[，]，)(，())，([()<br />
现在，给你一些由&lsquo;(&rsquo;，&lsquo;)&rsquo;，&lsquo;[&rsquo;，&lsquo;]&rsquo;构成的序列，你要做的，是找出一个最短规则序列，使得给你的那个序列是你给出的规则序列的子列。(对于序列a1，a2，&hellip;，&nbsp;和序列bl，b2，&hellip;，&nbsp;，如果存在一组下标1&le;i1&lt;i2&lt;&hellip;&lt;&nbsp;&le;m，使得aj＝&nbsp;对一切1&le;j&le;n成立，那么a1，a2&hellip;，&nbsp;就叫做b1，b2，&hellip;，&nbsp;的子列。</p> 

 
 # 输入格式 
<p>输入文件仅一行，全部由&lsquo;(&rsquo;，&lsquo;)&rsquo;，&lsquo;]&rsquo;，&lsquo;]&rsquo;组成，没有其他字符，长度不超过255。</p> 

 
 # 输出格式 
<p>添加括号最少的数目</p> 

 
 # 提示 
<p>ACM/ICPC&nbsp;2001</p> 
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
<tr><td>[[(([]</td><td>4</td></tr></table>
