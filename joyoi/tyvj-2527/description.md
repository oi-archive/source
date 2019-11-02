# 

 
 # 题目描述 
<p>
The cows have been sent on a mission through space to acquire a new<br>milking machine for their barn.  They are flying through a cluster<br>of stars containing N (1 <= N <= 50,000) planets, each with a trading<br>post.<br><br>The cows have determined which of K (1 <= K <= 1,000) types of<br>objects (numbered 1..K) each planet in the cluster desires, and<br>which products they have to trade. No planet has developed currency,<br>so they work under the barter system: all trades consist of each<br>party trading exactly one object (presumably of different types).<br><br>The cows start from Earth with a canister of high quality hay (item<br>1), and they desire a new milking machine (item K). Help them find<br>the best way to make a series of trades at the planets in the cluster<br>to get item K.  If this task is impossible, output -1.<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers, N and K.<br><br>* Lines 2..N+1: Line i+1 contains two space-separated integers, a_i<br>        and b_i respectively, that are planet i's trading trading<br>        products. The planet will give item b_i in order to receive<br>        item a_i.<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: One more than the minimum number of trades to get the<br>        milking machine which is item K (or -1 if the cows cannot<br>        obtain item K).<br></p> 
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
<tr><td>6 5   //6个星球,希望得到5,开始时你手中有1号货物.
1 3   //1号星球,希望得到1号货物,将给你3号货物
3 2
2 3
3 1
2 5
5 4
</td><td>4


OUTPUT DETAILS:

The cows possess 4 objects in total: first they trade object 1 for
object 3, then object 3 for object 2, then object 2 for object 5.</td></tr></table>
