# 题目描述


<p>
Farmer John went to cut some wood and left N (2 ≤ N ≤ 100,000) cows eating the grass, as usual. When he returned, he found to his horror that the cluster of cows was in his garden eating his beautiful flowers. Wanting to minimize the subsequent damage, FJ decided to take immediate action and transport each cow back to its own barn.
</p>
<p>
Each cow i is at a location that is Ti minutes (1 ≤ Ti ≤ 2,000,000) away from its own barn. Furthermore, while waiting for transport, she destroys Di (1 ≤ Di ≤ 100) flowers per minute. No matter how hard he tries, FJ can only transport one cow at a time back to her barn. Moving cow i to its barn requires 2*Ti minutes (Ti to get there and Ti to return). FJ starts at the flower patch, transports the cow to its barn, and then walks back to the flowers, taking no extra time to get to the next cow that needs transport.
</p>
<p>
Write a program to determine the order in which FJ should pick up the cows so that the total number of flowers destroyed is minimized.
</p>
<p>
</p><p>
FJ去砍柴了，留下N(2&lt;=n&lt;=100,000)头奶牛在牧场里像往常一样吃草。当他回来的时候，他惊恐的
</p>
<p>
发现牛们组队去他的花园里吃花了。为了将FJ花园的损失最小化，FJ决定采取快速的行动——把每头奶牛赶回她们自己的牛棚里。每头奶牛i所在的位置到她们
</p>
<p>
自己的牛棚要花费Ti(1&lt;=Ti&lt;=2,000,000)分钟，每头奶牛在花园中每分钟都会吃掉Di(1&lt;=Di&lt;=100)
</p>
<p>
朵花。
</p>
<p>
贴士：
</p>
<p>
1.FJ每次只能赶一头牛回牛棚。
</p>
<p>
2.因为FJ要一来一回，所以说他每赶一头牛回牛棚要花费2*Ti分钟。
</p>
<p>
3.FJ从花园中出发赶一头奶牛回牛棚，再从牛棚走到花园。
</p>
<p>
4.因为FJ会瞬移，所以说到花园之后不需要花多余的时间赶到下一头牛所在的地方。
</p>
<p>
求一个合理的顺序使FJ到花园损失的花朵数最小。
</p>
<p></p>
<p>
Input
</p>
<ul>
<li>
Line 1: A single integer N
</li>
</ul>
<ul>
<li>
Lines 2..N + 1: Each line contains two space-separated integers, Ti and Di, that describe a single cow&#39;s characteristics
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
第2~N+1行：两个由空格分开的整数，分别描述第i头奶牛的Ti和Di。
</p>
<p></p>
<p>
Output
</p>
<ul>
<li>
Line 1: A single integer that is the minimum number of destroyed flowers
</li>
</ul>
<p>
</p><p>
输出：
</p>
<p>
第1行：一个单独的整数，表示FJ损失的花的最小数目。
</p>
<p></p>
<p>
Sample Input
</p>
<pre>6
3 1
2 5
2 3
3 2
4 1
1 6
</pre>
<p>
Sample Output
</p>
<pre>86
</pre>
<p>
Output Details
</p>
<p>
FJ returns the cows in the following order: 6, 2, 3, 4, 1, 5. While he is transporting cow 6 to the barn, the others destroy 24 flowers; next he will take cow 2, losing 28 more of his beautiful flora. For the cows 3, 4, 1 he loses 16, 12, and 6 flowers respectively. When he picks cow 5 there are no more cows damaging the flowers, so the loss for that cow is zero. The total flowers lost this way is 24 + 28 + 16 + 12 + 6 = 86.
</p>
<p>
样例解释：
</p>
<p>
FJ赶牛的顺序是6-2-3-4-1-5，当他赶牛6时他损失了24朵花，当他赶牛2时他损失了28朵花，当他赶牛3时他损失了16朵花，
</p>
<p>
当他赶牛4时他损失了12朵花，当他赶牛1时他损失了6朵花，当他赶牛5时他损失了0朵花。24+28+16+12+6+0=86。
</p>
<p>
译：KZFFFFFFFF
</p>
