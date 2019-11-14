
# Description

<div class="content"><p><span style="font-size: medium">对于 N 神经组织的进化生物学研究将历史追溯到了人类社会形成之初、一个叫做 CCM 的神秘部落。<br/>
考古学证据表明,CCM 一度具有高度繁华的文明。然而 CCM 的历史却似乎在一夜之间神秘地消失了。考古学家近日在大西洋底发掘出了一处 CCM 文明遗迹,有希望能够揭开 CCM 古文明失落之谜。<br/>
CCM 遗迹的中央是一座巨大的石质建筑,被考古学家称之为金字塔。金字塔有这样四条性质:<br/>
1、CCM 金字塔由完全相同的 1*1*1 单位的立方体石块构成;<br/>
2、CCM 金字塔由若干层组成,每一层的石块从正上方看都在平面上形成一个联通块。高层的石块都有低层的石块在下方作为支撑,不会有石块悬空;<br/>
3、CCM 金字塔的每一层严格都满足左右对称和上下对称,并且所有层的对称轴是重合的,从左右/上下对称轴向两端长度/宽度非严格递减;<br/>
4、CCM 金字塔的每一层的最大长度和最大宽度都相等,并且都是偶数<br/>
(因为 CCM 人认为偶数代表了好运而奇数则会带来不幸)。<br/>
然而,不幸的是,遗迹中的金字塔由于年代过于久远,已经残缺不全,难以辨认全貌。为了尽可能地还原 CCM 金字塔的实际情况,考古学家们通过其<br/>
他证据估计出了 CCM 金字塔所使用的石块个数、金字塔的高度以及每一层的宽度,他们想请你帮忙计算符合上述性质的可能的金字塔个数。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">第一行两个整数:n,h,表示 CCM 金字塔的总石块数和 CCM 金字塔的高度。<br/>
从第二行开始的 h 行,每行一个整数 l。表示从最底层开始的每一层的最大长度(宽度),保证非严格递减。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">输出一行一个整数,表示可能的金字塔个数。由于方案数可能数量很大,<br/>
输出答案为模 1000000007 之后的结果。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">样例一：<br/>
36 3 <br/>
6 <br/>
4 <br/>
2 <br/>
样例二：<br/>
44 2 <br/>
6 <br/>
4 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例一：<br/>
1<br/>
样例二：<br/>
3<br/>
</span></div>

# Hint

<div class="content"><p></p><p>【Hint】<br/><br/>
样例一的金字塔从顶向下看的样子:(数字表示这一格的高度)<br/><br/>
    1 1<br/><br/>
    2 2<br/><br/>
1 2 3 3 2 1<br/><br/>
1 2 3 3 2 1<br/><br/>
    2 2<br/><br/>
    1 1 <br/><br/>
样例二的金字塔从顶向下看的样子:(数字表示这一格的高度)<br/><br/>
  1 1 1 1<br/><br/>
1 1 2 2 1 1<br/><br/>
1 2 2 2 2 1<br/><br/>
1 2 2 2 2 1<br/><br/>
1 1 2 2 1 1<br/><br/>
  1 1 1 1<br/><br/>
  <br/><br/>
  1 1 1 1<br/><br/>
  2 2 2 2<br/><br/>
1 2 2 2 2 1<br/><br/>
1 2 2 2 2 1<br/><br/>
  2 2 2 2<br/><br/>
  1 1 1 1</p><br/>
<p>    1 1<br/><br/>
1 2 2 2 2 1<br/><br/>
1 2 2 2 2 1<br/><br/>
1 2 2 2 2 1<br/><br/>
1 2 2 2 2 1<br/><br/>
    1 1</p><br/>
<p></p><br/>
<p><br/><br/>
对于 100%的数据,n≤1000,2≤l≤20,1≤h≤10。</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名提供">By 佚名提供</a></p></div>

