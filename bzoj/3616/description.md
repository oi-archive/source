
# Description

<div class="content"><div class="pdcont"><span style="font-size: medium">小x所在的世界正在经历一场在k个阵营之间的战争。每个阵营有若干个炮塔，每个炮塔由攻击系统和防御系统组成。第i个炮塔可以攻击到离它欧几里德距离小于等于ri 或者曼哈顿距离小于等于ai的炮塔，被攻击到的炮塔防御系统就会崩溃，同一联盟的炮塔不会被攻击到。每次会随机选择一个炮塔攻击它能打到的所有炮塔，问进行m轮后期望剩下多少个阵营，使得这些阵营拥有的炮塔的防御系统全部完好。防御系统崩溃的炮塔还是会被打到的。值得注意的是，如果一个联盟没有任何炮塔，那么不管怎样它都是完好的。</span></div></div>

# Input

<div class="content"><div class="pdcont"><span style="font-size: medium">　　输入文件第一行有三个整数n、m、k，分别表示炮塔数目、攻击轮数以及联盟个数。 接下去n行每行有五个正整数xi、yi、ri、ai、pi，其中xi、yi表示炮塔坐标，p表示炮塔所属于阵营。</span></div></div>

# Output

<div class="content"><div class="pdcont"><span style="font-size: medium">　　输出一行一个实数表示答案，你的输出与标准输出的误差在1e-3以内会被认为是正确的。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2 2 3<br/>
0 0 2 2 1<br/>
1 1 2 2 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1.500<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">　　100%的数据， 0 &lt;= n、m、k &lt;= 35000，1 &lt;= pi &lt;= k，其余所有数字均非负且小于10000，保证在数据生成时不考虑一个点的具体位置，而将它的横纵坐标分开考虑。</span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2014年国家集训队十五人互测 鸣谢佚名上传">2014年国家集训队十五人互测 鸣谢佚名上传</a></p></div>

