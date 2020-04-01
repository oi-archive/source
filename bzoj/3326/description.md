
# Description

<div class="content"><div align="left"><span style="font-size: 12pt">Fish </span><span style="font-size: 12pt">是一条生活在海里的鱼，有一天他很无聊，就开始数数玩。</span></div>
<div align="left"><span style="font-size: 12pt">他数数玩的具体规则是：</span></div>
<div align="left"><span style="font-size: 12pt">1. </span><span style="font-size: 12pt">确定数数的进制B</span></div>
<div align="left"><span style="font-size: 12pt">2. </span><span style="font-size: 12pt">确定一个数数的区间[L, R]</span></div>
<div align="left"><span style="font-size: 12pt">3. </span><span style="font-size: 12pt">对于[L, R] 间的每一个数，把该数视为一个字符串，列出该字符串的每一个（连续的）子串对应的B进制数的值。</span></div>
<div align="left"><span style="font-size: 12pt">4. </span><span style="font-size: 12pt">对所有列出的数求和。</span></div>
<div align="left"><span style="font-size: 12pt">现在Fish 数了一遍数，但是不确定自己的结果是否正确了。由于[L, R] 较大，他没有多余精力去验证是否正确，你能写一个程序来帮他验证吗？</span></div>
<div align="left"> </div>
<div style="margin: 0cm 0cm 12pt" align="left"> </div></div>

# Input

<div class="content"><div align="left"><span style="font-size: 12pt">输入包含三行。<br/>
第一行仅有一个数B，表示数数的进制。<br/>
第二行有N +1 个数，第一个数为N，表示数L 在B 进制下的长度为N，接下里的N个数从高位到低位的表示数L 的具体每一位。<br/>
第三行有M+ 1 个数，第一个数为M，表示数R 在B 进制下的长度为M，接下里的M个数从高位到低位的表示数R 的具体每一位。<br/>
<br/>
20% 数据，0 &lt;= R &lt;= L &lt;= 10^5。<br/>
50% 数据，2 &lt;= B &lt;= 1000，1 &lt;= N,M &lt;= 1000。<br/>
100% 数据，2 &lt;= B &lt;= 10^5，1 &lt;= N,M &lt;= 10^5。 </span></div></div>

# Output

<div class="content"><div align="left"><span style="font-size: 12pt">输出仅一行，即按照Fish 数数规则的结果，结果用10 进制表示，由于该数可能很大，输出该数模上20130427的模数。 </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
3 1 0 3<br/>
3 1 0 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">120<br/>
Hint<br/>
[103, 103] 之间仅有数103，该数的所有子串包括1, 10, 103, 0, 03, 3，其和为120。</span></div>

# Hint

<div class="content"><p></p><p>应上传者要求，此系列试题不公开,如有异议，本站将删除之。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

