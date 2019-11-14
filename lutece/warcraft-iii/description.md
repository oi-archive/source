
# Content

Elfness is a crazy player of a famous game, WarCraft III.He not only play solo but also Dota.

Now,an idea comes into his mind,he wants to play dota using the $24$ heroes in Solo instead of $101$ heroes in original Dota.In order to win the game, Elfness wants to choose $5$ heroes so that he can get a most powerful battle array. 

As we all know, each hero of these $24$ heroes has an elementary ability value,and because of some relationships, there is another ability value between every two heroes. That is, if we choose these two heroes we can get this additional value.

With these complicated rules, Elfness thinks it is hard to choose the best battle array by himself, so he asks you, a good programmer, to help him write a program to choose $5$ heroes.

# Standard Input

There is only one integer $T$($T\leq 10$) on the first line, which indicates the number of test cases.

At the first line of each test case, there is one integer $N$($5\leq n\leq 24$) indicates the number of heroes you can choose in this case. Then one line followed, this line contains $N$ strings, separated by one space, where each string's length is less than $20$.The $i\_{th}$ string is the name of the $i\_{th}$ hero. Then one line followed, this line contains $N$ nonnegative integers,each interger is less than $10^6$.The $i\_{th}$ integer is the elementary ability value of the $i\_{th}$ hero. Then $n$ lines followed, each line will have exactly $n$ nonnegative integers, and these $n\times n$ numbers represent an matrix $A$ means if we choose $i\_{th}$ hero and $j\_{th}$ hero,we can get an additional ability value of $2\times A\_{i,j}$. Of course, $A\_{i,i}=0$ and $A\_{i,j}=A\_{j,i}$.

# Standard Output

For each test case, you should output one line. First, output `Case #C: `, $C$ means the number of the test case which is from $1$ to $T$. Then, output an integer indicates the maximal total value you can get after choosing $5$ heroes.

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
<tr><td>2
5
Lich Archmage Firelord Farseer Warden
5 4 4 5 6
0 3 3 3 4
3 0 4 4 4
3 4 0 5 2
3 4 5 0 3
4 4 2 3 0
6
DeathKnight DemonHunter Paladin DarkRanger KeeperofGrove BladeMaster
4 5 3 3 3 5
0 3 4 5 3 3
3 0 4 3 5 5
4 4 0 3 4 5
5 3 3 0 3 3
3 5 4 3 0 5
3 5 5 3 5 0</td><td>Case #1: 94
Case #2: 102</td></tr></table>


# Constraints



# Note

In the second sample, we can choose these $5$ heroes: DeathKnight, DemonHunter, Paladin, KeeperofGrove, BladeMaster. Then,we get elementary values of $5$ heroes: $4+5+3+3+5=20$. And, we also get additional values: $2\times (a\_{1,2}+a\_{1,3}+a\_{1,5}+a\_{1,6}+a\_{2,3}+a\_{2,5}+a\_{2,6}+a\_{3,5}+a\_{3,6}+a\_{5,6})=2\times (3+4+3+3+4+5+5+4+5+5)=82$.
So, total value is $102$ and this value is maximal.

# Source


