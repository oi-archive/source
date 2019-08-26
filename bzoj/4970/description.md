
# Description

<div class="content"><div></div>
<div>
<div>古数学及哲学家毕氏相信自然之本质为数学。现代生物学家研究生物数列(biosequences)。 生物数数为满足下列</div>
<div>条件之 M 个整数所成的数数：</div>
<div>1: 包含从 0, 1, …, 到 M - 1 的所有数字</div>
<div>2: 起始数字为 0， 最后一个数字为 M - 1</div>
<div>?2:数列中 E+1 不可以紧接在 E 之后</div>
<div>生物数数的连续子数列称为数段(segments)。如果一个数段的起点为该数段最小的数字， 终点为该数段最大的数</div>
<div>字且与起点不是同一个数字，且介于这两个数字之间所有的整数都出现在这个数段中， 则称这个数段为框段(frame</div>
<div>d interval)，如果框段中并不包含题名小的框段，则称之为障碍段(empodio)。以(0,3,5,4,6,2,1,7)这个生物数</div>
<div>列为例。 整个生物数?是一个框段， 可是它包含了另外一框段 (3,5,4,6) ，因此该生物数列是障碍段。而框段 (</div>
<div>3,5,4,6) 并不包含任何更短的框段所以它是一个障碍段，而且是此生物数列中唯一的障碍段。请写一个程序， 在</div>
<div>输入生物数列后， 输出所有的障碍段 (empodia 为 empodio的复数形)。</div>
</div>
<div>
<div></div>
<div></div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>
<div>第一行为单一整数M，代表生物数列的长度。 </div>
<div>生物数列中的数字依序出现在接下来的 M 行，每一行有一个整数</div>
<div>M≤1100000</div>
</div>
<div></div>
</div>
<div>
<div>
<div></div>
<div>
<div></div>
</div>
</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>
<div>第一行为一整数H，代表该生物数列中的障碍段的个数。</div>
<div>接下来的 H 行，将每一个障碍段，依照起点在原输入生物数列中出现的顺序，依序输出。</div>
<div>每行以2个整数A 与 B 代表一个障碍段并以一个空白分开</div>
<div>原输入生物数列第 A 个元素为该障碍段之起点，而第 B 个元素为该障碍段之终点</div>
<div></div>
</div>
<div></div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">8<br/>
0<br/>
3<br/>
5<br/>
4<br/>
6</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
2 5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

