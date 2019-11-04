# 

 
 # 题目描述 
<p>
在遥远的东方，有一个神秘的民族，自称Y族。他们世代居住在水面上，奉龙王为神。每逢重大庆典，

 
 # 输入格式 
<p>
第一行包含两个用空格隔开的整数N、M，分别表示岔口和河道的数目，岔口从1到N编号。

 
 # 输出格式 
<p>
第一行包含一个整数K，表示最多能选取的祭祀点的个数。

 
 # 提示 
<p>
对于每个测试点：
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
<tr><td>4 4
1 2
3 4
3 2
4 2
</td><td>2

【样例说明】
在样例给出的水系中，不存在一种方法能够选择三个或者三个以上的祭祀点。包含两个祭祀点的测试点的方案有两种：
选择岔口1与岔口3（如样例输出第二行），选择岔口1与岔口4。
水流可以从任意岔口流至岔口2。如果在岔口2建立祭祀点，那么任意其他岔口都不能建立祭祀点
但是在最优的一种祭祀点的选取方案中我们可以建立两个祭祀点，所以岔口2不能建立祭祀点。对于其他岔口
至少存在一个最优方案选择该岔口为祭祀点，所以输出为1011。