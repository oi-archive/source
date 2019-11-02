# 

 
 # 题目描述 
<p>
最近Kfc新开了个KFC，该KFC提供N种食物，分别用1-N给这些食物编号，食物的价格与其编号有关，满足第K种食物的价格为2^(K-1)，例如：<br>食物的编号    1   2   3   4   5   6   7   8   9    10……<br>价格          1   2   4   8   16  32  64  128 256  512 ……<br>每位顾客最多可以选择L种食物，且每种食物仅一份。<br>当顾客选择食物时，他会说：我要第M便宜的食物组合。<br>Kfc的工作就是计算第该食物组合的价格。<br>一样食物都不要也是一种组合，因此第1便宜的食物组合价格为0。<br></p> 

 
 # 输入格式 
<p>
一行，包含三个整数N (1<=N<=30),，L (1<=L<=N)，M，用一个空格隔开。数据保证存在第M便宜的食品组合。</p> 

 
 # 输出格式 
<p>
一行，包含一个整数P，P为第M便宜的食品组合的价格。</p> 

 
 # 提示 
<p>
对于20%的数据，N<20；<br>对于40%的数据，M<1000000；<br></p> 
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
<tr><td>5 3 19</td><td>19</td></tr></table>
