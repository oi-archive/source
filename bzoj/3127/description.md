
# Description

<div class="content"><p></p>
<div>Farns (1 &lt;= N &lt;= 100,000) which are connected by N-1 edges such that he can reach any barn from any </div>
<div>other. Farmer John wants to choose a path which starts and ends at two different barns, such that he</div>
<div>does not traverse any edge twice. He worries that his path might be a little long, so he also wantst</div>
<div>o choose another &#34;rest stop&#34; barn located on this path (which is distinct from the start or the end)</div>
<div>. Along each edge is a herd of cows, either of the Charcolais (white hair) or the Angus (black hair)</div>
<div> variety. Being the wise man that he is, Farmer John wants to balance the forces of yin and yang tha</div>
<div>t weigh upon his walk. To do so, he wishes to choose a path such that he will pass by an equal numbe</div>
<div>r of Charcolais herds and Angus herds-- both on the way from the start to his rest stop, and on thew</div>
<div>ay from the rest stop to the end. Farmer John is curious how many different paths he can choose that</div>
<div> are &#34;balanced&#34; as described above. Two paths are different only if they consist of different setsof</div>
<div> edges; a path should be counted only once even if there are multiple valid &#34;rest stop&#34; locationsalo</div>
<div>ng the path that make it balanced. Please help determine the number of paths Farmer John can cho</div>
<p></p></div>

# Input

<div class="content"><p></p>
<div>* Line 1: The integer N.</div>
<div>* Lines 2..N: Three integers a_i, b_i and t_i, representing the two barns that edge i connects. t_i </div>
<div>is 0 if the herd along that edge is Charcolais, and 1 if the herd is Angus.</div></div>

# Output

<div class="content"><p>Line 1: One integer, representing the number of possible paths Farmer John can choose from.</p></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
1 2 0<br/>
3 1 1<br/>
2 4 0<br/>
5 2 0<br/>
6 3 1<br/>
5 7 1<br/>
INPUT DETAILS: <br/>
There are 7 barns and 6 edges. The edges from 1 to 2, 2 to 4 and 2 to 5 have Charcolais herds along <br/>
them.</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
OUTPUT DETAILS: <br/>
No path of length 2 can have a suitable rest stop on it, so we can only consider paths of length 4. <br/>
The only path that has a suitable rest stop is 3-1-2-5-7, with a rest stop at 2.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

