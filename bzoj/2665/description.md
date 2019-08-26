
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">你需要给一批商品编号，其中每个编号都是一个7位16进制数（由0~9, a-f组成）。为了防止在人工处理时不小心把编号弄错，要求任意两个编号至少有三个位置对应的数字不相同。第一个编号为0000000，第二个编号为不违反上述规定的前提下最小的编号，…，每次分配一个新编号时，总是选择不和前面编号冲突的最小编号（注意编号都是16进制数，可以比较大小）。按此规律，前面若干编号分别是：0000000, 0000111, 0000222, …, 0000fff, 0001012, 0001103,0001230,0001321,0001456,…</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">输入<i>k</i>，你的任务是求出第<i>k</i>小的编号。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行为整数<i>k</i>。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">输出第<i>k</i>小的编号（字母必须输出小写）。输入保证这个编号存在。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">20	</span></div>

# Sample Output

<div class="content"><span class="sampledata">0001321</span></div>

# Hint

<div class="content"><p></p><p><br/>
<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><table class="MsoNormalTable" cellspacing="0" cellpadding="0" border="1" style="border-right: medium none; border-top: medium none; border-left: medium none; border-bottom: medium none; border-collapse: collapse; mso-border-alt: solid windowtext .5pt; mso-yfti-tbllook: 480; mso-padding-alt: 0cm 5.4pt 0cm 5.4pt; mso-border-insideh: .5pt solid windowtext; mso-border-insidev: .5pt solid windowtext">
    <tbody>
        <tr style="mso-yfti-irow: 0; mso-yfti-firstrow: yes">
            <td valign="top" width="73" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 55.05pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-family: 黑体"><font size="3">编号<span lang="EN-US"><o:p></o:p></span></font></span></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-family: 黑体"><font size="3">1-3<o:p></o:p></font></span></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-family: 黑体"><font size="3">4-7<o:p></o:p></font></span></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: windowtext 1pt solid; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-family: 黑体"><font size="3">8-10<o:p></o:p></font></span></p><br/>
            </td>
        </tr>
        <tr style="mso-yfti-irow: 1; mso-yfti-lastrow: yes">
            <td valign="top" width="73" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: windowtext 1pt solid; width: 55.05pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><i style="mso-bidi-font-style: normal"><span lang="EN-US"><font size="3"><font face="Times New Roman">k<o:p></o:p></font></font></span></i></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">&lt;=200<o:p></o:p></font></font></span></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">&lt;=10000<o:p></o:p></font></font></span></p><br/>
            </td>
            <td valign="top" width="98" style="border-right: windowtext 1pt solid; padding-right: 5.4pt; border-top: #ece9d8; padding-left: 5.4pt; padding-bottom: 0cm; border-left: #ece9d8; width: 73.7pt; padding-top: 0cm; border-bottom: windowtext 1pt solid; background-color: transparent; mso-border-alt: solid windowtext .5pt; mso-border-left-alt: solid windowtext .5pt; mso-border-top-alt: solid windowtext .5pt"><br/>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><font size="3"><font face="Times New Roman">&lt;=200000<o:p></o:p></font></font></span></p><br/>
            </td>
        </tr>
    </tbody>
</table><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

