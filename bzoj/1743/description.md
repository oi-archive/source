
# Description

<div class="content">Farmer John has set up a puzzle for his cows to solve.  At the
entrance to the barn, he has laid out an H x W (1 &lt;= H &lt;= 30, 1 &lt;=
W &lt;= 30) grid of letters.  Before a cow can enter the barn, she
must spell out a valid English word by jumping from square to square,
creating a sequence of letters.  She can start at any square but
may only jump to a subsequent square that is located to the right
and/or above the current square (i.e., neither to the left nor
lower).  The next square can be any distance from the current one
since the cows are world-class jumpers!

No two cows may traverse the exact same path, although two cows are
allowed to spell the same word via different paths.

As an example, consider this grid (presuming &#39;TO&#39; and &#39;OX&#39; are
words):

  T X X O
  T X Q T
  X T X Q

Four paths are valid, all spelling &#39;TO&#39; (one spelling requires a
&#39;T&#39; from the bottom row and an &#39;O&#39; from the top row).  &#39;OX&#39; is a
valid word, but would require jumping to an &#39;X&#39; square left of the
&#39;O&#39;, which is not allowed.

Given the grid and a list of valid words, compute the number of
cows that can enter the barn without any cow repeating a path.  The
file `dict.txt&#39; will be available and will contain the list of valid
words, one per line. See a copy of it at
http://ace.delos.com/usaco/dict-twalk.txt .

</div>

# Input

<div class="content">* Line 1: Two integers: H and W

* Lines 2..H+1: Each line contains W characters, without spaces,
        representing a row in the grid.  The first row is the top row.
         The first character in each row is the left-most character.

</div>

# Output

<div class="content">* Line 1: The number of cows that can enter the barn without repeating
        a path.

</div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
TXXO<br/>
TXQT<br/>
XTXQ<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
4 cows can enter the barn, each one spelling out one of the &#39;TO&#39;s.<br/>
</span></div>

# Hint

<div class="content"><p>请不要提交此题....</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

