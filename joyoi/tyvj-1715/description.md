# 

 
 # 题目描述 
从前有一条神奇的项链，为什么说它神奇呢？因为它有两个性质：<BR>1.&nbsp;神奇的项链可以拉成一条线，线上依次是N&nbsp;个珠子，每个珠子有一个能量值Ei；<BR>2.&nbsp;除了第一个和最后一个珠子，其他珠子都满足Ei=(Ei-1+Ei+1)/2+Di。<BR>由于这条项链很长，我们只能知道其两端珠子的能量值。并且我们知道每个珠子的Di是多少。请聪明的你求出这N&nbsp;个珠子的能量值分别是多少。 

 
 # 输入格式 
第一行三个整数N、E1、EN，表示珠子个数N，第一个珠子和第N个珠子的能量值。<BR>第二行N-2个整数，表示第2个珠子到第N-1个珠子的Di。 

 
 # 输出格式 
输出仅一行，N个整数，表示1到N个这N个珠子各自的能量值Ei。<BR>请放心，数据保证对于任意珠子满足(Ei-1+Ei+1)Mod2=0。 

 
 # 提示 
【数据规模】<BR>40%的数据&nbsp;1&lt;N&lt;=100。<BR>70%的数据&nbsp;1&lt;N&lt;=5,000，所有数据（包括计算中的）不超过10^9。<BR>100%的数据&nbsp;1&lt;N&lt;=500,000，|E1|、|EN|&lt;=10^14，|Di|&lt;=10^4。 
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
<tr><td>Sample Input 1:
4 1 4
0 0

Sample Input 2:
10 1 22
1 2 -3 5 1 4 2 -1</td><td>Sample Output 1:
1 2 3 4

Sample Output 2:
1 14 25 32 45 48 49 42 31 22</td></tr></table>
