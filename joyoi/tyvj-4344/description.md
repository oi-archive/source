# 

 
 # 题目描述 
<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">LHX教主很能跳，因为Orz他的人太多了。教主跳需要消耗能量，每跳1米就会消耗1点能量，如果教主有很多能量就能跳很高。</p>

<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">教主为了收集能量，来到了一个神秘的地方，这个地方凡人是进不来的。在这里，教主的正上方每100米处就有一个能量球（也就是这些能量球位于海拔100，200，300&hellip;&hellip;米处），每个能量球所能提供的能量是不同的，一共有N个能量球（也就是最后一个能量球在N&times;100米处）。教主为了想收集能量，想跳着吃完所有的能量球。教主可以自由控制他每次跳的高度，接着他跳起把这个高度以下的能量球都吃了，他便能获得能量球内的能量，接着吃到的能量球消失。教主不会轻功，教主不会二段跳，所以教主不能因新吃到的能量而变化此次跳跃的高度。并且教主还是生活在地球上的，所以教主每次跳完都会掉下来。</p>

<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">问教主若要吃完所有的能量球，最多还能保留多少能量。</p> 

 
 # 输入格式 
<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">第1行包含两个<strong>正整数</strong>N，M，表示了能量球的个数和LHX教主的初始能量。</p>

<p style="margin: 5px 0px; font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">第2行包含N个<strong>非负整数</strong>，从左到右第I个数字依次从下向上描述了位于I&times;100米位置能量球包含的能量，整数之间用空格隔开。</p> 

 
 # 输出格式 
<p><span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">仅包括一个</span><strong style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">非负整数</strong><span style="font-family: 'Lucida Grande', Lucida, 'Lucida Sans Unicode', 'Lucida Sans', Tahoma, 'Segoe UI', Verdana, 微软雅黑, 'Microsoft YaHei', 宋体; font-size: 14px; line-height: 21px;">，为教主吃完所有能量球后最多保留的能量。</span></p> 

 
 # 提示 
<h2><strong>限制</strong></h2>

<p>对于10%的数据，有N&le;10；<br />
对于20%的数据，有N&le;100；<br />
对于40%的数据，有N&le;1000；<br />
对于70%的数据，有N&le;100000；<br />
对于100%的数据，有N&le;2000000。<br />
保证对于所有数据，教主都能吃到所有的能量球，并且能量球包含的能量之和不超过2^31-1。<br />
时限1s。</p>

<h2><strong>提示</strong></h2>

<p>第1次跳100米，得到200能量，消耗100能量，所以落地后拥有300能量。<br />
第2次跳300米，吃到剩下的第3棵能量球，消耗拥有的300能量，得到400能量。<br />
若第1次跳200米，第2次跳300米，最后剩余300能量。</p>

<h2><br />
<strong>来源</strong></h2>

<p>​Vijos&nbsp;1617</p>

<h2><strong>版权</strong></h2>

<p>本用户并不拥有该资料版权。如果无意侵犯了您的权益，请私信管理员或本用户。管理员接到通知后请删题，以避免不必要的纠纷，谢谢！</p> 
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
<tr><td>3 200
200 200 200</td><td>400</td></tr></table>
