
# Description

<div class="content"><div>
<div>健佳正在用大小相同的砖块来砌起一面墙。这面墙由 列砖块所组成，它们从左到右的编号0至n-1。各列的高度可</div>
<div>以不同。各列的高度就是该列砖块的数量。健佳用如下方式来建造这面墙。最开始每列都没有砖块。此后，健佳通</div>
<div>过k个阶段的增加(adding)或移除(removing)砖块操作来砌墙。当所有k个阶段完成后，这面墙就砌好了。在每个阶</div>
<div>段中，健佳都会被告知一个连续的砖块列的范围，以及一个高度值h，然后他就完成如下过程：在增加砖块(adding</div>
<div>)阶段，对于给定的列范围中高度小于h的列，健佳会增加砖块使它们的高度都恰好等于h。此时他不会改变那些高</div>
<div>度大于或等于h的列。在移除砖块(removing)阶段，对于给定的列范围中高度大于 的列，健佳会移除砖块使它们的</div>
<div>高度都恰好等于h。此时他不会改变那些高度小于或等于h的列。你的任务就是计算出这面墙的最后形状。</div>
</div></div>

# Input

<div class="content"><div>
<div>第1行：n, k。</div>
<div>第2+i 行(0≤i≤k-1)：op[i], left[i], right[i], height[i]。</div>
<div>n: 这面墙中的列数。</div>
<div>k: 阶段数。</div>
<div>op: 大小为k的数组；op[i]是第i个阶段的类型：1 表示增加阶段(adding) 而 2表示移除阶段(removing) </div>
<div>其中0≤i≤k-1。</div>
<div>left 和 right: 大小为k的数组；在第i个阶段中，列的范围从第left[i] 列开始到第right[i]列结束（包括两端</div>
<div>left[i] 和 right[i]），其中0≤i≤k-1。这里保证满足left[i]≤right[i]。</div>
<div>height: 大小为k的数组；height[i] 表示在阶段i的高度参数，其中0≤i≤k-1。</div>
</div></div>

# Output

<div class="content"><div>共n行</div>
<div>第i行包含一个整数表示finalHeight[i]。</div>
<div>finalHeight: 大小为n的数组；你需要把第i列砖块的最终数量存放到finalHeight[i]中做为返回结果</div>
<div>其中0≤i≤n-1。</div></div>

# Sample Input

<div class="content"><span class="sampledata">输入样例1<br/>
10 3<br/>
1 3 4 91220<br/>
1 5 9 48623<br/>
2 3 5 39412<br/>
<br/>
输入样例2<br/>
10 6<br/>
1 1 8 4<br/>
2 4 9 1<br/>
2 3 6 5<br/>
1 0 5 3<br/>
1 2 2 5<br/>
2 6 7 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">输出样例1<br/>
0<br/>
0<br/>
0<br/>
39412<br/>
39412<br/>
39412<br/>
48623<br/>
48623<br/>
48623<br/>
48623<br/>
<br/>
输出样例2<br/>
3<br/>
4<br/>
5<br/>
4<br/>
3<br/>
3<br/>
0<br/>
0<br/>
1<br/>
0</span></div>

# Hint

<div class="content"><p></p><p><img width="572" height="371" alt="" src="/source/bzoj/4364/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUxMi8xMS5HSUY=.GIF"/></p><br/>
<p><img width="277" height="550" src="/source/bzoj/4364/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUxMi8zMy5naWY=.gif" alt=""/></p><br/>
<p><!--[if gte mso 9]><xml><br />
<w:WordDocument><br />
<w:View>Normal</w:View><br />
<w:Zoom>0</w:Zoom><br />
<w:PunctuationKerning /><br />
<w:DrawingGridVerticalSpacing>7.8 磅</w:DrawingGridVerticalSpacing><br />
<w:DisplayHorizontalDrawingGridEvery>0</w:DisplayHorizontalDrawingGridEvery><br />
<w:DisplayVerticalDrawingGridEvery>2</w:DisplayVerticalDrawingGridEvery><br />
<w:ValidateAgainstSchemas /><br />
<w:SaveIfXMLInvalid>false</w:SaveIfXMLInvalid><br />
<w:IgnoreMixedContent>false</w:IgnoreMixedContent><br />
<w:AlwaysShowPlaceholderText>false</w:AlwaysShowPlaceholderText><br />
<w:Compatibility><br />
<w:SpaceForUL /><br />
<w:BalanceSingleByteDoubleByteWidth /><br />
<w:DoNotLeaveBackslashAlone /><br />
<w:ULTrailSpace /><br />
<w:DoNotExpandShiftReturn /><br />
<w:AdjustLineHeightInTable /><br />
<w:BreakWrappedTables /><br />
<w:SnapToGridInCell /><br />
<w:WrapTextWithPunct /><br />
<w:UseAsianBreakRules /><br />
<w:DontGrowAutofit /><br />
<w:UseFELayout /><br />
</w:Compatibility><br />
<w:BrowserLevel>MicrosoftInternetExplorer4</w:BrowserLevel><br />
</w:WordDocument><br />
</xml><![endif]--><!--[if gte mso 9]><xml><br />
<w:LatentStyles DefLockedState="false" LatentStyleCount="156"><br />
</w:LatentStyles><br />
</xml><![endif]--><!--[if gte mso 10]><br />
<style><br />
/* Style Definitions */<br />
table.MsoNormalTable<br />
{mso-style-name:普通表格;<br />
mso-tstyle-rowband-size:0;<br />
mso-tstyle-colband-size:0;<br />
mso-style-noshow:yes;<br />
mso-style-parent:"";<br />
mso-padding-alt:0cm 5.4pt 0cm 5.4pt;<br />
mso-para-margin:0cm;<br />
mso-para-margin-bottom:.0001pt;<br />
mso-pagination:widow-orphan;<br />
font-size:10.0pt;<br />
font-family:"Times New Roman";<br />
mso-fareast-font-family:"Times New Roman";<br />
mso-ansi-language:#0400;<br />
mso-fareast-language:#0400;<br />
mso-bidi-language:#0400;}<br />
</style><br />
<![endif]--><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;&lt;br /&gt;
mso-hansi-font-family:&#34;Times New Roman&#34;">对于</span><span lang="EN-US">100%</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:&lt;br /&gt;
&#34;Times New Roman&#34;">的数据，</span><span lang="EN-US">1</span><span style="font-size:&lt;br /&gt;
12.0pt;font-family:宋体;mso-bidi-font-family:Cambria">≤<span lang="EN-US">n</span>≤<span lang="EN-US">2,000,000</span>，<span lang="EN-US">1</span>≤<span lang="EN-US">k</span>≤<span lang="EN-US">500,000</span>。</span></p><br/>
<p>2016.6.17时限放至60s</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢yts1999上传">鸣谢yts1999上传</a></p></div>

