# 

 
 # 题目背景 
<p>noip2013day1</p>

<p>数据来自官方</p>

<p>&nbsp;</p> 

 
 # 题目描述 
<p>涵涵有两盒火柴，每盒装有&nbsp;n&nbsp;根火柴，每根火柴都有一个高度。&nbsp;现在将每盒中的火柴各<br />
自&nbsp;排成一列，&nbsp;同一列火柴的高度互不相同，&nbsp;两列火柴之间的距离定义为：<span style="line-height: 1.6em;">&sum;</span><span style="line-height: 1.6em;">(a</span><sub style="line-height: 1.6em;">i</sub><span style="line-height: 1.6em;">-b</span><sub style="line-height: 1.6em;">i</sub><span style="line-height: 1.6em;">)</span><sup style="line-height: 1.6em;">2</sup><span style="line-height: 1.6em;">，</span></p>

<p><span style="line-height: 1.6em;">其</span><span style="line-height: 1.6em;">中&nbsp;a</span><span style="line-height: 1.6em;">i&nbsp;</span><span style="line-height: 1.6em;">表示第一列火柴中第&nbsp;i&nbsp;个火柴的高度，&nbsp;b</span><span style="line-height: 1.6em;">i&nbsp;</span><span style="line-height: 1.6em;">表示第二列火柴中第&nbsp;i&nbsp;个火柴的高度。</span></p>

<p>每列火柴中相邻两根火柴的位置都可以交换，请你通过交换使得两列火柴之间的距离最<br />
小。请问得到这个最小的距离，最少需要交换多少次？&nbsp;如果这个数字太大，请输出这个最<br />
小交换次数对&nbsp;99,999,997&nbsp;取模的结果。</p> 

 
 # 输入格式 
<p>&nbsp;</p>

<p>&nbsp;</p>

<p><span style="color: rgb(0, 0, 0); font-family: 宋体; font-size: 10pt;">共三行，第一行包含一个整数&nbsp;n，表示每盒中火柴的数目。<br />
<span style="font-size: 10pt;">第二行有&nbsp;n&nbsp;个整数，每两个整数之间用一个空格隔开，表示第一列火柴的高度。<br />
<span style="font-size: 10pt;">第三行有&nbsp;n&nbsp;个整数，每两个整数之间用一个空格隔开，表示第二列火柴的高度。</span></span></span><br style="line-height: normal; orphans: 2; widows: 2;" />
&nbsp;</p> 

 
 # 输出格式 
<p>输出共一行,包含一个整数,表示最少交换次数对&nbsp;99,999,997&nbsp;取模的结果。</p> 

 
 # 提示 
<p>&nbsp;</p>

<p>对于&nbsp;10%的数据，&nbsp;1&nbsp;&le;&nbsp;n&nbsp;&le;&nbsp;10；<br />
对于&nbsp;30%的数据，&nbsp;1&nbsp;&le;&nbsp;n&nbsp;&le;&nbsp;100；<br />
对于&nbsp;60%的数据，&nbsp;1&nbsp;&le;&nbsp;n&nbsp;&le;&nbsp;1,000；<br />
对于&nbsp;100%的数据，&nbsp;1&nbsp;&le;&nbsp;n&nbsp;&le;&nbsp;100,000，&nbsp;0&nbsp;&le;火柴高度&le;&nbsp;2<sup>31</sup>&nbsp;&minus;&nbsp;1。<br />
by&nbsp;460289052</p> 
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
<tr><td>4
2 3 1 4
3 2 1 4
</td><td>1
</td></tr></table>
