<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　现在Berland正在举行一场赛车比赛。比赛赛道可以看成一条<i>s</i>公里长的直线。有<i>n</i>辆赛车参加了这个比赛，他们同时从赛道的起点出发。我们已经知道每辆赛车的行为——在每一阶段中赛车的速度是恒定的。第<i>i</i>辆赛车的第<i>j</i>个阶段可以用数对(<i>v</i><sub><i>i</i>, <i>j</i></sub>, <i>t</i><sub><i>i</i>, <i>j</i></sub>)表示，<i>v</i><sub><i>i</i>, <i>j</i></sub>表示第<i>i</i>辆赛车在第<i>j</i>个阶段的速度，单位是公里每小时，<i>t</i><sub><i>i</i>, <i>j</i></sub>表示第<i>i</i>辆赛车在第<i>j</i>个阶段的行驶时间，单位是小时。每个阶段按顺序给出，赛车将按照这些行驶。<br/>
　　你的任务就是统计这次比赛中出现了多少次超车，超车指一辆车行驶到了另一辆车的前面。所有超车都是在一瞬间完成的，也就是说不会存在两辆车在一段正长度的时间中并行的情况。可能存在同一时间发生多次超车的情况，此时每一个超车都必须被统计。两辆车在赛道的起点或终点相遇的情况不需要统计。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含两个整数<i>n</i>和<i>s</i>，赛车的数量和赛道的长度（单位：公里）。<br/>
　　接下来的<i>n</i>行描述了每辆赛车的行驶方式。每一行开头为一个整数<i>k</i>，表示这辆赛车行驶的阶段数。接着是<i>k</i>对用空格分隔的整数，每一对整数表示赛车在这一阶段的速度和行驶时间。保证每辆赛车所有阶段行驶路程的总长度等于<i>s</i>，所有的超车都在瞬间完成。</div>
# 输出格式

<div class="pdcont">　　输出一个整数——这场比赛中发生的超车次数。</div>
# 样例输入

<pre class="pddata">2 33
2 5 1 2 14
1 3 11
</pre>

# 样例输出

