
# Content

Emperor Montezuma of the ancient civilization of the Aztecs has a hard time planning the productivity of his capital city. The city is divided into square-shaped regions of the same size. Each region has three important properties: Workforce (number of people able to work),income (the amount of money Montezuma can earn from this region, given in Quetzal, the Aztec currency) and the number of farms. A region needs an administrator in order to contribute to the city. Otherwise, the region is self-sufficient and not officially a part of the city (and hence, Montezuma doesn't earn taxes, cannot utilize the work force and cannot access food produced from the region's farms).

Montezuma wants to make sure that his capital city is sufficiently prosperous, and he wants to achieve this prosperity by using as few administrators as possible. The capital city is prosperous if the sums of the workforces, income and farms for all administered regions exceed or are equal to the given values in each category.

Alas, Montezuma was born rather early and didn't have access to computers. However,you have read about Montezuma's exploits in the Civilopedia of the latest installment of the computer game Civilization. You found this scenario interesting enough that you have decided to write a computer program that calculates the fewest number of regions Montezuma would need to administer in order to have a city which is prosperous with regard to workforce, taxes and farms.

# Standard Input

The first line of the input consists of a single integer $T$, the number of test cases. Each test case begins with a line containing a single integer $N$, the number of regions near the capital city. The next line contains three integers $W,C,F$, representing the number of workers, tax income and number of farms which is needed for the city to be considered prosperous. The next $N$ lines contains three integers $w\_i,c\_i,f\_i$ , the number of workers, the tax income and the number of farms that region $i$ offers,respectively.

# Standard Output

For each test case, output the minimal number of regions that need to be administered. If it is impossible for the city to be prosperous, output `game over` instead (without quotes).

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
50 50 50
10 20 30
40 30 22
10 10 33
2
10 20 30
5 5 5
200 10 20</td><td>2
game over</td></tr></table>


# Constraints



# Note

$0 < T \leq 100$

$0 < N \leq 18$

$0 < W,C,F \leq 1000$

$0 < w\_i,c\_i,f\_i \leq 1000$

# Source


