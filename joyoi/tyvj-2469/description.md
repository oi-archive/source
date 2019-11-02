# 

 
 # 题目描述 
<p>
Farmer John and his herd of exotic dancing bovines have been <br>practicing for his new moosical, "The Street Cow Named Desire". At <br>one point in the middle of rehearsal, his cows are stacked on top <br>of each other in N (1 <= N <= 1,000) sets of 30, one cow standing <br>on the back of the other (they are quite amazing cows). Thus, the <br>pasture is dotted with both these stacks of 30 cows and also, in <br>separate locations, M (1 <= M <= 1,000) haystacks. Below is a sample <br>of one way they might be laid out: <br><br>8 ......... <br>7 ....CH.H. C = stack of 30 cows <br>6 ......... <br>5 ......... H = haystack <br>4 ..C.HH... <br>3 ......... <br>2 .....C.HH <br>1 ......... <br>123456789 <br><br>As the musical's conductor, Farmer John has four whistles with <br>various tones. One whistle commands the cow at the bottom of each <br>stack to move (along with all the stacked cows) one unit north, <br>another indicates a move to the south, one indicates a move to the <br>east, and a fourth to order a move to the west. <br><br>Any time the stack of cows enters a grid location with a haystack, <br>the cow on the top of the stack (even if the stack has height one) <br>will jump onto the haystack while the remaining cows move into the <br>same location as the haystack. Thus, if the bottom cow encounters <br>30 haystacks (perhaps different haystacks, perhaps not), the stack <br>of 30 cows is exhausted with all the cows standing on top of haystacks <br>(or standing on cows on haystacks). The sturdy haystacks can each <br>support an unlimited number of cows. <br><br>Farmer John glances across his pasture to Farmer Don's milking <br>facility to see, to his horror, a huge milk tank exploding and <br>unleashing a giant tidal wave of milk making its way toward the <br>performing cows! Since any cows on a haystack are safe, FJ must now <br>do what he can to save the lives of as many cows as possible using <br>what has turned from a simple dance routine into a lifesaving <br>technique. <br><br>Given the number of times K (1 <= K <= 30) farmer John can blow a <br>whistle until the wave of milk crashes over the pasture and also <br>the X_i, Y_i positions (1 <= X_i <= 1,000; 1 <= Y_i <= 1,000) of <br>the N stacks of cows and M haystacks (none of which currently has <br>any cows on it), report the greatest number of cows that can be <br>saved and find a sequence of whistle blows that does the job. The <br>sequence should be reported in terms of the four directions, 'E' <br>for east, 'N' for north, 'W' for west, 'S' for south. Among all <br>such sequences, farmer John wants the lexicographically least. <br>Initial locations of cows and haystacks will not share the same <br>coordinates in the input file. <br><br>Cows can be moved to any location, including ones outside the <br>pasture. <br>John有N摞高度为30的牛,N摞的牛看成一个整体，要移动的时候一起移动. <br>将移动到草堆所在的位置时，最上面那个牛就会跳到草堆上去. <br>现在给出M个草堆所在的位置，以及移动的次数K（K小于30) <br>问最多可移动多少头牛到草堆上去,并输出你每次移动的方向 <br><br><br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Three space-separated integers: N, M, and K <br>* Lines 2..N+1: Line i+1 describes the X,Y location of a stack of 30 <br>cows using two space-separated integers: X_i and Y_i <br>* Lines N+2..N+M+1: Line i+N+1 describes the X,Y location of a <br>haystack using two space-separated integers: X_i and Y_i <br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: A single integer that is the most number of cows that can be<br>        saved.<br>* Line 2: K characters, the lexicographically least sequence of<br>        commands FJ should issue to maximize the number of cows saved.<br></p> 
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
<tr><td>3 6 3 
3 4 
6 2 
5 7 
8 2 
9 2 
6 4 
5 4 
6 7 
8 7 


</td><td>Use the 'east' whistle three times, at which point the milk floods
the area.  Each haystack ends up saving 1 cow.

6 
EEE </td></tr></table>
