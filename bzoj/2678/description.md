
# Description

<div class="content"><div><span style="font-size: 14pt; color: black"> When Farmer John isn&#39;t milking cows, stacking haybales, lining up his cows, or building fences, he enjoys sitting down with a good book. Over the years, he has collected N books (1 &lt;= N &lt;= 100,000), and he wants to build a new set of bookshelves to hold them all. Each book i has a width W(i) and height H(i). The books need to be added to a set of shelves in order; for example, the first shelf should contain books 1...k for some k, the second shelf should start with book k+1, and so on. Each shelf can have a total width of at most L (1 &lt;= L &lt;= 1,000,000,000). The height of a shelf is equal to the height of the tallest book on that shelf, and the height of the entire set of bookshelves is the sum of the heights of all the individual shelves, since they are all stacked vertically. Please help FJ compute the minimum possible height for the entire set of bookshelves. PROBLEM NAME: bookshelf </span></div></div>

# Input

<div class="content"><p><font size="5">* Line 1: Two space-separated integers: N and L. * Lines 2..1+N: Line i+1 contains two space-separated integers: H(i) and W(i). (1 &lt;= H(i) &lt;= 1,000,000; 1 &lt;= W(i) &lt;= L). </font></p></div>

# Output

<div class="content"><p>* Line 1: The minimum possible total height for the set of bookshelves. SAMPLE</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 10 //五本书，每个书架的宽度不超过10<br/>
5 7 //第一本书的高度及宽度<br/>
9 2<br/>
8 5<br/>
13 2<br/>
3 8 <br/>
<br/>
INPUT DETAILS: There are 5 books. Each shelf can have total width at most 10. <br/>
OUTPUT FORMAT:<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">21 //5+13+3=21<br/>
OUTPUT DETAILS: There are 3 shelves, the first containing just book 1 (height 5, width 7), the second containing books 2..4 (height 13, width 9), and the third containing book 5 (height 3, width 8).</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

