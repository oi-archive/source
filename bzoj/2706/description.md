
# Description

<div class="content"><div style="text-indent: 21pt" align="left"><span style="font-size: medium">在一个N*M个方格组成的棋盘内，有K个方格被称为特殊方格。我们要使用一组俄罗斯方块来覆盖这个棋盘，保证特殊方格不能被覆盖，非特殊方格只能被一个俄罗斯方块覆盖，求最多能容纳的俄罗斯方块的数量。</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium">已知有以下三组俄罗斯方块，一个棋盘可能用其中的某一组。</span></div>
<div style="text-indent: 21pt" align="left"><span style="font-size: medium"><img height="200" alt="" width="392" src="/source/bzoj/2706/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIwNC9kZC5qcGc=.jpg"/></span></div>
<p></p></div>

# Input

<div class="content"><p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第一行三个整数，</span><span lang="EN-US"><font face="Times New Roman">N,M,K</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，和一个字符，</span><span lang="EN-US"><font face="Times New Roman">type</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，为所用的俄罗斯方块组。</span></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">接下来</span><span lang="EN-US"><font face="Times New Roman">K</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行每行两个整数，</span><span lang="EN-US"><font face="Times New Roman">X,Y</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，表示第</span><span lang="EN-US"><font face="Times New Roman">X</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行第</span><span lang="EN-US"><font face="Times New Roman">Y</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">列为特殊方格。</span></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><o:p></o:p></span></span><span lang="EN-US"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">一个整数，为所求的答案。</span></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">【样例输入</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">】</span></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">8 8 </font></span></span><span lang="EN-US"><font size="3"><font face="Times New Roman"><st1:chmetcnv w:st="on" tcsc="0" numbertype="1" negative="False" hasspace="True" sourcevalue="0" unitname="a"><span style="font-size: medium">0 A</span></st1:chmetcnv></font></font></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">【样例输出</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">】</span></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">32</font></span></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">【样例输入</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">】</span></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">7 6 </font></span></span><span lang="EN-US"><font size="3"><font face="Times New Roman"><st1:chmetcnv w:st="on" tcsc="0" numbertype="1" negative="False" hasspace="True" sourcevalue="6" unitname="C"><span style="font-size: medium">6 C</span></st1:chmetcnv></font></font></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">3 1</font></span></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">3 6</font></span></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">5 3</font></span></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">5 4</font></span></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">5 7</font></span></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">6 7</font></span></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">【样例输出</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">】</span></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">12</font></span></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">【数据范围】</span></span></p>
<p><table class="MsoNormalTable" cellspacing="0" cellpadding="0" border="1" style="border-right: medium none; border-top: medium none; border-left: medium none; border-bottom: medium none; border-collapse: collapse; mso-table-layout-alt: fixed; mso-border-alt: solid windowtext .5pt; mso-padding-alt: 0cm 5.4pt 0cm 5.4pt; mso-border-insideh: .5pt solid windowtext; mso-border-insidev: .5pt solid windowtext">
    <tbody>
        <tr>
            <td valign="top" width="114" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 85.2pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt">
            <p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">测试点</span></span></p>
            </td>
            <td valign="top" width="192" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 144.35pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt">
            <p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">N,M</font></span></span></p>
            </td>
            <td valign="top" width="225" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 168.75pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt">
            <p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">K</font></span></span></p>
            </td>
            <td valign="top" width="63" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 47.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt">
            <p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">type</font></span></span></p>
            </td>
        </tr>
        <tr>
            <td valign="top" width="114" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 85.2pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt">
            <p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">[1, 6]</font></span></span></p>
            </td>
            <td valign="top" width="192" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 144.35pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt">
            <p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">0 &lt; N,M &lt;= 100</font></span></span></p>
            </td>
            <td valign="top" width="225" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 168.75pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt">
            <p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">0&lt;=K&lt;=N*M</font></span></span></p>
            </td>
            <td valign="top" width="63" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 47.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt">
            <p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">A</font></span></span></p>
            </td>
        </tr>
        <tr>
            <td valign="top" width="114" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 85.2pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt">
            <p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">[7, 12]</font></span></span></p>
            </td>
            <td valign="top" width="192" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 144.35pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt">
            <p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">N=M=2^L,0&lt;L&lt;=200000</font></span></span></p>
            </td>
            <td valign="top" width="225" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 168.75pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt">
            <p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">K=1</font></span></span></p>
            </td>
            <td valign="top" width="63" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 47.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt">
            <p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">B</font></span></span></p>
            </td>
        </tr>
        <tr style="mso-yfti-lastrow: yes">
            <td valign="top" width="114" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 85.2pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt">
            <p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">[13, 20]</font></span></span></p>
            </td>
            <td valign="top" width="192" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 144.35pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt">
            <p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">0&lt;N,M&lt;=11</font></span></span></p>
            </td>
            <td valign="top" width="225" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 168.75pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt">
            <p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">0&lt;=K&lt;=N*M</font></span></span></p>
            </td>
            <td valign="top" width="63" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 47.25pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt">
            <p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">C</font></span></span></p>
            </td>
        </tr>
    </tbody>
</table>
</p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><o:p><font face="Times New Roman"> </font></o:p></span></span><span lang="EN-US"><o:p></o:p></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left"><span style="font-size: medium"><span lang="EN-US"><o:p><font face="Times New Roman"> </font></o:p></span></span><span lang="EN-US"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata"></span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=round1 day1">round1 day1</a></p></div>

