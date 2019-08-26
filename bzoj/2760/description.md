
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">小A是B公司的一名PM(product market)。B公司越来越注重产品使用情况分析，而小A的工作就是整天对着一堆数据分析来分析去，没完没了。其中有一个操作是小A很头疼的，就是要把多个csv文件的数据拷到同一个excel文件中去。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">有一天小A满怀期待地找到了你，一个高级程序员，她想让你写程序帮她完成这个简单重复性工作。这不是坑爹吗，直接操作excel还要用到第三方的库，还不如直接写到csv文件中，让她再手动去转成excel文件。经过内部沟通协调，最终定下了这个方案。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">csv是一种excel可支持和格式，且存储方式非常简单。它实际上就是用“，”来分隔相邻的两个列。比如以下三行数据</span></div>
<div style="border-right: windowtext 1pt solid; padding-right: 4pt; border-top: windowtext 1pt solid; padding-left: 4pt; padding-bottom: 1pt; border-left: windowtext 1pt solid; padding-top: 1pt; border-bottom: windowtext 1pt solid">
<div style="border-right: medium none; padding-right: 0cm; border-top: medium none; padding-left: 0cm; padding-bottom: 0cm; border-left: medium none; padding-top: 0cm; border-bottom: medium none"><span style="font-size: medium">a,a,a</span></div>
<div style="border-right: medium none; padding-right: 0cm; border-top: medium none; padding-left: 0cm; padding-bottom: 0cm; border-left: medium none; padding-top: 0cm; border-bottom: medium none"><span style="font-size: medium">b,,b</span></div>
<div style="border-right: medium none; padding-right: 0cm; border-top: medium none; padding-left: 0cm; padding-bottom: 0cm; border-left: medium none; padding-top: 0cm; border-bottom: medium none"><span style="font-size: medium">,c,c</span></div>
</div>
<div style="text-indent: 21pt"><span style="font-size: medium">表示的就是</span></div>
<div align="center">
<table cellspacing="0" cellpadding="0" border="1" style="border-right: medium none; border-top: medium none; border-left: medium none; border-bottom: medium none; border-collapse: collapse">
    <tbody>
        <tr>
            <td valign="top" width="35" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: black 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: black 1pt solid; width: 26.15pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">a</span></div>
            </td>
            <td valign="top" width="35" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: black 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 26.15pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">a</span></div>
            </td>
            <td valign="top" width="35" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: black 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 26.15pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">a</span></div>
            </td>
        </tr>
        <tr>
            <td valign="top" width="35" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: black 1pt solid; width: 26.15pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">b</span></div>
            </td>
            <td valign="top" width="35" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 26.15pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
            <td valign="top" width="35" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 26.15pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">b</span></div>
            </td>
        </tr>
        <tr>
            <td valign="top" width="35" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: black 1pt solid; width: 26.15pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
            <td valign="top" width="35" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 26.15pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">c</span></div>
            </td>
            <td valign="top" width="35" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 26.15pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">c</span></div>
            </td>
        </tr>
    </tbody>
