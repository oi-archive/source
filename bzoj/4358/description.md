
# Description

<div class="content"><div>给出一个长度为n的排列P(P1,P2,...Pn)，以及m个询问。每次询问某个区间[l,r]中，最长的值域</div>
<div>连续段长度。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数n,m。</div>
<div>接下来一行n个整数，描述P。</div>
<div>接下来m行，每行两个整数l,r，描述一组询问。</div>
<p></p></div>

# Output

<div class="content"><div>对于每组询问，输出一行一个整数，描述答案。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">8 3<br/>
3 1 7 2 5 8 6 4<br/>
1 4<br/>
5 8<br/>
1 7</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
3<br/>
4</span></div>

# Hint

<div class="content"><p></p><div>对于询问[1,4]，P2,P4,P1组成最长的值域连续段[1,3]；</div><br/>
<div>对于询问[5,8]，P8,P5,P7组成最长的值域连续段[4,6]；</div><br/>
<div>对于询问[1,7]，P5,P7,P3,P6组成最长的值域连续段[5,8]。</div><br/>
<div>1&lt;=n,m&lt;=50000</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By sumix173">By sumix173</a></p></div>

