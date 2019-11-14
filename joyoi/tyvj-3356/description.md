# 

 
 # 题目描述 
<p>
罚款（Penalty.pas\c\cpp） <br><br>【题目描述】<br>　　Symbol最近非常倒霉，开车魂不守舍，不是闯红灯就是超速，结果在某一天同时收到M张罚单，每张罚单交罚款都需要一定的天数才能完成，而且一定要处理完一张罚单后，才能处理下一张，罚金取决于完成交罚款的时间，假设罚单j在你收到罚单那天开始的第d天完成，那么罚金为ajd2+bjd+cj，而且罚金随着d的增大而增大。<br>　　你的任务制作一张安排表，使得最多的罚金最小。<br>　　如假设有3张罚单，罚单1需要3天来完成，罚金为3d+2；罚单2需要4天来完成，罚金为d+7;罚单3需要5天来完成，罚金为2d-4。<br>　　这样，最好的方案是按照1，3，2的顺序来处理，最多的罚金时19<br></p> 

 
 # 输入格式 
<p>
　　输入文件Penalty.in第一行是一个整数M,表示罚单的数量。接下来M行，每行包括4个整数，第i+1行描述了第i张罚单的情况，第一个数di表示需要di才能完成，接下来三个整数ai,bi,ci表示罚金表达式的三个参数。</p> 

 
 # 输出格式 
<p>
　　输出文件Penalty.out输出最大罚金的最小值。</p> 

 
 # 提示 
<p>
【数据说明】<br>　　100%的数据1<=M<=500000<br>　　50%的数据 1<=M<=5000<br>　　保证结果在int64范围内。<br></p> 
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
<tr><td>3
3 0 3 2
4 0 1 7
5 0 2 -4
</td><td>19</td></tr></table>
