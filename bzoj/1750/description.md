
# Description

<div class="content">
It is a little known fact that cows love apples.  Farmer John has
two apple trees (which are conveniently numbered 1 and 2) in his
field, each full of apples.  Bessie cannot reach the apples when
they are on the tree, so she must wait for them to fall.  However,
she must catch them in the air since the apples bruise when they
hit the ground (and no one wants to eat bruised apples).  Bessie
is a quick eater, so an apple she does catch is eaten in just a few
seconds.

Each minute, one of the two apple trees drops an apple. Bessie,
having much practice, can catch an apple if she is standing under
a tree from which one falls. While Bessie can walk between the two
trees quickly (in much less than a minute), she can stand under
only one tree at any time. Moreover, cows do not get a lot of
exercise, so she is not willing to walk back and forth between the
trees endlessly (and thus misses some apples).

Apples fall (one each minute) for T (1 &lt;= T &lt;= 1,000) minutes.
Bessie is willing to walk back and forth at most W (1 &lt;= W &lt;= 30)
times. Given which tree will drop an apple each minute, determine
the maximum number of apples which Bessie can catch.  Bessie starts
at tree 1.

</div>

# Input

<div class="content">
* Line 1: Two space separated integers: T and W

* Lines 2..T+1: 1 or 2: the tree that will drop an apple each minute.

</div>

# Output

<div class="content">
* Line 1: The maximum number of apples Bessie can catch without
        walking more than W times.

</div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
7 2<br/>
2<br/>
1<br/>
1<br/>
2<br/>
2<br/>
1<br/>
1<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
Seven apples fall - one from tree 2, then two in a row from tree 1, then<br/>
two in a row from tree 2, then two in a row from tree 1. Bessie is <br/>
willing to walk from one tree to the other twice.<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
6<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
Bessie can catch six apples by staying under tree 1 until the first two<br/>
have dropped, then moving to tree 2 for the next two, then returning back<br/>
to tree 1 for the final two.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

