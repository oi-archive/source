# 

 
 # 题目描述 
<p>
　　一条街的一边有几座房子。因为环保原因居民想要在路边种些树。路边的地区被分割成块，并被编号成1..N。每个部分为一个单位尺寸大小并最多可种一棵树。每个居民想在门前种些树并指定了三个号码B，E，T。这三个数表示该居民想在B和E之间最少种T棵树。当然，B≤E，居民必须记住在指定区不能种多于区域地块数的树，所以T≤E-B+l。居民们想种树的各自区域可以交叉。你的任务是求出能满足所有要求的最少的树的数量。

 
 # 输入格式 
<p>
　　第一行包含数据N，区域的个数(0<N≤30000)；

 
 # 输出格式 
<p>
　　输出文件一行，树的数目。</p> 

 
 # 提示 
<p>
　　样例的具体方案：1 4 5 8 9
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
<tr><td>9						
4						
1 4 2
4 6 2
8 9 2
3 5 2
</td><td>5</td></tr></table>