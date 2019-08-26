
# Description

<div class="content"><div>21ZZ 年，冬。</div>
<div>小诚退休以后， 不知为何重新燃起了对物理学的兴趣。 他从研究所借了些实验仪器，整天研究各种微观粒子。这</div>
<div>一天， 小诚刚从研究所得到了一块奇异的陨石样本， 便迫不及待地开始观测。 在精密仪器的视野下，构成陨石</div>
<div>的每个原子都无比清晰。 小诚发现， 这些原子排成若干列， 每一列的结构具有高度相似性。于是，他决定对单</div>
<div>独一列原子进行测量和测试。被选中的这列共有 N 个顺序排列的原子。 最初， 第 i 个原子具有能量 Ei。 随着</div>
<div>时间推移和人为测试， 这列原子在观测上会产生两种变化：</div>
<div>merge x e 当前第 x 个原子和第 x+1 个原子合并，得到能量为 e 的新原子；</div>
<div>insert x e 在当前第 x 个原子和第 x+1 个原子之间插入一个能量为 e 的新原子。</div>
<div>对于一列原子，小诚关心的是相邻一段中能量最大和能量最小的两个原子的能量差值，</div>
<div>称为区间极差。 因此， 除了观测变化外，小诚还要经常统计这列原子的两类数据：</div>
<div>max x y 当前第 x 到第 y 个原子之间的任意子区间中区间极差的最大值；</div>
<div>min x y 当前第 x 到第 y 个原子之间的任意子区间中区间极差的最小值。</div>
<div>其中， 子区间指的是长度至少是 2 的子区间。</div>
<div>小诚坚信这项研究可以获得诺贝尔物理学奖。为了让小诚早日了结心愿，你能否帮助他实现上述的观测和测量呢？</div></div>

# Input

<div class="content"><div>第一行， 两个整数 N， M， 分别表示最初的原子数目和事件总数。</div>
<div>第二行， N 个整数 E1, E2, …, EN， 由空格隔开。依次表示每个原子的能量。</div>
<div>接下来 M 行， 每行为一个字符串和两个整数， 描述一次事件，格式见题目描述。</div>
<div>N&lt;=100,000,M&lt;=100,000</div>
<div>1 ≤ e, Ei ≤ 109。 设 N’ 为当前时刻原子数目。</div>
<div>对于 merge 类事件， 1 ≤ x ≤ N’-1；</div>
<div>对于 insert 类事件， 1 ≤ x ≤ N’；</div>
<div>对于 max 和 min 类事件， 1 ≤ x &lt; y ≤ N’。</div>
<div>任何时刻，保证 N’ ≥ 2。</div></div>

# Output

<div class="content"><div>输出若干行， 按顺序依次表示每次 max 和 min 类事件的测量结果。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
5 8 10 2<br/>
max 1 3<br/>
min 1 3<br/>
max 2 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5 2 8</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

