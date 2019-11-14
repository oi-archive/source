
# Description

<div class="content"><p>小明爱上了炒股。经过近段时间的观察和整理，他发现了如果一个股<br/>
票出现了某种形态的k线，那么这个股票不久之后一定会大涨。小明<br/>
想利用这种神奇的k线来做一个股票软件。他将一条k线用整数序列a<br/>
来表示，并规定当且仅当a[i+1]-a[i]=p[i]时，这条k线是一条神奇<br/>
的k线。但是事情总不是一帆风顺的，小明发现许多k线不是神奇的，<br/>
但之后也能大涨。不过他发现这些k线都和神奇的k线很接近。为了进<br/>
一步扩展神奇的k线的用途，小明定义了两条k线b和a的差异度： 将b<br/>
中某一个元素修改成任意值的代价为cost1，将b中某一个元素删除的<br/>
代价为cost2。将b修改成a的前缀的最小的代价和就是b和a的差异度<br/>
。这里的前缀的定义有点特别，假设b的长度为m，b是a的前缀当且仅<br/>
当b[i+1]-b[i]=a[i+1]-a[i](1&lt;=i</p></div>

# Input

<div class="content"><p>第一行三个正整数n，cost1，cost2。<br/>
n表示给出的k线a的长度，cost1和cost2的含义如题。<br/>
第二行n-1个整数，依次表示p[1]到p[n-1]，含义如题。 <br/>
第三行n个整数，依次表示给出的k线a中的n个元素。<br/>
n&lt;=1500<br/>
cost1，cost2&lt;=1000000<br/>
p中每个元素的绝对值均&lt;=1000<br/>
a中每个元素的绝对值均&lt;=1000000</p></div>

# Output

<div class="content"><p>一个数，a和神奇的k线的差异度。</p></div>

# Sample Input

<div class="content"><span class="sampledata">8 1 2<br/>
1 2 3 4 5 6 7<br/>
0 1 999 6 10 -999 15 21<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
【样例解释】<br/>
将999改为3，删去-999，得到序列0 1 3 6 10 15 21。不存在代价更<br/>
小的方案。<br/>
<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 李宇亮">By 李宇亮</a></p></div>

