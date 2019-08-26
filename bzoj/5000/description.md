
# Description

<div class="content"><div>几天之后小跳蚤即将结束自己在lydsy星球上的旅行。这时，lydsy人却发现他们的超空间传送装置的能量早在小跳</div>
<div>蚤通过石板来到lydsy星球时就已经消耗光了。这时，小跳蚤了解到自己很有可能回不到跳蚤国了，于是掉下了伤</div>
<div>心的眼泪……lydsy人见状决定无论如何也要送小跳蚤回地球，于是lydsy人的大祭司lavendir决定拜访lydsy星球</div>
<div>的OI树，用咒语从OI树中取得能量。咒语中有K种字母，我们用前K个大写英文字母来表示它。OI树可以被认为是一</div>
<div>个有着N个节点的带权有向图，所有节点的出度都是K，并且所有的出边都对应于一个咒语中的字母。仪式开始的时</div>
<div>候有一个标记物放在OI树的1号节点上。之后，从咒语的第一个字母开始，每经过一个字母，标记物就沿着该字母</div>
<div>对应的出边进入这条边的终点，并且得到相当于边权大小的能量值。当咒语处理完毕时，就可以得到这个过程中得</div>
<div>到的所有能量了。现在由于lydsy人超群的计算能力，他们已经知道某咒语大概会获得多少能量，只是还想知道会</div>
<div>获得的能量值对一个数M取模的结果。跳蚤国王通过小跳蚤留下的石板也了解到了小跳蚤现在的处境，所以他又找</div>
<div>到了你，希望你帮助他计算出这个问题的答案。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行是两个空格分隔的整数N和K。</div>
<div>
<div>之后N行每行2*K个整数A_1，B_1，A_2，B_2，...，A_K，B_K，表示N个节点的K条出边。</div>
<div>第i行表示第 i-1 个节点，这一行的A_S，B_S的值表示第S个大写字母对应的出边的终点为A_S，权值为B_S。</div>
<div>下面一行有一个字符串，表示咒语。</div>
<div>由于咒语的长度会非常长，将采用压缩方式给出，用[SA]表示连续S个字母A，S是一个正整数，A是单个字母。</div>
<div>比如说，字符串[5A]BC[3A][3C]表示的咒语为AAAAABCAAACCC。</div>
<div>之后一个正整数M，表示取模的底数。</div>
<div>字符串长度≤120000，在一个压缩节[SA]中，S≤10^9。K≤26，N≤10000，M≤10^9，所有边的权值小于10^9</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>一个整数，表示问题的答案。</div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 2<br/>
3 3 2 5<br/>
1 7 3 2<br/>
4 3 2 5<br/>
2 10 3 2<br/>
[3A]B[2A][2B]<br/>
10000</span></div>

# Sample Output

<div class="content"><span class="sampledata">38</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

