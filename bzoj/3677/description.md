
# Description

<div class="content"><p><font face="Times New Roman" size="3">在列奥纳多·达·芬奇时期，有一个流行的童年游戏，叫做“连珠线”。不出所料，玩这个游戏只需要珠子和线，珠子从1到礼编号，线分为红色和蓝色。游戏 <br/>
开始时，只有1个珠子，而接下来新的珠子只能通过线由以下两种方式被加入： <br/>
1．Append(w，杪)：-个新的珠子w和一个已有的珠子杪连接，连接使用红线。 <br/>
2．Insert(w，u，v)：-个新的珠子w加入到一对通过红线连接的珠子（u，杪） <br/>
之间，并将红线改成蓝线。也就是将原来u连到1的红线变为u连到w的蓝线与W连到V的蓝线。 <br/>
无论红线还是蓝线，每条线都有一个长度。而在游戏的最后，将得到游戏的 <br/>
最后得分：所有蓝线的长度总和。 <br/>
现在有一个这个游戏的最终结构：你将获取到所有珠子之间的连接情况和所 <br/>
有连线的长度，但是你并不知道每条线的颜色是什么。 <br/>
你现在需要找到这个结构下的最大得分，也就是说：你需要给每条线一个颜 <br/>
色f红色或蓝色），使得这种连线的配色方案是可以通过上述提到的两种连线方式 <br/>
操作得到的，并且游戏得分最大。在本题中你只需要输出最大的得分即可。 <br/>
</font></p></div>

# Input

<div class="content"><p><font face="Times New Roman" size="3">第一行是一个正整数n，表示珠子的个数，珠子编号为1刭n。 <br/>
接下来n-l行，每行三个正整数ai，bi(l≤ai10000)，表示有一条长度为ci的线连接了珠子ai和珠子bi。 <br/>
</font></p></div>

# Output

<div class="content"><p><font face="Times New Roman" size="3">输出一个整数，为游戏的最大得分。 <br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2 10<br/>
1 3 40<br/>
1 4 15<br/>
1 5 20</span></div>

# Sample Output

<div class="content"><span class="sampledata">60 <br/>
<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">数据范围满足1≤n≤200000。 <br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

