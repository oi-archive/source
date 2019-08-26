
# Description

<div class="content"><div>小豆参加了生物实验室。在实验室里，他主要研究蛋臼质。他现在研究的蛋臼质是由k个氨基酸按一定顺序构成的</div>
<div>。每一个氨基酸都可能有a种碱基序  列si_j 构成。现在小豆有一个碱基串s，小豆想知道在这个碱基上都多少中</div>
<div>不同的组合方式可能得到这个蛋白质。即求由k段字符串有序合并成的字符串s1,有多少种不同方式能够匹配字符串</div>
<div>s，其中k段字符串的选法不同，或者与s匹配上  的位置不同认为是不同的方式。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行一个数，表示这个蛋臼质由k个氨基酸。</div>
<div>第二行一个字符串s，表示小豆现在有的碱基串。</div>
<div>第三行开始接下来k行表示第i个氨基酸可能的碱基序列，对于第i个氨基酸，ai表示这个氨基酸可能的碱基序列种数，</div>
<div>接下来ai个字符串表示这ai 种可能的碱基序列，用空格隔开。</div>
<div>1 ≤ k ≤ 100, |s| ≤ 10000,ai ≤ 10</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出一个数目标是不同的方案数</div>
<div>(不同的方案数是指不同的子碱基串或者相同的碱基串不同的氨基酸排列方式)</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
ABC<br/>
2  A AB<br/>
2  C BC</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
提示<br/>
第一个选A第二个选C，得到AC能够与ABC产生0中匹配方式  <br/>
第一个选A第二个选BC，得到ABC能够与ABC产生1中匹配方式<br/>
第一个选AB第二个选C，得到ABC能够与ABC产生1中匹配方式<br/>
第一个选AB第二个选BC，得到ABBC能够与ABC产生0中匹配方式<br/>
所以一共2种</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

