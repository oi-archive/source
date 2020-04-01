
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">D博士最近设计了一款新的密码锁，密码锁的工作原理如下：</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"><img height="59" width="122" alt="" src="/source/bzoj/2899/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIxMS8yLmpwZw==.jpg"/></span></div>
<div style="text-indent: 21pt"></div>
<div><span style="font-size: medium">       密码A是一个N个数的序列，每个元素都是1至N之间的一个整数。刚刚安装时，密码锁内部会随机出一个1至N的排列B，然后根据A、B产生一组比对码C：</span></div>
<div><span style="font-size: medium">       其中表示元素i在B中的位置，比如说：B = {3，1，2}，那么有：B<sub>3</sub><sup>-1</sup> =1、B<sub>1</sub><sup>-1</sup> =2。</span></div>
<div><span style="font-size: medium">       这种密码锁有非常优异的性能，比如说就算有人通过黑客手段得到C，他们也不可能轻易的得到正确的A输入，而如果没有A，仅仅得到了C也是没有用的。出于此，Y老板向D博士订购了一套这样的密码锁。这时一种D博士没有考虑到的特殊情况发生了：</span></div>
<div><span style="font-size: medium">       Y老板是一个非常健忘的人，有一天他竟然忘记了自己密码锁的密码！</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">D博士立刻从中取出了对应码C，但是因为不知道B，他仍然无法找出A的具体值，于是他把这个艰巨的任务交给你，他的助手。你的任务是，统计所有可能的A序列总数。</span></div></div>

# Input

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">输入文件第一行包含一个整数N，第二行包含N个整数表示对比码C。</span></div></div>

# Output

<div class="content"><div> </div>
<div style="text-indent: 21pt"><span style="font-size: medium">输出文件仅包含一个整数，即所有可能的A序列的总数，鉴于答案可能很大，你只需要输出其模1000000007的余数即可。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
3 2 5 2 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">120<br/>
Data Limit<br/>
对于30%的数据，有1 ≤ N ≤ 8。<br/>
对于100%的数据，有1 ≤ N ≤ 50。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

