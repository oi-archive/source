# 

 
 # 题目背景 
<div class="panel-body">
<p>XMJ是很萌的高新的呆萌小帅哥。他有很多妹子。</p>
</div> 

 
 # 题目描述 
<div class="panel-body">
<p>XMJ是很萌的高新的呆萌小帅哥。他有很多妹子，其中对于第i个妹子有一个能量值E[i]，而且&nbsp;这个妹子可以花费W[i]点能量A一道神题，或者花&nbsp;1点能量A一道水题。他想把妹子分成许多组，使得对于第j组里的妹子，每个妹子A&nbsp;shen[j]道神题和shui[j]道水题后，恰好消耗完能量值。注意：shen[j]与shui[j]可以是任意非负实数，<span style="">（这表示得了部分分<span style="text-decoration: underline;">&larr;强行解释ovo</span>）。</span></p>

<p><span style="">他想让妹子最多的一组的妹子尽量多，请你求出该组有多少个妹子，以及该组的shen[j]和shui[j]的值。</span></p>

<p>&nbsp;</p>

<p><span style="">保证对于所有数据，有方案可以把所有妹子合法分成不多于8组</span></p>

<p><span style="">保证答案唯一</span></p>
</div> 

 
 # 输入格式 
<div class="panel-body">
<p><span style="">第一行1个整数n，表示妹纸数。</span></p>

<p><span style="">接下来n行，每行2个正整数，表示这个妹纸能量（E[i]），以及消耗多少能量可以A一道神题（W[i]）。</span></p>

<p>&nbsp;</p>
</div> 

 
 # 输出格式 
<p>输出三个数，分别表示最多的一组有多少个妹子、该组的shen[j]、shui[j]（保留三位小数）</p>

<p>&nbsp;</p> 

 
 # 提示 
<div class="panel-body">
<p><strong><span style="">【样例解释】</span></strong></p>

<p><span style="">选择第1、2、4号妹纸分为一组。她们都可以A&nbsp;1/3道神题与2/3道水题。</span></p>

<p><span style="">1</span><span style="">号：1=(1/3)*1+(2/3)；</span></p>

<p><span style="">2</span><span style="">号：2=(1/3)*4+(2/3)；</span></p>

<p><span style="">4</span><span style="">号：3=(1/3)*7+(2/3)。</span></p>

<p><span style="">可以证明这是将最多的妹纸分为一组的方案。</span></p>

<p><strong><span style="">【数据范围】</span></strong></p>

<p><span style="">对于30%的数据，n&le;10，E[i]、W[i]&le;100。</span></p>

<p><span style="">对于50%的数据，n&le;1000，E[i]、W[i]&le;1000。</span></p>

<p><span style="">对于70%的数据，n&le;1000。</span></p>

<p><span style="">对于100%的数据，1＜n&le;10000，E[i]、W[i]为正整数，且E[i]&le;10^8、W[i]&le;10^8。</span></p>

<p style=""><span style="">保证对于所有数据，有方案可以把所有妹子合法分成不多于8组</span></p>

<p style=""><span style="">保证答案唯一</span></p>
</div> 
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
1 1
2 4
2 2
3 7</td><td>3 0.333 0.667
</td></tr></table>
