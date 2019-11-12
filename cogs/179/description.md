# 题目描述


<p>
Always bored with cud-chewing, the cows have invented a new game. One cow retrieves a set of N (3 ≤ N ≤ 20) hay bales from the shed each of which is one unit high. Each bale also has some unique width and unique breadth.
</p>
<p>
A second cow tries to choose a set of bales to make the tallest stack of bales in which each bale can be placed only on a bale whose own width and breadth are smaller than the width and breadth of the bale below. Bales can not be rotated to interchange the width and breadth.
</p>
<p>
Help the cows determine the highest achievable tower that can be legally built form a set of bales.
</p>
<p>
</p><p>
厌倦了无聊的反刍，奶牛们开发出来了一个新游戏，一头奶牛从储物室里拿出来一组N捆(3 ≤ N ≤ 20) 一样单位高度的干草。每捆干草的长和宽是不同的。
</p>
<p>
奶牛们要从中选出一些干草捆，并且把它们堆成最高的干草塔，但是每捆干草只能堆放在比它长和宽都大的干草捆上。顺便，干草捆是不能旋转来交换长和宽的。
</p>
<p>
帮助奶牛们堆出最高的干草塔。
</p>
<p></p>
<p>
Input
</p>
<ul>
<li>
Line 1: A single integer, N
</li>
</ul>
<ul>
<li>
Lines 2..N + 1: Each line describes a bale with two space-separated integers,respectively the width and breadth
</li>
</ul>
<p>
</p><p>
输入：
</p>
<p>
第1行：一个单独的整数N。
</p>
<p>
第2..N+1行:每行通过两个由空格分开的整数描述这一捆干草的长和宽。
</p>
<p></p>
<p>
Output
</p>
<ul>
<li>
Line 1: The height of the tallest possible tower that can legally be built from the bales.
</li>
</ul>
<p>
</p><p>
输出：
</p>
<p>
第1行：一个整数描述可以堆成的最高的合法的干草塔的高度。
</p>
<p></p>
<p>
Sample Input
</p>
<pre>6
6 9
10 12
9 11
8 10
7 8
5 3
</pre>
<p>
Sample Output
</p>
<pre>5
</pre>
<p>
Input Details Six bales of various widths and breadths
</p>
<p>
Output Details These bales can be stacked for a total height of 5:
</p>
<p>
</p><p>
输入细节：
</p>
<p>
有六捆干草可供选择。
</p>
<p>
输出细节：
</p>
<p>
总共可以堆成高度为5单位的干草塔。
</p>
<p>
[也存在别的同样高度的干草塔]
</p>
<p></p>
<pre>10 12
9 11
8 10
6 9
5 3
</pre>
<p>
[another stacking exists, too]
</p>
<p>
译byKZFFFFFFFF
</p>
