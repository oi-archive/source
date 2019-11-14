
# Description

<div class="content"><p><span style="font-size: medium">　　在平面直角坐标系中，Wayne需要你完成n次操作，操作只有两种：<br/>
　　1.0 x y。表示在坐标系中加入一个以(x, y)为圆心且过原点的圆。<br/>
　　2.1 x y。表示询问点(x, y)是否在所有已加入的圆的内部（含圆周），且至少在一个圆内部（含圆周）。<br/>
　　为了减少你的工作量，题目保证圆心严格在x轴上方（纵坐标为正），且横坐标非零。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">　　第1行一个整数n。<br/>
　　接下来n行，每行第一个数是0或1，分别表示两种操作。<br/>
　　接着有两个实数x和y，具体意义见题面。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">　　对于每个询问操作，如果点在所有已加入的圆内（或圆周上），则输出“Yes”（不含引号）；否则输出“No”（不含引号）。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
0 2.0000 3.0000<br/>
0 4.0000 1.0000<br/>
1 1.000000 1.000000<br/>
0 -3.0000 2.0000<br/>
1 1.000000 1.000000<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Yes<br/>
No</span></div>

# Hint

<div class="content"><p></p><div id="pcont1" style="margin-top: 20px; display: block; word-spacing: 0px; font: 12px ����, &#39;Times New Roman&#39;; text-transform: none; color: rgb(0,0,0); text-indent: 0px; white-space: normal; letter-spacing: normal; background-color: rgb(255,255,255); text-align: left; orphans: 2; widows: 2; webkit-text-size-adjust: auto; webkit-text-stroke-width: 0px"><br/>
<div class="pdcont" style="font-size: 14px; color: rgb(32,0,0); font-family: &#39;Times New Roman&#39;, ����"><img height="313" width="523" alt="" src="/source/bzoj/2961/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIxMi8xMSg2KS5qcGc=.jpg"/></div><br/>
<div class="pdcont" style="font-size: 14px; color: rgb(32,0,0); font-family: &#39;Times New Roman&#39;, ����">对于100%的数据，n≤500000，所有坐标绝对值不超过10000。<br/><br/>
　　输入数据保证圆心纵坐标为正，横坐标非零。<br/><br/>
　　圆心坐标保留4位小数，询问点坐标保留6位小数，请选手注意控制精度。<br/><br/>
</div><br/>
</div><br/>
<p><br class="Apple-interchange-newline"/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=中国国家队清华集训 2012-2013 第二天">中国国家队清华集训 2012-2013 第二天</a></p></div>

