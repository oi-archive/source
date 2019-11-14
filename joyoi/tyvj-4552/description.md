# 

 
 # 题目背景 
<p>&nbsp;&nbsp;&nbsp;shy认为『Re:ゼロから始める異世界生活』是一部很好看的电视动画。但是shy觉得昴一周不死就很难得，如果能知道<span style="line-height: 20.8px;">昴</span>所有领便当的情况，那么就不会badend了。于是，shy想计算出在某个周目<span style="line-height: 20.8px;">昴</span>最多需要死亡回归的次数。</p> 

 
 # 题目描述 
<p>&nbsp;&nbsp;&nbsp;话说，森林的封印被解除，魔兽到处出没，<span style="line-height: 20.8px;">昴</span>和拉姆进入森林去寻找雷姆。我们可以把森林看做一个n&times;n的矩阵，每个元素只可能是W(wood)或者R(rock)。虽然拉姆能使用千里眼和风系魔法，但是体力不足的她无法应对魔兽，如果不和雷姆会和的话<span style="line-height: 20.8px;">昴</span>和拉姆就很危险。<span style="line-height: 20.8px;">昴</span>和拉姆、雷姆只可能存在于全是W的两个矩形里（<strong>这里的矩形面积必须大于1</strong>），如果这两个矩形相离则<span style="line-height: 20.8px;">昴</span>会被魔兽咬死，然后死亡回溯到几天前宅邸的床上。</p>

<p>&nbsp;&nbsp;&nbsp;shy马上想到可以用暴力，但是时间太长的话，<span style="line-height: 20.8px;">昴</span>也会因为魔兽的诅咒而死，所以shy求助于你希望能在较短的时间内完成计算。由于这个数很大，shy只需要知道其对10007取模后的数即可。</p> 

 
 # 输入格式 
<p>第一行一个整数n，表示森林的规格是n&times;n。</p>

<p>接下来n行每行有n个字符，这些字符不是&rsquo;W&rsquo;就是&rsquo;R&lsquo;。</p> 

 
 # 输出格式 
<p>一个数Cnt,表示答案mod&nbsp;10007。</p> 

 
 # 提示 
<p>对于20%的数据，n&le;233；</p>

<p>对于100%的数据，n&le;2333。</p>

<p><strong>Tyvj的评测机会比本地跑得慢1倍左右，请尽可能地使用常数优化。</strong></p>

<p><span lang="EN-US" style="font-size: 10.5pt; font-family: 'Microsoft YaHei UI', sans-serif; color: black; background-image: initial; background-attachment: initial; background-size: initial; background-origin: initial; background-clip: initial; background-position: initial; background-repeat: initial;"><img alt="" src="/source/joyoi/tyvj-4552/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotNDU1Mi9odHRwOi8vdHl2ai5jbi9BdmF0YXIvNDE5MTk=" style="width: 720px; height: 855px;" /><br />
<!--[endif]--></span></p>

<p><u>Thanks&nbsp;for&nbsp;viewing&nbsp;this&nbsp;problem.</u></p> 
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
WWRR
RRWR
WWWR
RWRW</td><td>7</td></tr><tr><td>3
WWR
RRR
WWW</td><td>3</td></tr><tr><td>3
WWR
WRR
RWW</td><td>2</td></tr></table>
