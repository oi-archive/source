# 

 
 # 题目背景 
中中酷爱滑雪，某日突发奇想，带领所有BDEZ的OIER去Alps滑雪，不幸的是，中中和OIER们遭遇了雪崩，除了中中，所有的OIER们都埋在了雪坑里，此时，中中救援队闪亮登场~！（中中救援队只有中中一个人！Orz！） 

 
 # 题目描述 
雪崩之后，出现了N个雪坑，每个雪坑都有一名OIER深陷其中，只有中中幸免，现在中中找到了M条双向道路，每条道路都会连接两个雪坑，但是，由于中中是路痴（-_-||），所以中中希望去除M条道路中尽可能多的道路，但是还要保证任一雪坑都能到达其他的雪坑，所以要先选择留下N-1条道路，中中可以从任意一个雪坑出发，并且任务完成后要回到出发点（起点的雪坑和终点的雪坑也需要消耗体力），而且中中只记得他选择的道路<BR>中中每到一个雪坑i，都会消耗一定的体力值t[i]，即使这个雪坑的OIER已被救出。第j条道路连接x,y两个雪坑，而从x到达y也需要消耗体力值energy<BR>由于时间紧迫，中中请你这名OIER帮助他计算下救出这N名OIER所消耗的最小体力值是多少<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;——By&nbsp;宇溟义诚、five213ddking 

 
 # 输入格式 
输入第一行两个整数N和M，表示有N名OIER，M条连接的道路<BR>接下来N行，每行一个整数t[i]，表示第i个雪坑需要消耗中中的体力值<BR>然后M行，每行三个整数x,y,energy，表示从x坑滑到y坑需要消耗的体力值为energy 

 
 # 输出格式 
第1行，一个整数，为中中消耗的最小体力值 

 
 # 提示 
对于30%的数据<BR>5&lt;=N&lt;=100，N-1&lt;=M&lt;=500<BR>1&lt;=t[i]&lt;=100<BR>x&lt;=N，y&lt;=N，x&lt;&gt;y，1&lt;=energy&lt;=100<BR>对于全部数据<BR>5&lt;=N&lt;=10000，N-1&lt;=M&lt;=100000<BR>1&lt;=t[i]&lt;=1000<BR>x&lt;=N，y&lt;=N，x&lt;&gt;y，1&lt;=energy&lt;=1000<BR>结果保证不超过maxlongint 
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
<tr><td>5 7
6
5
13
8
18
4 1 7
5 2 5
1 5 16
2 3 20
3 1 18
4 3 12
2 4 15
</td><td>154
</td></tr></table>
