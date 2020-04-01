
# Description

<div class="content"><p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left; mso-layout-grid-align: none"><o:wrapblock><v:group id="_x0000_s1026" o:allowincell="f" coordsize="4500,4836" style="margin-top: 67.85pt; z-index: 1; left: 0px; margin-left: 87.85pt; width: 3in; position: absolute; height: 231.1pt; text-align: left"><v:shapetype id="_x0000_t202" coordsize="21600,21600" path="m,l,21600r21600,l21600,xe" o:spt="202"><v:stroke joinstyle="miter"></v:stroke><v:path o:connecttype="rect" gradientshapeok="t"></v:path></v:shapetype><v:shape id="_x0000_s1052" stroked="f" type="#_x0000_t202" style="left: 1980px; width: 900px; position: absolute; top: 4368px; height: 468px; mso-wrap-style: square"><v:textbox>
<table cellspacing="0" cellpadding="0" width="100%">
    <tbody>
        <tr>
            <td style="border-right: #ece9d8; border-top: #ece9d8; border-left: #ece9d8; border-bottom: #ece9d8; background-color: transparent">
            <div>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><b style="mso-bidi-font-weight: normal"><span style="color: fuchsia; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">图一</span></b></span><b style="mso-bidi-font-weight: normal"><span lang="EN-US" style="font-size: 12pt; color: fuchsia"><o:p></o:p></span></b></p>
            </div>
            </td>
        </tr>
    </tbody>
