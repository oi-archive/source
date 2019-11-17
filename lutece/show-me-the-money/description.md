
# Content

Frank Marks works at the Business Office of a large company. His company has customers all over the world and must deal with many different currencies. Employees often come to the Business Office with requisitions for certain amounts of money, such as $100$ American dollars or $452$ Euros. If Frank has the cash on hand, he gives the employee exactly what they need; if he does not have enough of the particular currency requested, he substitutes it with another one. This is sometimes difficult because he may have many different currencies to choose from and would like to pick the one which allows him to get as close to the original requisition as possible without going under (he must provide at least the value requested). For example, suppose Frank has six difference currencies - `A`, `B`, `C`, `D`, `E` and `F` - and he is aware of the following exchange rates:
```
23 A = 17 B
16 C = 29 E
5 B = 14 E
1 D = 7 F
```

If a requisition for `100 A` comes in but Frank has less than `100 A` available, he can substitute with either `74 B` (equivalent to about `100.12 A`), `115 C` (equivalent to about `100.72 A`) or `207 E` (equivalent to about `100.02 A`). Thus, the best approximation available to him is `207 E`. Note that Frank does not have enough information to find a relationship between currencies `A` and `D` or currencies `A` and `F`. Also, Frank only has at most $100,000$ units of any one currency in stock, so he could not satisfy a request for `64,000 A` using `E` currency and would need to use `73078 C` instead.

Determining the ideal substitute currency to use when he has completely run out of the requested currency is time consuming, so Frank would like a program to do the calculations for him.

# Standard Input

Each test case begins with a positive integer $n$ indicating the number of exchange rates. The next $n$ lines will be of the form

`val1 name1 = val2 name2`

where `name1` and `name2` are the names of two distinct currencies, and `val1` and `val2` are positive integers $\leq 30$ specifying the ratio between the two currencies. There will be no more than $8$ distinct currency names, and any two currencies will be paired together at most once. Currency names will consist of up to ten alphabetic characters. There will be no inconsistencies in the input (such as `1A = 2B`, `1B = 2C` and `1C = 2A`). Following these n lines will be a single line of the form
val name
which specifies the amount (a positive integer not exceeding $100,000$) and the name of the currency requested. A line containing $0$ will follow the last test case.

# Standard Output

For each test case, print the case number and the closest approximation without going under the requested value assuming that Frank does not have any of the requested currency available but is fully
in stock of all other currencies. There will be a unique answer for each problem instance.

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
23 A = 17 B
16 C = 29 E
5 B = 14 E
1 D = 7 F
100 A
1
1 shekel = 2 quatloo
40 quatloo
0</td><td>Case 1: 207 E
Case 2: 20 shekel</td></tr></table>


# Constraints



# Note



# Source