</table>
</div>
<div style="text-indent: 21pt"><span style="font-size: medium">现在小A想做的就是把各个文件按照从左往右的顺序拷到同一个文件当中。比如文件a的数据是</span></div>
<div style="border-right: windowtext 1pt solid; padding-right: 4pt; border-top: windowtext 1pt solid; padding-left: 4pt; padding-bottom: 1pt; border-left: windowtext 1pt solid; padding-top: 1pt; border-bottom: windowtext 1pt solid">
<div style="border-right: medium none; padding-right: 0cm; border-top: medium none; padding-left: 0cm; padding-bottom: 0cm; border-left: medium none; padding-top: 0cm; border-bottom: medium none"><span style="font-size: medium">a1,b1,c1</span></div>
<div style="border-right: medium none; padding-right: 0cm; border-top: medium none; padding-left: 0cm; padding-bottom: 0cm; border-left: medium none; padding-top: 0cm; border-bottom: medium none"><span style="font-size: medium">a2,b2</span></div>
</div>
<div style="text-indent: 21pt"><span style="font-size: medium">文件b的数据是</span></div>
<div style="border-right: windowtext 1pt solid; padding-right: 4pt; border-top: windowtext 1pt solid; padding-left: 4pt; padding-bottom: 1pt; border-left: windowtext 1pt solid; padding-top: 1pt; border-bottom: windowtext 1pt solid">
<div style="border-right: medium none; padding-right: 0cm; border-top: medium none; padding-left: 0cm; padding-bottom: 0cm; border-left: medium none; padding-top: 0cm; border-bottom: medium none"><span style="font-size: medium">a1,b1,c1,d1</span></div>
<div style="border-right: medium none; padding-right: 0cm; border-top: medium none; padding-left: 0cm; padding-bottom: 0cm; border-left: medium none; padding-top: 0cm; border-bottom: medium none"><span style="font-size: medium">a2,b2</span></div>
<div style="border-right: medium none; padding-right: 0cm; border-top: medium none; padding-left: 0cm; padding-bottom: 0cm; border-left: medium none; padding-top: 0cm; border-bottom: medium none"><span style="font-size: medium">a3,b3,c3</span></div>
<div style="border-right: medium none; padding-right: 0cm; border-top: medium none; padding-left: 0cm; padding-bottom: 0cm; border-left: medium none; padding-top: 0cm; border-bottom: medium none"><span style="font-size: medium">a4</span></div>
</div>
<div style="text-indent: 21pt"><span style="font-size: medium">那么她所希望的最终结果是</span></div>
<div align="center">
<table cellspacing="0" cellpadding="0" border="1" style="border-right: medium none; border-top: medium none; border-left: medium none; border-bottom: medium none; border-collapse: collapse">
    <tbody>
        <tr>
            <td valign="top" width="43" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: black 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: black 1pt solid; width: 32.45pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">a</span></div>
            </td>
            <td valign="top" width="40" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: black 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 29.65pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: black 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: black 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">b</span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: black 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: black 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: black 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
        </tr>
        <tr>
            <td valign="top" width="43" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: black 1pt solid; width: 32.45pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">a1</span></div>
            </td>
            <td valign="top" width="40" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 29.65pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">b1</span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">c1</span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">a1</span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">b1</span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">c1</span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">d1</span></div>
            </td>
        </tr>
        <tr>
            <td valign="top" width="43" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: black 1pt solid; width: 32.45pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">a2</span></div>
            </td>
            <td valign="top" width="40" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 29.65pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">b2</span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">a2</span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">b2</span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
        </tr>
        <tr>
            <td valign="top" width="43" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: black 1pt solid; width: 32.45pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
            <td valign="top" width="40" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 29.65pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">a3</span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">b3</span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">c3</span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
        </tr>
        <tr>
            <td valign="top" width="43" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: black 1pt solid; width: 32.45pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
            <td valign="top" width="40" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 29.65pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium">a4</span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
            <td valign="top" width="38" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 1cm; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent">
            <div><span style="font-size: medium"> </span></div>
            </td>
        </tr>
    </tbody>
