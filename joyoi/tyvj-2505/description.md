# 

 
 # 题目描述 
<p>
Farmer John has been informed of the location of a fugitive cow and<br>wants to catch her immediately. He starts at a point N (0 <= N <=<br>100,000) on a number line and the cow is at a point K (0 <= K <=<br>100,000) on the same number line. Farmer John has two modes of<br>transportation: walking and teleporting.<br><br>    * Walking: FJ can move from any point X to the points X-1 or<br>      X+1 in a single minute<br><br>    * Teleporting: FJ can move from any point X to the point 2*X<br>      in a single minute.<br><br>If the cow, unaware of its pursuit, does not move at all, how long<br>does it take for Farmer John to retrieve it?<br><br>从N点到K点,每次可以有两种选择<br>1:从X点到X-1或者X+1<br>2:从X点到2*X点.<br>问走多少点可以从N到K.</p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: N and K<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: The least amount of time, in minutes, it takes for Farmer<br>        John to catch the fugitive cow.<br><br></p> 
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
<tr><td>5 17
Farmer John starts at point 5 and the fugitive cow is at point 17.

</td><td>4

OUTPUT DETAILS:

The fastest way for Farmer John to reach the fugitive cow is to
move along the following path: 5-10-9-18-17, which takes 4 minutes.</td></tr></table>
