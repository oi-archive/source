
# Content

As we all know, LRZ is a very cute and hard-working girl. Every morning, LRZ will review her work finished in the previous days and she will only consider the last two days. 


We define $f(n)$ as the workload of the $nth$ day. LRZ will be pleased with the work she finished at the $(n-1)th$ day and she will finish $3$ times workload of the $(n-1)th$ day at the $nth$ day. 

Besides she will be dissatisfied of the work she finished at the $(n-2)th$ day just because LRZ improves herself day by day.Therefore LRZ will finished the workload of the $(n-2)th$ day less at the nth day. 

In other words, the workload LRZ will finish at the nth day is $f(n)=3f(n-1)-f(n-2),n\ge 3$. And we can define $f(1)=1,f(2)=2$.

LRZ will get happy point from her workload, we define $h(n)$ as her happy point at the $nth$ day, and we know

$$h(n)=f(n)^k$$

Now, you need to calculate the total happy points $S$ from the first day to the $nth$ day.

$$S=\sum_{i=1}^n h(n)$$

# Standard Input

Two integers $n,k$ ,$1\le n\le 1000000000$, $1\le k\le 1000000$

# Standard Output

You should output the $S$, the answer may be very large, so you should output $S \bmod 1000000009$

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
<tr><td>3 1
</td><td>8</td></tr><tr><td>3 2</td><td>30</td></tr></table>


# Constraints



# Note



# Source


