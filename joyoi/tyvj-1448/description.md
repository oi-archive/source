# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;cjBBteam拥有一个很大的野生动物园。这个动物园坐落在一个狭长的山谷内，这个区域从南到北被划分成N个区域，每个区域都饲养着一头狮子。这些狮子从北到南编号为1,2,3,…,N。每头狮子都有一个觅食能力值Ai，Ai越小觅食能力越强。饲养员cmdButtons决定对狮子进行M次投喂，每次投喂都选择一个区间[I,J]，从中选取觅食能力值第K强的狮子进行投喂。值得注意的是，cmdButtons不愿意对某些区域进行过多的投喂，他认为这样有悖公平。因此cmdButtons的投喂区间是互不包含的。你的任务就是算出每次投喂后，食物被哪头狮子吃掉了。 

 
 # 输入格式 
输入第一行有两个数N和M。此后一行有N个数，从南到北描述狮子的觅食能力值。此后M行，每行描述一次投喂。第t+2的三个数I,J,K表示在第t次投喂中，cmdButtons选择了区间[I,J]内觅食能力值第K强的狮子进行投喂。 

 
 # 输出格式 
输出有M行，每行一个整数。第i行的整数表示在第i次投喂中吃到食物的狮子的觅食能力值。 

 
 # 提示 
对于100%的数据，有1&lt;=N&lt;=100000，1&lt;=M&lt;=50000。周戈林 
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
<tr><td>7 2
1 5 2 6 3 7 4
1 5 3
2 7 1
</td><td>3
2
</td></tr></table>
