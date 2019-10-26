
# Content

Captain Chen used to be a naive boy. 
At that time he started to learn algorithm.

When he was learning the sort algorithm "bubble sort", he misunderstood the meaning of bubble.
Let's see his code:

<pre><code>void sort(int a[], int n) {
    for (int i = 0; i < n; ++ i)
        for (int j = 0; j + 2 < n; ++ j)
            if (a[j] > a[j + 2])
                swap(a[j], a[j + 2]);
}
</code></pre>

Now when he comes back to his code at that time, he finds it beautiful in some special way (though it is not correct).

Given an array a, can you tell Captain Chen whether his algorithm works at this case.

# Standard Input

The first line of the input contains an integer $N$ ($1\leq N\leq 10^5$), indicating the number of the elements in array.

The next lines contain $N$ integers $a_i$ ($1\leq a_i\leq 100$), 
indicating the element in the array.

# Standard Output

Output `Yes` if Captain Chen's algorithm works perfectly on the array, otherwise output `No`.

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
<tr><td>4
1 2 3 4</td><td>Yes</td></tr><tr><td>4
4 3 2 1</td><td>No</td></tr></table>


# Constraints



# Note



# Source