</table>
</div>
<div style="text-indent: 21pt"><span style="font-size: medium">这个结果在csv文件里就是</span></div>
<div style="border-right: windowtext 1pt solid; padding-right: 4pt; border-top: windowtext 1pt solid; padding-left: 4pt; padding-bottom: 1pt; border-left: windowtext 1pt solid; padding-top: 1pt; border-bottom: windowtext 1pt solid">
<div style="border-right: medium none; padding-right: 0cm; border-top: medium none; padding-left: 0cm; padding-bottom: 0cm; border-left: medium none; padding-top: 0cm; border-bottom: medium none"><span style="font-size: medium">a,,,b,,,</span></div>
<div style="border-right: medium none; padding-right: 0cm; border-top: medium none; padding-left: 0cm; padding-bottom: 0cm; border-left: medium none; padding-top: 0cm; border-bottom: medium none"><span style="font-size: medium">a1,b1,c1,a1,b1,c1,d1</span></div>
<div style="border-right: medium none; padding-right: 0cm; border-top: medium none; padding-left: 0cm; padding-bottom: 0cm; border-left: medium none; padding-top: 0cm; border-bottom: medium none"><span style="font-size: medium">a2,b2,,a2,b2,,</span></div>
<div style="border-right: medium none; padding-right: 0cm; border-top: medium none; padding-left: 0cm; padding-bottom: 0cm; border-left: medium none; padding-top: 0cm; border-bottom: medium none"><span style="font-size: medium">,,,a3,b3,c3,</span></div>
<div style="border-right: medium none; padding-right: 0cm; border-top: medium none; padding-left: 0cm; padding-bottom: 0cm; border-left: medium none; padding-top: 0cm; border-bottom: medium none"><span style="font-size: medium">,,,a4,,,</span></div>
</div>
<div style="text-indent: 21pt"><span style="font-size: medium">以上结果的第一行是每一个文件的文件名，文件名与相应文件的第一列对齐。如果相应文件不止一列，那么其它列用空的单元格来补充。</span></div>
<div><span style="font-size: medium">输入的csv文件里保证了每一行的末尾都没有“，”，也就是说像a文件的第2行的第3列一样，如那一格是空的，那么在b2后面是没有“，”的。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">输出的csv文件里因为是程序的输出结果，为了简化程序，如果末尾是空的，那么还是会显式输出“，”，如以上的结果所示。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">输入文件保证至少有一行一列非空。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">输出的文件要保证下一个文件的第一列要紧邻着上一文件的最后一个非空列的右面。最后一个文件只输出到最后一个非空列。</span></div></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21.2pt; mso-char-indent-count: 2.02"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第一行有一个整数</span><span lang="EN-US"><font face="Times New Roman">N</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">（</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体">≤</span><span lang="EN-US"><font face="Times New Roman">N</font></span><span style="font-family: 宋体">≤</span><span lang="EN-US"><font face="Times New Roman">100</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">），表示有</span><span lang="EN-US"><font face="Times New Roman">N</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个文件。</span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21.2pt; mso-char-indent-count: 2.02"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">以下</span><span lang="EN-US"><font face="Times New Roman">N</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个数据块的第一行有一个整数</span><span lang="EN-US"><font face="Times New Roman">M (1</font></span><span style="font-family: 宋体">≤</span><span lang="EN-US"><font face="Times New Roman">M</font></span><span style="font-family: 宋体">≤</span><span lang="EN-US"><font face="Times New Roman">100)</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和一个字符串</span><span lang="EN-US"><font face="Times New Roman">S (1</font></span><span style="font-family: 宋体">≤</span><span lang="EN-US"><font face="Times New Roman">length(S)</font></span><span style="font-family: 宋体">≤</span><span lang="EN-US"><font face="Times New Roman">100)</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">M</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">表示文件的行数，</span><span lang="EN-US"><font face="Times New Roman">S</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">表示文件名。</span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21.2pt; mso-char-indent-count: 2.02"><font size="3"><span lang="EN-US"><font face="Times New Roman">N</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个数据块的下面</span><span lang="EN-US"><font face="Times New Roman">M</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行中，每一行是一个字符串</span><span lang="EN-US"><font face="Times New Roman">T(1</font></span><span style="font-family: 宋体">≤</span><span lang="EN-US"><font face="Times New Roman">length(T)</font></span><span style="font-family: 宋体">≤</span><span lang="EN-US"><font face="Times New Roman">100)</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">T</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">只包含小写字母和“，”。</span></font></p>
<p></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">输出把</span><span lang="EN-US"><font face="Times New Roman">N</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个文件的数据合到一个文件的结果。</span></font></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
2 a<br/>
a1,b1,c1<br/>
a2,b2<br/>
4 b<br/>
a1,b1,c1,d1<br/>
a2,b2<br/>
a3,b3,c3<br/>
a4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">a,,,b,,,<br/>
a1,b1,c1,a1,b1,c1,d1<br/>
a2,b2,,a2,b2,,<br/>
,,,a3,b3,c3,<br/>
,,,a4,,,<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

