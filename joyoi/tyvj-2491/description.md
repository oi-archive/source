# 

 
 # 题目描述 
<p>
Farmer John's N (1 <= N <= 50,000) cows (numbered 1..N) are planning<br>to run away and join the circus.  Their hoofed feet prevent them<br>from tightrope walking and swinging from the trapeze (and their<br>last attempt at firing a cow out of a cannon met with a dismal<br>failure). Thus, they have decided to practice performing acrobatic<br>stunts.<br><br>The cows aren't terribly creative and have only come up with one<br>acrobatic stunt: standing on top of each other to form a vertical<br>stack of some height.  The cows are trying to figure out the order<br>in which they should arrange themselves within this stack.<br><br>Each of the N cows has an associated weight (1 <= W_i <= 10,000)<br>and strength (1 <= S_i <= 1,000,000,000).  The risk of a cow<br>collapsing is equal to the combined weight of all cows on top of<br>her (not including her own weight, of course) minus her strength<br>(so that a stronger cow has a lower risk).  Your task is to determine<br>an ordering of the cows that minimizes the greatest risk of collapse<br>for any of the cows.<br><br><br>//有三个头牛，下面三行二个数分别代表其体重及力量<br>//它们玩叠罗汉的游戏，每个牛的危险值等于它上面的牛的体重总和减去它的力量值，因为它要扛起上面所有的牛嘛.<br>//求所有方案中危险值最大的最小<br><br><br></p> 

 
 # 输入格式 
<p>
* Line 1: A single line with the integer N.<br><br>* Lines 2..N+1: Line i+1 describes cow i with two space-separated<br>        integers, W_i and S_i.<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: A single integer, giving the largest risk of all the cows in<br>        any optimal ordering that minimizes the risk.<br></p> 
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
10 3
2 5
3 3
</td><td>2

OUTPUT DETAILS:

Put the cow with weight 10 on the bottom. She will carry the other
two cows, so the risk of her collapsing is 2+3-3=2. The other cows
have lower risk of collapsing.</td></tr></table>
