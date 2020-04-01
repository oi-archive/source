
# Description

<div class="content">
One of the traps we will encounter in the Pyramid is located in the Large Room. A lot of small holes are drilled into the floor. They look completely harmless at the first sight. But when activated, they start to throw out very hot java, uh ... pardon, lava. Unfortunately, all known paths to the Center Room (where the Sarcophagus is) contain a trigger that activates the trap. The ACM were not able to avoid that. But they have carefully monitored the positions of all the holes. So it is important to find the place in the Large Room that has the maximal distance from all the holes. This place is the safest in the entire room and the archaeologist has to hide there. 
</div>

# Input

<div class="content">The input consists of T test cases. The number of them (T) is given on the first line of the input file. Each test case begins with a line containing three integers X, Y, M separated by space. The numbers satisfy conditions: 1 &lt;= X,Y &lt;=10000, 1 &lt;= M &lt;= 1000. The numbers X and Yindicate the dimensions of the Large Room which has a rectangular shape. The number M stands for the number of holes. Then exactly M lines follow, each containing two integer numbers Ui and Vi (0 &lt;= Ui &lt;= X, 0 &lt;= Vi &lt;= Y) indicating the coordinates of one hole. There may be several holes at the same position. 
</div>

# Output

<div class="content">
Print exactly one line for each test case. The line should contain the sentence &#34;The safest point is (P, Q).&#34; where P and Qare the coordinates of the point in the room that has the maximum distance from the nearest hole, rounded to the nearest number with exactly one digit after the decimal point (0.05 rounds up to 0.1). 
</div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
3<br/>
1000 50 1<br/>
10 10<br/>
100 100 4<br/>
10 10<br/>
10 90<br/>
90 10<br/>
90 90<br/>
3000 3000 4<br/>
1200 85<br/>
63 2500<br/>
2700 2650 <br/>
2990 100<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
The safest point is (1000.0, 50.0).<br/>
The safest point is (50.0, 50.0).<br/>
The safest point is (1433.0, 1669.8).<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Cerc1999">Cerc1999</a></p></div>

