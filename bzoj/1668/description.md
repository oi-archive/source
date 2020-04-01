
# Description

<div class="content"><p><span style="font-size: medium">最近，奶牛们热衷于把金币包在面粉里，然后把它们烤成馅饼。第i块馅饼中含有Ni(1&lt;=Ni&lt;=25)块金币，并且，这个数字被醒目地标记在馅饼表面。 奶牛们把所有烤好的馅饼在草地上排成了一个R行(1&lt;=R&lt;=100)C列(1&lt;=C&lt;=100)的矩阵。你现在站在坐标为(1,1)的馅饼边上，当然，你可以拿到那块馅饼里的所有金币。你必须从现在的位置，走到草地的另一边，在坐标为(R,C)的馅饼旁边停止走动。每做一次移动，你必须走到下一列的某块馅饼旁边，并且，行数的变动不能超过1（也就是说，如果现在你站在坐标为(r,c)的馅饼边上，下一步你可以走到坐标为(r-1,c+1),(r,c+1),或者(r+1,c+1)的馅饼旁边）。当你从一块馅饼边经过，你就可以拿走馅饼里所有的金币。当然啦，你一定不会愿意因半路离开草地而失去唾手可得的金币，但，最终你一定得停在坐标为(R,C)的馅饼旁边。 现在，你拿到了一张标记着馅饼矩阵中，每一块馅饼含金币数量的表格。那么，按照规则，你最多可以拿到多少金币呢？ 比方说，奶牛们把馅饼排成如下的矩阵，矩阵中的数字表示该位置的馅饼中含金币的数量：</span></p>
<p><span style="font-size: medium">6 5 3 7 9 2 7<br/>
2 4 3 5 6 8 6<br/>
4 9 9 9 1 5 8</span></p>
<p><span style="font-size: medium">以下是条合法的路线</span></p>
<p><span style="font-size: medium"><img height="145" width="291" alt="" src="/source/bzoj/1668/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS8yMig2KS5qcGc=.jpg"/></span></p>
<p><span style="font-size: medium">
</span></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Times New Roman">    </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">按上述的路线进行走动，一共可以获得</span><span lang="EN-US"><font face="Times New Roman">6+4+9+9+6+5+8=47</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个金币．按照规则，在这</span></font><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个矩阵中最多可以得到</span><span lang="EN-US"><font face="Times New Roman">50</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个金币，路线如下图所示：</span></font></p>
<p></p>
<p></p>
<p></p>
<p><span style="font-size: medium"><img height="146" width="291" alt="" src="/source/bzoj/1668/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS8yMig3KS5qcGc=.jpg"/></span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第1行: 两个用空格隔开的整数，R和C </span></p>
<p><span style="font-size: medium">* 第2..R+1行: 每行包含C个用空格隔开的正整数，依次表示一行中从左往右各 个馅饼里金币的数量 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第1行: 输出一个正整数，表示你所能收集到的最大金币数目 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 7<br/>
6 5 3 7 9 2 7<br/>
2 4 3 5 6 8 6<br/>
4 9 9 9 1 5 8<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">50<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

