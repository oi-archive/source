
# Description

<div class="content"><div>小H最近迷上了一个分隔序列的游戏。在这个游戏里，小H需要将一个长度为n的非负整数序列分割成k+1个非空的子序列。为了得到k+1个子序列，小H需要重复k次以下的步骤：</div>
<div>1.小H首先选择一个长度超过1的序列（一开始小H只有一个长度为n的序列——也就是一开始得到的整个序列）；</div>
<div>2.选择一个位置，并通过这个位置将这个序列分割成连续的两个非空的新序列。</div>
<div></div>
<div>每次进行上述步骤之后，小H将会得到一定的分数。这个分数为两个新序列中元素和的乘积。小H希望选择一种最佳的分割方式，使得k轮之后，小H的总得分最大。</div>
<div></div></div>

# Input

<div class="content"><p>输入第一行包含两个整数n，k（k+1≤n）。</p>
<div>第二行包含n个非负整数a1，a2，...，an（0≤ai≤10^4），表示一开始小H得到的序列。</div></div>

# Output

<div class="content"><p>输出第一行包含一个整数，为小H可以得到的最大分数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">7 3 <br/>
4 1 3 4 0 2 3 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">108 <br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"><br/><br/>
【样例说明】 <br/><br/>
在样例中，小H可以通过如下3轮操作得到108分： <br/><br/>
1．-开始小H有一个序列(4，1，3，4，0，2，3)。小H选择在第1个数之后的位置 <br/><br/>
将序列分成两部分，并得到4×(1+3+4+0+2+3)=52分。 <br/><br/>
2．这一轮开始时小H有两个序列：(4)，(1，3，4，0，2，3)。小H选择在第3个数 <br/><br/>
字之后的位置将第二个序列分成两部分，并得到(1+3)×(4+0+2+ <br/><br/>
3)=36分。 <br/><br/>
3．这一轮开始时小H有三个序列：(4)，(1，3)，(4，0，2，3)。小H选择在第5个 <br/><br/>
数字之后的位置将第三个序列分成两部分，并得到(4+0)×(2+3)= <br/><br/>
20分。 <br/><br/>
经过上述三轮操作，小H将会得到四个子序列：(4)，(1，3)，(4，0)，(2，3)并总共得到52+36+20=108分。 <br/><br/>
【数据规模与评分】 <br/><br/>
：数据满足2≤n≤100000,1≤k≤min(n -1，200)。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

