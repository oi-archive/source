
# Description

<div class="content"><div><span style="font-size: medium">       Alice家里有一盏很大的吊灯。所谓吊灯，就是由很多个灯泡组成。只有一个灯泡是挂在天花板上的，剩下的灯泡都是挂在其他的灯泡上的。也就是说，整个吊灯实际上类似于一棵树。其中编号为1的灯泡是挂在天花板上的，剩下的灯泡都是挂在编号小于自己的灯泡上的。</span></div>
<div><span style="font-size: medium">       现在，Alice想要办一场派对，她想改造一下这盏吊灯，将灯泡换成不同的颜色。她希望相同颜色的灯泡都是相连的，并且每一种颜色的灯泡个数都是相同的。</span></div>
<div><span style="font-size: medium">       Alice希望你能告诉她，总共有哪些方案呢？</span></div>
<div><span style="font-size: medium">       Alice是一个贪心的孩子，如果她发现方案不够多，或者太多了，就会很不高兴，于是她会尝试调整。对于编号为x(x≠1)的灯泡，如果原来是挂在编号为f[x]的灯泡上，那么Alice会把第x个灯泡挂到第 ( f[x] + 19940105 ) mod (x-1) + 1 个灯泡上。</span></div>
<div><span style="font-size: medium">       由于九在古汉语中表示极大的数，于是，Alice决定只调整9次。对于原始状态和每一次调整过的状态，Alice希望你依次告诉她每种状态下有哪些方案。</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">       第一行一个整数n，表示灯泡的数量。</span></div>
<div><span style="font-size: medium">       接下来一行，有n-1个整数Ui，第i个数字表示第i+1个灯泡挂在了Ui个的下面。保证编号为1的灯泡是挂在天花板上的。数字之间用逗号‘，’隔开且最后一个数字后面没有逗号。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">       对于10种状态下的方案，需要按照顺序依次输出。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">对于每一种状态，需要先输出单独的一行，表示状态编号，如样例所示。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">之后若干行，每行1个整数，表示划分方案中每种颜色的灯泡个数。</span></div>
<div><span style="font-size: medium">       按升序输出。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
1,2,3,4,5<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1:<br/>
1<br/>
2<br/>
3<br/>
6<br/>
Case #2:<br/>
1<br/>
2<br/>
6<br/>
Case #3:<br/>
1<br/>
3<br/>
6<br/>
Case #4:<br/>
1<br/>
3<br/>
6<br/>
Case #5:<br/>
1<br/>
3<br/>
6<br/>
Case #6:<br/>
1<br/>
2<br/>
6<br/>
Case #7:<br/>
1<br/>
2<br/>
3<br/>
6<br/>
Case #8:<br/>
1<br/>
6<br/>
Case #9:<br/>
1<br/>
2<br/>
6<br/>
Case #10:<br/>
1<br/>
3<br/>
6<br/>
</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
       对于100%的数据，n&lt;=1.2*106。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

