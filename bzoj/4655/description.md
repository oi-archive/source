
# Description

<div class="content"><div>有这么一个人叫做农民王 Q，他有一个家谱，现在他在想自己和上古农民王 U 到底有</div>
<div>多大的关系， 关系式中有这么些个亲戚：</div>
<div>“father, mother, son, daughter, husband, wife, brother, sister, grandfather, grandmother,</div>
<div>grandson, granddaughter, uncle, aunt, nephew, niece”</div>
<div>中文意思分别是：</div>
<div>“父亲，母亲，儿子，女儿，丈夫，妻子，兄弟，姐妹，爷爷，奶奶，孙子，孙女，叔</div>
<div>叔，阿姨，侄儿，侄女“</div>
<div>对于亲戚关系，满足以下几点：</div>
<div>1. Q 的兄弟等同于 Q 的父亲的或者母亲的儿子（ Q 自己除外）；</div>
<div>2. Q 的爷爷等同于 Q 的父亲的或者母亲的父亲；</div>
<div>3. Q 的孙子等同于 Q 的儿子的或者女儿的儿子；</div>
<div>4. Q 的叔叔等同于 Q 的父亲的或者母亲的兄弟；</div>
<div>5. Q 的侄儿等同于 Q 的兄弟的或者姐妹的儿子；</div>
<div>6. 上述规则对于姐妹，奶奶，孙女，阿姨和侄女类似。</div>
<div>血缘关系的定义如下：</div>
<div>1. Q 到 Q 的父亲， Q 的母亲， Q 的儿子或者 Q 的女儿的距离为 1；</div>
<div>2. Q 到 Q 的丈夫（妻子）的距离为 0；</div>
<div>3. Q 到 U 的距离等于在上述规则下推断出的 Q 到 U 的最短距离。</div>
<div>由于一条关系会出现很多种情况，所以农民王想知道他跟上古农民王的血缘关系距</div>
<div>离究竟有多少种？分别是多少？请你帮帮他好吗？</div>
<div>注明： 不会出现的关系包括收养，亲戚间结婚（家族树中无环），离婚，复婚，重婚，</div>
<div>同性恋等。</div>
<p></p></div>

# Input

<div class="content"><div>第 1 行包括一个字符串表示氏族谱图上的关系式，格式如下：</div>
<div>Q is U’s relation’s relation’s … relation 设关系式中出现的亲戚关系总个数为 l</div>
<div>100% 0 &lt;= l &lt;= 100， 不保证一定存在一种情况满足关系式</div></div>

# Output

<div class="content"><div>第 1 行一个整数 c，表示一共有多少种情况</div>
<div>第 2 行 c 个数，表示每种情况的距离，空格隔开，按升序输出</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">Q is U&#39;s father&#39;s brother&#39;s son&#39;s aunt<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
3 5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

