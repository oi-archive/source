
# Description

<div class="content"><p><img alt="" src="/source/bzoj/2341/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTEwNi8xMTEuanBn.jpg"/></p></div>

# Input

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21.3pt"><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">第一行两个正整数，<font face="Times New Roman">N</font><font face="宋体">表示山的折线上的拐点数（包括端点在内），</font><font face="Times New Roman">M</font><font face="宋体">则是你收到的消息数。</font><font face="Times New Roman">3 &lt;= N &lt;= 100000</font><font face="宋体">，</font><font face="Times New Roman">0 &lt;= M &lt;= 100000</font><font face="宋体">。</font></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21.3pt"><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">后面<font face="Times New Roman">N</font><font face="宋体">行，第</font><font face="Times New Roman">i</font><font face="宋体">行有两个非负整数</font><font face="Times New Roman">Xi</font><font face="宋体">和</font><font face="Times New Roman">Yi</font><font face="宋体">，表示折线上第</font><font face="Times New Roman">i</font><font face="宋体">个拐点的坐标。</font></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21.3pt"><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">后面<font face="Times New Roman">M</font><font face="宋体">行，每行是以下两种情况之一：</font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p><table style="padding-right: 5.4pt; padding-left: 5.4pt; padding-bottom: 0pt; padding-top: 0pt; border-collapse: collapse; mso-table-layout-alt: fixed">
    <tbody>
        <tr>
            <td valign="top" width="92" style="border-right: rgb(0,0,0) 0.5pt solid; padding-right: 5.4pt; border-top: rgb(0,0,0) 0.5pt solid; padding-left: 5.4pt; padding-bottom: 0pt; border-left: rgb(0,0,0) 0.5pt solid; width: 69.2pt; padding-top: 0pt; border-bottom: rgb(0,0,0) 0.5pt solid; mso-border-left-alt: 0.5000pt solid rgb(0,0,0); mso-border-right-alt: 0.5000pt solid rgb(0,0,0); mso-border-top-alt: 0.5000pt solid rgb(0,0,0); mso-border-bottom-alt: 0.5000pt solid rgb(0,0,0)">
            <p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 10.5pt; font-style: italic; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">Survey</span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"> x </span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;"><o:p></o:p></span></p>
            </td>
            <td valign="top" width="476" style="border-right: rgb(0,0,0) 0.5pt solid; padding-right: 5.4pt; border-top: rgb(0,0,0) 0.5pt solid; padding-left: 5.4pt; padding-bottom: 0pt; border-left: medium none; width: 357.2pt; padding-top: 0pt; border-bottom: rgb(0,0,0) 0.5pt solid; mso-border-left-alt: none; mso-border-right-alt: 0.5000pt solid rgb(0,0,0); mso-border-top-alt: 0.5000pt solid rgb(0,0,0); mso-border-bottom-alt: 0.5000pt solid rgb(0,0,0)">
            <p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 9pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">表示测量<font face="Times New Roman">x</font><font face="宋体">位置的水深和水平面的海拔高度。</font><font face="Times New Roman">x</font><font face="宋体">是一个实数，保证</font><font face="Times New Roman">X1 &lt;= x &lt;= Xn</font><font face="宋体">。</font></span><span style="font-size: 9pt; font-family: &#39;宋体&#39;"><o:p></o:p></span></p>
            </td>
        </tr>
        <tr style="page-break-inside: TableInfo">
            <td valign="top" width="92" style="border-right: rgb(0,0,0) 0.5pt solid; padding-right: 5.4pt; border-top: medium none; padding-left: 5.4pt; padding-bottom: 0pt; border-left: rgb(0,0,0) 0.5pt solid; width: 69.2pt; padding-top: 0pt; border-bottom: rgb(0,0,0) 0.5pt solid; mso-border-left-alt: 0.5000pt solid rgb(0,0,0); mso-border-right-alt: 0.5000pt solid rgb(0,0,0); mso-border-top-alt: 0.5000pt solid rgb(0,0,0); mso-border-bottom-alt: 0.5000pt solid rgb(0,0,0)">
            <p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 10.5pt; font-style: italic; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">Descend</span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"> x y </span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;"><o:p></o:p></span></p>
            </td>
            <td valign="top" width="476" style="border-right: rgb(0,0,0) 0.5pt solid; padding-right: 5.4pt; border-top: medium none; padding-left: 5.4pt; padding-bottom: 0pt; border-left: medium none; width: 357.2pt; padding-top: 0pt; border-bottom: rgb(0,0,0) 0.5pt solid; mso-border-left-alt: none; mso-border-right-alt: 0.5000pt solid rgb(0,0,0); mso-border-top-alt: 0.5000pt solid rgb(0,0,0); mso-border-bottom-alt: 0.5000pt solid rgb(0,0,0)">
            <p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 9pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">表示输入中的第<font face="Times New Roman">x</font><font face="宋体">个点的地面的海拔高度降低到了</font><font face="Times New Roman">y</font><font face="宋体">。</font></span><span style="font-size: 9pt; font-family: &#39;宋体&#39;"><o:p></o:p></span></p>
            </td>
        </tr>
    </tbody>
</table>
</p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21.3pt"><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">题中所有坐标（包括<font face="Times New Roman">Descend</font><font face="宋体">中的）都是</font><font face="Times New Roman">0</font><font face="宋体">到</font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">1000000</span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">之间的整数。</span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<!--EndFragment--></div>

# Output

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">输出格式：</span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21.3pt"><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">首先输出一开始的山上的储水量。</span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21.3pt"><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">对于每个<font face="Times New Roman">Survey</font><font face="宋体">，输出一行</font><font face="Times New Roman">a b</font><font face="宋体">。</font><font face="Times New Roman">a</font><font face="宋体">表示该位置的水深（如果没有水则为</font><font face="Times New Roman">0</font><font face="宋体">），</font><font face="Times New Roman">b</font><font face="宋体">表示该位置的水面的海拔高度（如果没有水，则为该位置的土地的高度）。</font></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21.3pt"><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">对于每个<font face="Times New Roman">Descend</font><font face="宋体">，输出新的储水量。</font></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21.3pt"><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">输出中的所有数字保留<font face="Times New Roman">2</font><font face="宋体">位小数。</font></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<!--EndFragment--></div>

# Sample Input

<div class="content"><span class="sampledata">7 3<br/>
0 0<br/>
1 4<br/>
2 2<br/>
3 6<br/>
4 4<br/>
6 5<br/>
8 0<br/>
Survey 5.5<br/>
Descend 3 2<br/>
Survey 5.5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2.75<br/>
0.25 5.00<br/>
4.00<br/>
0.00 4.75</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

