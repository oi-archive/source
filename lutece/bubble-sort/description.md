
# Content

Bubble sort is one of the simplest sorting algorithms. It works by repeatedly iterating with the array to be sorted, comparing two adjacent numbers in the array, and swapping them if they are in the wrong order. The iterations with the list are repeated until no swap is needed, which means that the array is sorted. The code below will show you how bubble sort works:​

```
void BubbleSort(int *a, int n) {
  for (int i = 1; i <= n; i++) {
    for (int j = 2; j <= n; j++) {
      if (a[j - 1] > a[j]) {
        int t = a[j]; a[j] = a[j - 1]; a[j - 1] = t; // swap a[j] and a[j - 1]
      }
    }
  }
}
```

Now, give you an permutation of $1\cdots n$, we can easily use bubble sort to sort them. But we are interested more in how many times we will swap two adjacent numbers, and what's more, we want to find a permutation of $1\cdots n$ to fit in the two limitation below:
1. the times that swapping when bubble sort it, is the same as the original permutation.
2. among all the permutations which fit in the first limitation, we need the one which has the smallest lexicographical order.

The lexicographical order is define as follow: for two permutations $A$ and $B$, if $A\_i=B\_i$ and $A\_{i+1}<B\_{i+1}$($1\leq i$), then the lexicographical order of $A$ is smaller than $B$. For example, `1 2 3` is smaller than `1 3 2`, and `1 3 2` is smaller than `2 1 3`.

# Standard Input

First line of the input is a single integer $T$($T\leq 30$), indicates there are $T$ test cases.

For each test case, the first line is an integer $n$($2\leq n\leq 2000$), the second line contains a permutation of $1\cdots n$ indicates the original permutation.

# Standard Output

For each case, you should output two lines.

First line you should output the number of swaps the original permutation needed.

Second line should contain a permutation of $1\cdots n$, indicate the permutation we want.

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
3
2 1 3
4
3 1 2 4</td><td>1
1 3 2
2
1 3 4 2</td></tr></table>


# Constraints



# Note

There is no space after the last number.

# Source


