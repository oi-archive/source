
# Content

There are $n$ light(s) in a row.These lights are numbered $1$ to $n$ from left to right.One of the lights are switched on.I wants to switch all the lights on. 
At each step I can switch a light on(this light should be switched off at that moment)if there's at least one "very close" light which is already switched on.
More exactly: when No.$i$ light(this light is switched on now),No.$j$ light can be switched on(this light is switched off now) if and only if $|i-j|<=2$.
I knows the initial state of lights and I wonder how many different ways there exist to switch all the lights on.

Please find the required number of ways modulo $1000000007 (10^9+7)$.

# Standard Input

The first line of the input contains two integers $n$ and $m$ where $n$ is the number of lights in the sequence and No.$m$ light are initially switched on,$(1<=n<=1000,1<=m<=n)$.

# Standard Output

In the only line of the output print the number of different possible ways to switch on all the lights modulo $1000000007 (10^9+7)$.

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
<tr><td>3 1</td><td>2</td></tr></table>


# Constraints



# Note



# Source


