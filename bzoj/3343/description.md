
# Description

<div class="content"><div style="text-indent: 21.75pt"><span style="font-size: medium">教主最近学会了一种神奇的魔法，能够使人长高。于是他准备演示给XMYZ信息组每个英雄看。于是<i>N</i>个英雄们又一次聚集在了一起，这次他们排成了一列，被编号为1、2、……、<i>N</i>。</span></div>
<div style="text-indent: 21.75pt"><span style="font-size: medium">每个人的身高一开始都是不超过1000的正整数。教主的魔法每次可以把闭区间[<i>L</i>, <i>R</i>]（1≤<i>L</i>≤<i>R</i>≤<i>N</i>）内的英雄的身高全部加上一个整数<i>W</i>。（虽然<i>L</i>=<i>R</i>时并不符合区间的书写规范，但我们可以认为是单独增加第<i>L</i>（<i>R</i>）个英雄的身高）</span></div>
<div style="text-indent: 21.75pt"><span style="font-size: medium">CYZ、光哥和ZJQ等人不信教主的邪，于是他们有时候会问WD闭区间 [<i>L</i>, <i>R</i>] 内有多少英雄身高大于等于<i>C</i>，以验证教主的魔法是否真的有效。</span></div>
<div style="text-indent: 21.75pt"><span style="font-size: medium">WD巨懒，于是他把这个回答的任务交给了你。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">       第1行为两个整数<i>N</i>、<i>Q</i>。<i>Q</i>为问题数与教主的施法数总和。</span></div>
<div><span style="font-size: medium">       第2行有<i>N</i>个正整数，第<i>i</i>个数代表第<i>i</i>个英雄的身高。</span></div>
<div><span style="font-size: medium">       第3到第<i>Q</i>+2行每行有一个操作：</span></div>
<div style="margin: 0cm 0cm 0pt 57pt; text-indent: -36pt"><span style="font-size: medium">（1）<span style="font: 7pt &#39;Times New Roman&#39;">       </span>若第一个字母为“M”，则紧接着有三个数字<i>L</i>、<i>R</i>、<i>W</i>。表示对闭区间 [<i>L</i>, <i>R</i>] 内所有英雄的身高加上<i>W</i>。</span></div>
<div style="margin: 0cm 0cm 0pt 57pt; text-indent: -36pt"><span style="font-size: medium">（2）<span style="font: 7pt &#39;Times New Roman&#39;">       </span>若第一个字母为“A”，则紧接着有三个数字<i>L</i>、<i>R</i>、<i>C</i>。询问闭区间 [<i>L</i>, <i>R</i>] 内有多少英雄的身高大于等于<i>C</i>。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">       对每个“A”询问输出一行，仅含一个整数，表示闭区间 [<i>L</i>, <i>R</i>] 内身高大于等于<i>C</i>的英雄数。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
1 2 3 4 5<br/>
A 1 5 4<br/>
M 3 5 1<br/>
A 1 5 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
3<br/>
</span></div>

# Hint

<div class="content"><p></p><div><span style="font-size: medium">【输入输出样例说明】</span></div><br/>
<div><span style="font-size: medium">原先5个英雄身高为1、2、3、4、5，此时[1, 5]间有2个英雄的身高大于等于4。教主施法后变为1、2、4、5、6，此时[1, 5]间有3个英雄的身高大于等于4。</span></div><br/>
<div><span style="font-size: medium"> </span></div><br/>
<div><span style="font-size: medium">【数据范围】</span></div><br/>
<div><span style="font-size: medium">对30%的数据，<i>N</i>≤1000，<i>Q</i>≤1000。</span></div><br/>
<div><span style="font-size: medium">对100%的数据，<i>N</i>≤1000000，<i>Q</i>≤3000，1≤<i>W</i>≤1000，1≤<i>C</i>≤1,000,000,000。</span></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

