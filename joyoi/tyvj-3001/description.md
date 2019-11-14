# 

 
 # 题目描述 
<p>
Feather的农场里有N*M块地，排列成N行，每行M块地。Feather在每块地里种植了不同的农作物。现在这些农作物都成熟了，可以摘取下来出售了。其中第i行第j列的地里的农作物的价值为W[i,j]。<br>JackRabbit是Feather的好友，平时经常为Feather的农作物除草除虫。为了答谢JackRabbit，Feather决定把一部分农作物送给JackRabbit。JackRabbit很高兴，恨不得一下子把农场里的农作物摘空。<br>为了防止JackRabbit把农作物摘空，Feather提出了两个条件：<br>1.每行最多选取两块地；<br>2.每列最多选取两块地。<br>这下子把JackRabbit难住了。如何在满足这两个条件的前提下，使得摘取的农作物的价值之和最大呢？<br></p> 

 
 # 输入格式 
<p>
第一行是两个整数Ｎ和Ｍ（3≤N≤30，3≤M≤30）。<br>以下N行每行M个整数，表示每块地的农作物的价值W[i,j]（0≤W[i,j]≤10000）。<br></p> 

 
 # 输出格式 
<p>
输出一个数，表示在满足条件的前提下摘取的农作物的价值之和的最大值。</p> 

 
 # 提示 
<p>
第一行选5和3，第二行选4和5，第三行选0和4，总和为21，是满足条件的最佳选取方案。</p> 
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
<tr><td>3 3
1 5 3
4 7 5
0 4 1
</td><td>21</td></tr></table>
