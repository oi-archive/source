
# Description

<div class="content">Farmer John made a profit last year! He would like to invest it
well but wonders how much money he will make. He knows the interest
rate R (an integer between 0 and 20) that is compounded annually
at his bank.  He has an integer amount of money M in the range
100..1,000,000.  He knows how many years Y (range: 0..400) he intends
to invest the money in the bank. Help him learn how much money he
will have in the future by compounding the interest for each year
he saves.  Print an integer answer without rounding. Answers for the test
data are guaranteed to fit into a signed 32 bit integer.

看了样例输入输出就知道怎么回事了..........</div>

# Input

<div class="content">* Line 1: Three space-separated integers: R, M, and Y

</div>

# Output

<div class="content">* Line 1: A single integer that is the number of dollars FJ will have
        after Y years.

</div>

# Sample Input

<div class="content"><span class="sampledata">5 5000 4<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
5% annual interest, 5000 money, 4 years<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6077<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
Year 1: 1.05 * 5000 = 5250<br/>
Year 2: 1.05 * 5250 = 5512.5<br/>
Year 3: 1.05 * 5512.50 = 5788.125<br/>
Year 4: 1.05 * 5788.125 = 6077.53125<br/>
The integer part of 6077.53125 is 6077.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

