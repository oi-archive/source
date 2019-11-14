
# Content

As we all know, LRZ is a knowledgeable girl, she will spend her spare time reading books. LRZ can read $k$ books every day. It is said Gaining New Insight through Reviewing Old Material, LRZ will read any book again after she finish this book once.


The library in LRZ’s university is now allowed to borrow books in a time limit. For the book $i$, we know it will be allowed to borrow in day $d\_i$ and lasted $t\_i$ days. For example if a book is allowed in day 2 and lasted 3 days, LRZ can borrow it in day 2, 3, 4. LRZ should return any book before day $d\_i+t\_i$, so if in the day 3, LRZ borrow a book which is allowed to borrow from day 2 and lasted 3 days, she will have 2 days to read this book.


Now you must figure out whether LRZ can read all the books the library allow to borrow.

# Standard Input

The first line contains two space-separated integers $n$ and $k$ ($1 \le n, k \le 100$), which are the number of books the library allow to borrow and the number of books LRZ can read every day. The $i-th$ of the following $n$ lines contains space-separated integers $d\_i$ and $t\_i$ ($0\le d\_i\le 1000,2\le t\_i\le 1000$)

# Standard Output

If LRZ can read all the book, you just output “Yes”, otherwise output “No”

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
<tr><td>3 2
1 3
1 3
1 3
</td><td>Yes
</td></tr><tr><td>2 1
1 3
1 3
</td><td>No
</td></tr></table>


# Constraints



# Note



# Source


