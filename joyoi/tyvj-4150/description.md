# 

 
 # 题目描述 
<p>一个吉他手准备参加一场演出。他不喜欢在演出时始终使用同一个音量，所以他决定每一首歌之前他都要改变一次音量。在演出开始之前，他已经做好了一个列表，里面写着在每首歌开始之前他想要改变的音量是多少。每一次改变音量，他可以选择调高也可以调低。</p>

<p>音量用一个整数描述。输入文件中给定整数beginLevel，代表吉他刚开始的音量，以及整数maxLevel，代表吉他的最大音量。音量不能小于0也不能大于maxLevel。输入文件中还给定了n个整数c1~cn，表示在第i首歌开始之前吉他手想要改变的音量是多少。</p>

<p>吉他手想以最大的音量演奏最后一首歌，你的任务是找到这个最大音量是多少。</p> 

 
 # 输入格式 
<p>第一行依次为三个整数：n,&nbsp;beginLevel,&nbsp;maxlevel。</p>

<p>第二行依次为n个整数：c1~cn。</p> 

 
 # 输出格式 
<p>输出演奏最后一首歌的最大音量。如果吉他手无法避免音量低于0或者高于maxLevel，输出-1。</p> 

 
 # 提示 
<p>对于30%的数据：1&lt;=n&lt;=10。</p>

<p>对于100%的数据：1&lt;=n&lt;=50，1&lt;=ci&lt;=maxlevel，1&lt;=maxlevel&lt;=1000，0&lt;=beginlevel&lt;=maxlevel。</p>

<p>双倍经验：2947</p> 
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
<tr><td>4 8 20
15 2 9 10 
</td><td>-1
</td></tr></table>
