# 

 
 # 题目描述 
<p>
<br>Bessie is out in the field and wants to get back to the barn to get<br>as much sleep as possible before Farmer John wakes her for the<br>morning milking. Bessie needs her beauty sleep, so she wants to get<br>back as quickly as possible.<br><br>Farmer John's field has N (2 <= N <= 1000) landmarks in it, uniquely<br>numbered 1..N. Landmark 1 is the barn; the apple tree grove in which<br>Bessie stands all day is landmark N.  Cows travel in the field using<br>T (1 <= T <= 2000) bidirectional cow-trails of various lengths<br>between the landmarks. Bessie is not confident of her navigation<br>ability, so she always stays on a trail from its start to its end<br>once she starts it.<br><br>Given the trails between the landmarks, determine the minimum<br>distance Bessie must walk to get back to the barn.  It is guaranteed<br>that some such route exists.<br><br></p> 

 
 # 输入格式 
<p>
<br>* Line 1: Two integers: T and N<br><br>* Lines 2..T+1: Each line describes a trail as three space-separated<br>        integers.  The first two integers are the landmarks between<br>        which the trail travels. The third integer is the length of<br>        the trail, range 1..100.<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: A single integer, the minimum distance that Bessie must<br>        travel to get from landmark N to landmark 1.<br><br></p> 
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
<tr><td>
5 5
1 2 20
2 3 30
3 4 20
4 5 20
1 5 100

INPUT DETAILS:

There are five landmarks.

</td><td>
90

OUTPUT DETAILS:

Bessie can get home by following trails 4, 3, 2, and 1.</td></tr></table>
