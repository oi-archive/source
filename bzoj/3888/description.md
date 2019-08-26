
# Description

<div class="content"><p><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;">Farmer John&#39;s N cows (1 &lt;= N &lt;= 50,000) appear to be stampeding along the road at the front of FJ&#39;s farm, but they are actually just running in a foot race to see which cow is the fastest.  Viewed from above, each cow is represented by a unit-length horizontal line segment, specified by the coordinates of its left corner point at time t=0.  For example, (-3,6) would specify a cow who at time t=0 is represented by the segment from (-3,6) to (-2,6).  Each cow is moving to the right (in the +x direction) at a certain rate, specified by the integer amount of time it takes her to move 1 unit to the right.  FJ is not particularly thrilled that his cows are outside running instead of in the barn producing milk.  He plans to admonish them with a stern lecture after the race ends.  In order to determine which of his cows are participating in the race, FJ situates himself at (0,0) and looks along a ray extending in the +y direction.  As the race unfolds, FJ sees a cow if she is ever the first cow visible along this ray.  That is, a cow might not be visible if another cow is &#34;in front&#34; of her during the entire time she crosses FJ&#39;s line of sight.  Please compute the number of cows FJ can see during the entire race.<br/>
</span>PoPoQQQ站在原点上向y轴正半轴看，然后有一群羊驼从他眼前飞过。这些羊驼初始都在第二象限，尾巴在(Xi,Yi)，头在(Xi+1,Yi)，每Ci秒向右走一个单位。  PoPoQQQ能看见一匹羊驼当且仅当它身体任意某部位x坐标为0时，没有其它y坐标小于此羊驼的羊驼身体某部位x坐标为0。  问PoPoQQQ能看见几匹羊驼？</p>
<p></p></div>

# Input

<div class="content"><div><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;">The first line of the input contains N.  Each of the following N lines describes a cow with three integers x y r, corresponding to a cow whose left endpoint is at (x,y) at time t=0, moving to the right at a continuous speed of 1 unit of distance every r units of time.  The value of x is in the range -1000..-1, the value of y is in the range 1..1,000,000 (and distinct for every cow, to prevent any possible collisions), and the value of r is in the range 1..1,000,000.<br/>
</span></div>
<p></p></div>

# Output

<div class="content"><div><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;">A single integer, specifying the number of cows FJ can see during the entire race (from t=0 onward).<br/>
</span></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
-2 1 3<br/>
-3 2 3<br/>
-5 100 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
<br/>
SOLUTION NOTES:<br/>
<br/>
FJ can see cows 1 and 2 but not cow 3.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver&amp;鸣谢PoPoQQQ">Silver&amp;鸣谢PoPoQQQ</a></p></div>

