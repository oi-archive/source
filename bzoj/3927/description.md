
# Description

<div class="content"><div>给出一个1到N的全排列，要求选出一个尽可能长的子序列，满足</div>
<div>1：不存在两个数0&lt;=i&lt;j&lt;N满足线段Min(A(i),A(i+1)),Max(A(i),A(i+1))</div>
<div>和线段Min(A(j),A(j+1),Max(A(j),A(j+1))有交但不互相包含。</div>
<div>2：A(0)一直为0.</div>
<div>例如1 5 3 4和1 5 3 2是两个合法方案并且在后面加上任意一个数都将导致不合法。3 5 1不合法是因为[0,3]和[1,5]相交但不互相包含。</div>
<div>N&lt;=200000</div>
<p></p></div>

# Input

<div class="content"><p>如题</p>
<p></p></div>

# Output

<div class="content"><p>如题</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">input 1<br/>
4<br/>
1 3 2 4<br/>
<br/>
input 2<br/>
4<br/>
1 4 2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">output 1<br/>
3<br/>
<br/>
output 2<br/>
4<br/>
</span></div>

# Hint

<div class="content"><p></p><div>第一个样例把3去掉以后就合法了</div><br/>
<div>第二个样例没有冲突 直接输出4</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

