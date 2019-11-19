# 

 
 # 题目描述 
某天WJMZBMR学习了一个神奇的算法：树的点分治！<BR>这个算法的核心是这样的：<BR>消耗时间=0<BR>Solve(树&nbsp;a)<BR>	消耗时间&nbsp;+=&nbsp;a&nbsp;的&nbsp;大小<BR>	如果&nbsp;a&nbsp;中&nbsp;只有&nbsp;1&nbsp;个点<BR>		退出<BR>	否则在a中选一个点x，在a中删除点x<BR>	那么a变成了几个小一点的树，对每个小树递归调用Solve<BR>我们注意到的这个算法的时间复杂度跟选择的点x是密切相关的。<BR>如果x是树的重心，那么时间复杂度就是O(nlogn)<BR>但是由于WJMZBMR比较傻逼，他决定随机在a中选择一个点作为x！<BR>Sevenkplus告诉他这样做的最坏复杂度是O(n^2)<BR>但是WJMZBMR就是不信&gt;_&lt;。。。<BR>于是Sevenkplus花了几分钟写了一个程序证明了这一点。。。你也试试看吧^_^<BR>现在给你一颗树，你能告诉WJMZBMR他的傻逼算法需要的期望消耗时间吗？（消耗时间按在Solve里面的那个为标准） 

 
 # 输入格式 
第一行一个整数n，表示树的大小<BR>接下来n-1行每行两个数a,b，表示a和b之间有一条边<BR>注意点是从0开始标号的 

 
 # 输出格式 
一行一个浮点数表示答案<BR>四舍五入到小数点后4位<BR>如果害怕精度跪建议用long&nbsp;double或者extended 

 
 # 提示 
其实跟点分治没什么大关系呢。。。真的吗？ 
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
0 1
1 2</td><td>5.6667</td></tr></table>
