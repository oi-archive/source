
# Description

<div class="content"><div>Teacher Mai has a multiplication table in base p.</div>
<div></div>
<div>For example, the following is a multiplication table in base 4:</div>
<div></div>
<div></div>
<div>* 0 1 2 3</div>
<div>0 00 00 00 00</div>
<div>1 00 01 02 03</div>
<div>2 00 02 10 12</div>
<div>3 00 03 12 21</div>
<div></div>
<div></div>
<div>But a naughty kid maps numbers 0..p-1 into another permutation and shuffle the multiplication table.</div>
<div></div>
<div>For example Teacher Mai only can see:</div>
<div></div>
<div></div>
<div>1*1=11 1*3=11 1*2=11 1*0=11</div>
<div>3*1=11 3*3=13 3*2=12 3*0=10</div>
<div>2*1=11 2*3=12 2*2=31 2*0=32</div>
<div>0*1=11 0*3=10 0*2=32 0*0=23</div>
<div></div>
<div></div>
<div>Teacher Mai wants you to recover the multiplication table. Output the permutation number 0..p-1 mapped into.</div>
<div></div>
<div>It&#39;s guaranteed the solution is unique.</div>
<p></p></div>

# Input

<div class="content"><div>There are multiple test cases, terminated by a line &#34;0&#34;.</div>
<div></div>
<div>For each test case, the first line contains one integer p(2&lt;=p&lt;=500).</div>
<div></div>
<div>In following p lines, each line contains 2*p integers.The (2*j+1)-th number x and (2*j+2)-th number y in the i-th line indicates equation i*j=xy in the shuffled multiplication table.</div>
<div></div>
<div>Warning: Large IO!</div>
<p></p></div>

# Output

<div class="content"><div>For each case, output one line.</div>
<div>
<div></div>
<div>First output &#34;Case #k:&#34;, where k is the case number counting from 1. The following are p integers, indicating the permutation number 0..p-1 mapped into.</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
2 3 1 1 3 2 1 0<br/>
1 1 1 1 1 1 1 1<br/>
3 2 1 1 3 1 1 2<br/>
1 0 1 1 1 2 1 3<br/>
0</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1: 1 3 2 0<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 镇海中学 鸣谢David Lee重新制作数据">By 镇海中学 鸣谢David Lee重新制作数据</a></p></div>

