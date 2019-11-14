
# Description

<div class="content"><p><img height="773" alt="" width="732" src="/source/bzoj/3671/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwNy8yMigzKS5qcGc=.jpg"/></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第1行包含5个整数，依次为 x_0,a,b,c,d ，描述小H采用的随机数生成算法所需的随机种子。第2行包含三个整数 N,M,Q ，表示小H希望生成一个1到 N×M 的排列来填入她 N 行 M 列的棋盘，并且小H在初始的 N×M 次交换操作后，又进行了 Q 次额外的交换操作。接下来 Q 行，第 i 行包含两个整数 u_i,v_i，表示第 i 次额外交换操作将交换 T_(u_i )和 T_(v_i ) 的值。 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">输出一行，包含 N+M-1 个由空格隔开的正整数，表示可以得到的字典序最小的路径序列。 </span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1 3 5 1 71 <br/>
3 4 3 <br/>
1 7 <br/>
9 9 <br/>
4 9 </span></div>

# Sample Output

<div class="content"><span class="sampledata"> 1 2 6 8 9 12 </span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: large"><img height="425" alt="" width="731" src="/source/bzoj/3671/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwNy8xMSg1KS5qcGc=.jpg"/></span></p><br/>
<p class="NOI" style="margin: 2.4pt 0cm; text-indent: 24pt"><span style="font-size: large"><span style="font-family: 宋体">本题的空间限制是 256 MB，请务必保证提交的代码运行时所使用的总内存空间不超过此限制。</span></span></p><br/>
<p class="NOI" style="margin: 2.4pt 0cm; text-indent: 24pt"><span style="font-size: large"><span style="font-family: 宋体">一个32位整数（例如C/C++中的int和Pascal中的Longint）为4字节，因而如果在程序中声明一个长度为 1024×1024 的32位整型变量的数组，将会占用 4 MB 的内存空间。</span></span></p><br/>
<div style="text-indent: 32px"><span style="font-size: large"><br/><br/>
</span></div><br/>
<p><span style="font-size: large"><em>2≤N,M≤5000</em></span></p><br/>
<p><span style="font-size: large"><span lang="EN-US">0</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Timesnewroman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">≤</span><span lang="EN-US">Q</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times Newroman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">≤</span><span lang="EN-US">50000</span></span></p><br/>
<p><span style="font-size: large"><span lang="EN-US">0</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times Newroman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">≤</span><span lang="EN-US">a</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Timesnewroman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">≤</span><span lang="EN-US">300</span></span></p><br/>
<p><span style="font-size: large"><span lang="EN-US">0≤b,c≤108</span></span></p><br/>
<p><span style="font-size: large"><span lang="EN-US">0≤x0&lt;d≤108</span></span><span style="font-size: large"><span lang="EN-US">1≤ui,vi≤N×M</span></span></p><br/>
<p></p><br/>
<p class="MsoNormal" align="center" style="text-align: center"></p><br/>
<p></p><br/>
<p></p><br/>
<p class="MsoNormal" align="center" style="text-align: center"></p><br/>
<p></p><br/>
<p></p><br/>
<p class="MsoNormal" align="center" style="text-align: center"></p><br/>
<p><span id="1406602731997E" style="display: none"> </span></p><br/>
<p></p><br/>
<p class="MsoNormal" align="center" style="text-align: center"></p><br/>
<p></p><br/>
<p class="MsoNormal" align="center" style="text-align: center"></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

