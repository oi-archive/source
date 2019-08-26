
# Description

<div class="content"><p><span style="font-size: medium">Autobyte Company is involved in the construction of one of Byteland motorways. Until recently the company collected toll charges only at the starting point of the motorway. However, Byteasar, the new chairman in charge of the company, noticed that in such a case the charged amount does not depend on the distance covered by customers in bytemiles. Therefore, the company plans to build toll-collecting points along the entire length of the motorway. <br/>
Byteasar, during his motorway trip, with the help of the odometer in his car, put down the location of all the  entry points (the position of an entry point is its distance from the start of the motorway). The company decided to locate  toll-collecting points evenly along the motorway. That means the distance between each two subsequent toll-collecting points would be the same. At the same time between each two such points there should be a motorway entry point and there should be toll-collecting point between each two subsequent motorway entries. Luckily, it turned out that the existing location of entry points makes possible such an arrangement. <br/>
Your task would be to calculate the minimum and maximum distance between toll-collecting points. Formally speaking, we are seeking the lowest and highest value for  , for which there exists a position B0of first toll-collecting point, such that the consecutive points should be located in B0+L,B0+2L…B0+NL positions. It may be so that the location of a given toll-collecting point, determined by the above procedure, falls in exactly the same position, as the location of an entry point. In this case the toll booth would be positioned in close vicinity of an entry point, either just before or just after it. In other words, the position of the  -th entry point should be included in the following interval |B0+(j-1)L,B0+JL|<br/>
. <br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">The first line of input contains one integer N (3&lt;=N&lt;=1000000): the number of motorway entry points. The second line of input contains an increasing sequence of  integers a1,a2…an(0&lt;=Ai&lt;=10^9). The following sequence elements are the positions of subsequent motorway entry points. <br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">Your program should produce two real numbers presenting smallest and largest possible distance between two subsequent toll collecting points in bytemiles. You can assume that the difference between these values is not less than 10^(-9). <br/>
Your result will be considered as being correct in case it is included in the interval |x(1-E)-E,x(1+E)+E|， where E is the correct answer,E=10^(-8). Therefore both relative error and absolute error of the answer equal to E will be accepted. <br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
2 3 4 5 6 7<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0.833333333333 1.250000000000<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

