
# Description

<div class="content"><div><span style="font-size: medium">小Y有一个又一个奇怪的想法，比如数的计数，块的计数等。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">想法虽多，但是某些想法却会和另一些想法矛盾。某个想法i出现的时候，或什么都不会影响，或肯定(或否定)想法i之后出现的某个想法A[i]。小Y每天每时每刻每秒都会有新的想法产生。小Y有的时候想知道，对的想法最多有多少个。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">即便如此，小Y仍表示十分苦恼，因为自己所有的想法几乎不可能都是对的。所以有时候他会YY：1.假如某个想法x不是肯定(或否定)A[x]，而是肯定(或否定)y的话，该多好啊(想法y可能出现在想法x之前)；2.假如某个想法x没有肯定(或否定)A[x]该多好啊。当然，光想想也不能知道这样改变之后是不是会更好。所以，每次小YYY的时候，都想知道，假如上述某一条件达成，是否会出现悖论，如果没有出现悖论，对的想法最多有几个。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">小Y知道，凭借自己的智商是没有办法解决这个问题的。所以他又找到了你……</span></div>
<div><span style="font-size: medium">       注意：1.YY是不会对现实有任何影响的，所以任何A[i]在小YYY前后保持不变；</span></div>
<div><span style="font-size: medium">2.小Y知道自己最后会有几个想法，所以在计算想法个数时，未出现的想法也必须统计在内。</span></div>
<div><span style="font-size: medium">3.错的想法对应的观点必然是错的，不存在某个想法的观点是对的，想法本身却是错的，具体见样例解释第2条。</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">       第一行两个整数N，M，分别表示小Y想法的个数和各种操作的总个数。</span></div>
<div><span style="font-size: medium">       接下来M行，每行可能为：</span></div>
<div><span style="font-size: medium">              1.Add_idea x y k：出现想法x，A[x]=y。当A[x]=-1时，想法x什么都不影响；否则，当k=0时否定想法A[x]；当k=1时肯定想法A[x]。该操作的总次数固定为N。</span></div>
<div><span style="font-size: medium">              2.Max：输出对的想法最多有多少个。</span></div>
<div><span style="font-size: medium">              3.If x y k then …：如果A[x]变成y后出现悖论输出0，否则输出1，并输出对的想法最多有多少个。当y=-1时对应小YYY的第二种情况。其中x可以是没有出现过的想法。</span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">       对于每个Max操作，单独输出一行一个整数Ans，表示所求的答案。</span></div>
<div><span style="font-size: medium">       对于每个If x y k then …操作，假如出现悖论，单独输出一行一个整数0；否则输出一行两个整数1和Ans，Ans表示所求的答案。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 7<br/>
Max<br/>
Add_idea 1 2 0<br/>
Max<br/>
If 1 2 1 then …<br/>
Add_idea 2 3 0<br/>
Add_idea 3 -1 0<br/>
If 3 1 0 then …<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
2<br/>
1 3<br/>
0<br/>
【样例解释】<br/>
       1.初始三个想法各不影响，都可以是对的。<br/>
2.想法1否定了想法2，所以想法1、2中必然有一个是错的。所以对的想法最多为2。在此声明，想法1、2不可能都错，因为假如想法2是错的，想法1就是对的。<br/>
3.同2。<br/>
4.如果想法1不是否定想法2，而是肯定想法2，那么3个想法可以都是对的。<br/>
5.想法2否定了想法3。<br/>
6.想法3出现了，没有任何影响。<br/>
7.假如想法3不是肯定想法1，而是否定了想法1，那么假如想法3是对的，想法1就是错的，想法2就是对的，想法3就是错的，自相矛盾，出现悖论。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

