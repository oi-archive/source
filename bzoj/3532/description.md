
# Description

<div class="content"><p><span style="font-size: medium"> 给定序列A，序列中的每一项Ai有删除代价Bi和附加属性Ci。请删除若<br/>
干项，使得4的最长上升子序列长度减少至少1，且付出的代价之和最小，并输出方案。<br/>
    如果有多种方案，请输出将删去项的附加属性排序之后，字典序最小的一种。<br/>
  </span></p></div>

# Input

<div class="content"><p><font size="4">  输入包含多组数据。<br/>
    输入的第一行包含整数T，表示数据组数。接下来4*T行描述每组数据。<br/>
    每组数据的第一行包含一个整数N，表示A的项数，接下来三行，每行N个整数A1．．An，B1．，Bn，C1．．Cn，满足1 &lt; =Ai，Bi，Ci &lt; =10^9，且Ci两两不同。<br/>
</font></p></div>

# Output

<div class="content"><p><font size="4">    对每组数据，输出两行。第一行包含两个整数S，M，依次表示删去项的代价和与数量；接下来一行M个整数，表示删去项在4中的的位置，按升序输出。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">    1<br/>
    6<br/>
    3 4 4 2 2 3<br/>
    2 1 1 1 1 2<br/>
    6 5 4 3 2 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">    4 3<br/>
    2 3 6<br/>
解释：删去(A2，43，A6)，(A1，A6)，(A2，43，44，A5)等都是合法的方案，但<br/>
{A2，43，A6)对应的C值的字典序最小。</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">1 &lt; =N &lt; =700     T &lt; =5 </span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round 1 Day 2">Round 1 Day 2</a></p></div>

