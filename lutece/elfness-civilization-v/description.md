
# Content

Elfness is addicted to a game named "Civilization V" recently.Last day he found a secret of "Civilization V" by chance.

In fact,after you win a game in the $8\_{th}$ difficulty.There'll be a hidden stage for you to choose.You can visit the Base of UESTC_ACMers as long as you can pass the hidden stage.

The hidden stage is :
1. Give you $K$ integers : $1,10,100,1000,\cdots ,10^{K-1}$.
2. You should choose $2$ integers which are considered as $a$ and $b$, from the list.
3. Delete $a,b$ from the list and insert an new interger whose value is $a-b$ into the list 【After this step,the size of the list will decrease by one】
4、If the size of the list is $1$,print the last number in the list,otherwise repeat operation $2,3,4$.

The final question is:How many different types of number can be printed after all these operations.

# Standard Input

The first line contains one integer $T$($0< T\leq 100$),indicate the number of cases.

For each case,there is one line contains a integer $k$($2\leq k\leq15$) as mentioned above.

# Standard Output

For each case,print one line which contain a integer,indicate the number of different value that $x$ can be.

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
<tr><td>1
3</td><td>6</td></tr></table>


# Constraints



# Note

In the Sample,the last number might be $-109, -91, -89, 89, 91, 109$.

# Source


