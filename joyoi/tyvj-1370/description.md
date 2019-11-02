# 

 
 # 题目背景 
占卜大典在占卜哥lyd和宠物猫神zsw95的主持下开始了。 

 
 # 题目描述 
　武则天举行占卜典礼，有n个大臣站成一列，标号从前到后一次为1,2,...,n-1,n.&nbsp;<BR>　　过了很久很久，正当台上的大师在自我陶醉地占卜时，台下的大臣们早已不耐烦了。于是，他们很多人都想聊天消磨时间。&nbsp;但是，渐渐地他们发现，若i想和j聊天，如果i和j之间有k正在说话，那么i和j的谈话就会被k干扰，从而无法聊天。<BR>&nbsp;&nbsp;现在已知有m对大臣想要聊天，要你求出[最多有多少人可以不受干扰的聊天]以及[这些人中(每两人聊天中间&nbsp;&nbsp;间隔的人数&nbsp;&nbsp;的总和)的最小值]<BR>(注意：每个人同时最多只能和一个人聊天，不能三心二意，但可以渴望和多个人聊天)<BR> 

 
 # 输入格式 
第一行，两个正整数n和m，分别表示大臣个数与想要讲话的人的对数<BR>接下来m行，每行两个数a和b，表示a和b渴望聊天<BR><BR>n&lt;=300(官僚机构当然不会太冗余啦)<BR>m&lt;=(n-1)*n/2<BR>1&lt;=a,b&lt;=n<BR> 

 
 # 输出格式 
两个整数，分别表示[最多可以聊天的人数s]和[这s个人中(每&nbsp;两人&nbsp;聊天&nbsp;中间&nbsp;间隔的&nbsp;人数的&nbsp;总和)的最小值]<BR> 

 
 # 提示 
By&nbsp;lydliyudong 
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
<tr><td>9 5
1 4
1 2
3 6
5 7
8 9</td><td>6 1</td></tr></table>
