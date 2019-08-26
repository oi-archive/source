
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
</xml><![endif]--><!--[if gte mso 10]>
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
mso-fareast-font-family:"Times New Roman";
mso-ansi-language:#0400;
mso-fareast-language:#0400;
mso-bidi-language:#0400;}
</style>
<![endif]--></p>
<p align="left" class="MsoNormal" style="text-align: left; text-indent: 24pt;"><span style="font-size: 12pt; font-family: 宋体;">给你一对数</span><span lang="EN-US" style="font-size: 12pt;">a,b</span><span style="font-size: 12pt; font-family: 宋体;">，你可以任意使用</span><span lang="EN-US" style="font-size: 12pt;">(a,b), (a,-b), (-a,b), (-a,-b), (b,a), (b,-a), (-b,a), (-b,-a)</span><span style="font-size: 12pt; font-family: 宋体;">这些向量，问你能不能拼出另一个向量</span><span lang="EN-US" style="font-size: 12pt;">(x,y)</span><span style="font-size: 12pt; font-family: 宋体;">。</span></p>
<p align="left" class="MsoNormal" style="text-align: left; text-indent: 24pt;"><span style="font-size: 12pt; font-family: 宋体;">说明：这里的拼就是使得你选出的向量之和为</span><span lang="EN-US" style="font-size: 12pt;">(x,y)</span></p>
<p class="MsoNormal"><span lang="EN-US" style="font-size: 12pt;"> </span></p></div>

# Input

<div class="content"><p><span style="font-size: 12pt; font-family: 宋体;">第一行数组组数</span><span lang="EN-US" style="font-size: 12pt;">t</span><span style="font-size: 12pt; font-family: 宋体;">，</span><span lang="EN-US" style="font-size: 12pt;">(t&lt;=50000)</span></p>
<p class="MsoNormal" style="text-indent: 24pt;"><span style="font-size: 12pt; font-family: 宋体;">接下来</span><span lang="EN-US" style="font-size: 12pt;">t</span><span style="font-size: 12pt; font-family: 宋体;">行每行四个整数</span><span lang="EN-US" style="font-size: 12pt;">a,b,x,y<span style="">  </span>(-2*10<sup>9</sup>&lt;=a,b,x,y&lt;=2*10<sup>9</sup>)</span></p></div>

# Output

<div class="content"><p><span lang="EN-US" style="font-size: 12pt;"> </span></p>
<p>t行每行为Y或者为N，分别表示可以拼出来，不能拼出来</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
<br/>
2 1 3 3<br/>
<br/>
1 1 0 1<br/>
<br/>
1 0 -2 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Y<br/>
<br/>
N<br/>
<br/>
Y<br/>
<br/>
 <br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p> <br/><br/>
<br/><br/>
样例解释：<br/><br/>
<br/><br/>
第一组：(2,1)+(1,2)=(3,3)<br/><br/>
<br/><br/>
第三组：(-1,0)+(-1,0)+(0,1)+(0,1)+(0,1)=(-2,3)</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

