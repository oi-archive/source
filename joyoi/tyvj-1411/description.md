# 

 
 # 题目描述 
<p>&nbsp;&nbsp;&nbsp;&nbsp;想必大家都看过成龙大哥的《80天环游世界》，里面的紧张刺激的打斗场面一定给你留下了深刻的印象。现在就有这么<br />
&nbsp;&nbsp;&nbsp;&nbsp;一个80人的团伙，也想来一次环游世界。<br />
&nbsp;&nbsp;&nbsp;&nbsp;他们打算兵分多路，游遍每一个国家。<br />
&nbsp;&nbsp;&nbsp;&nbsp;因为他们主要分布在东方，所以他们只朝西方进军。设从东方到西方的每一个国家的编号依次为1...N。假若第i个人的游历路线为P1、P2......Pk(0&le;k&le;N)，则P1&lt;P2&lt;......&lt;Pk。<br />
&nbsp;&nbsp;&nbsp;&nbsp;众所周知，中国相当美丽，这样在环游世界时就有很多人经过中国。我们用一个正整数Vi来描述一个国家的吸引程度，Vi值越大表示该国家越有吸引力，同时也表示有且仅<br />
有Vi个人会经过那一个国家。<br />
&nbsp;&nbsp;&nbsp;&nbsp;为了节省时间，他们打算通过坐飞机来完成环游世界的任务。同时为了省钱，他们希望总的机票费最小。<br />
&nbsp;&nbsp;&nbsp;&nbsp;明天就要出发了，可是有些人临阵脱逃，最终只剩下了M个人去环游世界。他们想知道最少的总费用，你能告诉他们吗？</p> 

 
 # 输入格式 
<p>&nbsp;&nbsp;&nbsp;&nbsp;第一行两个正整数N，M。<br />
&nbsp;&nbsp;&nbsp;&nbsp;第二行有N个不大于M正整数，分别表示V1，V2......VN。<br />
&nbsp;&nbsp;&nbsp;&nbsp;接下来有N-1行。第i行有N-i个整数，该行的第j个数表示从第i个国家到第i+j个国家的机票费（如果该值等于-1则表示这两个国家间没有通航）。</p> 

 
 # 输出格式 
<p>在第一行输出最少的总费用。</p> 

 
 # 提示 
<p>在10%的数据中，M=1<br />
在20%的数据中，1&le;M&le;2<br />
在40%的数据中，1&le;M&le;3<br />
在60%的数据中，1&le;M&le;4<br />
在100%的数据中，1&le;N&le;100，1&le;M&le;79<br />
保证所以输入数据中最少费用小于10^6。<br />
保证至少存在一种可行方案。纪中联赛模拟题<br />
BY&nbsp;CQF</p> 
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
<tr><td>6 3
2 1 3 1 2 1
2 6 8 5 0
8 2 4 1
6 1 0
4 -1
4
</td><td>27
</td></tr></table>
