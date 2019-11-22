# 

 
 # 题目描述 
<p>
The N (2 <= N <= 10,000) cows are so excited: it's prom night! They<br>are dressed in their finest gowns, complete with corsages and new<br>shoes. They know that tonight they will each try to perform the<br>Round Dance.<br><br>Only cows can perform the Round Dance which requires a set of ropes<br>and a circular stock tank. To begin, the cows line up around a<br>circular stock tank and number themselves in clockwise order<br>consecutively from 1..N. Each cow faces the tank so she can see the<br>other dancers.<br><br>They then acquire a total of M (2 <= M <= 50,000) ropes all of which<br>are distributed to the cows who hold them in their hooves.  Each<br>cow hopes to be given one or more ropes to hold in both her left<br>and right hooves; some cows might be disappointed.<br><br>For the Round Dance to succeed for any given cow (say, Bessie), the<br>ropes that she holds must be configured just right. To know if<br>Bessie's dance is successful, one must examine the set of cows<br>holding the other ends of her ropes (if she has any), along with<br>the cows holding the other ends of any ropes they hold, etc.  When<br>Bessie dances clockwise around the tank, she must instantly pull<br>all the other cows in her group around clockwise, too. Likewise,<br>if she dances the other way, she must instantly pull the entire<br>group counterclockwise (anti-clockwise in British English).<br><br>Of course, if the ropes are not properly distributed then a set of<br>cows might not form a proper dance group and thus can not succeed<br>at the Round Dance. One way this happens is when only one rope<br>connects two cows. One cow could pull the other in one direction,<br>but could not pull the other direction (since pushing ropes is<br>well-known to be fruitless). Note that the cows must Dance in<br>lock-step: a dangling cow (perhaps with just one rope) that is<br>eventually pulled along disqualifies a group from properly performing<br>the Round Dance since she is not immediately pulled into lockstep<br>with the rest.<br><br>Given the ropes and their distribution to cows, how many groups of<br>cows can properly perform the Round Dance? Note that a set of ropes<br>and cows might wrap many times around the stock tank.<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: N and M<br><br>* Lines 2..M+1: Each line contains two space-separated integers A and<br>        B that describe a rope from cow A to cow B in the clockwise<br>        direction.<br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: A single line with a single integer that is the number of<br>        groups successfully dancing the Round Dance.<br></p> 
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
<tr><td>5 4
2 4
3 5
1 2
4 1

INPUT DETAILS:

ASCII art for Round Dancing is challenging. Nevertheless, here is a
representation of the cows around the stock tank:
       _1___
      /**** \
   5 /****** 2
  / /**TANK**|
  \ \********/
   \ \******/  3
    \ 4____/  /
     \_______/

</td><td>
1

OUTPUT DETAILS:

Cows 1, 2, and 4 are properly connected and form a complete Round
Dance group. Cows 3 and 5 don't have the second rope they'd need
to be able to pull both ways, thus they can not properly perform the
Round Dance.</td></tr></table>
