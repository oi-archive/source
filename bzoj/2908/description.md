
# Description

<div class="content"><div>首先知道A nand B=not(A and B) （运算操作限制了数位位数为K）比如2 nand 3，K=3，则2 nand 3=not (2 and 3)=not 2=5。</div>
<div>给出一棵树，树上每个点都有点权，定义树上从a到b的费用为0与路径上的点的权值顺次nand的结果，例如：从2号点到5号点顺次经过2-&gt;3-&gt;5，权值分别为5、7、2，K=3，那么最终结果为0 nand 5 nand 7 nand 2=7 nand 7 nand 2=0 nand 2=7，现在这棵树需要支持以下操作。</div>
<div>①    Replace a b:将点a（1≤a≤N）的权值改为b。</div>
<div>②    Query a b:输出点a到点b的费用。</div>
<div>请众神给出一个程序支持这些操作。</div></div>

# Input

<div class="content"><div>
<div>第一行N，M，K，树的节点数量、总操作个数和运算位数。</div>
<div>接下来一行N个数字，依次表示节点i的权值。</div>
<div>接下来N-1行，每行两个数字a,b（1≤a,b≤N）表示a,b间有一条树边。</div>
<div>接下来M行，每行一个操作，为以上2类操作之一。</div>
<div>N、M≤100000，K≤32</div>
</div></div>

# Output

<div class="content"><p>对于操作②每个输出一行，如题目所述。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3 3<br/>
2 7 3 <br/>
1 2<br/>
2 3<br/>
Query 2 3<br/>
Replace 1 3<br/>
Query 1 1  <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
7<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

