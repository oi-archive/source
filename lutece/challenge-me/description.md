
# Content

![title](/source/lutece/challenge-me/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzYyLzIwMTQwNDExMTM0MjIxNTEyMzEuanBn.jpg)

CC has a balance and some weights. But CC’s balance is so strange that it will keep balance whenever the left side is no more than Mg heavier or lighter than the right side. Now, CC wants to put all his weights on the balance, and each time he can choose an arbitrary one to put on the left side or right side as long as the one is legal, meaning that after which the balance should also keep balance. CC is wondering if he could successfully put all his weights on the balance. And as CC is an ACMer, he thinks that he can use greedy algorithm to solve this puzzle, so he wrote a program as follow.

```
bool used[110];
bool solve(int M, int N, int num[]) {
    for (int i = 0; i < N; i++) {
        used[i] = false;
    }
    for (int k = 0, w = 0; k < N; k++) {
        int idx = -1;
        for (int i = 0; i < N; i++) {
            if (!used[i] && w - num[i] >= -M
                    && (idx == -1 || num[idx] < num[i])) {
                idx = i;
            }
        }
        if (idx == -1) {
            return false;
        }
        used[idx] = true;
        if (w + num[idx] <= M) {
            w += num[idx];
        } else {
            w -= num[idx]
        }
        if (w < 0) {
            w = -w;
        }
    }
    return true;
}
```

I would like to explain some details about CC’s program here. Each time, CC chooses the heaviest one from all legal weights to put on the balance. If he could put it on the heavy side, he will do. Otherwise, he will put it on the lighter side. CC can’t prove his program is right, neither can he find counterexamples. He needs your help.

In this problem, CC will give some balance coefficients to you. Can you find a counterexample for him? A counterexample is legal while it consists of positive integers only. And among all counterexamples, you should choose the one has least number of weights. And if several counterexamples have a tie, you should choose the lexicographically smallest one. A counterexample $a\_1, a\_2, \cdots a\_N$, is lexicographically smaller than another one $b\_1, b\_2, \cdots b\_N$ while we sort them in nondecreasing order, and the first position $k$ from left to right where $a\_k \neq b\_k$, we have $a\_k < b\_k$.

# Standard Input

The first line of the input is an integer $T$ ($T\leq 50$), which stands for the number of test cases you need to solve.

Every test case is an integer $M$ ($0\leq M\leq 30$), meaning the balance coefficient of CC’s balance.

# Standard Output

For every test case, you should output `Case #k:` on a single line first, where $k$ indicates the case number and starts at $1$. If you can’t find a counterexample for CC, only output `NO` on a single line. Otherwise, you should output `YES` on a single line first, and then on the next line output the number of weights in your counterexample, and finally on the next several lines output weights in nondecreasing order, where every weight occupies a line.

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
<tr><td>No Sample Input</td><td>No Sample Output</td></tr></table>


# Constraints



# Note



# Source


