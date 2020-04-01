
# Description

<div class="content"><div>给定一个数列a：</div>
<div>当n&lt;=2时,a[n]=n</div>
<div>当n&gt;2，且n是奇数时，a[n]=2a[n-1]</div>
<div>当n&gt;2，且n是偶数时，a[n]=a[n-1]+r[n-1]</div>
<div>其中r[n-1]=mex(|a[i]-a[j]|)(1&lt;=i&lt;=j&lt;=n-1)，mex{S}表示最小的不在S集合里面的非负整数。</div>
<div>数列a的前若干项依次为：1,2,4,8,16,21,42,51,102,112,224,235,470,486,972,990,1980。</div>
<div>可以证明，对于任意正整数x，只存在唯一一对整数(p,q)满足x=a[p]-a[q]，定义为repr(x)。</div>
<div>比如repr(17)=(6,3)，repr(18)=(16,15)。</div>
<div>现有n个询问，每次给定一个正整数x，请求出repr(x)。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个正整数n(1&lt;=n&lt;=10^5)。</div>
<div>接下来n行，每行一个正整数x(1&lt;=x&lt;=10^9)，表示一个询问。</div>
<p></p></div>

# Output

<div class="content"><div>输出n行，每行两个正整数p,q，依次回答每个询问。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
17<br/>
18</span></div>

# Sample Output

<div class="content"><span class="sampledata">6 3<br/>
16 15</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris上传">鸣谢Claris上传</a></p></div>

