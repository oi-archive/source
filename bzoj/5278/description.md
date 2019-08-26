
# Description

<div class="content"><div>留意着农场之外的长期职业生涯的可能性，奶牛Bessie开始在不同的在线编程网站上学习算法。她到目前为止最喜</div>
<div>欢的算法是“冒泡排序”。这是Bessie最初的对长度为N的数组A进行排序的奶牛码实现。</div>
<div></div>
<div>sorted = false</div>
<div>while (not sorted):</div>
<div>   sorted = true</div>
<div>   moo</div>
<div>   for i = 0 to N-2:</div>
<div>      if A[i+1] &lt; A[i]:</div>
<div>         swap A[i], A[i+1]</div>
<div>         sorted = false</div>
<div></div>
<div>显然，奶牛码中的“moo”指令的作用只是输出“moo”。</div>
<div>奇怪的是，Bessie看上去执着于在她的代码中的不同位置使用这个语句。</div>
<div></div>
<div>在用若干个数组测试了她的代码之后，Bessie得到一个有趣的观察现象：大的元素很快就会被拉到数组末尾，然而</div>
<div>小的元素需要很长时间“冒泡”到数组的开头（她怀疑这就是为什么这个算法得名的原因）。为了实验和缓解这一</div>
<div>问题，Bessie试着修改了她的代码，使代码在每次循环中向前再向后各扫描一次，从而无论是大的元素还是小的元</div>
<div>素在每一次循环中都有机会被拉较长的一段距离。她的代码现在是这样的：</div>
<div></div>
<div>sorted = false</div>
<div>while (not sorted):</div>
<div>   sorted = true</div>
<div>   moo</div>
<div>   for i = 0 to N-2:</div>
<div>      if A[i+1] &lt; A[i]:</div>
<div>         swap A[i], A[i+1]</div>
<div>   for i = N-2 downto 0:</div>
<div>      if A[i+1] &lt; A[i]:</div>
<div>         swap A[i], A[i+1]</div>
<div>   for i = 0 to N-2:</div>
<div>      if A[i+1] &lt; A[i]:</div>
<div>         sorted = false</div>
<div></div>
<div>给定一个输入数组，请预测Bessie修改后的代码会输出多少次“moo”。</div></div>

# Input

<div class="content"><div>输入的第一行包含N。接下来N行描述了A[0]…A[N-1]，每个数都是一个范围为0…10^9的整数。</div>
<div>输入数据不保证各不相同。</div>
<div>1≤N≤100,000</div></div>

# Output

<div class="content"><div>输出“moo”被输出的次数。</div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1<br/>
8<br/>
5<br/>
3<br/>
2</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

