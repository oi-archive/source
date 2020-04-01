
# Description

<div class="content"><p><span style="font-size: medium">A crime has been comitted: a load of grain has been taken from the barn by one of FJ&#39;s cows. FJ is trying to determine which of his C (1 &lt;= C &lt;= 100) cows is the culprit. Fortunately, a passing satellite took an image of his farm M (1 &lt;= M &lt;= 70000) seconds before the crime took place, giving the location of all of the cows. He wants to know which cows had time to get to the barn to steal the grain. Farmer John&#39;s farm comprises F (1 &lt;= F &lt;= 500) fields numbered 1..F and connected by P (1 &lt;= P &lt;= 1,000) bidirectional paths whose traversal time is in the range 1..70000 seconds (cows walk very slowly). Field 1 contains the barn. It takes no time to travel within a field (switch paths). Given the layout of Farmer John&#39;s farm and the location of each cow when the satellite flew over, determine set of cows who could be guilty. NOTE: Do not declare a variable named exactly &#39;time&#39;. This will reference the system call and never give you the results you really want. </span></p>
<div>
<div>谷仓里发现谷物被盗！约翰正试图从C(1≤C≤100)只奶牛里找出那个偷谷物的罪犯．幸运的是，一个恰好路过的卫</div>
<div>星拍下谷物被盗前M(1≤M≤70000)秒的农场的图片．这样约翰就能通过牛们的位置来判断谁有足够的时间来盗窃谷</div>
<div>物．约翰农场有F(1≤F≤500)草地，标号1到F，还有P(1≤P≤1000)条双向路连接着它们．通过这些路需要的时间</div>
<div>在1到70000秒的范围内．田地1上建有那个被盗的谷仓． 给出农场地图，以及卫星照片里每只牛所在的位置．请判</div>
<div>断哪些牛有可能犯罪．</div>
</div></div>

# Input

<div class="content"><div>* Line 1: Four space-separated integers: F, P, C, and M </div>
<div>* Lines 2..P+1: Three space-separated integers describing a path: F1, F2, and T. The path connects F</div>
<div>1 and F2 and requires T seconds to traverse. </div>
<div>* Lines P+2..P+C+1: One integer per line, the location of a cow. The first line gives the field numb</div>
<div>er of cow 1, the second of cow 2, etc.</div>
<div></div>
<div>第1行输入四个整数F，只C，和M;</div>
<div>接下来P行每行三个整数描述一条路，起点终点和通过时间．</div>
<div>接下来C行每行一个整数，表示一头牛所在的地点．</div></div>

# Output

<div class="content"><div>* Line 1: A single integer N, the number of cows that could be guilty of the crime.</div>
<div>* Lines 2..N+1: A single cow number on each line that is one of the cows that could be guilty of the</div>
<div> crime. The list must be in ascending order.</div>
<div>第1行输出嫌疑犯的数目，接下来一行输出一只嫌疑犯的编号．</div></div>

# Sample Input

<div class="content"><span class="sampledata">7 6 5 8<br/>
1 4 2<br/>
1 2 1<br/>
2 3 6<br/>
3 5 5<br/>
5 4 6<br/>
1 7 9<br/>
1<br/>
4<br/>
5<br/>
3<br/>
7<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
1<br/>
2<br/>
3<br/>
4<br/>
</span></div>

# Hint

<div class="content"><p></p><p><img height="256" alt="" width="622" src="/source/bzoj/1681/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS80NCg0KS5qcGc=.jpg"/></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

