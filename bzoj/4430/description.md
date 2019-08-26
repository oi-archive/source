
# Description

<div class="content"><div>Jaap, Jan, and Thijs are on a trip to the desert after having attended the ACM ICPC World Finals 2015 in Morocco. The trip included a camel ride, and after returning from the ride, their guide invited them to a big camel race in the evening. The camels they rode will also participate and it is customary to bet on the results of the race.</div>
<div>One of the most interesting bets involves guessing the complete order in which the camels will finish the race. This bet offers the biggest return on your money, since it is also the one that is the hardest to get right.</div>
<div></div>
<div>Jaap, Jan, and Thijs have already placed their bets, but the race will not start until an hour from now, so they are getting bored. They started wondering how many pairs of camels they have put in the same order. If camel cc is before camel d on Jaap&#39;s, Jan&#39;s and Thijs&#39; bet, it means that all three of them put c and d in the same order. Can you help them to calculate the number of pairs of camels for which this happened?</div>
<div></div>
<div>Jaap，Jan和Thijs在摩洛哥参加完ACMICPC2015全球总决赛后去沙漠进行了一次旅行。旅行包括了骑骆驼。在骑完回来之后，他们的向导邀请他们在晚上去看一场盛大的骆驼赛跑。他们骑的骆驼也会参加，而赌比赛的结果是一个习惯。其中一个最有趣的赌涉及猜测完成比赛的骆驼的完整名单。这个赌可以为你赢得最多的钱，因为它也是最难猜对的。</div>
<div>Jaap，Jan和Thijs已经下了注，但比赛要在一个小时后才开始，所以他们觉得很无聊。他们开始想知道有多少对骆驼他们赌了同样的顺序。如果在他们三人的猜测名单中，骆驼c在骆驼d前，就意味着c和d在他们的名单中有相同的顺序。你能帮他们计算有多少对骆驼是这样的吗？</div>
<p></p></div>

# Input

<div class="content"><div>The input consists of:</div>
<div>one line with an integer n ( 2≤n≤200000), the number of camels;</div>
<div>one line with n integers a1,…,ana1,…,an ( 1≤ai≤n for all i ), Jaap&#39;s bet. Here a1 is the camel in the first position of Jaap&#39;s bet, a2 is the camel in the second position, and so on;</div>
<div>one line with Jan&#39;s bet, in the same format as Jaap&#39;s bet;</div>
<div>one line with Thijs&#39; bet, in the same format as Jaap&#39;s bet.</div>
<div>The camels are numbered 1,…,n . Each camel appears exactly once in each bet.</div>
<div>输入包括：</div>
<div>第一行是一个整数n（2&lt;=n&lt;=200000），骆驼的数量。</div>
<div>第二行有n个整数a1…an（1&lt;=ai&lt;=n），是Jaap的下赌名单。a1是名单中第一位，a2是第二位，等等。</div>
<div>第三行是Jan的名单，格式同上。</div>
<div>第四行是Thijs的名单，格式同上。</div>
<div>骆驼从1到n编号，每头骆驼在一份名单中只出现一次。</div>
<p></p></div>

# Output

<div class="content"><div>Output the number of pairs of camels that appear in the same order in all 3 bets.</div>
<div>输出在三份名单中同样顺序的骆驼有多少对。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">Sample input 1<br/>
3<br/>
3 2 1<br/>
1 2 3<br/>
1 2 3<br/>
Sample input 2<br/>
4<br/>
2 3 1 4<br/>
2 1 4 3<br/>
2 4 3 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">Sample output 1<br/>
0<br/>
Sample output 2<br/>
3<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

