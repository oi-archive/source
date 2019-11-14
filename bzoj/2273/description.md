
# Description

<div class="content"><p><br/>
One sunny day farmer John was kidnapped by evil farmer Marcus&#39;s<br/>
cows. FJ wasn&#39;t too concerned about his forced holiday but wanted<br/>
to make sure that his cows got home safely together.<br/>
<br/>
The cows are spread out in every one of FJ&#39;s N (3 &lt;= N &lt;= 200)<br/>
pastures conveniently numbered 1..N. The barn is located at pasture<br/>
1. The farm has an interesting navigation system: at every pasture<br/>
i there are M (1 &lt;= M &lt;= 200) signs S_ij (1 &lt;= S_ij &lt;= N) which one<br/>
could reference as S_i1..S_iM; each sign points the way to a pasture.<br/>
Sometimes a sign points to a path that leads back to the same<br/>
pasture.<br/>
<br/>
Farmer Marcus&#39;s cows allow FJ to write a single message to all of<br/>
his cows. FJ&#39;s plan is to write a list of sign numbers such that<br/>
any cow who follows those instructions will all arrive at the barn<br/>
when each cow has completed all the instructions.<br/>
<br/>
When a cow starts at a given pasture then she will first follow the<br/>
path indicated by the first sign number on FJ&#39;s list. When she<br/>
arrives at the second pasture, she looks at the second sign of FJ&#39;s<br/>
list and follows the path marked by that sign. She continues until<br/>
she exhausts the instruction list, at which point she should be at<br/>
the barn.<br/>
<br/>
Find a list of instructions containing no more than 5,000,000 sign<br/>
numbers that will guide every cow, from every pasture, to the barn<br/>
after all instructions are followed.  It is guaranteed that such a<br/>
list exists.<br/>
<br/>
Consider a set of three signs in four pastures that direct the cows<br/>
like these do:<br/>
                               ** Pasture# **<br/>
                              1    2    3    4<br/>
                     Sign 1   4    4    1    3<br/>
                     Sign 2   1    3    2    4<br/>
                     Sign 3   4    2    3    1<br/>
<br/>
The set of instructions below will direct cows to the barn from any<br/>
of the four pastures:<br/>
<br/>
       Instruction#   Sign#            Instruction#   Sign#<br/>
            1           1                   5           3<br/>
            2           2                   6           1<br/>
            3           1                   7           3<br/>
            4           2<br/>
<br/>
The cow in pasture 1 will read sign #1 at time 1 and be directed<br/>
to pasture 4.  At time 2, she is in pasture 4 and (per FJ&#39;s<br/>
instructions) read sign #2 and then be directed to pasture 4. Below<br/>
is a table that shows the cow&#39;s travels:<br/>
<br/>
                  * * * *  Cow in pasture  1  * * * *<br/>
<br/>
        Time    CurrentPasture#    WhichSign     Sign-&gt;Nextpasture<br/>
          1            1               1                4<br/>
          2            4               2                4 (same pasture!)<br/>
          3            4               1                3<br/>
          4            3               2                2<br/>
          5            2               3                2 (same pasture)<br/>
          6            2               1                4<br/>
          7            4               3                1 Barn!<br/>
<br/>
Similarly: Pasture 2&#39;s cow visits pastures [2]-4-4-3-2-2-4-1. <br/>
           Pasture 3&#39;s cow visits pastures [3]-1-1-4-4-1-4-1.<br/>
           Pasture 4&#39;s cow visits pastures [4]-3-2-4-4-1-4-1.<br/>
<br/>
Given a set of signs, create a set of instructions.<br/>
</p></div>

# Input

<div class="content"><p><br/>
* Line 1: Two space separated integers: N and M<br/>
<br/>
* Lines 2..M+1: Line i+1 describes the contents of each pasture&#39;s N<br/>
        signs with N integers: S_1i..S_Ni<br/>
</p></div>

# Output

<div class="content"><p><br/>
* Lines 1..?: The sign numbers the cows should follow, one per line.</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
4 4 1 3<br/>
1 3 2 4<br/>
4 2 3 1<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
1<br/>
2<br/>
3<br/>
1<br/>
3<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

