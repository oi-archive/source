
# Description

<div class="content"><div>有这么一则传闻，O(nlogn)的排序发明之前，滋滋国的排序都是采用的冒泡排序。即使是冒泡排序，对当时的国民</div>
<div>来说也太复杂太难以理解，于是滋滋国出现了这样一个职业——排序使，收取报酬并负责给序列排序。作为冒泡协</div>
<div>会首席排序使，Lyra收费颇高，为了照顾并不富裕的人，Lyra允许顾客只支付一部分酬劳并获得并不完美的冒泡排</div>
<div>序服务。众所周知，n个元素的冒泡排序需要n?1n-1轮才能完成，有一位顾客支付的费用，只能够完成前k轮的排序</div>
<div>。作为冒泡排序的首席排序使，天赋卓绝的Lyra暗地里早就掌握了O(nlogn)的排序方法，这也是她轻松当选首席排</div>
<div>序使的原因——排序速度无人能敌。而现在面对只能够完成前k轮冒泡排序的要求，Lyra犯了难，于是她来寻求你</div>
<div>的帮助。给定一个序列，执行如下程序：</div>
<div>for i from 1 to k</div>
<div>    for j from 1 to n-1</div>
<div>         if Aj&gt;Aj+1</div>
<div>            swap(Aj,Aj+1)</div>
<div></div>
<div>并输出之后的A序列。</div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数n,k表示序列的长度和轮数。</div>
<div>接下来n行每行一个整数表示Ai</div>
<div>1≤k&lt;n≤200000;1≤Ai≤10^9</div>
<div></div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出n行每行一个整数表示冒泡排序k轮后的Ai</div>
<div></div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 1<br/>
3<br/>
2<br/>
1</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1<br/>
3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By C_SUNSHINE">By C_SUNSHINE</a></p></div>

