
# Description

<div class="content"><p><span style="font-size: medium">Fascinated by his experience with balanced parentheses so far, Farmer John is curious if you can help him solve one final problem. As it turns out, FJ&#39;s farm is in the shape of a giant tree of N pastures (1 &lt;= N &lt;= 40,000), each of which he has labeled with either ( or ). For example: &#39;(&#39;--&#39;(&#39;--&#39;)&#39;--&#39;(&#39;--&#39;)&#39; | | &#39;)&#39; &#39;)&#39;--&#39;(&#39;--&#39;(&#39; | | &#39;)&#39; &#39;(&#39;--&#39;)&#39;--&#39;)&#39;--&#39;)&#39;--&#39;(&#39; Recall that since his farm is a tree, this means that certain pairs of pastures are connected by corridors so that there is one unique path between any given pair of pastures. FJ believes that some of these paths represent balanced strings of parentheses. In particular, he would like to know, among all such balanced strings represented by paths through the tree, what is the maximum nesting depth one can find. The nesting depth of a balanced string of parentheses is the maximum, over all prefixes of the string, of the excess number of (&#39;s within the prefix. For example, the string ()()() has nesting depth 1, but the string ((()))() has nesting depth 3, as we can see clearly if we count excess (&#39;s for every prefix of the string: ((()))() 12321010 For the example farm above, the deepest string is ((())) with a depth of 3, and can be obtained by taking the path from A to B below: &#39;(&#39;--&#39;(&#39;--&#39;)&#39;--&#39;(&#39;--&#39;)&#39; | | &#39;)&#39; &#39;)&#39;--&#39;(&#39;--&#39;(&#39; &lt; A | | &#39;)&#39; &#39;(&#39;--&#39;)&#39;--&#39;)&#39;--&#39;)&#39;--&#39;(&#39; ^C ^B Note that this is different than the longest balanced string; for instance (())(()), starting at A and ending at C, has length 8. Your task is to output the nesting depth of the deepest balanced path in the tree. </span></p>
<div>
<div>给出一棵树，每个结点上有一个括号。问在所有括号平衡的路径中，最大嵌套深度为多少。</div>
<div>（最大嵌套深度的大概意思：()()()的最大嵌套深度为1，((()))的最大嵌套深度为3）</div>
</div>
<div></div></div>

# Input

<div class="content"><div>* Line 1: A single integer N, the number of nodes in the tree.</div>
<div>* Lines 2..N: Line i+1: A single integer p_(i+1) (1 &lt;= p_(i+1) &lt;= i), </div>
<div>denoting an edge between nodes i+1 and p_{i+1} in the tree.</div>
<div>* Lines N+1..2N: Line N+i: Either ( or ), the label of node i.</div></div>

# Output

<div class="content"><p>* Line 1: A single integer, giving the maximum nesting depth of a balanced path.</p></div>

# Sample Input

<div class="content"><span class="sampledata">15<br/>
1<br/>
2<br/>
1<br/>
4<br/>
4<br/>
6<br/>
7<br/>
5<br/>
9<br/>
9<br/>
11<br/>
12<br/>
13<br/>
14<br/>
(<br/>
)<br/>
)<br/>
(<br/>
)<br/>
)<br/>
(<br/>
)<br/>
(<br/>
(<br/>
(<br/>
)<br/>
)<br/>
)<br/>
(<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> 3 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