</table>
</v:textbox></v:shape><w:wrap type="topAndBottom"></w:wrap></v:group></o:wrapblock><span style="font-size: medium"><br clear="all" style="mso-ignore: vglayout"/>
<span style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt">有一个<span lang="EN-US">n*n</span>的网格，每一“格”上有一个可以翻转的方块，方块的两面分别涂成黑、白两种颜色。另外，有一个沿着网格线活动的东西——不妨称之为“动子”。初始时，每个方块随机地被翻成黑或白色，“动子”停在网格线的某个顶点上。例如如图一就是一个<span lang="EN-US">4*4</span>的网格的一种可能的开局情况。</span></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left; mso-layout-grid-align: none"><span style="font-size: medium"><span style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt"><img height="352" alt="" width="368" src="/source/bzoj/3633/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwNi8xKDEpLmpwZw==.jpg"/></span></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left; mso-layout-grid-align: none"><span style="font-size: medium"><span style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt"><span style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt">“动子”在网格线上运动时，从一个顶点<span lang="EN-US">A</span>到相邻的另一个顶点<span lang="EN-US">B</span>之后，以网格线<span lang="EN-US">AB</span>为边的两个或一个网格上的方块就会翻转——白变黑，黑变白。例如图一的“动子”向右移动一步之后变成图二，向下移动一步之后变成图三。</span></span></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left; mso-layout-grid-align: none"></p>
<p></p>
<p></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left; mso-layout-grid-align: none"><span style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt"><font size="3"><span lang="EN-US"><o:p><span style="font-size: medium"><img height="358" alt="" width="693" src="/source/bzoj/3633/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwNi8yKDEpLmpwZw==.jpg"/></span></o:p></span></font></span></p>
<p></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left; mso-layout-grid-align: none"><v:group id="_x0000_s1052" o:allowincell="f" coordsize="4500,4836" style="margin-top: 298.5pt; z-index: 2; left: 0px; margin-left: 208.4pt; width: 213.05pt; position: absolute; height: 228.15pt; text-align: left"><v:rect id="_x0000_s1053" strokeweight="1.25pt" strokecolor="blue" fillcolor="#9cf" style="left: 180px; width: 4320px; position: absolute; height: 4320px; mso-wrap-style: square"></v:rect><v:line id="_x0000_s1054" strokeweight="1pt" strokecolor="#36f" to="2340,4368" from="2340,0" style="position: absolute; mso-wrap-style: square"></v:line><v:line id="_x0000_s1055" strokeweight="1pt" strokecolor="#36f" to="1260,4368" from="1260,0" style="position: absolute; mso-wrap-style: square"></v:line><v:line id="_x0000_s1056" strokeweight="1pt" strokecolor="#36f" to="3420,4368" from="3420,0" style="position: absolute; mso-wrap-style: square"></v:line><v:line id="_x0000_s1057" strokeweight="1pt" strokecolor="#36f" to="4500,2184" from="180,2184" style="position: absolute; mso-wrap-style: square"></v:line><v:line id="_x0000_s1058" strokeweight="1pt" strokecolor="#36f" to="4500,1092" from="180,1092" style="position: absolute; mso-wrap-style: square"></v:line><v:line id="_x0000_s1059" strokeweight="1pt" strokecolor="#36f" to="4500,3276" from="180,3276" style="position: absolute; mso-wrap-style: square"></v:line><v:oval id="_x0000_s1060" strokecolor="lime" fillcolor="#f90" style="width: 360px; position: absolute; top: 3072px; height: 360px; mso-wrap-style: square"></v:oval><v:rect id="_x0000_s1061" style="left: 360px; width: 720px; position: absolute; top: 156px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1062" style="left: 1440px; width: 720px; position: absolute; top: 156px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1063" style="left: 2520px; width: 720px; position: absolute; top: 156px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1064" fillcolor="black" style="left: 3600px; width: 720px; position: absolute; top: 156px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1065" style="left: 3600px; width: 720px; position: absolute; top: 1248px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1066" fillcolor="black" style="left: 2520px; width: 720px; position: absolute; top: 1248px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1067" style="left: 1440px; width: 720px; position: absolute; top: 1248px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1068" fillcolor="black" style="left: 360px; width: 720px; position: absolute; top: 2400px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1069" fillcolor="black" style="left: 360px; width: 720px; position: absolute; top: 1248px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1070" fillcolor="black" style="left: 1440px; width: 720px; position: absolute; top: 2340px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1071" style="left: 2520px; width: 720px; position: absolute; top: 2340px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1072" style="left: 3600px; width: 720px; position: absolute; top: 2340px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1073" style="left: 3600px; width: 720px; position: absolute; top: 3432px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1074" fillcolor="black" style="left: 2520px; width: 720px; position: absolute; top: 3432px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1075" style="left: 1440px; width: 720px; position: absolute; top: 3432px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1076" style="left: 360px; width: 720px; position: absolute; top: 3432px; height: 720px; mso-wrap-style: square"></v:rect><v:shapetype id="_x0000_t202" coordsize="21600,21600" path="m,l,21600r21600,l21600,xe" o:spt="202"><v:stroke joinstyle="miter"></v:stroke><v:path o:connecttype="rect" gradientshapeok="t"></v:path></v:shapetype><v:shape id="_x0000_s1077" stroked="f" type="#_x0000_t202" style="left: 1980px; width: 900px; position: absolute; top: 4368px; height: 468px; mso-wrap-style: square"><v:textbox>
<table cellspacing="0" cellpadding="0" width="100%">
    <tbody>
        <tr>
            <td style="border-right: #ece9d8; border-top: #ece9d8; border-left: #ece9d8; border-bottom: #ece9d8; background-color: transparent">
            <div>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><b style="mso-bidi-font-weight: normal"><span style="color: fuchsia; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">图三</span></b></span><b style="mso-bidi-font-weight: normal"><span lang="EN-US" style="font-size: 12pt; color: fuchsia"><o:p></o:p></span></b></p>
            </div>
            </td>
        </tr>
    </tbody>
