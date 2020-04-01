
# Description

<div class="content"><div>一个二维平面初始时为空，有一串往平面中加入点的命令。加入的点有两种，这里称为A类点和B类点（如图1，黑</div>
<div>色正方形表示A类点，小圆黑点表示B类点）。A类点一定位于X轴上，而且不会重叠，而B类点可以出现在平面上的</div>
<div>任何一个位置，可以重叠。每个B类点有一个权值W。</div>
<div><img src="/source/bzoj/1157/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMi8xKDMpLnBuZw==.png" width="541" height="218" alt=""/></div>
<div>处理：一、最初，将相邻两个A类点之间连一个与X轴成45度的正方形（如图2）。二、每次可以将任意两个有公共</div>
<div>点的正方形合并为一个大正方形，合并之后两个小正方形消失。图2的左数第2、3的正方形合并后在图3中表示为灰</div>
<div>边正方形。</div>
<div> <img src="/source/bzoj/1157/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMi8yKDIpLnBuZw==.png" width="348" height="241" alt=""/>        </div>
<div>合并后的正方形将平面划分为9个区域，与正方形4条边相邻的4个区域分别为图3中的I，II，III，IV。落在区域I</div>
<div>中的B类点的权值和记为w1，落在区域II中的B类点的权值和记为w2，落在区域III中的B类点的权值和记为w3，落在</div>
<div>区域IV中的B类点的权值和记为w4。落在灰色正方形内部的B类点的权值和记为w5（B类点保证不会出现在任何一个</div>
<div>区域的边界上），则合并费用为1w1+2w2+3w3+4w4+5w5。落在其他区域的B类点不予考虑。每次合并之后并不影响B</div>
<div>类点在平面上的位置和它自己所拥有的权值。每进行一次合并，由A类点形成的正方形会减少一个，直到只剩下一</div>
<div>个正方形为止。合并总费用为每次合并费用之和。不同合并顺序的合并费用可能会不同。点是一个一个加入到平面</div>
<div>的。加入第i个A类点后，平面上有i个A类点和在此之前加入的所有B类点。设此时的最小合并费用为f(i)。给定费</div>
<div>用限制L，编程求出A类点的最大数目K，使得前K个A类点的最小合并费用不超过L，即f(K)&lt;=L。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含两个数M，L，表示有M条加入点的命令，费用限制为L。</div>
<div>以下包含M行，每行一个字母表示点的类型。“A”表示A类点，“B”表示B类点。</div>
<div>对于A类点，后面一个数表示这个点的X坐标；</div>
<div>对于B类点，后面三个数表示这个点的X，Y坐标和这个点的权值。</div></div>

# Output

<div class="content"><p>输出件仅包含一个整数Kmax，即使f(K)&lt;=L的最大K。</p></div>

# Sample Input

<div class="content"><span class="sampledata">8 30.0<br/>
A -2<br/>
A 0<br/>
B 7 8 5.0<br/>
B 4 -3 2.0<br/>
B -3 4 1.0<br/>
A 2<br/>
B -4 5 1.0<br/>
A 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p><div>输入最后一个点时，所有点如下图。B类点旁边的数字为权值。</div><br/>
<div><img src="/source/bzoj/1157/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMi8zLnBuZw==.png" width="208" height="201" alt=""/></div><br/>
<div>合并前3个点的最小费用为f(3) = 27, 合并前4个点的最小费用f(4) = 36。</div><br/>
<div>由于f(3) &lt; 30而f(4) &gt; 30，因此最大的K为3。</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

