
# Content

Hys likes to play with Hsy. Although poor Hys cannot play ping-pong, he follows Hsy when she goes to play ping-pong with her roommates every Sunday. In the ping-pong stadium, each girl plays with every other once, and the one who lose will have to treat the winner an ice-cream even when they are on diet. The results of games are related to the state of girls, which can be represented by a value $S$. The state of girls may differ in different weeks. The better state a girl has, the greater her $S$ is, also, the higher win probability she has. The win probability of a girl whose state value is $S\_i$ is $\frac{S\_i}{S\_i + S\_j}$ when she competes with the other girl with $S\_j$. Girls count the number they win or lose and buy ice-cream at the end of that day before they return home.

After being an onlooker for several weeks, Hys came up with a good idea to participate in the games. On the way to ping-pong stadium, he would choose one from the $K$ girls (including Hsy) to be his `trustee`. Then in each game the girl Hys chooses plays, he would win or lose ice-cream as the girl would. Hys can alter his choice in the next week. However, he has to give the girl he chose last time $P$ ice-cream to show his apologies. 

Note that buying ice-cream is equivalent to receiving ice-cream of negative number. If the number of ice-cream Hys gets is negative, he has to pay them himself. Otherwise, Hys would give all ice-cream he gets to Hsy to show his heart.

Hys wants to find a strategy to choose `trustee` so that the expected number of ice-cream Hsy gets in $N$ weeks is maximized.

# Standard Input

The first line of the input is $T$ (no more than $1000$), which stands for the number of test cases you need to solve. 

Each test case begins with $N$, $K$, $P$. $K$ is the number of girls. $2\leq K \leq 4$, $1\leq N\leq 52$, $0\leq P\leq 5$. 

The next $N$ lines give $K$ positive integers not bigger than $100$. The $j\_{th}$ number on the $i\_{th}$ line is the state value of the $j\_{th}$ girl in the $i\_{th}$ week. Note that Hsy is the first girl.

# Standard Output

Please output the greatest expect number of ice-cream Hsy gets for each test case. The result should be printed accurately rounded to three decimals.

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
1 2 2
60 40
2 4 2
90 80 70 60
85 80 95 80
10 3 0
41 21 1
79 12 11
91 56 93
99 43 23
56 5 86
55 13 34
26 48 21
1 54 85
48 81 29
59 31 51
10 3 5
41 21 1
79 12 11
91 56 93
99 43 23
56 5 86
55 13 34
26 48 21
1 54 85
48 81 29
59 31 51</td><td>0.800
4.154
12.442
35.546</td></tr></table>


# Constraints



# Note

Assume $P=2$ and HYS chose girl-A in the $1\_{st}$ week and girl-B(another girl) in the $2\_{nd}$ week.If HYS win $1$ ice-cream in the $2\_{nd}$ week,then he will give HSY $1$ ice-cream and give girl-A $2$ ice-cream.

# Source


