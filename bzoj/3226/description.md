
# Description

<div class="content"><div align="left"><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">　　受校门外的树这道经典问题的启发，A君根据基本的离散数学的知识，抽象出5种运算维护集合S(S初始为空)并最终输出S。现在，请你完成这道校门外的树之难度增强版——校门外的区间。</span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">　　5种运算如下：</span></div>
<p>
<table cellspacing="0" cellpadding="0" border="1" style="border-right: medium none; border-top: medium none; margin: auto auto auto 25.55pt; border-left: medium none; border-bottom: medium none; border-collapse: collapse">
    <tbody>
        <tr>
            <td valign="top" width="52" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 39.05pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="center"><span style="font-size: medium">U T</span></div>
            </td>
            <td valign="top" width="82" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 61.55pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="center"><span style="font-size: medium">S∪T</span></div>
            </td>
        </tr>
        <tr>
            <td valign="top" width="52" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 39.05pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="center"><span style="font-size: medium">I T</span></div>
            </td>
            <td valign="top" width="82" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 61.55pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="center"><span style="font-size: medium">S∩T</span></div>
            </td>
        </tr>
        <tr>
            <td valign="top" width="52" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 39.05pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="center"><span style="font-size: medium">D T</span></div>
            </td>
            <td valign="top" width="82" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 61.55pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="center"><span style="font-size: medium">S－T</span></div>
            </td>
        </tr>
        <tr style="height: 4.5pt">
            <td valign="top" width="52" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 39.05pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; height: 4.5pt; background-color: transparent">
            <div align="center"><span style="font-size: medium">C T</span></div>
            </td>
            <td valign="top" width="82" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 61.55pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; height: 4.5pt; background-color: transparent">
            <div align="center"><span style="font-size: medium">T－S</span></div>
            </td>
        </tr>
        <tr>
            <td valign="top" width="52" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 39.05pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="center"><span style="font-size: medium">S T</span></div>
            </td>
            <td valign="top" width="82" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 61.55pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="center"><span style="font-size: medium">S⊕T</span></div>
            </td>
        </tr>
    </tbody>
</table>
</p>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">　　基本集合运算如下：</span></div>
<p>
<table cellspacing="0" cellpadding="0" border="1" style="border-right: medium none; border-top: medium none; margin: auto auto auto 25.55pt; border-left: medium none; border-bottom: medium none; border-collapse: collapse">
    <tbody>
        <tr>
            <td valign="top" width="63" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 47.3pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="center"><span style="font-size: medium">A∪B</span></div>
            </td>
            <td valign="top" width="171" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 128.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="center"><span style="font-size: medium">{x : xÎA or xÎB}</span></div>
            </td>
        </tr>
        <tr>
            <td valign="top" width="63" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 47.3pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="center"><span style="font-size: medium">A∩B</span></div>
            </td>
            <td valign="top" width="171" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 128.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="center"><span style="font-size: medium">{x : xÎA and xÎB}</span></div>
            </td>
        </tr>
        <tr>
            <td valign="top" width="63" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 47.3pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="center"><span style="font-size: medium">A－B</span></div>
            </td>
            <td valign="top" width="171" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 128.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent">
            <div align="center"><span style="font-size: medium">{x : xÎA and xÏB}</span></div>
            </td>
        </tr>
        <tr style="height: 4.5pt">
            <td valign="top" width="63" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 47.3pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; height: 4.5pt; background-color: transparent">
            <div align="center"><span style="font-size: medium">A⊕B</span></div>
            </td>
            <td valign="top" width="171" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 128.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; height: 4.5pt; background-color: transparent">
            <div align="center"><span style="font-size: medium">(A－B)∪(B－A)</span></div>
            </td>
        </tr>
    </tbody>
</table>
</p>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">　　输入共M行。</span></div>
<div><span style="font-size: medium">　　每行的格式为X T，用一个空格隔开，X表示运算的种类，T为一个区间(区间用(a,b), (a,b], [a,b), [a,b]表示)。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">　　共一行，即集合S，<span style="color: #ff0000">每个区间后面带一个空格</span>。若S为空则输出&#34;empty set&#34;。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">U [1,5]<br/>
D [3,3]<br/>
S [2,4]<br/>
C (1,5)<br/>
I (2,3]<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">(2,3) <br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于 100% 的数据，0≤a≤b≤65535，1≤M≤70000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

