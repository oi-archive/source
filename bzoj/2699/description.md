
# Description

<div class="content"><div><span style="font-size: medium">       对于一个数列A[1..N]，一种寻找最大值的方法是：依次枚举A[2]到A[N]，如果A[i]比当前的A[1]值要大，那么就令A[1]=A[i]，最后A[1]为所求最大值。假设所有数都在范围[1, K]内，按上面的步骤执行，有多少个长度N的数列满足A[1]被更新的次数恰好为P呢？</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">       本题有多组数据。输入第一行一个数T为数据组数，下面T行每行依次三个数N、K和P。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">       对每组数据输出一行，为方案数模1000000007的值。</span></div>
<div><span style="font-size: medium"> </span></div>
<p><table cellspacing="0" cellpadding="0" border="1" style="border-right: medium none; border-top: medium none; border-left: medium none; border-bottom: medium none; border-collapse: collapse">
    <tbody>
        <tr>
            <td valign="top" width="164" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: black 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: black 1pt solid; width: 123.2pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">输入</span></div>
            </td>
            <td valign="top" width="164" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: black 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 123.2pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">输出</span></div>
            </td>
            <td valign="top" width="240" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: black 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 179.7pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">解释</span></div>
            </td>
        </tr>
        <tr>
            <td valign="top" width="164" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: black 1pt solid; width: 123.2pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">3</span></div>
            <div><span style="font-size: medium">4 3 2</span></div>
            <div><span style="font-size: medium">2 3 1</span></div>
            <div><span style="font-size: medium">3 4 1</span></div>
            </td>
            <td valign="top" width="164" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 123.2pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">6</span></div>
            <div><span style="font-size: medium">3</span></div>
            <div><span style="font-size: medium">30</span></div>
            </td>
            <td valign="top" width="240" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 179.7pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">对第一组数据N=4, K=3, P=2, 所有满足的序列有下面六种：</span></div>
            <div><span style="font-size: medium">1) {1,1,2,3}   2) {1,2,1,3}</span></div>
            <div><span style="font-size: medium">3) {1,2,2,3}   4) {1,2,3,1}</span></div>
            <div><span style="font-size: medium">5) {1,2,3,2}   6) {1,2,3,3}</span></div>
            </td>
        </tr>
    </tbody>
</table>
</p>
<div><span style="font-size: medium"> </span></div>
<div style="margin: 12pt 0cm 3pt"><span style="font-size: medium"><b>数据范围</b></span></div>
<div><span style="font-size: medium">       前20%的数据满足T ≤ 5</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">前50%的数据满足1 ≤ N ≤ 50，1 ≤ K ≤ 100</span></div>
<div><span style="font-size: medium">       对100%的数据，T ≤ 1000，1 ≤ N ≤ 150，0 ≤ P &lt; N，1 ≤ K ≤ 300</span></div></div>

# Sample Input

<div class="content"><span class="sampledata"></span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

