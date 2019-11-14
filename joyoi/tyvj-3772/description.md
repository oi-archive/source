# 

 
 # 题目背景 
<p style="box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-family: inherit; font-size: 14px; font-weight: inherit; line-height: 20px;">魔法炮系列（三）</p> 

 
 # 题目描述 
<p style="font-family: inherit; font-weight: inherit; box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px;"><span style="box-sizing: border-box; font-family: inherit; font-weight: inherit;"><img height="183" src="/source/joyoi/tyvj-3772/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzc3Mi9odHRwOi8vbWVzc2lzeGgtd29yZHByZXNzLnN0b3Iuc2luYWFwcC5jb20vdXBsb2Fkcy8yMDE0LzEyLzEtMzAweDE4My5wbmc=.png" style="opacity: 0.9; box-sizing: border-box; border: 0px; vertical-align: middle;" title="1" width="300" /></span></p>

<p style="font-family: inherit; font-weight: inherit; box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px;"><span style="box-sizing: border-box; font-family: inherit; font-weight: inherit;">每当魔法炮闲暇之时，他总是喜欢玩一些网游来消遣，其中QQ飞车就是一个很好的选择。魔法炮是一个追求速度的人，总是希望自己的车速能够无限增加。于是，他研究了一条名叫&ldquo;极速飞车&rdquo;的赛道。</span></p>

<p style="font-family: inherit; font-weight: inherit; box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px;"><span style="box-sizing: border-box; font-family: inherit; font-weight: inherit;">这条赛道只有直道没有弯道，所以不会有任何速度损失。所有赛道中有n个特殊的加速带，这些加速带只能使用氮气来触发，而且仅当完整地经过某一条时，你的车速会增加L&middot;v，L为加速带长度。重叠的多条加速带互不影响，效果叠加。也就是说，对于每条加速带，你只能选择加速或不加速。玩家的氮气是无限的，但是只能在加速带上使用。不过由于这条赛道的路面很脆弱，赛道的任何位置最多能承受k个加速叠加，否则就不能通过了（加速带的起点和终点不计入叠加）。</span></p>

<p style="font-family: inherit; font-weight: inherit; box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-size: 14px; line-height: 20px;"><span style="box-sizing: border-box; font-family: inherit; font-weight: inherit;">魔法炮自然想做赛道之王，所以他想在赛前布置好加速的策略，使他最终的速度最大，因为这条赛道是按到达终点时的速度来排名的。</span></p> 

 
 # 输入格式 
<p><span style="color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">第一行四个整数n,k,v0,v.其中v0表示比赛开始的速度.接下来n行每行两个正整数li,ri，表示第i个加速带的起点和终点。</span></p> 

 
 # 输出格式 
<p><span style="color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">一个整数，代表最终的速度。</span></p> 

 
 # 提示 
<p style="box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;"><span style="box-sizing: border-box;">1&lt;=n&lt;=1000</span></p>

<p style="box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;"><span style="box-sizing: border-box;">1&lt;=li&lt;ri&lt;=10</span><span style="box-sizing: border-box; position: relative; font-size: 12px; line-height: 0; vertical-align: baseline; top: -0.5em;">6</span></p>

<p style="box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;"><span style="box-sizing: border-box;">保证结果不会超过</span><span style="box-sizing: border-box; font-family: 'Times New Roman';">int</span><span style="box-sizing: border-box;">范围</span></p>

<p style="box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;">&nbsp;</p>

<p style="box-sizing: border-box; margin: 0px 0px 10px; color: rgb(88, 102, 110); font-family: 'Source Sans Pro', 'Helvetica Neue', Helvetica, Arial, 微软雅黑, 黑体, sans-serif; font-size: 14px; line-height: 20px;"><span style="box-sizing: border-box;">初始速度</span><span style="box-sizing: border-box;">100</span><span style="box-sizing: border-box;">，经前四条加速带加速，速度达到</span><span style="box-sizing: border-box;">100+(2+1+6+4)*50=750</span><span style="box-sizing: border-box;">。但是无法使用第五条加速带，因为</span><span style="box-sizing: border-box;">8</span><span style="box-sizing: border-box;">和</span><span style="box-sizing: border-box;">9</span><span style="box-sizing: border-box;">之间已经叠加了</span><span style="box-sizing: border-box;">2</span><span style="box-sizing: border-box;">次加速。</span></p> 
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
<tr><td>5 2 100 50
1 3
5 6
3 9
7 11
8 10</td><td>750</td></tr></table>
