# 

 
 # 题目背景 
Tyvj最近全面招聘管理员，这是第二个故事，上一个请见《无聊的点击》。<BR>Admin经过了漫长的无聊的点击，终于下定决心登录coderspace查看。不看不要紧，一看吓一跳，那里边的回复有???条<BR>（某生:“到底是几条？”Admin:“我要是数的清看得完还用你编程序？？!”）。<BR>不只是有申请，还有一堆堆的占楼。。。所以Admin神牛决定请你编个程序来挑出一些回复给他看。<BR>（某生:“神牛你为什么不自己编呢？？”Admin:“Shut&nbsp;up！”） 

 
 # 题目描述 
Admin一共想花n时间看回复，coderspace一共有m条回复可供选择。回复分为“申请”和“占楼”。一条申请的重要度为2，一条占楼回复的重要度为1,每条回复需要一定的时间P去看。admin希望在看不超过n时间的情况下，使重要度总和最大。<BR><BR>对于40%的数据，0&lt;=n&lt;=100&nbsp;且n小数点后有两位小数，1&lt;=m&lt;=100<BR>对于100%的数据，0&lt;=n&lt;=10000且n小数点后有两位小数，1&lt;=p&lt;=100且p小数点后有两位小数，1&lt;=m&lt;=10000。 

 
 # 输入格式 
第一行可用时间n<BR>第二行回复总数m<BR>接下来m行&nbsp;每行两个数：所需时间P和重要度F<BR> 

 
 # 输出格式 
最大的重要度总和ans<BR> 

 
 # 提示 
By&nbsp;Lydliyudong<BR> 
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
<tr><td>47.13
4
17.11 2
11.48 1
18.42 2
30.01 2
</td><td>5</td></tr></table>
