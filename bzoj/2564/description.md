
# Description

<div class="content"><div style="background: white" align="left"><span style="font-size: medium"><span style="color: #200000">　　对于一个平面上点的集合</span><span style="color: #200000">P={(x<sub>i</sub>,y<sub>i</sub> )}</span><span style="color: #200000">，定义集合</span><span style="color: #200000">P</span><span style="color: #200000">的面积</span><span style="color: #200000">F(P)</span><span style="color: #200000">为点集</span><span style="color: #200000">P</span><span style="color: #200000">的凸包的面积。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　对于两个点集</span><span style="color: #200000">A</span><span style="color: #200000">和</span><span style="color: #200000">B</span><span style="color: #200000">，定义集合的和为：</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　</span><span style="color: #200000">A+B={(x<sub>i</sub><sup>A</sup>+x<sub>j</sub><sup>B</sup>,y<sub>i</sub><sup>A</sup>+y<sub>j</sub><sup>B</sup> ):(x<sub>i</sub><sup>A</sup>,y<sub>i</sub><sup>A</sup> )</span><span style="color: #200000">∈</span><span style="color: #200000">A,(x<sub>j</sub><sup>B</sup>,y<sub>j</sub><sup>B</sup> )</span><span style="color: #200000">∈</span><span style="color: #200000">B}<br/>
</span><span style="color: #200000">　　现在给定一个</span><span style="color: #200000">N</span><span style="color: #200000">个点的集合</span><span style="color: #200000">A</span><span style="color: #200000">和一个</span><span style="color: #200000">M</span><span style="color: #200000">个点的集合</span><span style="color: #200000">B</span><span style="color: #200000">，求</span><span style="color: #200000">2F</span><span style="color: #200000">(A+B)</span><span style="color: #200000">。</span></span></div>
<div style="background: white" align="left"><span style="font-size: medium"><span style="color: #200000">　</span></span></div></div>

# Input

<div class="content"><p><font size="4"><font color="#200000">　第一行包含用空格隔开的两个整数，分别为<span style="color: #200000">N</span></font><span style="color: #200000">和</span><span style="color: #200000">M</span><span style="color: #200000">；</span></font><span style="color: #200000"><br/>
</span><font size="4"><span style="color: #200000">　　第二行包含</span><span style="color: #200000">N</span><span style="color: #200000">个不同的数对，表示</span><span style="color: #200000">A</span><span style="color: #200000">集合中的</span><span style="color: #200000">N</span><span style="color: #200000">个点的坐标；</span></font><span style="color: #200000"><br/>
</span><font size="4"><span style="color: #200000">　　第三行包含</span><span style="color: #200000">M</span><span style="color: #200000">个不同的数对，表示</span><span style="color: #200000">B</span><span style="color: #200000">集合中的</span><span style="color: #200000">M</span><span style="color: #200000">个点的坐标。</span></font></p>
<div style="background: white" align="left"><span style="font-size: medium"><span style="color: #200000">　</span></span></div></div>

# Output

<div class="content"><p><font color="#200000"><font size="4">　一共输出一行一个整数，<span style="color: #200000">2F</span></font></font><font size="4"><span style="color: #200000">(A+B)</span><span style="color: #200000">。</span></font></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 5<br/>
0 0 2 1 0 1 2 0<br/>
0 0 1 0 0 2 1 2 0 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">18<br/>
数据规模和约定<br/>
　　对于30%的数据满足N ≤ 200，M ≤ 200；<br/>
　　对于100%的数据满足N ≤ 10^5，M ≤ 10^5，|xi|, |yi| ≤ 10^8。<br/>
 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2012国家集训队Round 1 day2">2012国家集训队Round 1 day2</a></p></div>

