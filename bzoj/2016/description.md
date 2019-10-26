
# Description

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">贝西从大牛那里收到了</span><span lang="EN-US">N</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">块巧克力。她不想把它们马上吃完，而是打算制定一个计划，</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">使得在接下来的</span><span lang="EN-US">D</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">天里，她能够尽量地快乐。贝西的快乐指数可以用一个整数来衡量，一开始的时候是</span><span lang="EN-US">0</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，当她每天晚上睡觉的时候，快乐指数会减半（奇数时向下取整）。贝西把她的巧克力按照收到的时间排序，并坚持按照这个顺序来吃巧克力。当她吃掉第</span><span lang="EN-US">i</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">块巧克力的时候，她的快乐指数会增加</span><span lang="EN-US">Hj</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。每天可以吃任意多块巧克力，如何帮助贝西合理安排，使得</span><span lang="EN-US">D</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">天内她的最小快乐指数最大呢？</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US">    </span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">举个例子：假设一共有五块巧克力，贝西打算在五天时间内将它们吃完，每块巧克力提</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">供的快乐指数分别为</span><span lang="EN-US">10</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US">40</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US">13</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US">22</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US">7</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。则最好的方案如</span><span lang="EN-US">F</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">：</span></span></p>
<p><table class="MsoNormalTable" cellspacing="0" cellpadding="0" border="1" style="mso-cellspacing: 0cm; mso-padding-alt: 0cm 0cm 0cm 0cm">
    <tbody>
        <tr style="height: 16.5pt; mso-yfti-irow: 0; mso-yfti-firstrow: yes">
            <td nowrap="nowrap" width="50" style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; width: 37.5pt; padding-top: 0cm; border-bottom: #ece9d8; height: 16.5pt; background-color: transparent">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">天数</span></span></p>
            </td>
            <td nowrap="nowrap" width="144" style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; width: 108pt; padding-top: 0cm; border-bottom: #ece9d8; height: 16.5pt; background-color: transparent">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">起床时快乐指数</span></span></p>
            </td>
            <td nowrap="nowrap" width="126" style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; width: 94.5pt; padding-top: 0cm; border-bottom: #ece9d8; height: 16.5pt; background-color: transparent">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">食用的巧克力</span></span></p>
            </td>
            <td nowrap="nowrap" width="142" style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; width: 106.5pt; padding-top: 0cm; border-bottom: #ece9d8; height: 16.5pt; background-color: transparent">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">就寝时快乐指数</span></span></p>
            </td>
        </tr>
        <tr style="height: 101.25pt; mso-yfti-irow: 1">
            <td nowrap="nowrap" width="50" style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; width: 37.5pt; padding-top: 0cm; border-bottom: #ece9d8; height: 101.25pt; background-color: transparent">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US">    1<br/>
                2<br/>
                3<br/>
                4<br/>
                5</span></span></p>
            </td>
            <td nowrap="nowrap" width="144" style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; width: 108pt; padding-top: 0cm; border-bottom: #ece9d8; height: 101.25pt; background-color: transparent">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US">    0<br/>
                25<br/>
                12<br/>
                12<br/>
                17</span></span></p>
            </td>
            <td nowrap="nowrap" width="126" style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; width: 94.5pt; padding-top: 0cm; border-bottom: #ece9d8; height: 101.25pt; background-color: transparent">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US">    10+ 40<br/>
             <br/>
                13<br/>
                22<br/>
                7</span></span></p>
            </td>
            <td nowrap="nowrap" width="142" style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; width: 106.5pt; padding-top: 0cm; border-bottom: #ece9d8; height: 101.25pt; background-color: transparent">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US">    50<br/>
                25<br/>
                25<br/>
                34<br/>
                24</span></span></p>
            </td>
        </tr>
        <tr style="mso-yfti-irow: 2; mso-yfti-lastrow: yes">
            <td style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0cm; border-bottom: #ece9d8; background-color: transparent">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><o:p> </o:p></span></span><span lang="EN-US"><o:p></o:p></span></p>
            </td>
            <td style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0cm; border-bottom: #ece9d8; background-color: transparent">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><o:p> </o:p></span></span><span lang="EN-US"><o:p></o:p></span></p>
            </td>
            <td style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0cm; border-bottom: #ece9d8; background-color: transparent">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><o:p> </o:p></span></span><span lang="EN-US"><o:p></o:p></span></p>
            </td>
            <td style="border-right: #ece9d8; padding-right: 0cm; border-top: #ece9d8; padding-left: 0cm; padding-bottom: 0cm; border-left: #ece9d8; padding-top: 0cm; border-bottom: #ece9d8; background-color: transparent">
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><o:p> </o:p></span></span><span lang="EN-US"><o:p></o:p></span></p>
            </td>
        </tr>
    </tbody>
</table>
</p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">五天内的最小快乐指数为</span><span lang="EN-US">24</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，这是所有吃法中的最大值。</span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"></p></div>

# Input

<div class="content"><div><span style="font-size: medium">  第一行：两个用空格分开的整数：N和D，1≤N．D≤50000</span></div>
<div><span style="font-size: medium">  第二行到第N+1行：第1+1行表示第i块巧克力提供的快乐指数Hj，1≤Hi≤1000000</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">  第一行：单个整数，表示贝西在接下来D天内的最小快乐指数的最大值</span></div>
<div><span style="font-size: medium">  第二行到第N+1:在第i+l行有一个整数，代表贝西应该在哪一天吃掉第i块巧克力。</span></div>
<div><span style="font-size: medium">    如果有多种吃法，则输出按照词典序排序后最靠后的方案</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">55<br/>
10<br/>
40<br/>
13<br/>
22<br/>
7<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">24<br/>
 1<br/>
 1<br/>
 3<br/>
 4<br/>
 5<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

