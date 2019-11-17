
# Content

One day, Bob was playing an OOXX Game with his girl friend Alice. Bob was trying to make Alice laugh and happy. So, he decided to tell $N$ jokes to Alice. Some of his jokes were funny and Alice laughed out loud. However, some of them were very boring and Alice didn't like it.

Let's mark the Game they had played as a String S. Each character of String S is either an 'O' or an 'X'. The length of String is exactly $N$. If $S_i$='O', that means Alice liked $i^{th}$ jokes Bob had told. Otherwise, if $S_i$='X', that means Alice disliked it.

We can grade for Bob by following rules. We find each long consecutive substring of S which only contains 'O' and add the square of its length to the score. For example, S="OOOXXOOXXOOO", we can find three long consecutive substring of S which are "OOO", "OO" , "OOO". Each of their length is 3, 2, 3. So the final score we grade for Bob is $3^2+2^2+3^2=22$.

Now, I would like to give you the possibility of each joke Alice liked. Please tell me the expected score we will grade for Bob.

# Standard Input

The first line contains an integer $N$($1 \leq N \leq 10^5$), meaning the number jokes Bob had told.

The following line contains $N$ real number $p_1, p_2, ... ,p_N$($0 \leq p_i \leq 1$), meaning the possibility of each joke Alice liked.

There will be at most six digits after the decimal point for each $p_i$.

# Standard Output

Output a real number with 6 digits exactly after the decimal point indicating the expected score we will grade for Bob.

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
0.4 0.5</td><td>1.300000</td></tr><tr><td>3
0.000001 0.123456 0.654321</td><td>0.939338</td></tr></table>


# Constraints



# Note



# Source


