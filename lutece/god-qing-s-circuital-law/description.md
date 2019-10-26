
# Content

As we all know,God Qing is a very powerful ACMer. She very like junior sister apprentice,but in UESTC-ACM team,there is no junior sister apprentice,we can use a mathematical formula to express it.

<center>![title](/source/lutece/god-qing-s-circuital-law/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTI3My8yMDE1MTIxNzIyMzQxNTMzNDEwLnBuZw==.png)</center>

  But God Qing is a life winner , she has many beautiful girls,every girl has its BeautifulValue V ,and he want to take the most beautiful girl among all girls. For every girl,if God Qing chooses her,she can get a value called Life-Winner Point. We can use a mathematical formula to express it.

 
<center>$LifeWinnerPoint = HandsomeValue * BeautifulValue$</center>


  When other people who come from UESTC-ACM team(such as Liao772002,Final-Pan,Final-Zhu and so on) know God Qing want to choose the most beautiful girl,they can't stand it! ,They also want  a girl,for every person,he/she has its own HandsomeValue P. But God Qing wants to make her Life-Winner Point most,so she wants you to tell her there are how many ways can GodQing get the most Life-Winner Point. 
 
   In general. Thre are $N$ competitors come from UESTC-ACM team(God Qing's ID is always $1$) and $N$ Girls, for every competitor,he/she has a HandsomeValue $P[i]$ , for every girl , she has a BeatuifulValue $V[i]$,every competitor can only choose a girl,and every girl can be only chose once. you should calculate there are how many ways that make GodQing get the most Life-Winner Point. (God Qing’s Life-Winner Point strictly greater than any other competitors).
 
  Because the answer can be very large,you only need to print the answer modulo $10^9 + 7$.

# Standard Input

Line 1: an integet $N$(the number of competitors and girls).

Line 2: $N$ numbers $p[i]$(the HandsomeValue of every competitor)

Line 3: $N$ numbers $v[i]$(the BeautifulValue of every girl).

$1 <= N <= 100$, $1 <= p[i] <= 10^6$ , $1 <= v[i] <= 10^6$.

# Standard Output

the number of ways that GodQing can get the most Life-Winner Point.

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>4
5 8 4 8
19 40 25 20</td><td>2</td></tr></table>


# Constraints



# Note

Valid assignment #1: (5,40), (8,19), (4,25), (8,20).

Valid assignment #2: (5,40), (8,20), (4,25), (8,19).

In assignment #1, the Life-Winner Point of God Qing  is 5 x 40 = 200. The other three units have Life-Winner Point 8 x 19 = 152, 4 x 25 = 100, and 8 x 20 = 160. This is a valid assignment because the number 200 is strictly greater than each of the numbers 152, 100, and 160.

# Source


