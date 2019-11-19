# 

 
 # 题目描述 
<p>
N (1 <= N <= 50,000) cows conveniently numbered 1..N are driving<br>in separate cars along a highway in Cowtopia. Cow i can drive in<br>any of M different high lanes (1 <= M <= N) and can travel at a<br>maximum speed of S_i (1 <= S_i <= 1,000,000) km/hour.<br><br>After their other bad driving experience, the cows hate collisions<br>and take extraordinary measures to avoid them. On this highway, cow<br>i reduces its speed by D (0 <= D <= 5,000) km/hour for each cow in<br>front of it on the highway (though never below 0 km/hour). Thus,<br>if there are K cows in front of cow i, the cow will travel at a<br>speed of max[S_i - D * K, 0]. While a cow might actually travel<br>faster than a cow directly in front of it, the cows are spaced far<br>enough apart so crashes will not occur once cows slow down as<br>described,<br><br>Cowtopia has a minimum speed law which requires everyone on the<br>highway to travel at a a minimum speed of L (1 <= L <= 1,000,000)<br>km/hour so sometimes some of the cows will be unable to take the<br>highway if they follow the rules above. Write a program that will<br>find the maximum number of cows that can drive on the highway while<br>obeying the minimum speed limit law.<br></p> 

 
 # 输入格式 
<p>
* Line 1: Four space-separated integers: N, M, D, and L<br><br>* Lines 2..N+1: Line i+1 describes cow i's initial speed with a single<br>        integer: S_i<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: A single integer representing the maximum number of cows<br>        that can use the highway<br><br></p> 
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
<tr><td>3 1 1 5//三头牛开车过一个通道.当一个牛进入通道时，它的速度V会变成V-D*X(X代表在它前面有多少牛),它减速后，速度不能小于L
5
7
5

INPUT DETAILS:

There are three cows with one lane to drive on, a speed decrease
of 1, and a minimum speed limit of 5.

</td><td>2

OUTPUT DETAILS:

Two cows are possible, by putting either cow with speed 5 first and the cow
with speed 7 second.
</td></tr></table>
