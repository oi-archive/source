
# Content

The gentleman Inco Gnito is attempting to infiltrate the Entership Starprise, and has been tasked with assisting the chief engineer Forgie with repairs. Forgie has brought with him some tools, and will repeatedly ask Inco for a subset of these. Only when Inco has placed exactly the correct tools in front of Forgie will he take them, utilise them and return them to Inco. This process will repeat itself until the repairs are complete. This sounds simple enough, but the problem is that Inco has no idea what any of the tools are called! Luckily Inco is a quick study, and he is thus able to use all the information of his previous errors and successes when trying to find a new subset of tools. On the other hand, if he is very unlucky, he could be stuck with Forgie for a very very long time, and possibly be revealed as a spy.

Calculate how many different subsets of tools Inco will have to offer Forgie in total,assuming he has the least possible amount of luck during this assignment.

# Standard Input

The first line of the input consists of a single integer $T$, the number of test cases. Each test case begins with a line containing two integers $N$, the number of tools, and $K$, the number of different subsets Forgie will ask for. The next line contains $N$ space-separated tool names consisting of up to $25$ lowercase letters `a`-`z` and `-`. Then follow $K$ lines containing an integer $M$ and then the names of $M$ different tools as above. Tool names are unique within a test case, and the tools for different test cases are not related.

# Standard Output

For each test case, output the maximal number of subsets Inco might have to oer Forgie,assuming he learns all he can during the assignment. The answer can be a very large number, so output the result modulo $2^{31}-1$.

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
3 3
tricorder quantum-flux-regulator hyperspanner
1 tricorder
1 quantum-flux-regulator
1 hyperspanner
5 4
pulse-drill phase-coil-resonator duct-tape crowbar optronic-coupler
2 phase-coil-resonator optronic-coupler
2 pulse-drill optronic-coupler
1 crowbar
1 duct-tape</td><td>6
19</td></tr></table>


# Constraints



# Note

$0 < T \leq 100$

$0 < N \leq 1000$

$0 < K \leq 100$

$0 < M \leq N$

# Source


