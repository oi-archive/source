
# Content

Zplinti1 is a Grocery shopkeeper in Lemuria. His shop provides home delivery service, that is, when someone needs, he can always deliver the goods to their houses.

The Country of Lemuria consists of n islands, some of the islands are connected by bridges. So, zplinti1 needs to pass the bridges to send the goods using his little truck.

But there is a little problem: different bridges can stand different amount of loads. For example, if the bridge connecting Island $A$ and Island $B$ can stand at most $5$ tons’ weight, and bridge connecting Island $B$ and $C$ can stand at most $4$, then zplinti1 can’t delivery $5$ tons of goods at once from $A$ to $C$.

Realizing the problem, zplinti1 calls kennethsnow, one of the staffs in his shop, to investigate the issue. Zplinti1 wants to know, between any two islands $u$ and $v$, what is the maximum weight of goods he can delivery, satisfying no matter what delivery paths he chooses, there will be no danger of overload. Note that zplinti1 always chooses simple paths, that is , he will never pass a same island twice!

Kennethsnow gives zplinti1 an $n\times n$ array, say array $G$. The number $G\_{ij}$ is the answer between Island $i$ and Island $j$, if two islands are not connected, the answer will be $-1$.

Zplinti1 do not know the actual loads each bridge can stand, still he doubt that kennethsnow is lying. He wonders whether kennethsnow’s answer can be true.

# Standard Input

The first line of input contains a number $T$($T\leq 30$), indicating the number of test cases. 

For each case, there are two numbers $n$ and $m$ which is the number of islands and bridges in Lemuria($1\leq n \leq 1,000$,$0\leq m \leq 300,000$). The next $m$ lines come, each with two integers $u$ and $v$, meaning there is a bridge between Island $u$ and Island $v$($0\leq u,v < n$). Then $n$ lines are given, each with $n$ numbers, meaning the $n\times n$ array $G$ kennethsnow provides. You can asume that $G\_{ii}$ always equals $0$.

# Standard Output

For each case, output `Case #i: ` first. ($i$ is the number of the test case, from $1$ to $T$). If kennethsnow is lying , output `No`, otherwise `Yes`.

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
<tr><td>3
4 5
0 1
0 2
0 3
1 2
1 3
0 5 5 5
5 0 5 5
5 5 0 4
5 5 4 0
4 4
0 1
0 2
1 2
1 3
0 4 4 4
4 0 4 5
4 4 0 4
4 5 4 0
4 2
0 1
1 2
0 3 3 -1
3 0 4 -1
3 4 0 -1
-1 -1 -1 0</td><td>Case #1: No
Case #2: Yes
Case #3: Yes</td></tr></table>


# Constraints



# Note



# Source


