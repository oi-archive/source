
# Description

<div class="content"><div>你被要求设计一个计算器完成以下三项任务：</div>
<div>1、给定y,z,p,计算Y^Z Mod P 的值；</div>
<div>2、给定y,z,p，计算满足xy≡ Z ( mod P )的最小非负整数；</div>
<div>3、给定y,z,p，计算满足Y^x ≡<span> Z ( mod P)</span>的最小非负整数。</div></div>

# Input

<div class="content"><p> 输入包含多组数据。</p>
<div>第一行包含两个正整数T,K分别表示数据组数和询问类型（对于一个测试点内的所有数据，询问类型相同）。</div>
<div>以下行每行包含三个正整数y,z,p，描述一个询问。</div></div>

# Output

<div class="content"><div>对于每个询问，输出一行答案。对于询问类型2和3，如果不存在满足条件的，则输出“Orz, I cannot find x!”，注意逗号与“I”之间有一个空格。</div></div>

# Sample Input

<div class="content"><span class="sampledata">【样例输入1】<br/>
3 1<br/>
2 1 3<br/>
2 2 3<br/>
2 3 3<br/>
【样例输入2】<br/>
3 2<br/>
2 1 3<br/>
2 2 3<br/>
2 3 3<br/>
【数据规模和约定】<br/>
对于100%的数据，1&lt;=y,z,p&lt;=10^9，P为质数，1&lt;=T&lt;=10。</span></div>

# Sample Output

<div class="content"><span class="sampledata">【样例输出1】<br/>
2<br/>
1<br/>
2<br/>
【样例输出2】<br/>
2<br/>
1<br/>
0<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=第一轮day1">第一轮day1</a></p></div>

