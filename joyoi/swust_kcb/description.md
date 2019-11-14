# 问题描述
购房从银行贷了一笔款d，准备每月还款额为p，月利率为r，计算多少月能还清。计算还清月数的公式如下：
m=（log(p/(p-d*r))/log(1+r)

# 格式
## 输入
三个数d,p,r，以空格分隔。(d,p为整数，且200000<=d<=500000,1000<=p<=10000.r为实数，且0.005<=r<=0.02)

## 输出
一个数m(保留两位小数)

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
<tr><td>300000，6000，0.01</td><td>69.7</td></tr></table>
