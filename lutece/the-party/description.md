
# Content

2018 is about to end , 2019 is coming soon.Well , boys in UESTC ,do you have girlfriends? Of course, $\ bachelor$  XYZ is also worried about this problem. But now , he thinks of a good idea. 

Tomorrow UESTC will hold a party , and XYZ is going to invite a girl whose name is Q to this party. 

Q is a clever girl,she says: " Sure , but  at first, you should solve my problem . If you can solve this problem, I will come with you and dance with you . " 

Here is the problem: Suppose there are $n$ people in the party,  everyone has a charm value. The i-person's charm value is $a[i]$ . Now Q defines a $function$: $f(k)$ . The meaning of $f(k)$ is as follows: We choose $k$  people from $n$ people, the value of $f(k)$ is equal to the $Great  Common  Divisor$ of these $k$ people's charm value.

And Q wants the $f(k)$ as large as possible. So now , she asks XYZ :" Can you calculate the $f(k)$ when $k$ from $1$ to $n$ and $k$ is an integer?"

As we all know , XYZ is not good at math, can you help him ?

Note: Q wants the $f(k)$ as large as possible when $k$ from $1$ to $n$ and $k$ is an integer.

# Standard Input

The first line contains an integer $n$.

then $n$ lines are as follows: every line contains an integer $a[i]$, which means i-person's charm value.

$\ n\leq 50000$,$\ a[i]\leq 100000$;

# Standard Output

There are $n$ lines , the i-th line outputs the $f(k)$ when $k=i$ .

Note again: The $f(k)$ should be maximized.

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
1
2
4</td><td>4
2
1</td></tr></table>


# Constraints



# Note

$f(1)=\max\{\gcd(1),\gcd(2),\gcd(4)\} =4$ ;

$f(2)=\max\{\gcd(1,2),\gcd(2,4),\gcd(1,4)\}=2$;

$f(3)=\max\{\gcd(1,2,4)\}=1$;

Here is the gcd function :
``` c++
int gcd(int a,int b){
    return b==0?a:gcd(b,a%b);
}
```

# Source


