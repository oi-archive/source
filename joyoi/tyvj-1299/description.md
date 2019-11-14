# 

 
 # 题目描述 
从前有一个庞大的家族，光10岁以下的小朋友都有N(N&lt;=10^4)个.他们的名字也非常有意思,第i个小朋友叫做i.<BR>平时小朋友们喜欢一起去占卜婆婆那里玩占卜。一天占卜婆婆说用一种非常诡异的方法可以知道小朋友们的身高，具体方法如下：<BR>小朋友在家里面把所有的有标价的玩具都找出来，随便怎样摆放在屋子中。然后占卜婆婆给小朋友们每个手上都画了一个数字。例如第i个小朋友的手上有个数字为j，那么就是在玩具中的前j个玩具中尽量的装在自己背包中（每个孩子的背包是一模一样的。），这些小朋友天资聪颖，他们肯定会尽量使自己背包装满，并且让背包里面的价值最大。<BR>当然，一个孩子装完玩具知道价值了以后就会把玩具放回原位。<BR>而每个孩子所得到玩具的最大价值就是他的身高了。<BR>当然，身高并不是我们这个题所要求的答案。<BR>【再插一句】也许很多童鞋们都做过"最长上升子序列"这道题吧....在本题中,我们求的也不是最长上升子序列.不过和这个很类似.<BR>首先我们把小朋友们按照其名字升序排成一个圆圈围在桌子旁坐着,就像这样：<BR><img src="/source/joyoi/tyvj-1299/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTI5OS9Qcm9ibGVtSW1nL3AxMjk5LmpwZw==.jpg" border=0 align=middle><BR>&nbsp;&nbsp;（PS：&nbsp;每个小朋友旁边的数字是他的高度,不是名字）<BR>然后我们要求的就是"环状最长上升子序列".并且我们以小朋友们的身高作为值。<BR>&nbsp;&nbsp;&nbsp;&nbsp;也就是说,我们需要在环中任意一个人开始向某一个方向找最长上升子序列,直到没有一个点比目前的人高即可.<BR><BR><BR> 

 
 # 输入格式 
第一行为n，m，v。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;其中n为小朋友个数，m为玩具的个数，v为一个背包的体积。<BR>&nbsp;&nbsp;&nbsp;第二行中第i个数为小朋友i手掌上写的数字。(保证数字不超过maxlongint)<BR>&nbsp;&nbsp;&nbsp;第三行中第i个数表示第i个玩具的价值。(保证价值总和不超过maxlongint)<BR>&nbsp;&nbsp;&nbsp;第四行中第i个数表示第i个玩具的体积。(保证体积不超过maxlongint)<BR>&nbsp;&nbsp;&nbsp;&nbsp;以上数据保证每行数据用空格隔开。<BR><BR> 

 
 # 输出格式 
&nbsp;第一行要输出环形最长上升序列的长度。<BR>&nbsp;&nbsp;&nbsp;第二行要输出环形最长上升序列的方案，数据按照升序输出。<BR><BR> 

 
 # 提示 
【数据范围】<BR>&nbsp;&nbsp;&nbsp;&nbsp;对于30%的数据，0&lt;=N,M,V&lt;=400<BR>对于100%的数据，1&lt;=N,M,V&lt;=8,000<BR><BR> 
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
<tr><td>2 4 6
2 3
4 5 7 2
2 3 4 1

</td><td>2
9 11

</td></tr></table>
