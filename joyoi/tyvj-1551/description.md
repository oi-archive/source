# 

 
 # 题目描述 
问题描述<BR>&nbsp;&nbsp;&nbsp;&nbsp;milesian在你的帮助下（假设你把第一题AC了~）终于摆脱了女生的诱惑。但是女生们又缠上了另外一个帅哥——taring。但是taring保持清醒的方式不同，他会选择同时和所有女生聊天。这时，所有女生，还有taring，都站在牛顿广场上。且这种诱惑能量，是一个向量。满足向量定理。这个力为Fi，现在taring，站在高台上，希望找一个点，使他所受的诱惑能量和（向量和）为0。注意，他可以选择和某一个点的女生相吻在一起。这时他所受的这个女生的诱惑能量为0（因为女生被吻的时候，头脑是一片空白）。求这个点的横纵坐标。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;这个问题的化简：给定一个2维平面,平面上有N个村庄,每个村庄有f[i]个人,你需要选择一个地方建造医院,使得所有人到医院的总距离最小 

 
 # 输入格式 
&nbsp;&nbsp;第一行为一个正整数N，表示女生个数<BR>&nbsp;&nbsp;以下N行，每行有三个整数Xi，Yi，Fi。分别表示第i个女生的横坐标，纵坐标，能量的大小<BR>&nbsp;&nbsp;(0&lt;N&lt;=1000,-1000&lt;=XI,YI&lt;=1000,sum(Fi)&lt;=maxlongint) 

 
 # 输出格式 
两个实数，为帮taring选择的横坐标和纵坐标（保留小数点后两位）<BR>保证输出答案唯一 

 
 # 提示 
N&lt;=1000;-1000&lt;=xi，yi&lt;=1000<BR>fi不超过maxlongint<BR>并且保证标量和不超过maxlongint 
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
<tr><td>4
0 0 10
3 0 10
0 3 10
1 1 1</td><td>0.74 0.74</td></tr></table>
