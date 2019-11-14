
# Description

<div class="content"><p><!--[if gte mso 9]><xml>
<w:WordDocument>
<w:View>Normal</w:View>
<w:Zoom>0</w:Zoom>
<w:PunctuationKerning />
<w:DrawingGridVerticalSpacing>7.8 磅</w:DrawingGridVerticalSpacing>
<w:DisplayHorizontalDrawingGridEvery>0</w:DisplayHorizontalDrawingGridEvery>
<w:DisplayVerticalDrawingGridEvery>2</w:DisplayVerticalDrawingGridEvery>
<w:ValidateAgainstSchemas />
<w:SaveIfXMLInvalid>false</w:SaveIfXMLInvalid>
<w:IgnoreMixedContent>false</w:IgnoreMixedContent>
<w:AlwaysShowPlaceholderText>false</w:AlwaysShowPlaceholderText>
<w:Compatibility>
<w:SpaceForUL />
<w:BalanceSingleByteDoubleByteWidth />
<w:DoNotLeaveBackslashAlone />
<w:ULTrailSpace />
<w:DoNotExpandShiftReturn />
<w:AdjustLineHeightInTable />
<w:BreakWrappedTables />
<w:SnapToGridInCell />
<w:WrapTextWithPunct />
<w:UseAsianBreakRules />
<w:DontGrowAutofit />
<w:UseFELayout />
</w:Compatibility>
<w:BrowserLevel>MicrosoftInternetExplorer4</w:BrowserLevel>
</w:WordDocument>
</xml><![endif]--><!--[if gte mso 9]><xml>
<w:LatentStyles DefLockedState="false" LatentStyleCount="156">
</w:LatentStyles>
</xml><![endif]--><!--[if !mso]><object
classid="clsid:38481807-CA0E-42D2-BF39-B33AF135CC4D" id=ieooui></object>
<style>
st1\:*{behavior:url(#ieooui) }
</style>
<![endif]--><!--[if gte mso 10]>
<style>
/* Style Definitions */
table.MsoNormalTable
{mso-style-name:普通表格;
mso-tstyle-rowband-size:0;
mso-tstyle-colband-size:0;
mso-style-noshow:yes;
mso-style-parent:"";
mso-padding-alt:0cm 5.4pt 0cm 5.4pt;
mso-para-margin:0cm;
mso-para-margin-bottom:.0001pt;
mso-pagination:widow-orphan;
font-size:10.0pt;
font-family:"Times New Roman";
mso-ansi-language:#0400;
mso-fareast-language:#0400;
mso-bidi-language:#0400;}
</style>
<![endif]--></p>
<span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">给</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">n</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">个人安排座位，先给每个人一个</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">1~n</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">的编号，设第</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">i</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">个人的编号为</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">ai</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">（不同人的编号可以相同），接着从第一个人开始，大家依次入座，第</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">i</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">个人来了以后尝试坐到</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">ai</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">，如果</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">ai</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">被占据了，就尝试</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">ai+1</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">，</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">ai+1</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">也被占据了的话就尝试</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">ai+2</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">，……，如果一直尝试到第</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">n</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">个都不行，该安排方案就不合法。然而有</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">m</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">个人的编号已经确定</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">(</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">他们或许贿赂了你的上司</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">...)</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">，你只能安排剩下的人的编号，求有多少种合法的安排方案。由于答案可能很大，只需输出其除以</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">M</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">后的余数即可。</span>
<p style="line-height: 150%;" class="MsoNormal"><span lang="EN-US" style="font-size: 12pt; line-height: 150%;"> </span></p></div>

# Input

<div class="content"><p><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">第一行一个整数</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">T</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">，表示数据组数</span></p>
<p style="line-height: 150%;" class="MsoNormal"><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">对于每组数据，第一行有三个整数，分别表示</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">n</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">、</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">m</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">、</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">M</span></p>
<p style="line-height: 150%;" class="MsoNormal"><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">若</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">m</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">不为</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">0</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">，则接下来一行有</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">m</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">对整数，</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">p1</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">、</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">q1</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">，</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">p2</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">、</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">q2 ,…, pm</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">、</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">qm</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">，其中第</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">i</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">对整数</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">pi</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">、</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">qi</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">表示第</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">pi</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">个人的编号必须为</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">qi</span></p>
<p style="line-height: 150%;" class="MsoNormal"><span lang="EN-US" style="font-size: 12pt; line-height: 150%;"> </span></p></div>

# Output

<div class="content"><p><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">对于每组数据输出一行，若是有解则输出</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">YES</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">，后跟一个整数表示方案数</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">mod M</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">，注意，</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">YES</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">和数之间只有一个空格，否则输出</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">NO</span></p>
<p style="line-height: 150%;" class="MsoNormal"><span lang="EN-US" style="font-size: 12pt; line-height: 150%;"> </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
<br/>
4 3 10<br/>
<br/>
1 2 2 1 3 1<br/>
<br/>
10 3 8882<br/>
<br/>
7 9 2 9 5 10<br/>
<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
<br/>
YES 4<br/>
<br/>
NO<br/>
<br/>
 <br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
100%的数据满足：1≤T≤10，1≤n≤300，0≤m≤n，2≤M≤109，1≤pi、qi≤n   且保证pi互不相同。<br/><br/>
<br/><br/>
 <br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

