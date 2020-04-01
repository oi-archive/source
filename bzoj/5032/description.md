
# Description

<div class="content"><div>JSOI爆发一种罕见的懒惰拖延症，为了拯救小伙伴们于水生火热之中，</div>
<div>JYY 收集了 JSOI王国中所有病毒的DNA序列，并希望对这些DNA序列进行分类, </div>
<div>以便深入分析来找出治疗拖延症的方法。</div>
<div>JSOI王国里一共有N种不同的病毒，每种病毒的DNA序列都由一个大写字母序列来表示。</div>
<div>JYY希望将这些病毒分成尽量少的类别,使得每个病毒都属于且仅属于某一个类别。</div>
<div>分入同一个类别的病毒需要满足如下两条性质中的至少一条：</div>
<div>1、 所有同类病毒DNA序列的“k前缀”（前k个大写字母）都相同；</div>
<div>2、 所有同类病毒DNA序列的“k后缀”（后k个大写字母）都相同。</div>
<div>JYY希望找出一种分类方案,使得所分成的类别满足要求并且类别总数最小。</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含两个正整数 N 和 k 。</div>
<div>接下来 N 行，第 i 行包含一个字符串 Si ，表示编号为 i 的病毒的 DNA 序列 。</div>
<div>数据保证 Si 的长度不小于 k 。</div>
<div>N≤5000 &amp; k≤550 &amp; k≤|Si|≤600</div>
<div></div></div>

# Output

<div class="content"><div>第一行包含一个整数 C ，表示最少的类别的数量。</div>
<div>接下来 C 行，每一行首先为一个正整数 w ，表示当前类别中的病毒数量，</div>
<div>接下来 w 个正整数，表示属于当前类别的病毒的编号。</div>
<div>如果有多个最佳方案，输出任意一组即可。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 1<br/>
A<br/>
AB<br/>
BB<br/>
BA</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
2 1 2<br/>
2 3 4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round3">Round3</a></p></div>

