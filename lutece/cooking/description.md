
# Content

Potter needs to cook $n$ pieces of beef. Cooking a piece of beef needs $m$ steps and each step takes $t$ minutes. It's not necessary to cook a piece of beef continueously, which means after finishing one step, he can set the beef aside and cook another one. Potter is a skilled cook that he can deal with at most $k$ **different** pieces of beef at the same time. 

Potter want to finish it as soon as possible. Please help him calculate how long will it take to finish cooking ?

# Standard Input

$n,m,k,t$

# Standard Output

An integer $T$, indicating that Potter has to spend at least $T$ minutes on cooking.

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
<tr><td>3 2 2 3</td><td>9</td></tr></table>


# Constraints

$1≤n,m,k,t≤100$

# Note

n=3 m=2 k=2 t=3

At the beginning : (0,0,0)

3min to deal with the first and the second : (1,1,0)

3min to deal with the first and the third : (2,1,1)

3min to deal with the second and the third : (2,2,2)

It takes 9 min totally.

# Source


