
# Description

<div class="content"><p>Bessie is out in the field and wants to get back to the barn to get as much sleep as possible before Farmer John wakes her for the morning milking. Bessie needs her beauty sleep, so she wants to get back as quickly as possible.  Farmer John&#39;s field has N (2 &lt;= N &lt;= 1000) landmarks in it, uniquely numbered 1..N. Landmark 1 is the barn; the apple tree grove in which Bessie stands all day is landmark N.  Cows travel in the field using T (1 &lt;= T &lt;= 2000) bidirectional cow-trails of various lengths between the landmarks. Bessie is not confident of her navigation ability, so she always stays on a trail from its start to its end once she starts it.  Given the trails between the landmarks, determine the minimum distance Bessie must walk to get back to the barn.  It is guaranteed that some such route exists.</p></div>

# Input

<div class="content"><p>* Line 1: Two integers: T and N  * Lines 2..T+1: Each line describes a trail as three space-separated         integers.  The first two integers are the landmarks between         which the trail travels. The third integer is the length of         the trail, range 1..100.</p></div>

# Output

<div class="content"><p>* Line 1: A single integer, the minimum distance that Bessie must         travel to get from landmark N to landmark 1.</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
1 2 20<br/>
2 3 30<br/>
3 4 20<br/>
4 5 20<br/>
1 5 100<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
There are five landmarks.</span></div>

# Sample Output

<div class="content"><span class="sampledata">90<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
Bessie can get home by following trails 4, 3, 2, and 1.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

