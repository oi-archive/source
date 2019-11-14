
# Description

<div class="content"><p><span style="font-size: medium">Farmer John has a problem: the dirt road from his farm to town has suffered in the recent rainstorms and now contains (1 &lt;= N &lt;= 10,000) mud pools. Farmer John has a collection of wooden planks of length L that he can use to bridge these mud pools. He can overlap planks and the ends do not need to be anchored on the ground. However, he must cover each pool completely. Given the mud pools, help FJ figure out the minimum number of planks he needs in order to completely cover all the mud pools. </span></p>
<div><span style="font-size: medium">    牧场里下了一场暴雨，泥泞道路上出现了许多水坑，约翰想用一批长度为L的木板将这些水坑盖住.    牧场里的道路可以看成一根数轴，每个水坑可以用数轴上的两个坐标表示，如(3，6)表示从3到6有一个长度为3的水坑．所有的水坑都是不重叠的，(3，6)和(6，9)可以出现在同一个输入数据中，因为它们是两个连续的水坑，但不重叠．</span></div>
<div><span style="font-size: medium">    请你帮助约翰计算最少要用多少块木板才能将所有水坑盖住</span></div></div>

# Input

<div class="content"><p>* Line 1: Two space-separated integers: N and L * Lines 2..N+1: Line i+1 contains two space-separated integers: s_i and e_i (0 &lt;= s_i &lt; e_i &lt;= 1,000,000,000) that specify the start and end points of a mud pool along the road. The mud pools will not overlap. These numbers specify points, so a mud pool from 35 to 39 can be covered by a single board of length 4. Mud pools at (3,6) and (6,9) are not considered to overlap.</p>
<div><span style="font-size: medium">    第1行有二个用空格隔开的整数N和L．其中1≤N≤10000，表示水坑总数．L为木板长度．</span></div>
<div><span style="font-size: medium">接下来的N行每行有二个用整数si和ei(0≤si&lt;ei≤109)，表示一个水坑的两个坐标．</span></div></div>

# Output

<div class="content"><p>* Line 1: The miminum number of planks FJ needs to use.</p>
<div> </div>
<div><span style="font-size: medium">    一个整数，表示约翰盖住所有水坑最少要用多少块长为L的木板．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
1 6<br/>
13 17<br/>
8 12<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
</span></div>

# Hint

<div class="content"><p></p><p><img height="189" width="813" alt="" src="/source/bzoj/1689/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS8xMSgxKS5qcGc=.jpg"/></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

