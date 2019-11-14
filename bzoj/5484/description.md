
# Description

<div class="content"><div>FJ有N（1≤N≤10^5）头奶牛（分别用1…N编号）排成一行。FJ喜欢他的奶牛以升序排列，不幸的是现在她们的顺</div>
<div>序被打乱了。在过去FJ曾经使用一些诸如“冒泡排序”的开创性的算法来使他的奶牛排好序，但今天他想偷个懒。</div>
<div>取而代之，他会每次对着一头奶牛叫道“按顺序排好”。当一头奶牛被叫到的时候，她会确保自己在队伍中的顺序</div>
<div>是正确的（从她的角度看来）。只要有一头紧接在她右边的奶牛的编号比她小，她们就交换位置。然后，只要有一</div>
<div>头紧接在她左边的奶牛的编号比她大，她们就交换位置。这样这头奶牛就完成了“按顺序排好”，在这头奶牛看来</div>
<div>左边的奶牛编号比她小，右边的奶牛编号比她大。FJ想要选出这些奶牛的一个子集，然后遍历这个子集，依次对着</div>
<div>每一头奶牛发号施令（按编号递增的顺序），重复这样直到所有N头奶牛排好顺序。例如，如果她选出了编号为{2,</div>
<div>4,5}的奶牛的子集，那么他会喊叫奶牛2，然后是奶牛4，然后是奶牛5。如果N头奶牛此时仍未排好顺序他会再次对</div>
<div>着这几头奶牛喊叫，如果有必要的话继续重复。由于FJ不确定哪些奶牛比较专心，他想要使得这个子集最小。此外</div>
<div>，他认为K是个幸运数字。请帮他求出满足重复喊叫可以使得所有奶牛排好顺序的最小子集之中字典序第K小的子集</div>
<div>。我们称{1,…,N}的一个子集S在字典序下小于子集T，当S的所有元素组成的序列（按升序排列）在字典序下小于T</div>
<div>的所有元素组成的序列（按升序排列）。例如，{1,3,6} 在字典序下小于{1,4,5}。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入的第一行包含一个整数N。</div>
<div>
<div>第二行包含一个整数K（1≤K≤10^18）。第三行包含N个空格分隔的整数，表示从左到右奶牛的编号。</div>
<div>保证存在至少K个符合要求的子集。</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>第一行输出最小子集的大小。</div>
<div>接下来输出字典序第K小的最小子集中奶牛的编号，每行一个数，升序排列。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 1<br/>
4 2 1 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1<br/>
4<br/>
//开始的时候序列为4213<br/>
。在FJ喊叫编号为1的奶牛之后，序列变为1423。<br/>
在FJ喊叫编号为4的奶牛之后，序列变为1234。在这个时候，序列已经完成了排序。 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum ">Platinum </a></p></div>

