
# Description

<div class="content"><p><span style="font-size: medium">Farmer John wishes to build a corral for his cows. Being finicky beasts, they demand that the corral be square and that the corral contain at least C (1 &lt;= C &lt;= 500) clover fields for afternoon treats. The corral&#39;s edges must be parallel to the X,Y axes. FJ&#39;s land contains a total of N (C &lt;= N &lt;= 500) clover fields, each a block of size 1 x 1 and located at with its lower left corner at integer X and Y coordinates each in the range 1..10,000. Sometimes more than one clover field grows at the same location; such a field would have its location appear twice (or more) in the input. A corral surrounds a clover field if the field is entirely located inside the corral&#39;s borders. Help FJ by telling him the side length of the smallest square containing C clover fields. </span></p>
<div><span style="font-size: medium">    约翰打算建一个围栏来圈养他的奶牛．作为最挑剔的兽类，奶牛们要求这个围栏必须是正方形的，而且围栏里至少要有C(1≤C≤500)个草场，来供应她们的午餐．</span></div>
<div><span style="font-size: medium">    约翰的土地上共有N(C≤N≤500)个草场，每个草场在一块lxl的方格内，而且这个方格的坐标不会超过10000.有时候，会有多个草场在同一个方格内，那他们的坐标就会相同．</span></div>
<div><span style="font-size: medium">    告诉约翰，最小的围栏的边长是多少？</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Two space-separated integers: C and N </span></p>
<p><span style="font-size: medium">* Lines 2..N+1: Each line contains two space-separated integers that are the X,Y coordinates of a clover field. </span></p>
<div><span style="font-size: medium">    第1行输入C和N，接下来N行每行输入一对整数，表示一个草场所在方格的坐标</span></div></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: A single line with a single integer that is length of one edge of the minimum size square that contains at least C clover fields. </span></p>
<div><span style="font-size: medium">    输入最小边长．</span></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
1 2<br/>
2 1<br/>
4 1<br/>
5 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
Below is one 4x4 solution (C&#39;s show most of the corral&#39;s area); many<br/>
others exist.<br/>
<br/>
|CCCC<br/>
|CCCC<br/>
|*CCC*<br/>
|C*C*<br/>
+------</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

