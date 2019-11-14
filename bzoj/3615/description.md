
# Description

<div class="content"><div class="probtitle" id="ptit"><span style="font-size: medium">　小C正在出一道题...因为语文水平有限他想不出复杂的背景，所以以下就是题意了。<br/>
　　平面上有N个点，开始时每个点属于一个不同的集合。不妨设点P<sub>i</sub>属于集合S<sub>i</sub>。请维护数据结构支持以下三种操作：<br/>
　　&#34;Merge x y&#34;：将集合S<sub>y</sub>中的点到S<sub>x</sub>中；<br/>
　　&#34;Split i d v&#34;（d ∈ {0, 1}）：创建新集合S<sub>c + 1</sub>，S<sub>c + 2</sub>，之后将集合S<sub>i</sub>中的所有点中，第d维坐标不超过v的到集合S<sub>c + 1</sub>中，超过v的移动到集合S<sub>c + 2</sub>中，其中c为现有集合数（ 包括之前合并和分割中产生的空集 ）；<br/>
　　&#34;Query i&#34;：查询集合S<sub>i</sub>中点权值的最大值，最小值及和；<br/>
　　&#34;Add i d&#34;：将集合S<sub>i</sub>中所有点的权值增加d。<br/>
　　方便起见，对于d ∈ {0, 1}，输入的所有点的第d维坐标不重复。所有操作涉及的集合非空。</span></div>
<div id="pcont1" style="margin-top: 20px; display: block"></div></div>

# Input

<div class="content"><div id="pcont1" style="margin-top: 20px; display: block">
<div class="pdcont"><span style="font-size: medium">　　第一行一个整数N表示点数。<br/>
　　接下来N行，每行3个整数分别表示P<sub>i</sub>的坐标与权值。<br/>
　　接下来一个整数Q表示操作数。<br/>
　　接下来Q行，每行描述一个操作，格式如上所述。</span></div>
</div></div>

# Output

<div class="content"><div class="pdcont"><span style="font-size: medium">　　对于每个Q操作，输出三个整数，依次表示询问集合权值的最大值，最小值与和。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
4 7 3<br/>
18 16 2<br/>
14 13 1<br/>
10 2 10<br/>
3 8 5<br/>
11<br/>
Merge 2 3<br/>
Merge 4 5<br/>
Split 2 1 13<br/>
Query 4<br/>
Query 6<br/>
Add 6 2<br/>
Query 6<br/>
Merge 6 4<br/>
Split 6 0 10<br/>
Query 9<br/>
Split 8 0 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">10 5 15<br/>
1 1 1<br/>
3 3 3<br/>
3 3 3</span></div>

# Hint

<div class="content"><p></p><p>N&lt;=50000</p><br/>
<p>Q&lt;=100000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2014年国家集训队十五人互测 鸣谢Dragonite上传">2014年国家集训队十五人互测 鸣谢Dragonite上传</a></p></div>

