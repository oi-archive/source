
# Description

<div class="content"><div>Farmer John has lost his favorite cow bell, and Bessie the cow has agreed to help him find it! They both fan out and search the farm along different paths, but stay in contact via radio so they can keep in touch with each-other. Unfortunately, the batteries in their radios are running low, so they want to plan their movements so as to conserve power, by trying to stay always within a short distance apart.</div>
<div>Farmer John starts at location (fx,fy) and plans to follow a path consisting of N steps, each of which is either &#39;N&#39; (north), &#39;E&#39; (east), &#39;S&#39; (south), or &#39;W&#39; west. Bessie starts at location (bx,bybx,by) and follows a similar path consisting of MM steps. Both paths may share points in common. At each time step, Farmer John can either stay put at his current location, or take one step forward along his path, in whichever direction happens to be next (assuming he has not yet reached the final location in his path). Bessie can make a similar choice. At each time step (excluding the first step where they start at their initial locations), their radios consume energy equal to the square of the distance between them.</div>
<div></div>
<div>Please help FJ and Bessie plan a joint movement strategy that will minimize the total amount of energy consumed up to and including the final step where both of them first reach the final locations on their respective paths.</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains N and M (1&lt; =N,M&lt; =1000). The second line contains integers fx and fy, and the third line contains bxbx and byby (0&lt; =fx,fy,bx,by&lt; =10000). The next line contains a string of length N describing FJ&#39;s path, and the final line contains a string of length MM describing Bessie&#39;s path.</div>
<div>It is guranteed that Farmer John and Bessie&#39;s coordinates are always in the range (0&lt; =x,y&lt; =1000) throughout their journey. Note that East points in the positive x direction and North points in the positive y direction.</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Output a single integer specifying the minimum energy FJ and Bessie can use during their travels.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 7<br/>
3 0<br/>
5 0<br/>
NN<br/>
NWWWWWN</span></div>

# Sample Output

<div class="content"><span class="sampledata">28</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

