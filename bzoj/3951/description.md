
# Description

<div class="content"><div>队(dou)友(bi)翻译了一道题，题面是这样的：</div>
<div>·给定一个长度为n的整数序列a[i]，其中|a[i]|&lt;=1。</div>
<div>·操作：选择一个1&lt;=i&lt;n，令a[i+1]增加a[i]，这个过程中允许|a[i]|&gt;1。</div>
<div>·目标：用最少的操作使得a不降，输出操作数。如果不可行，输出-1。</div>
<div>龙泉寺法师：这么简单？你是看错题了吧？</div>
<div>队(dou)友(bi)：啊……说不定是吧……</div>
<div>龙泉寺法师：这题一定是这样的~(balabala)</div>
<div>·给定一个长度为n的整数序列a[i]，其中|a[i]|&lt;=1</div>
<div>·有m个要求</div>
<div>·第一种要求是将某一个a[i]修改成x(|x|&lt;=1)</div>
<div>·第二种要求是询问[l,r]这一段用最少的操作数使它变得不降。如果不可行，输出-1。</div>
<div>于是，龙泉寺法师迅速把龙泉寺敌法从电脑前踹开，自己开始编写这题的AC算法……</div>
<div>队(dou)友(bi)：这题我不会啊。。</div>
<div>现在请你帮助队(dou)友(bi)解决这道题。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个数n,m，空格分隔，表示序列长度和操作数。</div>
<div>
<div>第二行n个数，表示序列a，满足|a[i]|&lt;=1</div>
<div>接下来m行，每行3个数</div>
<div>如果是第一种要求，四个数0 wi xi，空格分隔，表示把a[wi]修改成xi。</div>
<div>如果是第二种要求，三个数1 li ri，空格分隔，表示询问[li,ri]这一段至少要多少次操作才能不降。如果不可行，输出-1。</div>
</div>
<p></p></div>

# Output

<div class="content"><div>
<div>对于每个第二种要求，输出一行，包含一个数，表示询问的答案。</div>
<div>为了避免可能的空输出问题，最后输出一行，表示额外的一个询问1 1 n的答案。</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 6<br/>
1 1 0 -1 0 1<br/>
1 1 4<br/>
0 1 -1<br/>
0 2 -1<br/>
1 1 4<br/>
1 3 5<br/>
0 2 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
1<br/>
-1<br/>
3<br/>
样例说明<br/>
1、询问1 1 0 -1，操作3次变成1 1 1 1，输出3<br/>
2、修改a[1]为-1，序列为-1 1 0 -1 0 1<br/>
3、修改a[2]为-1，序列为-1 -1 0 -1 0 1<br/>
4、询问 -1 -1 0 -1，操作1次变成-1 -1 -1 -1，输出1<br/>
5、询问0 -1 0，前两个位置不可能非递减，无解，输出-1<br/>
6、修改a[2]为1，序列为-1 1 0 -1 0 1<br/>
最后输出整体的答案：操作3次变为-1 -1 -1 -1 0 1，输出3</span></div>

# Hint

<div class="content"><p></p><div>n,m&lt;=1000000</div><br/>
<div>建议使用读入优化</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2014年国家集训队十五人互测">2014年国家集训队十五人互测</a></p></div>

