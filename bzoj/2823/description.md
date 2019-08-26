
# Description

<div class="content"><div>在野外训练中，为了确保每位参加集训的成员安全，实时的掌握和收集周边环境和队员信息非常重要，集训队采用</div>
<div>的方式是在训练所在地散布N个小型传感器来收集并传递信息，这些传感器只与设在集训地中的信号塔进行通信，</div>
<div>信号塔接收信号的覆盖范围是圆形，可以接收到所有分布在该集训区域内所有N个小型传感器（包括在该圆形的边</div>
<div>上）发出的信号。信号塔的功率与信号塔接收范围半径的大小成正比，因为是野外训练，只能使用事先储备好的蓄</div>
<div>电设备，因此在可以收集所有传感器信息的基础上，还应使得信号塔的功率最小。小龙帮助教官确定了一种信号塔</div>
<div>设置的方案，既可以收集到所有N个传感器的信号，又可以保证这个信号塔的功率是最小的。同学们，你们知道，</div>
<div>这个信号塔的信号收集半径有多大，它应该设置在何处吗？</div></div>

# Input

<div class="content"><div>共N+1行，第一行为正整数N（1≤N≤1000000），表示队员个数。接下来N行，每行两个实数用空格分开，分别是第</div>
<div>i个队员的坐标X</div></div>

# Output

<div class="content"><div>一行，共三个实数（中间用空格隔开），分别是信号塔的坐标，和信号塔 覆盖的半径。 （注：队员是否在边界上</div>
<div>的判断应符合他到圆心的距离与信号塔接收半径之差的绝对值小于10^-6</div></div>

# Sample Input

<div class="content"><span class="sampledata">5 <br/>
1.200 1.200 <br/>
2.400 2.400 <br/>
3.800 4.500 <br/>
2.500 3.100 <br/>
3.900 1.300 </span></div>

# Sample Output

<div class="content"><span class="sampledata">2.50 2.85 2.10 </span></div>

# Hint

<div class="content"><p></p><p><span lang="EN-US" style="font-size: 12pt; color: black; font-family: &#34;Courier New&#34;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-fareast-font-family: 宋体; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">1≤N≤500000 </span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

