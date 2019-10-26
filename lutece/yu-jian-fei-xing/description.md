
# Content

After beating Hierarch of Baiyue, Xiaoyao went back to his home (Shengyu Cun). And every kid in the country thought the skill "Yu Jian Fei Xing"（御剑飞行） is very cool, so they often asked Xiaoyao flying above the clouds with them.

Today, several kids want to fly to their own favourite place from their home. But the lazy Xiaoyao tell them: "I will just stop at one certain place during my flying, and I will minimize the total cost of travelling without flying." 

We assume that all of the places in this problem are lying on a same line, and the places are labeled with $1,2,3,\cdots,N-1$ and the home of Xiaoyao and the kids is always labeled with $0$. Given the cost of travelling without flying between every pair of adjacent place, can you determine the total cost of those kids?

# Standard Input

The first line of the input contains a single integer $T$($T\leq 50$), indicates there are $T$ test cases.

For each test case, there are four lines. The first line contains a single integer $N$($4\leq N\leq 100000$), indicates there are $N$ places in this world.

Then, $N-1$ integers in a line, indicates the $cost$ of travelling without flying between every pair of adjacent place($1\leq cost\leq 1000$). For example, the first integer is the cost of travelling without flying between their home and the $1\_{st}$ place, and the second integer is the cost of travelling without flying between the $1\_{st}$ place and the $2\_{nd}$ place.

Then, a line contains a single integer $M$($1\leq M\leq 100000$), indicates there are $M$ kids will fly with Xiaoyao.

The last line contains $M$ integers $X\_i$($1\leq X\_i\leq N-1$), each $X\_i$ indicates the favourite place for $i\_{th}$ kid.

# Standard Output

For each test case, first output `Case #C: `, $C$ means the number of the test case which is counted from $1$ to $T$.

Then output the answer, the minimal total cost of travelling without flying of those kids.

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
4
1 3 2
5
1 2 3 2 2 
5
3 1 2 4
5
2 3 4 4 3</td><td>Case #1: 5
Case #2: 10</td></tr></table>


# Constraints



# Note

1. Remeber that the stop is at one certain place except their home. That is to say, the place $1,2,\cdots, N-1$ are potential stop.
2. If someone want to travel without flying from $S$ to $T$($S<T$), he/she will cost the summation of energy needed for each segment between $S$ and $T$ such as $S$ to $S+1$, $S+1$ to $S+2$.
  * Explanation: For Sample $1$, Xiaoyao will stop at the $2\_{nd}$ place, and the $3$ kids who want to go to the $2\_{nd}$ place will cost $0$, and the kid who want to $1\_{st}$ place will cost $3$ and the kid who want to $3\_{rd}$ place will cost $2$. So total cost is $5$, and it's minimal. For Sample $2$, Xiaoyao will stop at the $3\_{rd}$ place.
3. Huge input, recommand use `scanf` instead of `cin` in C++.

# Source


