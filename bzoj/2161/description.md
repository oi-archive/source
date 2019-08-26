
# Description

<div class="content"><div>小时候的雨荨非常听话，是父母眼中的好孩子。在学校是老师的左右手，同学的好榜样。后来她成为艾利斯顿第二</div>
<div>代考神，这和小时候培养的良好素质是分不开的。雨荨的妈妈也为有这么一个懂事的女儿感到高兴。一次期末考试</div>
<div>，雨荨不知道第多少次，再次考了全年级第一名。雨荨的妈妈看到女儿100分的成绩单时，脸上又泛起了幸福的笑</div>
<div>容，作为奖励，她给雨荨买了n个布娃娃。细心的雨荨发现，第i个布娃娃有一个耐心值P[i]以及一个魅力值C[i]，</div>
<div>并且还有能够忍受的耐心值的上限R[i]以及下限L[i]。当一个布娃娃j满足L[j]&lt;=P[i]并且P[i]&lt;=R[j]，那么布娃</div>
<div>娃j喜欢布娃娃i。雨荨还发现，一个布娃娃有可能喜欢它自己。每个布娃娃心中都有一个谜团，具体来说就是：第</div>
<div>i个布娃娃想知道喜欢它的布娃娃中，魅力值第i大的布娃娃的魅力值是多少，并且称这个布娃娃的谜团答案为这个</div>
<div>魅力值的大小，如果不存在，那么这个布娃娃的谜团答案为0。鉴于雨荨的上司栋栋不让题目的数据过大，下面给</div>
<div>出数据的生成方法：给出16个参数：</div>
<div>Padd, Pfirst, Pmod, Pprod, Cadd, Cfirst, Cmod, Cprod, Ladd, Lfirst, Lmod, Lprod, Radd, Rfirst, Rmod, Rprod。</div>
<div>----------------------------------------------------------------------------------------</div>
<div>P[1] = Pfirst % Pmod, P[i] = (P[i-1]   Pprod + Padd + i) % Pmod (i &gt; 1)。</div>
<div>----------------------------------------------------------------------------------------</div>
<div>对于C、L、R数组也有类似的得到方式, %代表取余运算。注意：L和R数组生成完之后，如果某个布娃娃的忍耐度上</div>
<div>限小于下限，那么交换它的上限和下限。当然，雨荨也不会让你告诉她每个布娃娃的谜团答案，因为那样会使输出</div>
<div>数据很大。所以雨荨希望你告诉她，所有布娃娃谜团答案的和除以19921228的余数是多少。</div></div>

# Input

<div class="content"><div>输入的第一行有一个整数n，代表布娃娃的个数。</div>
<div>输入的第二行有16个用空格隔开的整数</div>
<div>分别代表Padd,Pfirst,Pmod,Pprod,Cadd,Cfirst,Cmod,Cprod,Ladd,Lfirst,Lmod,Lprod,Radd,Rfirst,Rmod,Rprod。</div>
<div>16个参数均为1到100,000,000中的整数。</div>
<div></div></div>

# Output

<div class="content"><p>输出一个整数，代表所有布娃娃谜团答案的和除以19921228的余数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
2 3 4 3 1 4 5 2 3 6 9 1 1 2 3 4 </span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

