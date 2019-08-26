
# Description

<div class="content"><div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">背景【backboard】：</span></div>
<div><span style="font-size: medium"> Memphis等一群蒟蒻出题中，花神凑过来秒题……</span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">描述【discribe】：</span></div>
<div><span style="font-size: medium"> 花花山峰峦起伏，峰顶常年被雪，Memphis打算帮花花山风景区的人员开发一个滑雪项目。</span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium"> 我们可以把风景区看作一个n*n的地图，每个点有它的初始高度，滑雪只能从高处往低处滑【严格大于】。但是由于地势经常变动【比如雪崩、滑坡】，高度经常变化；同时，政府政策规定对于每个区域都要间歇地进行保护，防止环境破坏。现在，滑雪项目的要求是给出每个n*n个点的初始高度，并给出m个命令，C a b c表示坐标为a,b的点的高度改为c；S a b c d表示左上角为a,b右下角为c,d的矩形地区开始进行保护，即不能继续滑雪；B a b c d表示左上角为a b,右下角为c d的矩形地区取消保护，即可以开始滑雪；Q表示询问现在该风景区可以滑雪的最长路径为多少。对于每个Q要作一次回答。</span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium"> 花神一看，这不是超简单！立刻秒出了标算~</span></div>
<div><span style="font-size: medium"> </span></div>
<p></p></div>

# Input

<div class="content"><div style="text-indent: 12pt"><span style="font-size: medium">第一行n，第二行开始n*n的地图，意义如上；接下来一个m，然后是m个命令，如上</span></div>
<div><span style="font-size: medium"> </span></div>
<p></p></div>

# Output

<div class="content"><div><span style="font-size: medium">对于每一个Q输出单独一行的回答</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2 3 4 5<br/>
10 9 8 7 6<br/>
11 12 13 14 15<br/>
20 19 18 17 16<br/>
21 22 23 24 25<br/>
5<br/>
C 1 1 3<br/>
Q<br/>
S 1 3 5 5<br/>
S 3 1 5 5<br/>
Q<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">24<br/>
3<br/>
 <br/>
样例解释：<br/>
第一个Q路线为：25-&gt;24-&gt;23-&gt;22….-&gt;3-&gt;2<br/>
第二个Q的路线为：10-&gt;9-&gt;2<br/>
</span></div>

# Hint

<div class="content"><p></p><p>100%的数据：1&lt;=n&lt;=700;1&lt;=m&lt;=1000000;其中Q、S、B操作总和&lt;=100;<br/><br/>
题中所有数据不超过2*10^9</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=原创 Memphis">原创 Memphis</a></p></div>

