
# Description

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">众所周知，小</span><span lang="EN-US"><font face="Calibri">C</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">是个宅男，所以他的每天的食物要靠外卖来解决。小</span><span lang="EN-US"><font face="Calibri">C</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">现在有</span><span lang="EN-US"><font face="Calibri">M</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">元钱，他想知道这些钱他最多可以吃多少天。</span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US"><o:p><font face="Calibri" size="3"> </font></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">餐厅提供</span><span lang="EN-US"><font face="Calibri">N</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">种食物，每种食物有两个属性，单价</span><span class="apple-style-span"><b><span lang="EN-US" style="background: white; color: black; mso-bidi-font-family: Arial"><font face="Calibri">P<sub>i</sub></font></span></b></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">和保质期</span><span class="apple-style-span"><b><span lang="EN-US" style="background: white; color: black; font-family: Arial">S<sub>i</sub></span></b></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">，表示小</span><span lang="EN-US"><font face="Calibri">C</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">需要花</span><span class="apple-style-span"><b><span lang="EN-US" style="background: white; color: black; mso-bidi-font-family: Arial"><font face="Calibri">P<sub>i</sub></font></span></b></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">元才能买到足够一天吃的这种食物，并且需要在送到</span><span class="apple-style-span"><b><span lang="EN-US" style="background: white; color: black; font-family: Arial">S<sub>i</sub></span></b></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">天内吃完，否则食物会变质，就不能吃了，若</span><span class="apple-style-span"><b><span lang="EN-US" style="background: white; color: black; font-family: Arial">S<sub>i</sub></span></b></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">为</span><span lang="EN-US"><font face="Calibri">0</font></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">则意味着必须在送到当天吃完。另外，每次送餐需要额外</span><span class="apple-style-span"><b><span lang="EN-US" style="background: white; color: black; font-family: Arial">F</span></b></span><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">元送餐费。</span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"></p></div>

# Input

<div class="content"><div><font size="3">每个测试点包含多组测试数据；</font></div>
<div><font size="3">每个测试数据第一行三个整数M,F,N，如题目描述中所述；</font></div>
<div><font size="3">以下N行，每行两个整数，分别表示<b><span style="background: white; color: black">P<sub>i</sub></span>和<b><span style="background: white; color: black">S<sub>i</sub></span>。</b></b></font></div></div>

# Output

<div class="content"><div><font size="3">对于每个测试数据输出一行，表示最多可以吃的天数。</font></div></div>

# Sample Input

<div class="content"><span class="sampledata">32 5 2<br/>
5 0<br/>
10 2<br/>
10 10 1<br/>
10 10<br/>
10 1 1<br/>
1 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
0<br/>
8<br/>
</span></div>

# Hint

<div class="content"><p></p><p>【数据规模及约定】<br/><br/>
对于40%的数据，M,Si &lt;= 2*10^6；<br/><br/>
对于100%的数据，M, Si&lt;= 10^18，1 ≤ T ≤ 50，1 ≤ F ≤ M，1 ≤ N ≤ 200，1 ≤ Pi ≤ M。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

