
# Description

<div class="content"><div style="text-indent: 21pt" align="left"><span style="font-size: medium">Morenan被困在了一个迷宫里。迷宫可以视为N个点M条边的有向图，其中Morenan处于起点S，迷宫的终点设为T。可惜的是，Morenan非常的脑小，<b>他只会从一个点出发随机沿着一条从该点出发的有向边，到达另一个点。</b>这样，Morenan走的步数可能很长，也可能是无限，更可能到不了终点。<b>若到不了终点，则步数视为无穷大。</b>但你必须想方设法求出Morenan所走步数的期望值。</span></div></div>

# Input

<div class="content"><div style="text-indent: 21pt" align="left"><span style="font-size: medium">第1行4个整数，N,M,S,T</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">第[2, M+1]行每行两个整数o1, o2，表示有一条从o1到o2的边。</span></div></div>

# Output

<div class="content"><div style="text-indent: 21pt" align="left"><span style="font-size: medium">一个浮点数，保留小数点3位，为步数的期望值。若期望值为无穷大，则输出&#34;INF&#34;。</span></div>
<div align="left"><span style="font-size: medium">【样例输入1】</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">6 6 1 6</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">1 2</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">1 3</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">2 4</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">3 5</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">4 6</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">5 6</span></div>
<div align="left"><span style="font-size: medium">【样例输出1】</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">3.000</span></div>
<div align="left"><span style="font-size: medium">【样例输入2】</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">9 12 1 9</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">1 2</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">2 3</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">3 1</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">3 4</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">3 7</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">4 5</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">5 6</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">6 4</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">6 7</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">7 8</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">8 9</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">9 7</span></div>
<div align="left"><span style="font-size: medium">【样例输出2】</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">9.500</span></div>
<div align="left"><span style="font-size: medium">【样例输入3】</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">2 0 1 2</span></div>
<div align="left"><span style="font-size: medium">【样例输出3】</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">INF</span></div>
<div align="left"><span style="font-size: medium">【数据范围】</span></div>
<p><table cellspacing="0" cellpadding="0" border="1" style="border-right: medium none; border-top: medium none; border-left: medium none; border-bottom: medium none; border-collapse: collapse">
    <tbody>
        <tr style="height: 14.35pt">
            <td valign="top" width="142" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 106.5pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; height: 14.35pt; background-color: transparent">
            <div align="left"><span style="font-size: medium">测试点</span></div>
            </td>
            <td valign="top" width="142" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 106.5pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; height: 14.35pt; background-color: transparent">
            <div align="left"><span style="font-size: medium">N</span></div>
            </td>
            <td valign="top" width="142" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 106.55pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; height: 14.35pt; background-color: transparent">
            <div align="left"><span style="font-size: medium">M</span></div>
            </td>
            <td valign="top" width="142" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 106.55pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; height: 14.35pt; background-color: transparent">
            <div align="left"><span style="font-size: medium">Hint</span></div>
            </td>
        </tr>
        <tr>
            <td valign="top" width="142" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 106.5pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="left"><span style="font-size: medium">[1, 6]</span></div>
            </td>
            <td valign="top" width="142" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 106.5pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="left"><span style="font-size: medium">&lt;=10</span></div>
            </td>
            <td valign="top" width="142" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 106.55pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="left"><span style="font-size: medium">&lt;=100</span></div>
            </td>
            <td valign="top" width="142" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 106.55pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="left"><span style="font-size: medium"> </span></div>
            </td>
        </tr>
        <tr>
            <td valign="top" width="142" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 106.5pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="left"><span style="font-size: medium">[7, 12]</span></div>
            </td>
            <td valign="top" width="142" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 106.5pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="left"><span style="font-size: medium">&lt;=200</span></div>
            </td>
            <td valign="top" width="142" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 106.55pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="left"><span style="font-size: medium">&lt;=10000</span></div>
            </td>
            <td valign="top" width="142" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 106.55pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="left"><span style="font-size: medium"> </span></div>
            </td>
        </tr>
        <tr>
            <td valign="top" width="142" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 106.5pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="left"><span style="font-size: medium">[13, 20]</span></div>
            </td>
            <td valign="top" width="142" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 106.5pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="left"><span style="font-size: medium">&lt;=10000</span></div>
            </td>
            <td valign="top" width="142" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 106.55pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="left"><span style="font-size: medium">&lt;=1000000</span></div>
            </td>
            <td valign="top" width="142" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 106.55pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="left"><span style="font-size: medium">保证强连通分量的大小不超过100</span></div>
            <div align="left"><span style="font-size: medium"> </span></div>
            </td>
        </tr>
    </tbody>
</table>
</p>
<div align="left"><span style="font-size: medium"> </span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">另外，均匀分布着40%的数据，图中没有环，也没有自环</span></div></div>

# Sample Input

<div class="content"><span class="sampledata"></span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=round 1 day1">round 1 day1</a></p></div>

