
# Description

<div class="content"><div>Your current task is to make a ground plan for a residential building located in HZXJHS. So you must determine a way to split the floor building with walls to make apartments in the shape of a rectangle. Each built wall must be paralled to the building&#39;s sides.</div>
<div>The floor is represented in the ground plan as a large rectangle with dimensions n×m, where each apartment is a smaller rectangle with dimensions a×b located inside. For each apartment, its dimensions can be different from each other. The number a and b must be integers.</div>
<div>Additionally, the apartments must completely cover the floor without one 1×1 square located on (x,y). The apartments must not intersect, but they can touch.</div>
<div>For this example, this is a sample of n=2,m=3,x=2,y=2.</div>
<div><img src="/source/bzoj/4302/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUxMC9mZi5KUEc=.JPG" width="282" height="206" alt=""/></div>
<div></div>
<div>To prevent darkness indoors, the apartments must have windows. Therefore, each apartment must share its at least one side with the edge of the rectangle representing the floor so it is possible to place a window.</div>
<div></div>
<div>Your boss XXY wants to minimize the maximum areas of all apartments, now it&#39;s your turn to tell him the answer.</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>There are at most 10000 testcases.</div>
<div>For each testcase, only four space-separated integers, n,m,x,y(1&lt;=n,m&lt;=10^8,n×m&gt;1,1 &lt; = x &lt; = n,1&lt; = y &lt; =m).</div>
<div> </div>
<div></div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>For each testcase, print only one interger, representing the answer.</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 3 2 2<br/>
3 3 1 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

