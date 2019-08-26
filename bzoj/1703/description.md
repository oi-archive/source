
# Description

<div class="content"><div><span style="font-size: medium">    农夫约翰有N(1≤N≤1000)头奶牛，每一头奶牛都有一个确定的独一无二的正整数产奶率．约翰想要让这些奶牛按产奶率从高到低排序．    约翰已经比较了M(1≤M≤10000)对奶牛的产奶率，但他发现，他还需要再做一张关于另外C对奶牛的产奶率比较，才能推断出所有奶牛的产奶率排序．请帮他确定C的最小值．</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">    第1行包含两个用空格分开的整数N和M.接下来M行，每行有两个用空格分开的整数X和Y(1≤X，y≤1000)，表示奶牛X的产奶率高于奶牛Y.</span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">  C的最小值．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
2 1<br/>
1 5<br/>
2 3<br/>
1 4<br/>
3 4<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
FJ is comparing 5 cows and has already determined that cow 2 &gt; cow<br/>
1, cow 1 &gt; cow 5, cow 2 &gt; cow 3, cow 1 &gt; cow 4, and cow 3 &gt; cow 4<br/>
(where the &#39;&gt;&#39; notation means &#34;produces milk more quickly&#34;).<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">    </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">从输入样例中可以发现，约翰已经知道的排名有奶牛</span><span lang="EN-US"><font face="Times New Roman">2&gt;</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">奶牛</span><span lang="EN-US"><font face="Times New Roman">1&gt;</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">奶牛</span><span lang="EN-US"><font face="Times New Roman">5</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和奶牛</span><span lang="EN-US"><font face="Times New Roman">2&gt;</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">奶牛</span><span lang="EN-US"><font face="Times New Roman">3&gt;</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">奶牛</span><span lang="EN-US"><font face="Times New Roman">4</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，奶牛</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">排名第一．但是他还需要知道奶牛</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的名次是否高于奶牛</span><span lang="EN-US"><font face="Times New Roman">3</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">来确定排名第</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的奶牛，假设奶牛</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的名次高于奶牛</span><span lang="EN-US"><font face="Times New Roman">3</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">．接着，他需要知道奶牛</span><span lang="EN-US"><font face="Times New Roman">4</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和奶牛</span><span lang="EN-US"><font face="Times New Roman">5</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的名次，假设奶牛</span><span lang="EN-US"><font face="Times New Roman">5</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的名次高于奶牛</span><span lang="EN-US"><font face="Times New Roman">4</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">．在此之后，他还需要知道奶牛</span><span lang="EN-US"><font face="Times New Roman">5</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的名次是否高于奶牛</span><span lang="EN-US"><font face="Times New Roman">3</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">．所以，他至少仍需要知道</span><span lang="EN-US"><font face="Times New Roman">3</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个关于奶牛的排名．</span></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

