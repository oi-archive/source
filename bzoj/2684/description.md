
# Description

<div class="content"><div><b><span style="font-size: 12pt">       </span></b><span style="font-size: 12pt">给定一个</span><span style="font-size: 12pt">M*N</span><span style="font-size: 12pt">的系数矩阵</span><span style="font-size: 12pt">A</span><span style="font-size: 12pt">和一个</span><span style="font-size: 12pt">M*N</span><span style="font-size: 12pt">的初始矩阵</span><span style="font-size: 12pt">B</span><span style="font-size: 12pt">，我们定义矩阵序列</span><span style="font-size: 12pt">SB={B<sub>k</sub>}</span><span style="font-size: 12pt">，满足序列第一项</span><span style="font-size: 12pt">B<sub>1</sub></span><span style="font-size: 12pt">等于</span><span style="font-size: 12pt">B</span><span style="font-size: 12pt">，对于其他项则满足下式：</span></div>
<div></div>
<div><span style="font-size: 12pt"><img height="92" width="328" alt="" src="/source/bzoj/2684/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIwNC8xMTEuanBn.jpg"/></span></div>
<div></div>
<div></div>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">其中上式</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">b</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的右上角的数表示上标，即其在矩阵序列中的位置。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt"><span style="mso-tab-count: 1"><font face="Times New Roman">       </font></span></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">你需要回答</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">Q</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">次询问，每次询问矩阵序列中第</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">k</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">项的第</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">i</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行第</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">j</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">列的数</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">mod 1000000007</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt"><span style="mso-tab-count: 1"><font face="Times New Roman">       </font></span></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">提示，</span><span lang="EN-US" style="font-size: 12pt"><font face="Times New Roman">1000000007</font></span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">是一个质数</span><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><b style="mso-bidi-font-weight: normal"><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">数据范围：</span></b><b style="mso-bidi-font-weight: normal"><span lang="EN-US" style="font-size: 12pt"><o:p></o:p></span></b></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font face="Times New Roman"><b style="mso-bidi-font-weight: normal"><span lang="EN-US" style="font-size: 12pt"><span style="mso-tab-count: 1">       </span></span></b><span lang="EN-US" style="font-size: 12pt">M,N&lt;=20,Q&lt;=1000<o:p></o:p></span></font></p>
<p></p></div>

# Input

<div class="content"><div class="ptx" lang="en-US">
<p>The input consists of a single test case and is given in the following format:</p>
<div style="padding-left: 2em">
<table>
    <tbody>
        <tr>
            <td><i>m</i></td>
            <td><i>n</i></td>
            <td><i>t</i></td>
            <td></td>
        </tr>
        <tr>
            <td><i>a</i><sub>11</sub></td>
            <td><i>a</i><sub>12</sub></td>
            <td align="center">⋯</td>
            <td><i>a</i><sub>1<i>n</i></sub></td>
        </tr>
        <tr>
            <td><i>a</i><sub>21</sub></td>
            <td><i>a</i><sub>22</sub></td>
            <td align="center">⋯</td>
            <td><i>a</i><sub>2<i>n</i></sub></td>
        </tr>
        <tr>
            <td align="center">⋮</td>
            <td align="center">⋮</td>
            <td align="center">⋱</td>
            <td align="center">⋮</td>
        </tr>
        <tr>
            <td><i>a<sub>m</sub></i><sub>1</sub></td>
            <td><i>a<sub>m</sub></i><sub>2</sub></td>
            <td align="center">⋯</td>
            <td><i>a<sub>mn</sub></i></td>
        </tr>
        <tr>
            <td><i>b</i><sub>11</sub></td>
            <td><i>b</i><sub>12</sub></td>
            <td align="center">⋯</td>
            <td><i>b</i><sub>1<i>n</i></sub></td>
        </tr>
        <tr>
            <td><i>b</i><sub>21</sub></td>
            <td><i>b</i><sub>22</sub></td>
            <td align="center">⋯</td>
            <td><i>b</i><sub>2<i>n</i></sub></td>
        </tr>
        <tr>
            <td align="center">⋮</td>
            <td align="center">⋮</td>
            <td align="center">⋱</td>
            <td align="center">⋮</td>
        </tr>
        <tr>
            <td><i>b<sub>m</sub></i><sub>1</sub></td>
            <td><i>b<sub>m</sub></i><sub>2</sub></td>
            <td align="center">⋯</td>
            <td><i>b<sub>mn</sub></i></td>
        </tr>
        <tr>
            <td><i>i</i><sub>1</sub></td>
            <td><i>j</i><sub>1</sub></td>
            <td><i>k</i><sub>1</sub></td>
            <td></td>
        </tr>
        <tr>
            <td><i>i</i><sub>2</sub></td>
            <td><i>j</i><sub>2</sub></td>
            <td><i>k</i><sub>2</sub></td>
            <td></td>
        </tr>
        <tr>
            <td>⋮</td>
            <td>⋮</td>
            <td>⋮</td>
            <td></td>
        </tr>
        <tr>
            <td><i>i<sub>t</sub></i></td>
            <td><i>j<sub>t</sub></i></td>
            <td><i>k<sub>t</sub></i></td>
            <td></td>
        </tr>
    </tbody>
</table>
</div>
<p>Bounds on the values are: 1 ≤ <i>m</i>, <i>n</i> ≤ 20; 1 ≤ <i>t</i> ≤ 1000; 0 ≤ <i>a<sub>ij</sub></i>, <i>b<sub>ij</sub></i> ≤ 10; 1 ≤ <i>i<sub>t</sub></i> ≤ <i>m</i>; 1 ≤ <i>j<sub>t</sub></i> ≤ <i>n</i>; 1 ≤ <i>k<sub>t</sub></i> ≤ 10<sup>9</sup>.</p>
</div>
<div class="ptx" lang="en-US"></div></div>

# Output

<div class="content"><div class="ptx" lang="en-US">
<p>For each <i>t</i>, output <i>b<sub>i<sub>t</sub>j<sub>t</sub></sub><sup style="margin-left: -2ex">k<sub>t</sub></sup></i> mod 1,000,000,007.</p>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">2 2 5<br/>
1 2<br/>
2 1<br/>
1 1<br/>
1 1<br/>
1 1 2<br/>
1 2 2<br/>
2 1 2<br/>
2 2 2<br/>
1 1 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2<br/>
2<br/>
9<br/>
1<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

