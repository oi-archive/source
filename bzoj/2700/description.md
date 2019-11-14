
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">Alice正在组织一次有M位同学参加的同学聚会。Alice有N种不同的茶，每种茶有各自的单价和类别（红茶或绿茶）。每隔一单位时间，聚会上都有一个同学离开。Alice希望安排一种泡茶的方案，每单位时间都给所有剩下的同学们泡同一种之前没有泡过的茶，花费就是此茶的单价乘以剩余的同学数。同时，他不希望连续三次泡的茶都是红茶或都是绿茶。请你找出一种方案，在满足上面的条件下使得总花费最小。如果有多种方案，找出任意一种。保证存在解。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">       输入第一行两个数M和N，下面N行每行两个数ci和si，ci为第i种茶的单价，si=1表示第i种茶是红茶，si=0表示第i种茶是绿茶。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">       输出第一行为最小总花费，</span><span style="font-size: medium"><b>样例数据</b></span></div>
<p><table cellspacing="0" cellpadding="0" border="1" style="border-right: medium none; border-top: medium none; border-left: medium none; border-bottom: medium none; border-collapse: collapse">
    <tbody>
        <tr>
            <td valign="top" width="155" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: black 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: black 1pt solid; width: 116.1pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">输入</span></div>
            </td>
            <td valign="top" width="155" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: black 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 116.1pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">输出</span></div>
            </td>
            <td valign="top" width="259" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: black 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 193.9pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">说明</span></div>
            </td>
        </tr>
        <tr>
            <td valign="top" width="155" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: black 1pt solid; width: 116.1pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">3 4</span></div>
            <div><span style="font-size: medium">1 0</span></div>
            <div><span style="font-size: medium">2 0</span></div>
            <div><span style="font-size: medium">4 1</span></div>
            <div><span style="font-size: medium">3 1</span></div>
            </td>
            <td valign="top" width="155" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 116.1pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">10</span></div>
            </td>
            <td valign="top" width="259" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 193.9pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">第一次泡单价1的绿茶，花费1*3；第二次泡单价2的绿茶，花费2*2；第三次泡单价3的红茶，花费3*1。总花费3+4+3=10。</span></div>
            </td>
        </tr>
    </tbody>
</table>
</p>
<div><span style="font-size: medium"> </span></div>
<div style="margin: 12pt 0cm 3pt"><span style="font-size: medium"><b>数据规模</b></span></div>
<div><span style="font-size: medium">       对于20%的数据满足1 ≤ M ≤ N ≤ 10</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">对于50%的数据满足1 ≤ M ≤ N ≤ 100</span></div>
<div><span style="font-size: medium">       对于100%的数据满足1 ≤ M ≤ N ≤ 1000，1 ≤ ci ≤ 100000</span></div></div>

# Sample Input

<div class="content"><span class="sampledata"></span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

