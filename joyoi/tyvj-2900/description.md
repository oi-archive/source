# 

 
 # 题目描述 
<p>话说小X现在正在家闲的无聊，这天小X正在观看北京奥运会，他突然很有兴趣想了解一段时间内中国队获得金牌的情况。还有一点，小X有特殊能力，可以预知未来，他可以准确的猜到中国队在某一个单位时间内获得的金牌数。但是，还有但是！由于工作量太大，再加上猜金牌要费很多的体力，所以他无法准确的计算出一段时间内获得的金牌数最大的单位时间是哪个，就因为这样小X很郁闷。他思索来思索去就想到了你，因为他知道你是个OIer，所以他对你呵呵一笑就把问题交给你了，你只有1s的时间来解决问题。</p> 

 
 # 输入格式 
<p>第一行一个n表示有n个时间段。<br />
接下来一行有n个数ai，ai表示小X猜到的中国队在第i个时间段内获得的金牌数。<br />
然后，第三行有一个数m，表示小X有m个问题。<br />
接下来有m行，每行有2个数分别为xi&nbsp;yi，表示要询问在时间段[xi,yi]内中国队获得金牌数最大的是哪个单位时间。<br />
小X有一个习惯，他问问题是有先后的，也就是说后一个问题总是在前一个问题之后提出的。<br />
注意对于第i个提问和第i+1个提问严格的有xi&lt;=xi+1，yi&lt;=yi+1。</p> 

 
 # 输出格式 
<p>一共m行，每行一个ki，表示第i个询问的答案。</p> 

 
 # 提示 
<p>数据范围：<br />
30%：&nbsp;n&lt;=1000&nbsp;m&lt;=1000<br />
100%：&nbsp;n&lt;=100000&nbsp;m&lt;=100000<br />
其他有关输入输出均小于maxlongint。</p>

<h1><strong style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei UI', 'Microsoft YaHei', 'Segou UI'; font-size: 14px; line-height: 20px;"><u>如果有ai相同的这个意外情况，请输出最早的那一天。</u></strong></h1> 
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
<tr><td>5
2 3 4 5 6
5
1 1
1 2
2 3
3 4
4 5
</td><td>1
2
3
4
5
</td></tr></table>
