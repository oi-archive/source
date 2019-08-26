
# Description

<div class="content"><p></p>
<p></p>
<div class="pdcont" style="font-size: 12pt; color: rgb(32,0,0); font-family: &#39;Times New Roman&#39;, 宋体"></div>
<p></p>
<p><span id="1324814811462E" style="display: none"> </span></p>
<p></p>
<div class="pdcont" style="font-size: 12pt; color: rgb(32,0,0); font-family: &#39;Times New Roman&#39;, 宋体">　　铭铭有n个十分漂亮的珠子和若干根颜色不同的绳子。现在铭铭想用绳子把所有的珠子连接成一个整体。<br/>
　　现在已知所有珠子互不相同，用整数1到n编号。对于第i个珠子和第j个珠子，可以选择不用绳子连接，或者在ci,j根不同颜色的绳子中选择一根将它们连接。如果把珠子看作点，把绳子看作边，将所有珠子连成一个整体即为所有点构成一个连通图。特别地，珠子不能和自己连接。<br/>
　　铭铭希望知道总共有多少种不同的方案将所有珠子连成一个整体。由于答案可能很大，因此只需输出答案对1000000007取模的结果。<br/>
</div>
<div class="pdcont" style="font-size: 12pt; color: rgb(32,0,0); font-family: &#39;Times New Roman&#39;, 宋体">　</div></div>

# Input

<div class="content"><p><span style="font-size: medium">　标准输入。输入第一行包含一个正整数n，表示珠子的个数。接下来n行，每行包含n个非负整数，用空格隔开。这n行中，第i行第j个数为ci,j。<br/>
</span></p>
<div class="pdcont" style="font-size: 12pt; color: rgb(32,0,0); font-family: &#39;Times New Roman&#39;, 宋体"><span style="font-size: medium">　</span></div></div>

# Output

<div class="content"><p><span style="font-size: medium">　标准输出。输出一行一个整数，为连接方案数对1000000007取模的结果。<br/>
</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
0 2 3<br/>
2 0 4<br/>
3 4 0<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">50</span></div>

# Hint

<div class="content"><p></p><p>　　对于100%的数据，n为正整数，所有的ci,j为非负整数且不超过1000000007。保证ci,j=cj,i。每组数据的n值如下表所示。<br/><br/>
 <br/><br/>
编号 1 2 3 4 5 6 7 8 9 10    <br/><br/>
n      8 9 9 10 11 12 13 14 15 16  <br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2012国家集训队Round 1 day1">2012国家集训队Round 1 day1</a></p></div>

