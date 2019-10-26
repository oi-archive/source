
# Description

<div class="content"><div><span style="font-size: medium">在中国民间，人们相信鬼只能沿直线移动。在修建寺庙时，那是非常重要的。寺庙要修建在四边分别平行于南北西东的矩形位置之上。两个矩形不能有公共交点。入口位于四堵墙中一堵的中间，门的宽度等于墙长度的一半。祭坛出现在寺庙的中间，矩形的对角线在那里相交。如果鬼魂在这个点出现，那么寺庙将被亵渎。仅当存在从祭坛射出的一束光线，通过入口到外面而且不与其他寺庙（位于建筑区域平行的地带）的墙壁相交或接触，这种情形才可能发生，也就是能在建筑区域从祭坛到无穷远处画一条直线而不碰到任何墙。</span></div>
<div style="margin: auto 0cm"><span style="font-size: medium"><b>任务</b></span></div>
<div><span style="font-size: medium">写一个程序:  </span></div>
<ul type="disc">
    <li><span style="font-size: medium">读取寺庙的描述， </span></li>
    <li><span style="font-size: medium">检验哪个寺庙可能被亵渎， </span></li>
    <li><span style="font-size: medium">输出结果 </span></li>
</ul></div>

# Input

<div class="content"><div style="margin: auto 0cm"> <span style="font-size: medium">首行有一个整数n被列出（<i>1 &lt;= n &lt;= 1000</i>）。</span></div>
<div><span style="font-size: medium">在接下来的n行的每一行有一个寺庙的描述（在第I行有第I个寺庙的描述）。寺庙的描述由四个非负的不大于8000的整数和字母E,W,S和N组成。头两个数字是寺庙的西北角的坐标，接下来的两个是相对的东南角的坐标。为了指定一个点的坐标，我们给出了它的地理精度，从西往东增加，纬度从南往北增加。描述的第五个元素代表入口的墙（E-东，W-西，S-南，N-北）。寺庙的描述元素由单空格隔开。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">接下来的几行，你的程序应该按升序写下可能被鬼魂亵渎的寺庙编号。每一个编号占一行。如果没有编号，在文件OLT.OUT中，你应该写一个字符串：BRAK(波兰语中意思为“没有”)。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
1 7 4 1 E<br/>
3 9 11 8 S<br/>
6 7 10 4 N<br/>
8 3 10 1 N<br/>
11 4 13 1 E<br/>
14 8 20 7 W<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> <br/>
1<br/>
2<br/>
5<br/>
6<br/>
</span></div>

# Hint

<div class="content"><p></p><p><img height="292" width="606" alt="" src="/source/bzoj/2934/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIxMi8xMSgzKS5qcGc=.jpg"/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

