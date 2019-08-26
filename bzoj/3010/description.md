
# Description

<div class="content"><p><span style="font-size: medium">Life is tough on the farm, and when life is tough you have to get tough. The cows have formed gangs (conveniently numbered 1 to M). The gangs coexisted in peace for a while, but now things are really getting out of control! The cows are competing over control of a great grazing field. This conflict happens over a series of minutes. Each minute a single cow walks into the field. If the field is empty the new cow&#39;s gang is considered to take control of the field. If the field is already controlled by the new cow&#39;s gang then the cow just starts grazing. Otherwise, a single cow from the controlling gang that is grazing confronts the new cow. These confrontations between two cows start with some arguing and inevitably end up with the pair coming to realize how much more more alike than different they are. The cows, seeing the error in their ways, leave the gang and the field and get a cold glass of soy milk at FJ&#39;s tavern. If after this confrontation the field is empty than no gang controls the field. Bessie realizes how these confrontations will occur. She knows how many cows are in each gang. Bessie really wants her gang to control the field after the conflict is over and all cows are either on the field or at FJ&#39;s tavern. Help Bessie determine if it is possible for her gang, labeled 1, to control the field in the end. If it is possible, Bessie wants to know the maximum number of cows from her gang that could be on the field at the end. Output this number and the lexicographically earliest ordering of cows that results in this number of cows from Bessie&#39;s gang at the end. An ordering X is said to be lexicographically earlier than Y if there is some k such that X[k] &lt; Y[k] and X[i] = Y[i] for i &lt; k. </span></p>
<p><span style="font-size: medium"><font face="System">n头牛结成了m个帮派，现在它们争夺一块草地。每个单位时间内会有一头牛来。如果草地上还没有牛或者只有自己帮派的牛，他会留在这里。但如果已经有别的帮派的牛，它们会打一架，这使得当前牛和草地上的一头牛去找农夫思考人生。问如何安排来的牛的编号顺序，能使一  号帮派最后有最多的牛留在草地上，如果不为0，还要输出字典序最小的一组方案。</font><br/>
</span></p></div>

# Input

<div class="content"><p><font size="4"> * Line 1: N (1 &lt;= N &lt;= 100) and M (1 &lt;= M &lt;= N) separated by a space. The total number of cows in all the gangs will be N. The total number of gangs is M.</font></p>
<p><font size="4"> * Lines 2..1+M: The (1+i)th line indicates how many members are in gang i. Each gang has at least 1 member. </font></p></div>

# Output

<div class="content"><p> * Line 1: Output YES on a single line if Bessie&#39;s gang can control the field after the conflict. Otherwise output NO on a single line.</p>
<p>* Line 2: If Bessie&#39;s gang can control the field after the conflict output the maximum number of cows that could be on the field on a single line. * Lines 3..2+N: On the (i+2)th line output the index of the gang of the cow that appears in the ith minute in the lexicographically earliest ordering that leaves the maximum number of cows on the field after the conflict. </p></div>

# Sample Input

<div class="content"><span class="sampledata"> 5 3 <br/>
2<br/>
1<br/>
2<br/>
 INPUT DETAILS: There are 5 cows and 3 gangs. Bessie&#39;s gang (gang 1) has 2 members, gang 2 has 1 member, and gang 3 has 2 members. </span></div>

# Sample Output

<div class="content"><span class="sampledata">YES<br/>
1<br/>
1<br/>
3 <br/>
2 <br/>
3 <br/>
1 <br/>
<br/>
OUTPUT DETAILS: Only one cow from Bessie&#39;s gang can end up on the field. </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

