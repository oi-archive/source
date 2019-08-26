
# Description

<div class="content"><div>很久很久以前，中原地区分成了N个国家，编号为1到N，任意两个国家都可互达。每个国家有一个攻击值A[i]和防</div>
<div>御值B[i]。定义一个人从i国去j国的危险值为：假如A[i]&gt;B[j]，则危险值为( - )，否则危险值为0。现在，Nan从</div>
<div>国家1出发，经过每一个国家有且仅有一次，最后回到国家1，要求找出一种方案，使得其中危险值的最大值最小。</div></div>

# Input

<div class="content"><div>第一行正整数N，表示有N个国家； N&lt;=1000000</div>
<div>第二行正整数A[1],A[2],x,y,z，有等式A[i]=(x*A[i-1]+y*A[i-2]+z)mod 32767；</div>
<div>第三行正整数B[1],B[2],x,y,z，有等式B[i]=(x*B[i-1]+y*B[i-2]+z)mod 32767。</div></div>

# Output

<div class="content"><p>输出一个数,表示危险值的最大值最小是多少。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
2 4 1231 4432 123<br/>
123 45 3245 555 6676 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">9171832<br/>
【样例说明】<br/>
A数组为2,4,13911,5151,3031 <br/>
B数据为123,45,24364,26060,21765 <br/>
其中一种最优方案为1- 2- 4- 3- 5-1，危险值分别为0,0,0,0,9171832</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

