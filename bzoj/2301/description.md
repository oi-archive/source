
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
<span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">对于给出的</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">n</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">个询问，每次求有多少个数对</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">(x,y)</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">，满足</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">a</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">≤</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">x</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">≤</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">b</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">，</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">c</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">≤</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">y</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">≤</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">d</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">，且</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">gcd(x,y) = k</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">，</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">gcd(x,y)</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">函数为</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">x</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">和</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">y</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">的最大公约数。</span>
<p style="line-height: 150%;" class="MsoNormal"><span lang="EN-US" style="font-size: 12pt; line-height: 150%;"><br/>
</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;"><br/>
</span></p></div>

# Input

<div class="content"><p><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">第一行一个整数</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">n</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">，接下来</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">n</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">行每行五个整数，分别表示</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">a</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">、</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">b</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">、</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">c</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">、</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">d</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">、</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">k</span></p>
<p style="line-height: 150%;" class="MsoNormal"><span lang="EN-US" style="font-size: 12pt; line-height: 150%;"> </span></p></div>

# Output

<div class="content"><p><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">共</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">n</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">行，每行一个整数表示满足要求的数对</span><span lang="EN-US" style="font-size: 12pt; line-height: 150%;">(x,y)</span><span style="font-size: 12pt; line-height: 150%; font-family: 宋体;">的个数</span></p>
<p style="line-height: 150%;" class="MsoNormal"><span lang="EN-US" style="font-size: 12pt; line-height: 150%;"> </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
<br/>
2 5 1 5 1<br/>
<br/>
1 5 1 5 2<br/>
<br/>
 <br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
14<br/>
<br/>
3<br/>
<br/>
 <br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
100%的数据满足：1≤n≤50000，1≤a≤b≤50000，1≤c≤d≤50000，1≤k≤50000<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

