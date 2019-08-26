
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">数轴上有<i>m</i>个生产车间可以生产零件。一共有<i>n</i>种零件，编号为1~<i>n</i>。第<i>i</i>个车间的坐标为<i>x<sub>i</sub></i>，生产第<i>p<sub>i</sub></i>种零件（1&lt;=<i>p<sub>i</sub></i>&lt;=<i>n</i>）。你需要在数轴上的某个位置修建一个组装车间，把这些零件组装起来。为了节约运输成本，你需要最小化cost(1)+cost(2)+…+cost(<i>n</i>)，其中cost(<i>x</i>)表示生产第<i>x</i>种零件的车间中，到组装车间距离的平方的最小值。</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">输入第一行为两个整数<i>n</i>, <i>m</i>，即零件的种类数和生产车间的个数。以下<i>m</i>行每行两个整数<i>x<sub>i</sub></i>和<i>p<sub>i</sub></i>（1&lt;=<i>p<sub>i</sub></i>&lt;=<i>n</i>）。输入按照生产车间从左到右的顺序排列（即<i>x<sub>i</sub></i>&lt;=<i>x<sub>i</sub></i><sub>+1</sub>。注意车间位置可以重复）。输入保证每种零件都有车间生产。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">输出仅一行，即组装车间的最优位置（可以和某个生产车间重合），四舍五入保留四位小数。输入保证最优位置惟一。</span></div>
<div><span style="font-size: medium"> </span></div>
<div></div>
<p> </p></div>

# Sample Input

<div class="content"><span class="sampledata">3 5<br/>
-1 3<br/>
0 1<br/>
2 3<br/>
4 2<br/>
5 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2.0000</span></div>

# Hint

<div class="content"><p></p><p><br/>
<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><table class="MsoNormalTable" cellspacing="0" cellpadding="0" border="1" style="border-right: medium none; border-top: medium none; border-left: medium none; border-bottom: medium none; border-collapse: collapse; mso-border-alt: solid windowtext .5pt; mso-yfti-tbllook: 480; mso-padding-alt: 0cm 5.4pt 0cm 5.4pt; mso-border-insideh: .5pt solid windowtext; mso-border-insidev: .5pt solid windowtext">
    <tbody>
        <tr style="mso-yfti-irow: 0; mso-yfti-firstrow: yes">
            <td valign="top" width="73" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 55.05pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-family: 黑体"><font size="3">编号<span lang="EN-US"><o:p></o:p></span></font></span></p><br/>
            </td>
            <td valign="top" width="123" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 92.1pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-family: 黑体"><font size="3">1-4<o:p></o:p></font></span></p><br/>
            </td>
            <td valign="top" width="123" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 92.15pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-family: 黑体"><font size="3">5-10<o:p></o:p></font></span></p><br/>
            </td>
        </tr>
        <tr style="mso-yfti-irow: 1">
            <td valign="top" width="73" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 55.05pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><i style="mso-bidi-font-style: normal"><span lang="EN-US"><font size="3"><font face="Times New Roman">n<o:p></o:p></font></font></span></i></p><br/>
            </td>
            <td valign="top" width="123" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 92.1pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">&lt;=15<o:p></o:p></font></font></span></p><br/>
            </td>
            <td valign="top" width="123" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 92.15pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">&lt;=10000<o:p></o:p></font></font></span></p><br/>
            </td>
        </tr>
        <tr style="mso-yfti-irow: 2">
            <td valign="top" width="73" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 55.05pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><i style="mso-bidi-font-style: normal"><span lang="EN-US"><font size="3"><font face="Times New Roman">m<o:p></o:p></font></font></span></i></p><br/>
            </td>
            <td valign="top" width="123" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 92.1pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">&lt;=25<o:p></o:p></font></font></span></p><br/>
            </td>
            <td valign="top" width="123" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 92.15pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">&lt;=100000<o:p></o:p></font></font></span></p><br/>
            </td>
        </tr>
        <tr style="mso-yfti-irow: 3; mso-yfti-lastrow: yes">
            <td valign="top" width="73" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 55.05pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><i style="mso-bidi-font-style: normal"><span lang="EN-US"><font size="3"><font face="Times New Roman">x<sub>i</sub><o:p></o:p></font></font></span></i></p><br/>
            </td>
            <td valign="top" width="123" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 92.1pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">&lt;=100<o:p></o:p></font></font></span></p><br/>
            </td>
            <td valign="top" width="123" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 92.15pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">&lt;=100,000<o:p></o:p></font></font></span></p><br/>
            </td>
        </tr>
    </tbody>
</table><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

