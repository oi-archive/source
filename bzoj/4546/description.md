
# Description

<div class="content"><div>给定一个初始时为空的整数序列（元素由1开始标号）以及一些询问：</div>
<div>类型1：在数组后面就加入数字x。</div>
<div>类型2：在区间L…R中找到y，最大化（x xor y）。</div>
<div>类型3：删除数组最后K个元素。</div>
<div>类型4：在区间L…R中，统计小于等于x的元素个数。</div>
<div>类型5：在区间L…R中，找到第k小的数。</div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入数据第一行为一个整数q，表示询问个数，接下来q行，每行一条询问 对应题目描述。</div>
<div>类型1的询问格式为“1 x”。</div>
<div>类型2的询问格式为“2 L R x”。</div>
<div>类型3的询问格式为“3 k”。</div>
<div>类型4的询问格式为“4 L R x”。</div>
<div>类型5的询问格式为“5 L R k”。</div>
<div></div>
<p></p>
<p></p></div>

# Output

<div class="content"><div>对于每个2、4、5询问输出一行对应答案</div>
<div></div>
<p></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
1 8<br/>
5 1 1 1<br/>
1 2<br/>
2 2 2 7<br/>
2 2 2 7<br/>
1 1<br/>
4 2 2 2<br/>
2 1 2 3<br/>
4 1 3 5<br/>
1 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
2<br/>
2<br/>
1<br/>
8<br/>
2</span></div>

# Hint

<div class="content"><p></p><div>令N表示每次询问前数组中元素的个数</div><br/>
<div>1&lt;=L&lt;=R&lt;=N</div><br/>
<div>1&lt;=x&lt;=500,000</div><br/>
<div>对于第三类询问 1&lt;=k&lt;=N       </div><br/>
<div>对于第五类询问 k&lt;=R-L+1 </div><br/>
<div>1&lt;=N&lt;=500,000</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

