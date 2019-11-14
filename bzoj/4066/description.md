
# Description

<div class="content"><div><span style="font-size: 12pt; font-family: arial, verdana, helvetica, sans-serif; text-indent: 23.25pt;">你有一个N*N的棋盘，每个格子内有一个整数，初始时的时候全部为0，现在需要维护两种操作：</span></div>
<p class="MsoNormal" style="font-family: arial, verdana, helvetica, sans-serif; font-size: 18px; margin: 0cm 0cm 0pt; text-indent: 23.25pt;"><span lang="EN-US" style="font-family: 宋体; font-size: 12pt;"><o:p style="font-family: arial, verdana, helvetica, sans-serif;"> </o:p></span></p>
<table class="MsoNormalTable" cellspacing="0" cellpadding="0" border="1" style="font-family: arial, verdana, helvetica, sans-serif; border: medium none; border-collapse: collapse;">
    <tbody>
        <tr>
            <td valign="top" width="189" style="font-family: arial, verdana, helvetica, sans-serif; border: 1pt solid black; padding: 0cm 5.4pt; width: 142pt; background-color: transparent;">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span style="font-family: 宋体; font-size: 12pt;">命令<span lang="EN-US" style="font-family: arial, verdana, helvetica, sans-serif;"><o:p></o:p></span></span></p>
            </td>
            <td valign="top" width="189" style="font-family: arial, verdana, helvetica, sans-serif; border-color: black black black rgb(236, 233, 216); border-right-width: 1pt; border-right-style: solid; padding: 0cm 5.4pt; border-top-width: 1pt; border-top-style: solid; width: 142.05pt; border-bottom-width: 1pt; border-bottom-style: solid; background-color: transparent;">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span style="font-family: 宋体; font-size: 12pt;">参数限制<span lang="EN-US" style="font-family: arial, verdana, helvetica, sans-serif;"><o:p></o:p></span></span></p>
            </td>
            <td valign="top" width="189" style="font-family: arial, verdana, helvetica, sans-serif; border-color: black black black rgb(236, 233, 216); border-right-width: 1pt; border-right-style: solid; padding: 0cm 5.4pt; border-top-width: 1pt; border-top-style: solid; width: 142.05pt; border-bottom-width: 1pt; border-bottom-style: solid; background-color: transparent;">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span style="font-family: 宋体; font-size: 12pt;">内容<span lang="EN-US" style="font-family: arial, verdana, helvetica, sans-serif;"><o:p></o:p></span></span></p>
            </td>
        </tr>
        <tr>
            <td valign="top" width="189" style="font-family: arial, verdana, helvetica, sans-serif; border-color: rgb(236, 233, 216) black black; border-right-width: 1pt; border-right-style: solid; padding: 0cm 5.4pt; border-left-width: 1pt; border-left-style: solid; width: 142pt; border-bottom-width: 1pt; border-bottom-style: solid; background-color: transparent;">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span lang="EN-US" style="font-family: 宋体; font-size: 12pt;">1 x y A<o:p style="font-family: arial, verdana, helvetica, sans-serif;"></o:p></span></p>
            </td>
            <td valign="top" width="189" style="font-family: arial, verdana, helvetica, sans-serif; border-color: rgb(236, 233, 216) black black rgb(236, 233, 216); border-right-width: 1pt; border-right-style: solid; padding: 0cm 5.4pt; width: 142.05pt; border-bottom-width: 1pt; border-bottom-style: solid; background-color: transparent;">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span lang="EN-US" style="font-family: 宋体; font-size: 12pt;">1&lt;=x,y&lt;=N</span><span style="font-family: 宋体; font-size: 12pt;">，<span lang="EN-US" style="font-family: arial, verdana, helvetica, sans-serif;">A</span>是正整数<span lang="EN-US" style="font-family: arial, verdana, helvetica, sans-serif;"><o:p></o:p></span></span></p>
            </td>
            <td valign="top" width="189" style="font-family: arial, verdana, helvetica, sans-serif; border-color: rgb(236, 233, 216) black black rgb(236, 233, 216); border-right-width: 1pt; border-right-style: solid; padding: 0cm 5.4pt; width: 142.05pt; border-bottom-width: 1pt; border-bottom-style: solid; background-color: transparent;">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span style="font-family: 宋体; font-size: 12pt;">将格子<span lang="EN-US" style="font-family: arial, verdana, helvetica, sans-serif;">x,y</span>里的数字加上<span lang="EN-US" style="font-family: arial, verdana, helvetica, sans-serif;">A<o:p></o:p></span></span></p>
            </td>
        </tr>
        <tr>
            <td valign="top" width="189" style="font-family: arial, verdana, helvetica, sans-serif; border-color: rgb(236, 233, 216) black black; border-right-width: 1pt; border-right-style: solid; padding: 0cm 5.4pt; border-left-width: 1pt; border-left-style: solid; width: 142pt; border-bottom-width: 1pt; border-bottom-style: solid; background-color: transparent;">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span lang="EN-US" style="font-family: 宋体; font-size: 12pt;">2 x<sub style="font-family: arial, verdana, helvetica, sans-serif;">1</sub> y<sub style="font-family: arial, verdana, helvetica, sans-serif;">1</sub> x<sub style="font-family: arial, verdana, helvetica, sans-serif;">2</sub> y<sub style="font-family: arial, verdana, helvetica, sans-serif;">2</sub><o:p style="font-family: arial, verdana, helvetica, sans-serif;"></o:p></span></p>
            </td>
            <td valign="top" width="189" style="font-family: arial, verdana, helvetica, sans-serif; border-color: rgb(236, 233, 216) black black rgb(236, 233, 216); border-right-width: 1pt; border-right-style: solid; padding: 0cm 5.4pt; width: 142.05pt; border-bottom-width: 1pt; border-bottom-style: solid; background-color: transparent;">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span lang="EN-US" style="font-family: 宋体; font-size: 12pt;">1&lt;=x<sub style="font-family: arial, verdana, helvetica, sans-serif;">1</sub>&lt;= x<sub style="font-family: arial, verdana, helvetica, sans-serif;">2</sub>&lt;=N<o:p style="font-family: arial, verdana, helvetica, sans-serif;"></o:p></span></p>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span lang="EN-US" style="font-family: 宋体; font-size: 12pt;">1&lt;=y<sub style="font-family: arial, verdana, helvetica, sans-serif;">1</sub>&lt;= y<sub style="font-family: arial, verdana, helvetica, sans-serif;">2</sub>&lt;=N<o:p style="font-family: arial, verdana, helvetica, sans-serif;"></o:p></span></p>
            </td>
            <td valign="top" width="189" style="font-family: arial, verdana, helvetica, sans-serif; border-color: rgb(236, 233, 216) black black rgb(236, 233, 216); border-right-width: 1pt; border-right-style: solid; padding: 0cm 5.4pt; width: 142.05pt; border-bottom-width: 1pt; border-bottom-style: solid; background-color: transparent;">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span style="font-family: 宋体; font-size: 12pt;">输出<span lang="EN-US" style="font-family: arial, verdana, helvetica, sans-serif;">x<sub>1</sub> y<sub>1</sub> x<sub>2</sub> y<sub>2</sub></span>这个矩形内的数字和<span lang="EN-US" style="font-family: arial, verdana, helvetica, sans-serif;"><o:p></o:p></span></span></p>
            </td>
        </tr>
        <tr>
            <td valign="top" width="189" style="font-family: arial, verdana, helvetica, sans-serif; border-color: rgb(236, 233, 216) black black; border-right-width: 1pt; border-right-style: solid; padding: 0cm 5.4pt; border-left-width: 1pt; border-left-style: solid; width: 142pt; border-bottom-width: 1pt; border-bottom-style: solid; background-color: transparent;">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span lang="EN-US" style="font-family: 宋体; font-size: 12pt;">3<o:p style="font-family: arial, verdana, helvetica, sans-serif;"></o:p></span></p>
            </td>
            <td valign="top" width="189" style="font-family: arial, verdana, helvetica, sans-serif; border-color: rgb(236, 233, 216) black black rgb(236, 233, 216); border-right-width: 1pt; border-right-style: solid; padding: 0cm 5.4pt; width: 142.05pt; border-bottom-width: 1pt; border-bottom-style: solid; background-color: transparent;">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span style="font-family: 宋体; font-size: 12pt;">无<span lang="EN-US" style="font-family: arial, verdana, helvetica, sans-serif;"><o:p></o:p></span></span></p>
            </td>
            <td valign="top" width="189" style="font-family: arial, verdana, helvetica, sans-serif; border-color: rgb(236, 233, 216) black black rgb(236, 233, 216); border-right-width: 1pt; border-right-style: solid; padding: 0cm 5.4pt; width: 142.05pt; border-bottom-width: 1pt; border-bottom-style: solid; background-color: transparent;">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt;"><span style="font-family: 宋体; font-size: 12pt;">终止程序<span lang="EN-US" style="font-family: arial, verdana, helvetica, sans-serif;"><o:p></o:p></span></span></p>
            </td>
        </tr>
    </tbody>
</table>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入文件第一行一个正整数N。</div>
<div>
<div>接下来每行一个操作。每条命令除第一个数字之外，</div>
<div>均要异或上一次输出的答案last_ans，初始时last_ans=0。</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>对于每个2操作，输出一个对应的答案。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 2 3 3<br/>
2 1 1 3 3<br/>
1 1 1 1<br/>
2 1 1 0 7<br/>
3</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
5</span></div>

# Hint

<div class="content"><p></p><div>数据规模和约定</div><br/>
<div>1&lt;=N&lt;=500000,操作数不超过200000个，内存限制20M，保证答案在int范围内并且解码之后数据仍合法。</div><br/>
<div>样例解释见OJ2683</div><br/>
<div></div><br/>
<div>新加数据一组，但未重测----2015.05.24</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By wjy1998">By wjy1998</a></p></div>

