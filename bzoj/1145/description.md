
# Description

<div class="content"><div>　　在完成了古越州圆盘密码的研究之后，考古学家小布来到了南美大陆的西部。相传很久以前在这片土地上生活</div>
<div>着两个部落，一个部落崇拜闪电，另一个部落崇拜高山，他们分别用闪电和山峰的形状作为各自部落的图腾。小布</div>
<div>的团队在山洞里发现了一幅巨大的壁画，壁画上被标记出了N个点，经测量发现这N个点的水平位置和竖直位置是两</div>
<div>两不同的。小布认为这幅壁画所包含的信息仅与这N个点的相对位置有关，因此不妨设坐标分别为(1, y1) , (2, y</div>
<div>2), ..., (n, yn)，其中y1~yn是1~N的一个排列。小布的团队打算研究在这幅壁画中包含着多少个图腾，其中闪电</div>
<div>图腾的定义图示如下（图腾的形式只与4个纵坐标值的相对大小排列顺序有关）：</div>
<p> <img alt="" border="0" src="/source/bzoj/1145/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzExNDVfMS5qcGc=.jpg"/></p>
<div>　　崇拜高山的部落有两个氏族，因而山峰图腾有如下两种形式，左边为A类，右边为B类（同样，图腾的形式也都</div>
<div>只与4个纵坐标值的大小排列顺序有关）：</div>
<p></p>
<p><img alt="" border="0" src="/source/bzoj/1145/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzExNDVfMi5qcGc=.jpg"/> </p>
<div>　　小布的团队希望知道，这N个点中两个部落图腾数目的差值。因此在本题中，你需要帮助小布的团队编写一个</div>
<div>程序，计算闪电图腾数目减去山峰图腾数目的值，由于该值可能绝对值较大，本题中只需输出该值对16777216的余</div>
<div>数（注意余数必为正值，例如-1对16777216的余数为16777215）。</div></div>

# Input

<div class="content"><div>
<div>第一行包含一个整数N，为点的数目。</div>
<div>接下来一行包含N个整数，分别为y1,y2,…,yn。</div>
<div>保证y1,y2,…,yn是1~N的一个排列。</div>
<div>N≤200000</div>
</div></div>

# Output

<div class="content"><p>仅包含一个数，表示闪电图腾数目与山峰图腾数目的差值对16777216的余数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">【样例输入一】<br/>
 5<br/>
  1 5 3 2 4<br/>
【样例输入二】<br/>
 4<br/>
  1 2 4 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">【样例输出一】<br/>
0<br/>
【样例输出二】<br/>
16777215<br/>
样例一中共有1个闪电图腾（1324）和1个B类山峰图腾（1532）。<br/>
样例二中仅有一个A类山峰图腾（1243），故差值为-1，答案为16777215。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

