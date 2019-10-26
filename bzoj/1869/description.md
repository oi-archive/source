
# Description

<div class="content"><img border="0" src="/source/bzoj/1869/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE4NjkuanBn.jpg"/> </div>

# Input

<div class="content">The first line of the input contains an integer, the number of test cases. A test case includes one line with Test N, where N is the current test case number followed by eight lines, specifying the two partial configurations C1 and C2 in this order. Each configuration is specified by four lines.

The first line of the partial configuration contains three numbers: n1, n2, n3 denoting the heights of the three towers of the partial configuration (0 &lt;= n1, n2, n3 &lt;= 50). The second line contains n1 letters (B or W) separated by spaces describing the first tower. The third line contains n2 letters separated by spaces describing the second tower. The fourth line contains n3 letters separated by spaces describing the third tower. A letter W denotes a white cube and the letter B denotes a black cube. Each tower is described in the bottom-to-top order.

</div>

# Output

<div class="content">For each test case, print on a separate line the test case number and Yes if C1 is at least as favorable for white as the partial configuration C2, and No otherwise.

</div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
Test 1<br/>
3 3 1<br/>
W B B<br/>
W B W<br/>
B<br/>
3 3 3<br/>
B W W<br/>
B W W<br/>
W B B<br/>
Test 2<br/>
3 3 2<br/>
W B B<br/>
W B W<br/>
B B<br/>
3 3 3<br/>
B W W<br/>
B W W<br/>
W B B<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Test 1: Yes<br/>
Test 2: No</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=MIT Programming Contest 2005">MIT Programming Contest 2005</a></p></div>