</table>
</v:textbox></v:shape></v:group><o:wrapblock><v:group id="_x0000_s1026" o:allowincell="f" coordsize="4320,4836" style="margin-top: 299.2pt; z-index: 1; left: 0px; margin-left: -11.1pt; width: 207.8pt; position: absolute; height: 228.15pt; text-align: left"><v:rect id="_x0000_s1027" strokeweight="1.25pt" strokecolor="blue" fillcolor="#9cf" style="width: 4320px; position: absolute; height: 4320px; mso-wrap-style: square"></v:rect><v:line id="_x0000_s1028" strokeweight="1pt" strokecolor="#36f" to="2160,4368" from="2160,0" style="position: absolute; mso-wrap-style: square"></v:line><v:line id="_x0000_s1029" strokeweight="1pt" strokecolor="#36f" to="1080,4368" from="1080,0" style="position: absolute; mso-wrap-style: square"></v:line><v:line id="_x0000_s1030" strokeweight="1pt" strokecolor="#36f" to="3240,4368" from="3240,0" style="position: absolute; mso-wrap-style: square"></v:line><v:line id="_x0000_s1031" strokeweight="1pt" strokecolor="#36f" to="4320,2184" from="0,2184" style="position: absolute; mso-wrap-style: square"></v:line><v:line id="_x0000_s1032" strokeweight="1pt" strokecolor="#36f" to="4320,1092" from="0,1092" style="position: absolute; mso-wrap-style: square"></v:line><v:line id="_x0000_s1033" strokeweight="1pt" strokecolor="#36f" to="4320,3276" from="0,3276" style="position: absolute; mso-wrap-style: square"></v:line><v:oval id="_x0000_s1034" strokecolor="lime" fillcolor="#f90" style="left: 900px; width: 360px; position: absolute; top: 2028px; height: 360px; mso-wrap-style: square"></v:oval><v:rect id="_x0000_s1035" style="left: 180px; width: 720px; position: absolute; top: 156px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1036" style="left: 1260px; width: 720px; position: absolute; top: 156px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1037" style="left: 2340px; width: 720px; position: absolute; top: 156px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1038" fillcolor="black" style="left: 3420px; width: 720px; position: absolute; top: 156px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1039" style="left: 3420px; width: 720px; position: absolute; top: 1248px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1040" fillcolor="black" style="left: 2340px; width: 720px; position: absolute; top: 1248px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1041" style="left: 1260px; width: 720px; position: absolute; top: 1248px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1042" fillcolor="black" style="left: 180px; width: 720px; position: absolute; top: 2400px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1043" style="left: 180px; width: 720px; position: absolute; top: 1248px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1044" fillcolor="black" style="left: 1260px; width: 720px; position: absolute; top: 2340px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1045" style="left: 2340px; width: 720px; position: absolute; top: 2340px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1046" style="left: 3420px; width: 720px; position: absolute; top: 2340px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1047" style="left: 3420px; width: 720px; position: absolute; top: 3432px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1048" fillcolor="black" style="left: 2340px; width: 720px; position: absolute; top: 3432px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1049" style="left: 1260px; width: 720px; position: absolute; top: 3432px; height: 720px; mso-wrap-style: square"></v:rect><v:rect id="_x0000_s1050" style="left: 180px; width: 720px; position: absolute; top: 3432px; height: 720px; mso-wrap-style: square"></v:rect><v:shape id="_x0000_s1051" stroked="f" type="#_x0000_t202" style="left: 1800px; width: 900px; position: absolute; top: 4368px; height: 468px; mso-wrap-style: square"><v:textbox>
<table cellspacing="0" cellpadding="0" width="100%">
    <tbody>
        <tr>
            <td style="border-right: #ece9d8; border-top: #ece9d8; border-left: #ece9d8; border-bottom: #ece9d8; background-color: transparent">
            <div>
            <p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><b style="mso-bidi-font-weight: normal"><span style="color: fuchsia; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">图二</span></b></span><b style="mso-bidi-font-weight: normal"><span lang="EN-US" style="font-size: 12pt; color: fuchsia"><o:p></o:p></span></b></p>
            </div>
            </td>
        </tr>
    </tbody>
