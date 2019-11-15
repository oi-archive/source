
# Content

Living in BUPT, you have to be accustomed to the crowded canteen. I hate the terrible feeling when stepping into the student canteen. The only thing which interests me is to count how many people are there in the canteen. Of course, this counting problem is too easy and naive to you. So let us consider a more complicated problem. Because of the flow of people stepping in and out, the number of people in the canteen is dynamic shifting. You task is to find the peak value of the number of people in the canteen at some moments.

To describe the problem more clearly, we define the triple $< s, e, n>$ to describe the group of people stepping in and out. Specifically, they separately represent the arriving moment, leaving moment, and the number of people in this group. Note that the given time interval of the group of people in the canteen is from $s$ to $e$, inclusive. That is, the people are considered exactly in the canteen at moment $s$, and they will stay there during $[s, e]$, while right after moment $e$ they would leave. You may take the samples below for more details.

# Standard Input

The first line of input is the number of test cases $T$ ($T\leq 100$).

In each test case, the first line consists of an integer $N$ ($0 < N\leq 10^4$), which indicates the number of groups. Then each of the next $N$ lines shows three integer in triple which has been defined above.($0\leq s\_i,e\_i\leq 10^5$, $0 < n\_i\leq 100$)

# Standard Output

For each test case, output only one integer which indicates the peak value of crowd.

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
2
0 2 1
1 4 1
3
1 3 2
3 5 1
2 4 1</td><td>2
4</td></tr></table>


# Constraints



# Note



# Source


