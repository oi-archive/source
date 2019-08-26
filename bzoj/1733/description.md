
# Description

<div class="content"><p><span style="font-size: medium">Farmer John is constructing a new milking machine and wishes to keep it secret as long as possible. He has hidden in it deep within his farm and needs to be able to get to the machine without being detected. He must make a total of T (1 &lt;= T &lt;= 200) trips to the machine during its construction. He has a secret tunnel that he uses only for the return trips. The farm comprises N (2 &lt;= N &lt;= 200) landmarks (numbered 1..N) connected by P (1 &lt;= P &lt;= 40,000) bidirectional trails (numbered 1..P) and with a positive length that does not exceed 1,000,000. Multiple trails might join a pair of landmarks. To minimize his chances of detection, FJ knows he cannot use any trail on the farm more than once and that he should try to use the shortest trails. Help FJ get from the barn (landmark 1) to the secret milking machine (landmark N) a total of T times. Find the minimum possible length of the longest single trail that he will have to use, subject to the constraint that he use no trail more than once. (Note well: The goal is to minimize the length of the longest trail, not the sum of the trail lengths.) It is guaranteed that FJ can make all T trips without reusing a trail. </span></p>
<div><span style="font-size: medium">约翰正在制造一台新型的挤奶机，但他不希望别人知道．他希望尽可能久地隐藏这个秘密．</span><span style="font-size: medium">他把挤奶机藏在他的农场里，使它不被发现．在挤奶机制造的过程中，他需要去挤奶机所在的地方T(1≤T≤200)次．他的农场里有秘密的地道，但约翰只在返回的时候用它．</span><span style="font-size: medium">农场被划分成N(2≤N≤200)块区域，用1到200标号．这些区域被P(1≤P≤40000)条道路连接，每条路有一个小于10^6的长度L．两块区域之间可能有多条道路连接．</span><span style="font-size: medium">为了减少被发现的可能，约翰不会两次经过农场上的任何一条道路．当然了，他希望走最短的路． 请帮助约翰寻找这T次从仓库走到挤奶机所在地的路线．仓库是区域1，挤奶机所在地是区域N．我们现在要求的是约翰经过的这些道路中最长的路的长度最小是多少，当然他不能重复走某一条路．请注意，我们要求的不是最短的总路程长度，而是所经过的直揍连接两个区域的道路中最长的道路的最小长度． 数据保证约翰可以找到T条没有重复的从仓库到挤奶机所在区域的路．</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Three space-separated integers: N, P, and T * Lines 2..P+1: Line i+1 contains three space-separated integers, A_i, B_i, and L_i, indicating that a trail connects landmark A_i to landmark B_i with length L_i. </span></p>
<div><span style="font-size: medium">    第1行是3个整数N、P和T，用空格隔开．</span></div>
<div><span style="font-size: medium">    第2到P+1行，每行包括3个整数，Ai，Bi，Li．表示区域Ai、Bi之间有一条长度为Li的道路．</span></div></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer that is the minimum possible length of the longest segment of Farmer John&#39;s route. </span></p>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">    输出只有一行，包含一个整数，即约翰经过的这些道路中最长的路的最小长度．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">7 9 2<br/>
1 2 2<br/>
2 3 5<br/>
3 7 5<br/>
1 4 1<br/>
4 3 1<br/>
4 5 7<br/>
5 7 1<br/>
1 6 3<br/>
6 7 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
<br/>
约翰选择1-2-3-7和1-6-7两条路线．这些路线中最长路的最小长度是5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