<pre class="pddata">1
【数据规模和约定】
<!--[if gte mso 9]><xml>
<w:WordDocument>
<w:View>Normal</w:View>
<w:Zoom>0</w:Zoom>
<w:TrackMoves/>
<w:TrackFormatting/>
<w:PunctuationKerning/>
<w:DrawingGridVerticalSpacing>7.8 磅</w:DrawingGridVerticalSpacing>
<w:DisplayHorizontalDrawingGridEvery>0</w:DisplayHorizontalDrawingGridEvery>
<w:DisplayVerticalDrawingGridEvery>2</w:DisplayVerticalDrawingGridEvery>
<w:ValidateAgainstSchemas/>
<w:SaveIfXMLInvalid>false</w:SaveIfXMLInvalid>
<w:IgnoreMixedContent>false</w:IgnoreMixedContent>
<w:AlwaysShowPlaceholderText>false</w:AlwaysShowPlaceholderText>
<w:DoNotPromoteQF/>
<w:LidThemeOther>EN-US</w:LidThemeOther>
<w:LidThemeAsian>ZH-CN</w:LidThemeAsian>
<w:LidThemeComplexScript>X-NONE</w:LidThemeComplexScript>
<w:Compatibility>
<w:SpaceForUL/>
<w:BalanceSingleByteDoubleByteWidth/>
<w:DoNotLeaveBackslashAlone/>
<w:ULTrailSpace/>
<w:DoNotExpandShiftReturn/>
<w:AdjustLineHeightInTable/>
<w:BreakWrappedTables/>
<w:SnapToGridInCell/>
<w:WrapTextWithPunct/>
<w:UseAsianBreakRules/>
<w:DontGrowAutofit/>
<w:SplitPgBreakAndParaMark/>
<w:DontVertAlignCellWithSp/>
<w:DontBreakConstrainedForcedTables/>
<w:DontVertAlignInTxbx/>
<w:Word11KerningPairs/>
<w:CachedColBalance/>
<w:UseFELayout/>
</w:Compatibility>
<w:BrowserLevel>MicrosoftInternetExplorer4</w:BrowserLevel>
<m:mathPr>
<m:mathFont m:val="Cambria Math"/>
<m:brkBin m:val="before"/>
<m:brkBinSub m:val="--"/>
<m:smallFrac m:val="off"/>
<m:dispDef/>
<m:lMargin m:val="0"/>
<m:rMargin m:val="0"/>
<m:defJc m:val="centerGroup"/>
<m:wrapIndent m:val="1440"/>
<m:intLim m:val="subSup"/>
<m:naryLim m:val="undOvr"/>
</m:mathPr></w:WordDocument>
</xml><![endif]-->
</pre>
<div class="pddata"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">数据组数<br/>
</td><td valign="top" colspan="2" style="border:solid 1.0pt">输入数据或输入数据规模<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" colspan="2" style="border:solid 1.0pt"><pre class="pddata">5 33
2 1 3 3 10
1 11 3
2 5 3 3 6
2 3 1 10 3
2 6 3 3 5
</pre>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" colspan="2" style="border:solid 1.0pt"><pre class="pddata">5 835293
2 421 965 758 566
3 357 337 956 745 4 691
2 433 925 464 937
5 67 581 109 375 463 71 499 819 589 533
2 918 828 353 213
</pre>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">3~8<br/>
</td><td valign="top" style="border:solid 1.0pt">2 ≤ <i>n</i> ≤ 30<br/>
</td><td valign="top" rowspan="2" style="border:solid 1.0pt">1 ≤ <i>s</i> ≤ 10<sup>6</sup>,1 ≤ <i>k</i> ≤ 100,1 ≤ <i>v<sub>i</sub></i><sub>,</sub><sub> <i>j</i></sub> ≤ 1000,1 ≤ <i>t<sub>i</sub></i><sub>,</sub><sub> <i>j</i></sub> ≤ 1000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">7~20<br/>
</td><td valign="top" style="border:solid 1.0pt">2 ≤ <i>n</i> ≤ 100<br/>
</td></tr></tbody></table><pre class="pddata"><!--[if gte mso 9]><xml>
<w:LatentStyles DefLockedState="false" DefUnhideWhenUsed="true"
DefSemiHidden="true" DefQFormat="false" DefPriority="99"
LatentStyleCount="267">
<w:LsdException Locked="false" Priority="0" SemiHidden="false"
UnhideWhenUsed="false" QFormat="true" Name="Normal"/>
<w:LsdException Locked="false" Priority="9" SemiHidden="false"
UnhideWhenUsed="false" QFormat="true" Name="heading 1"/>
<w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 2"/>
<w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 3"/>
<w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 4"/>
<w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 5"/>
<w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 6"/>
<w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 7"/>
<w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 8"/>
<w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 9"/>
<w:LsdException Locked="false" Priority="39" Name="toc 1"/>
<w:LsdException Locked="false" Priority="39" Name="toc 2"/>
<w:LsdException Locked="false" Priority="39" Name="toc 3"/>
<w:LsdException Locked="false" Priority="39" Name="toc 4"/>
<w:LsdException Locked="false" Priority="39" Name="toc 5"/>
<w:LsdException Locked="false" Priority="39" Name="toc 6"/>
<w:LsdException Locked="false" Priority="39" Name="toc 7"/>
<w:LsdException Locked="false" Priority="39" Name="toc 8"/>
<w:LsdException Locked="false" Priority="39" Name="toc 9"/>
<w:LsdException Locked="false" Priority="35" QFormat="true" Name="caption"/>
<w:LsdException Locked="false" Priority="10" SemiHidden="false"
UnhideWhenUsed="false" QFormat="true" Name="Title"/>
<w:LsdException Locked="false" Priority="1" Name="Default Paragraph Font"/>
<w:LsdException Locked="false" Priority="11" SemiHidden="false"
UnhideWhenUsed="false" QFormat="true" Name="Subtitle"/>
<w:LsdException Locked="false" Priority="22" SemiHidden="false"
UnhideWhenUsed="false" QFormat="true" Name="Strong"/>
<w:LsdException Locked="false" Priority="20" SemiHidden="false"
UnhideWhenUsed="false" QFormat="true" Name="Emphasis"/>
<w:LsdException Locked="false" Priority="59" SemiHidden="false"
UnhideWhenUsed="false" Name="Table Grid"/>
<w:LsdException Locked="false" UnhideWhenUsed="false" Name="Placeholder Text"/>
<w:LsdException Locked="false" Priority="1" SemiHidden="false"
UnhideWhenUsed="false" QFormat="true" Name="No Spacing"/>
<w:LsdException Locked="false" Priority="60" SemiHidden="false"
UnhideWhenUsed="false" Name="Light Shading"/>
<w:LsdException Locked="false" Priority="61" SemiHidden="false"
UnhideWhenUsed="false" Name="Light List"/>
<w:LsdException Locked="false" Priority="62" SemiHidden="false"
UnhideWhenUsed="false" Name="Light Grid"/>
<w:LsdException Locked="false" Priority="63" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Shading 1"/>
<w:LsdException Locked="false" Priority="64" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Shading 2"/>
<w:LsdException Locked="false" Priority="65" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium List 1"/>
<w:LsdException Locked="false" Priority="66" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium List 2"/>
<w:LsdException Locked="false" Priority="67" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 1"/>
<w:LsdException Locked="false" Priority="68" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 2"/>
<w:LsdException Locked="false" Priority="69" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 3"/>
<w:LsdException Locked="false" Priority="70" SemiHidden="false"
UnhideWhenUsed="false" Name="Dark List"/>
<w:LsdException Locked="false" Priority="71" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful Shading"/>
<w:LsdException Locked="false" Priority="72" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful List"/>
<w:LsdException Locked="false" Priority="73" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful Grid"/>
<w:LsdException Locked="false" Priority="60" SemiHidden="false"
UnhideWhenUsed="false" Name="Light Shading Accent 1"/>
<w:LsdException Locked="false" Priority="61" SemiHidden="false"
UnhideWhenUsed="false" Name="Light List Accent 1"/>
<w:LsdException Locked="false" Priority="62" SemiHidden="false"
UnhideWhenUsed="false" Name="Light Grid Accent 1"/>
<w:LsdException Locked="false" Priority="63" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Shading 1 Accent 1"/>
<w:LsdException Locked="false" Priority="64" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Shading 2 Accent 1"/>
<w:LsdException Locked="false" Priority="65" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium List 1 Accent 1"/>
<w:LsdException Locked="false" UnhideWhenUsed="false" Name="Revision"/>
<w:LsdException Locked="false" Priority="34" SemiHidden="false"
UnhideWhenUsed="false" QFormat="true" Name="List Paragraph"/>
<w:LsdException Locked="false" Priority="29" SemiHidden="false"
UnhideWhenUsed="false" QFormat="true" Name="Quote"/>
<w:LsdException Locked="false" Priority="30" SemiHidden="false"
UnhideWhenUsed="false" QFormat="true" Name="Intense Quote"/>
<w:LsdException Locked="false" Priority="66" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium List 2 Accent 1"/>
<w:LsdException Locked="false" Priority="67" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 1 Accent 1"/>
<w:LsdException Locked="false" Priority="68" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 2 Accent 1"/>
<w:LsdException Locked="false" Priority="69" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 3 Accent 1"/>
<w:LsdException Locked="false" Priority="70" SemiHidden="false"
UnhideWhenUsed="false" Name="Dark List Accent 1"/>
<w:LsdException Locked="false" Priority="71" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful Shading Accent 1"/>
<w:LsdException Locked="false" Priority="72" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful List Accent 1"/>
<w:LsdException Locked="false" Priority="73" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful Grid Accent 1"/>
<w:LsdException Locked="false" Priority="60" SemiHidden="false"
UnhideWhenUsed="false" Name="Light Shading Accent 2"/>
<w:LsdException Locked="false" Priority="61" SemiHidden="false"
UnhideWhenUsed="false" Name="Light List Accent 2"/>
<w:LsdException Locked="false" Priority="62" SemiHidden="false"
UnhideWhenUsed="false" Name="Light Grid Accent 2"/>
<w:LsdException Locked="false" Priority="63" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Shading 1 Accent 2"/>
<w:LsdException Locked="false" Priority="64" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Shading 2 Accent 2"/>
<w:LsdException Locked="false" Priority="65" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium List 1 Accent 2"/>
<w:LsdException Locked="false" Priority="66" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium List 2 Accent 2"/>
<w:LsdException Locked="false" Priority="67" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 1 Accent 2"/>
<w:LsdException Locked="false" Priority="68" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 2 Accent 2"/>
<w:LsdException Locked="false" Priority="69" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 3 Accent 2"/>
<w:LsdException Locked="false" Priority="70" SemiHidden="false"
UnhideWhenUsed="false" Name="Dark List Accent 2"/>
<w:LsdException Locked="false" Priority="71" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful Shading Accent 2"/>
<w:LsdException Locked="false" Priority="72" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful List Accent 2"/>
<w:LsdException Locked="false" Priority="73" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful Grid Accent 2"/>
<w:LsdException Locked="false" Priority="60" SemiHidden="false"
UnhideWhenUsed="false" Name="Light Shading Accent 3"/>
<w:LsdException Locked="false" Priority="61" SemiHidden="false"
UnhideWhenUsed="false" Name="Light List Accent 3"/>
<w:LsdException Locked="false" Priority="62" SemiHidden="false"
UnhideWhenUsed="false" Name="Light Grid Accent 3"/>
<w:LsdException Locked="false" Priority="63" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Shading 1 Accent 3"/>
<w:LsdException Locked="false" Priority="64" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Shading 2 Accent 3"/>
<w:LsdException Locked="false" Priority="65" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium List 1 Accent 3"/>
<w:LsdException Locked="false" Priority="66" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium List 2 Accent 3"/>
<w:LsdException Locked="false" Priority="67" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 1 Accent 3"/>
<w:LsdException Locked="false" Priority="68" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 2 Accent 3"/>
<w:LsdException Locked="false" Priority="69" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 3 Accent 3"/>
<w:LsdException Locked="false" Priority="70" SemiHidden="false"
UnhideWhenUsed="false" Name="Dark List Accent 3"/>
<w:LsdException Locked="false" Priority="71" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful Shading Accent 3"/>
<w:LsdException Locked="false" Priority="72" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful List Accent 3"/>
<w:LsdException Locked="false" Priority="73" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful Grid Accent 3"/>
<w:LsdException Locked="false" Priority="60" SemiHidden="false"
UnhideWhenUsed="false" Name="Light Shading Accent 4"/>
<w:LsdException Locked="false" Priority="61" SemiHidden="false"
UnhideWhenUsed="false" Name="Light List Accent 4"/>
<w:LsdException Locked="false" Priority="62" SemiHidden="false"
UnhideWhenUsed="false" Name="Light Grid Accent 4"/>
<w:LsdException Locked="false" Priority="63" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Shading 1 Accent 4"/>
<w:LsdException Locked="false" Priority="64" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Shading 2 Accent 4"/>
<w:LsdException Locked="false" Priority="65" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium List 1 Accent 4"/>
<w:LsdException Locked="false" Priority="66" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium List 2 Accent 4"/>
<w:LsdException Locked="false" Priority="67" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 1 Accent 4"/>
<w:LsdException Locked="false" Priority="68" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 2 Accent 4"/>
<w:LsdException Locked="false" Priority="69" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 3 Accent 4"/>
<w:LsdException Locked="false" Priority="70" SemiHidden="false"
UnhideWhenUsed="false" Name="Dark List Accent 4"/>
<w:LsdException Locked="false" Priority="71" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful Shading Accent 4"/>
<w:LsdException Locked="false" Priority="72" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful List Accent 4"/>
<w:LsdException Locked="false" Priority="73" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful Grid Accent 4"/>
<w:LsdException Locked="false" Priority="60" SemiHidden="false"
UnhideWhenUsed="false" Name="Light Shading Accent 5"/>
<w:LsdException Locked="false" Priority="61" SemiHidden="false"
UnhideWhenUsed="false" Name="Light List Accent 5"/>
<w:LsdException Locked="false" Priority="62" SemiHidden="false"
UnhideWhenUsed="false" Name="Light Grid Accent 5"/>
<w:LsdException Locked="false" Priority="63" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Shading 1 Accent 5"/>
<w:LsdException Locked="false" Priority="64" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Shading 2 Accent 5"/>
<w:LsdException Locked="false" Priority="65" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium List 1 Accent 5"/>
<w:LsdException Locked="false" Priority="66" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium List 2 Accent 5"/>
<w:LsdException Locked="false" Priority="67" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 1 Accent 5"/>
<w:LsdException Locked="false" Priority="68" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 2 Accent 5"/>
<w:LsdException Locked="false" Priority="69" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 3 Accent 5"/>
<w:LsdException Locked="false" Priority="70" SemiHidden="false"
UnhideWhenUsed="false" Name="Dark List Accent 5"/>
<w:LsdException Locked="false" Priority="71" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful Shading Accent 5"/>
<w:LsdException Locked="false" Priority="72" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful List Accent 5"/>
<w:LsdException Locked="false" Priority="73" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful Grid Accent 5"/>
<w:LsdException Locked="false" Priority="60" SemiHidden="false"
UnhideWhenUsed="false" Name="Light Shading Accent 6"/>
<w:LsdException Locked="false" Priority="61" SemiHidden="false"
UnhideWhenUsed="false" Name="Light List Accent 6"/>
<w:LsdException Locked="false" Priority="62" SemiHidden="false"
UnhideWhenUsed="false" Name="Light Grid Accent 6"/>
<w:LsdException Locked="false" Priority="63" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Shading 1 Accent 6"/>
<w:LsdException Locked="false" Priority="64" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Shading 2 Accent 6"/>
<w:LsdException Locked="false" Priority="65" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium List 1 Accent 6"/>
<w:LsdException Locked="false" Priority="66" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium List 2 Accent 6"/>
<w:LsdException Locked="false" Priority="67" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 1 Accent 6"/>
<w:LsdException Locked="false" Priority="68" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 2 Accent 6"/>
<w:LsdException Locked="false" Priority="69" SemiHidden="false"
UnhideWhenUsed="false" Name="Medium Grid 3 Accent 6"/>
<w:LsdException Locked="false" Priority="70" SemiHidden="false"
UnhideWhenUsed="false" Name="Dark List Accent 6"/>
<w:LsdException Locked="false" Priority="71" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful Shading Accent 6"/>
<w:LsdException Locked="false" Priority="72" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful List Accent 6"/>
<w:LsdException Locked="false" Priority="73" SemiHidden="false"
UnhideWhenUsed="false" Name="Colorful Grid Accent 6"/>
<w:LsdException Locked="false" Priority="19" SemiHidden="false"
UnhideWhenUsed="false" QFormat="true" Name="Subtle Emphasis"/>
<w:LsdException Locked="false" Priority="21" SemiHidden="false"
UnhideWhenUsed="false" QFormat="true" Name="Intense Emphasis"/>
<w:LsdException Locked="false" Priority="31" SemiHidden="false"
UnhideWhenUsed="false" QFormat="true" Name="Subtle Reference"/>
<w:LsdException Locked="false" Priority="32" SemiHidden="false"
UnhideWhenUsed="false" QFormat="true" Name="Intense Reference"/>
<w:LsdException Locked="false" Priority="33" SemiHidden="false"
UnhideWhenUsed="false" QFormat="true" Name="Book Title"/>
<w:LsdException Locked="false" Priority="37" Name="Bibliography"/>
<w:LsdException Locked="false" Priority="39" QFormat="true" Name="TOC Heading"/>
</w:LatentStyles>
</xml><![endif]--><!--[if gte mso 10]>
<style>
/* Style Definitions */
table.MsoNormalTable
{mso-style-name:普通表格;
mso-tstyle-rowband-size:0;
mso-tstyle-colband-size:0;
mso-style-noshow:yes;
mso-style-priority:99;
mso-style-qformat:yes;
mso-style-parent:"";
mso-padding-alt:0cm 5.4pt 0cm 5.4pt;
mso-para-margin:0cm;
mso-para-margin-bottom:.0001pt;
mso-pagination:widow-orphan;
font-size:10.5pt;
mso-bidi-font-size:11.0pt;
font-family:"Calibri","sans-serif";
mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;
mso-hansi-font-family:Calibri;
mso-hansi-theme-font:minor-latin;
mso-font-kerning:1.0pt;}
table.MsoTableGrid
{mso-style-name:网格型;
mso-tstyle-rowband-size:0;
mso-tstyle-colband-size:0;
mso-style-priority:59;
mso-style-unhide:no;
border:solid black 1.0pt;
mso-border-themecolor:text1;
mso-border-alt:solid black .5pt;
mso-border-themecolor:text1;
mso-padding-alt:0cm 5.4pt 0cm 5.4pt;
mso-border-insideh:.5pt solid black;
mso-border-insideh-themecolor:text1;
mso-border-insidev:.5pt solid black;
mso-border-insidev-themecolor:text1;
mso-para-margin:0cm;
mso-para-margin-bottom:.0001pt;
mso-pagination:widow-orphan;
font-size:10.5pt;
mso-bidi-font-size:11.0pt;
font-family:"Calibri","sans-serif";
mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;
mso-hansi-font-family:Calibri;
mso-hansi-theme-font:minor-latin;
mso-font-kerning:1.0pt;}
</style>
<![endif]-->
</pre>
</div>

</div>