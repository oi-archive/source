# 

 
 # 题目描述 
某一天WJMZBMR在打osu~~~但是他太弱逼了，有些地方完全靠运气:(<BR>我们来简化一下这个游戏的规则<BR>有n次点击要做，成功了就是o，失败了就是x，分数是按comb计算的，连续a个comb就有a*a分，comb就是极大的连续o。<BR>比如ooxxxxooooxxx，分数就是2*2+4*4=4+16=20。<BR>Sevenkplus闲的慌就看他打了一盘，有些地方跟运气无关要么是o要么是x，有些地方o或者x各有50%的可能性，用?号来表示。<BR>比如oo?xx就是一个可能的输入。<BR>那么WJMZBMR这场osu的期望得分是多少呢？<BR>比如oo?xx的话，?是o的话就是oooxx&nbsp;=&gt;&nbsp;9，是x的话就是ooxxx&nbsp;=&gt;&nbsp;4<BR>期望自然就是(4+9)/2&nbsp;=6.5了 

 
 # 输入格式 
第一行一个整数n，表示点击的个数<BR>接下来一个字符串，每个字符都是ox？中的一个 

 
 # 输出格式 
一行一个浮点数表示答案<BR>四舍五入到小数点后4位<BR>如果害怕精度跪建议用long&nbsp;double或者extended 

 
 # 提示 
osu很好玩的哦<BR>WJMZBMR技术还行(雾),x基本上很少呢 
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
????</td><td>4.1250</td></tr></table>
