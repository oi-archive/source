
# Description

<div class="content"><div style="text-indent: 23.25pt"><span style="font-size: 12pt">你有一个N*N的棋盘，每个格子内有一个整数，初始时的时候全部为0，现在需要维护两种操作：</span></div>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 23.25pt"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 黑体; mso-font-kerning: 0pt"><o:p> </o:p></span></p>
<p><table class="MsoNormalTable" cellspacing="0" cellpadding="0" border="1" style="border-right: medium none; border-top: medium none; border-left: medium none; border-bottom: medium none; border-collapse: collapse; mso-border-alt: solid black .5pt; mso-yfti-tbllook: 1184; mso-padding-alt: 0cm 5.4pt 0cm 5.4pt; mso-border-insideh: .5pt solid black; mso-border-insidev: .5pt solid black">
    <tbody>
        <tr style="mso-yfti-irow: 0; mso-yfti-firstrow: yes">
            <td valign="top" width="189" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: black 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: black 1pt solid; width: 142pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent; mso-border-alt: solid black .5pt">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 黑体; mso-font-kerning: 0pt">命令<span lang="EN-US"><o:p></o:p></span></span></p>
            </td>
            <td valign="top" width="189" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: black 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 142.05pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent; mso-border-alt: solid black .5pt; mso-border-left-alt: solid black .5pt">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 黑体; mso-font-kerning: 0pt">参数限制<span lang="EN-US"><o:p></o:p></span></span></p>
            </td>
            <td valign="top" width="189" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: black 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 142.05pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent; mso-border-alt: solid black .5pt; mso-border-left-alt: solid black .5pt">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 黑体; mso-font-kerning: 0pt">内容<span lang="EN-US"><o:p></o:p></span></span></p>
            </td>
        </tr>
        <tr style="mso-yfti-irow: 1">
            <td valign="top" width="189" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: black 1pt solid; width: 142pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent; mso-border-alt: solid black .5pt; mso-border-top-alt: solid black .5pt">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 黑体; mso-font-kerning: 0pt">1 x y A<o:p></o:p></span></p>
            </td>
            <td valign="top" width="189" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 142.05pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent; mso-border-alt: solid black .5pt; mso-border-left-alt: solid black .5pt; mso-border-top-alt: solid black .5pt">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 黑体; mso-font-kerning: 0pt">1&lt;=x,y&lt;=N</span><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 黑体; mso-font-kerning: 0pt">，<span lang="EN-US">A</span>是正整数<span lang="EN-US"><o:p></o:p></span></span></p>
            </td>
            <td valign="top" width="189" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 142.05pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent; mso-border-alt: solid black .5pt; mso-border-left-alt: solid black .5pt; mso-border-top-alt: solid black .5pt">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 黑体; mso-font-kerning: 0pt">将格子<span lang="EN-US">x,y</span>里的数字加上<span lang="EN-US">A<o:p></o:p></span></span></p>
            </td>
        </tr>
        <tr style="mso-yfti-irow: 2">
            <td valign="top" width="189" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: black 1pt solid; width: 142pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent; mso-border-alt: solid black .5pt; mso-border-top-alt: solid black .5pt">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 黑体; mso-font-kerning: 0pt">2 x<sub>1</sub> y<sub>1</sub> x<sub>2</sub> y<sub>2</sub><o:p></o:p></span></p>
            </td>
            <td valign="top" width="189" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 142.05pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent; mso-border-alt: solid black .5pt; mso-border-left-alt: solid black .5pt; mso-border-top-alt: solid black .5pt">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 黑体; mso-font-kerning: 0pt">1&lt;=x<sub>1</sub>&lt;= x<sub>2</sub>&lt;=N<o:p></o:p></span></p>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 黑体; mso-font-kerning: 0pt">1&lt;=y<sub>1</sub>&lt;= y<sub>2</sub>&lt;=N<o:p></o:p></span></p>
            </td>
            <td valign="top" width="189" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 142.05pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent; mso-border-alt: solid black .5pt; mso-border-left-alt: solid black .5pt; mso-border-top-alt: solid black .5pt">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 黑体; mso-font-kerning: 0pt">输出<span lang="EN-US">x<sub>1</sub> y<sub>1</sub> x<sub>2</sub> y<sub>2</sub></span>这个矩形内的数字和<span lang="EN-US"><o:p></o:p></span></span></p>
            </td>
        </tr>
        <tr style="mso-yfti-irow: 3; mso-yfti-lastrow: yes">
            <td valign="top" width="189" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: black 1pt solid; width: 142pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent; mso-border-alt: solid black .5pt; mso-border-top-alt: solid black .5pt">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 黑体; mso-font-kerning: 0pt">3<o:p></o:p></span></p>
            </td>
            <td valign="top" width="189" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 142.05pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent; mso-border-alt: solid black .5pt; mso-border-left-alt: solid black .5pt; mso-border-top-alt: solid black .5pt">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 黑体; mso-font-kerning: 0pt">无<span lang="EN-US"><o:p></o:p></span></span></p>
            </td>
            <td valign="top" width="189" style="border-right: black 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 142.05pt; padding-top: 0cm; border-bottom: black 1pt solid; background-color: transparent; mso-border-alt: solid black .5pt; mso-border-left-alt: solid black .5pt; mso-border-top-alt: solid black .5pt">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-bidi-font-family: 黑体; mso-font-kerning: 0pt">终止程序<span lang="EN-US"><o:p></o:p></span></span></p>
            </td>
        </tr>
    </tbody>
</table>
</p></div>

# Input

<div class="content"><div>输入文件第一行一个正整数N。</div>
<div>接下来每行一个操作。</div>
<div> </div></div>

# Output

<div class="content"><div>对于每个2操作，输出一个对应的答案。</div>
<div> </div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 2 3 3<br/>
2 1 1 3 3<br/>
1 2 2 2<br/>
2 2 2 3 4<br/>
3<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
5<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><div>1&lt;=N&lt;=500000,操作数不超过200000个，内存限制20M。</div><br/>
<div>对于100%的数据，操作1中的A不超过2000。</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