</table>
</v:textbox></v:shape><w:wrap type="topAndBottom"></w:wrap></v:group></o:wrapblock><span style="font-size: medium"><br clear="all" style="mso-ignore: vglayout"/>
</span>
</p><p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left; mso-layout-grid-align: none"><span style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt"><span lang="EN-US"><o:p></o:p></span></span></p>
<p></p><p></p>
<p></p>
<span style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt"><br/>
</span><p></p>
<p><span style="font-size: medium"><span style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt">给定一个初始状态，求“动子”的一种运动轨迹，可以将所有的格子变成白色，最后“动子”停在哪里是无所谓的。</span></span></p></div>

# Input

<div class="content"><p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left; mso-layout-grid-align: none"><span style="font-size: medium"><span style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt">第一行<span lang="EN-US">T</span>表示数据组数</span></span><span style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt"><font size="3"><span lang="EN-US"><o:p></o:p></span></font></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left; mso-layout-grid-align: none"><span style="font-size: medium"><span style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt">对于每组数据，第一行<span lang="EN-US">n</span>表示网格大小</span></span><span style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt"><font size="3"><span lang="EN-US"><o:p></o:p></span></font></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left; mso-layout-grid-align: none"><span style="font-size: medium"><span style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt">接下来<span lang="EN-US">n</span>行<span lang="EN-US">n</span>列描述初始网格，<span lang="EN-US">0</span>表示白色，<span lang="EN-US">1</span>表示黑色</span></span><span style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt"><font size="3"><span lang="EN-US"><o:p></o:p></span></font></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-indent: 21pt; text-align: left; mso-layout-grid-align: none"><span style="font-size: medium"><span style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt">接下来一行<span lang="EN-US">x y</span>表示动子的初始位置，左上角为<span lang="EN-US">(1,1)</span>，左下角为<span lang="EN-US">(n+1,1)</span></span></span><span style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt"><font size="3"><span lang="EN-US"><o:p></o:p></span></font></span></p>
<p></p></div>

# Output

<div class="content"><p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left; mso-layout-grid-align: none"><span style="font-size: medium"><b style="mso-bidi-font-weight: normal"><span lang="EN-US" style="color: black; font-family: 幼圆; mso-font-kerning: 0pt; mso-hansi-font-family: 宋体; mso-bidi-font-family: SimSun-Identity-H"><span style="mso-tab-count: 1">   </span></span></b><span style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt">对于每组数据，在一行中输出一个相应的答案</span></span><span style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt"><font size="3"><span lang="EN-US"><o:p></o:p></span></font></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; text-align: left; mso-layout-grid-align: none"><span style="font-size: medium"><span lang="EN-US" style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt"><span style="mso-tab-count: 1">    </span></span><span style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt">若无解则输出“<span lang="EN-US">No Solution!”</span>，否则输出一个仅包含‘<span lang="EN-US">L’</span>‘<span lang="EN-US">R’</span>‘<span lang="EN-US">U</span>’‘<span lang="EN-US">D’</span>（上下左右）的字符串表示“动子”的移动路线，有多解时任意输出任意一组解即可，要求输出的解长度不超过<span lang="EN-US">5000</span></span></span><font size="3"><span style="color: black; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: SimSun-Identity-H; mso-bidi-font-size: 10.5pt"><span lang="EN-US"><o:p></o:p></span></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><span lang="EN-US" style="font-size: 10pt; font-family: 宋体"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1<br/>
1<br/>
1 1<br/>
2<br/>
0 1<br/>
1 0<br/>
2 2<br/>
7<br/>
1 1 0 0 1 0 1 <br/>
1 1 0 1 0 1 1 <br/>
1 0 1 0 1 1 1 <br/>
0 1 0 1 1 0 1 <br/>
1 1 1 1 1 1 1 <br/>
1 1 1 1 1 1 1 <br/>
1 1 1 1 1 1 1 <br/>
1 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">R<br/>
ULDR<br/>
No Solution!<br/>
</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><font size="3"><span lang="EN-US" style="color: black; font-family: 宋体; mso-font-kerning: 0pt">T≤5，1≤n≤15</span></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><font size="3"><span lang="EN-US" style="color: black; font-family: 宋体; mso-font-kerning: 0pt">请不要提交，期待SPJ</span></font></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

