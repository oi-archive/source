
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">有一个称为“模拟工厂”的游戏是这样的：在时刻0，工厂的生产力等于1。在每个时刻，你可以提高生产力或者生产商品。如果选择提高生产力，在下一个时刻时工厂的生产力加1；如果选择生产商品，则下一个时刻你所拥有的商品数量增加<i>p</i>，其中<i>p</i>是本时刻工厂的生产力。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">有<i>n</i>个订单，可以选择接受或者不接受。第<i>i</i>个订单(<i>t<sub>i</sub></i>, <i>g<sub>i</sub></i>, <i>m<sub>i</sub></i>)要求在时刻<i>t<sub>i</sub></i>给买家提供<i>g<sub>i</sub></i>个商品，事成之后商品数量减少g<sub>i</sub>，而收入增加<i>m<sub>i</sub></i>元。如果接受订单<i>i</i>，则必须恰好在时刻<i>t<sub>i</sub></i>交易，不能早也不能晚。同一时刻可以接受多个订单，但每个订单只能被接受一次。要求最后的总收入最大。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">例如，如果一共有两个订单(5,1,8)和(7,15,3)，用如下策略是最优的：时刻0, 1, 2提高生产力（时刻3的生产力为4），然后在时刻3，4生产商品，则在时刻5时将拥有8个商品。此时接受第1个订单（还会剩下7个商品），并且在时刻5，6继续生产商品，则在时刻7时拥有7+4+4=15个商品，正好满足订单2。</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">输入第一行包含一个整数<i>n</i>，即订单数目。以下<i>n</i>行每行三个整数<i>t<sub>i</sub></i>, <i>g<sub>i</sub></i>, <i>m<sub>i</sub></i>。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">输出仅一行，为最大总收入。输出保证在32位带符号整数范围内。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
5 1 8<br/>
7 15 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">11</span></div>

# Hint

<div class="content"><p></p><p><br/>
<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><table class="MsoNormalTable" cellspacing="0" cellpadding="0" border="1" style="border-right: medium none; border-top: medium none; border-left: medium none; border-bottom: medium none; border-collapse: collapse; mso-border-alt: solid windowtext .5pt; mso-yfti-tbllook: 480; mso-padding-alt: 0cm 5.4pt 0cm 5.4pt; mso-border-insideh: .5pt solid windowtext; mso-border-insidev: .5pt solid windowtext">
    <tbody>
        <tr style="mso-yfti-irow: 0; mso-yfti-firstrow: yes">
            <td valign="top" width="73" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 55.05pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-family: 黑体"><font size="3">编号<span lang="EN-US"><o:p></o:p></span></font></span></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-family: 黑体"><font size="3">1-3<o:p></o:p></font></span></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-family: 黑体"><font size="3">4-6<o:p></o:p></font></span></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-family: 黑体"><font size="3">7-10<o:p></o:p></font></span></p><br/>
            </td>
        </tr>
        <tr style="mso-yfti-irow: 1">
            <td valign="top" width="73" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 55.05pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><i style="mso-bidi-font-style: normal"><span lang="EN-US"><font size="3"><font face="Times New Roman">n<o:p></o:p></font></font></span></i></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">&lt;=5<o:p></o:p></font></font></span></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">&lt;=10<o:p></o:p></font></font></span></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">&lt;=15<o:p></o:p></font></font></span></p><br/>
            </td>
        </tr>
        <tr style="mso-yfti-irow: 2">
            <td valign="top" width="73" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 55.05pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><i style="mso-bidi-font-style: normal"><span lang="EN-US"><font size="3"><font face="Times New Roman">t<sub>i</sub><o:p></o:p></font></font></span></i></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">100<o:p></o:p></font></font></span></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">100<o:p></o:p></font></font></span></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">&lt;=100,000<o:p></o:p></font></font></span></p><br/>
            </td>
        </tr>
        <tr style="mso-yfti-irow: 3">
            <td valign="top" width="73" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 55.05pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><i style="mso-bidi-font-style: normal"><span lang="EN-US"><font size="3"><font face="Times New Roman">g<sub>i<o:p></o:p></sub></font></font></span></i></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">10,000<o:p></o:p></font></font></span></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">10,000<o:p></o:p></font></font></span></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">&lt;=10<sup>9</sup><o:p></o:p></font></font></span></p><br/>
            </td>
        </tr>
        <tr style="mso-yfti-irow: 4; mso-yfti-lastrow: yes">
            <td valign="top" width="73" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 55.05pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><i style="mso-bidi-font-style: normal"><span lang="EN-US"><font size="3"><font face="Times New Roman">m<sub>i</sub><o:p></o:p></font></font></span></i></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">10,000<o:p></o:p></font></font></span></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">10,000<o:p></o:p></font></font></span></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">&lt;=10<sup>9</sup></font></font><o:p></o:p></span></p><br/>
            </td>
        </tr>
    </tbody>
</table><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

