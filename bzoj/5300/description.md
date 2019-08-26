
# Description

<div class="content"><div>九连环是一种源于中国的传统智力游戏。</div>
<div><img src="source/bzoj/5300/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwNC92MS5wbmc=.png" width="217" height="165" alt=""/></div>
<div>如图所示，九个的圆环套在一把“剑”上，并且互相牵连。游戏的目标是把九个圆环全部从“剑”上卸下。</div>
<div>圆环的装卸需要遵守两个规则</div>
<div>1．第一个（最右边）环任何时候都可以任意装上或卸下</div>
<div>2．如果第k个环没有被卸下，且第k个环右边的所有环都被卸下，则第k+l个环（第k个环左边相邻的环）</div>
<div>可以任意装上或卸下与魔方的千变万化不同，解九连环的最优策略是唯一的。</div>
<div>为简单起见，我们以“四连环”为例，演示这一过程。这里用1表示环在“剑”上，0表示环已经卸下。</div>
<div>初始状态为1111，每步的操作如下</div>
<div>1. 1101（根据规则2卸下第2个环）</div>
<div>2. 1100（根据规则1卸下第1个环）</div>
<div>3. 0100（根据规则2卸下第4个环）</div>
<div>4. 0101（根据规则1装上第1个环）</div>
<div>5. 0111（根据规则2装上第2个环）</div>
<div>6. 0110（根据规则1卸下第1个环）</div>
<div>7. 0010（根据规则2卸下第3个环）</div>
<div>8. 0001（根据规则1装上第1个环）</div>
<div>9. 0001（根据规则2卸下第2个环）</div>
<div>10. 0000（根据规则1卸下第1个环）</div>
<div>由此可见，卸下“四连环”至少需要10步。</div>
<div>随着环数增加，需要的步数也会随之增多。例如卸下九连环．就至少需要341步。</div>
<div>请你计算，有n个环的情况下，按照规则，全部卸下至少需要多少步。</div></div>

# Input

<div class="content"><div>输入文件第一行，为一个整数m，表示测试点数目。</div>
<div>接下来m行，每行一个整数n。</div>
<div>1≤n≤10^5，1≤m≤10</div></div>

# Output

<div class="content"><div>输出文件共m行，对应每个测试点的计算结果。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
3<br/>
5<br/>
9</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
21<br/>
341</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Amphetamine整理题面">鸣谢Amphetamine整理题面</a></p></div>

