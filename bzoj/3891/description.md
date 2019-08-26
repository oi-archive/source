
# Description

<div class="content"><p><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;">Bessie and her sister Elsie graze in different fields during the day, and in the evening they both want to walk back to the barn to rest. Being clever bovines, they come up with a plan to minimize the total amount of energy they both spend while walking.  Bessie spends B units of energy when walking from a field to an adjacent field, and Elsie spends E units of energy when she walks to an adjacent field.  However, if Bessie and Elsie are together in the same field, Bessie can carry Elsie on her shoulders and both can move to an adjacent field while spending only P units of energy (where P might be considerably less than B+E, the amount Bessie and Elsie would have spent individually walking to the adjacent field).  If P is very small, the most energy-efficient solution may involve Bessie and Elsie traveling to a common meeting field, then traveling together piggyback for the rest of the journey to the barn.  Of course, if P is large, it may still make the most sense for Bessie and Elsie to travel separately.  On a side note, Bessie and Elsie are both unhappy with the term &#34;piggyback&#34;, as they don&#39;t see why the pigs on the farm should deserve all the credit for this remarkable form of transportation.  Given B, E, and P, as well as the layout of the farm, please compute the minimum amount of energy required for Bessie and Elsie to reach the barn.<br/>
</span></p>
<div>给定一个N个点M条边的无向图，其中Bessie在1号点，Elsie在2号点，它们的目的地为N号点。Bessie每经过一条边需要消耗B点能量，Elsie每经过一条边需要消耗E点能量。当它们相遇时，它们可以一起行走，此时它们每经过一条边需要消耗P点能量。求它们两个到达N号点时最少消耗多少能量？</div>
<p><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;"> </span></p>
<p></p>
<p></p></div>

# Input

<div class="content"><div><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;">The first line of input contains the positive integers B, E, P, N, and M.  All of these are at most 40,000.  B, E, and P are described above. N is the number of fields in the farm (numbered 1..N, where N &gt;= 3), and M is the number of connections between fields.  Bessie and Elsie start in fields 1 and 2, respectively.  The barn resides in field N.  The next M lines in the input each describe a connection between a pair of different fields, specified by the integer indices of the two fields.  Connections are bi-directional.  It is always possible to travel from field 1 to field N, and field 2 to field N, along a series of such connections.  <br/>
</span></div>
<p></p></div>

# Output

<div class="content"><div>A single integer specifying the minimum amount of energy Bessie and</div>
<div>Elsie collectively need to spend to reach the barn.  In the example</div>
<div>shown here, Bessie travels from 1 to 4 and Elsie travels from 2 to 3</div>
<div>to 4.  Then, they travel together from 4 to 7 to 8.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4 5 8 8<br/>
1 4<br/>
2 3<br/>
3 4<br/>
4 7<br/>
2 5<br/>
5 6<br/>
6 8<br/>
7 8</span></div>

# Sample Output

<div class="content"><span class="sampledata">22</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

