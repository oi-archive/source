
# Description

<div class="content"><div>
<div>ls是一个特别堕落的小朋友，对于n个连续的小时，他将要么睡觉要么打隔膜，一个小时内他不能既睡觉也打隔膜</div>
<div>，因此一个小时内他只能选择睡觉或者打隔膜，当然他也必须选择睡觉或打隔膜，对于每一个小时，他选择睡觉或</div>
<div>打隔膜的愉悦值是不同的，对于第i个小时，睡觉的愉悦值为si，打隔膜的愉悦值为ei，同时又有一个奥妙重重的</div>
<div>规定：对于任意一段连续的k小时，ls必须至少有t1时间在睡觉，t2时间在打隔膜。那么ls想让他获得的愉悦值尽</div>
<div>量大，他该如何选择呢？</div>
<div></div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行四个整数,n,k(1&lt;=k&lt;=n&lt;=1000),t1,t2(0&lt;=t1,t2&lt;=k;t1+t2&lt;=k),含义如上所述。</div>
<div>接下来一行n个整数，第i个整数si(0&lt;=si&lt;=1e9)表示睡觉的愉悦值。</div>
<div>接下来一行n个整数，第i个整数ei(0&lt;=ei&lt;=1e9)表示打隔膜的愉悦值。</div>
<div></div></div>

# Output

<div class="content"><div>第一行输出最大的愉悦值。</div>
<div>接下来一行输出一个长度为n的字符串</div>
<div>第i个字符为E则代表第i小时在打隔膜，第i个字符为S则代表第i个小时在睡觉。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">10 4 1 2<br/>
1 2 3 4 5 6 7 8 9 10<br/>
10 9 8 7 6 5 4 3 2 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">69<br/>
EEESESEESS</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Nirobc提供SPJ">鸣谢Nirobc提供SPJ</a></p></div>

