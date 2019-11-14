
# Description

<div class="content"><div>给定一个n，最开始序列长这样：</div>
<div></div>
<div>1111...10000...0__</div>
<div></div>
<div>n个1，n个0，两个空格</div>
<div></div>
<div>现在要求用最少的交换步数，使得最终的序列为</div>
<div></div>
<div>1010...1010__</div>
<div></div>
<div>就是前2n个都是10交替</div>
<div></div>
<div>所谓交换是指将相邻两个非空格的数一起挪到两个空格上。例如，下面是n=4时的一组合法解</div>
<div></div>
<div>11110000__</div>
<div></div>
<div>__11000011</div>
<div></div>
<div>101__00011</div>
<div></div>
<div>1010100__1</div>
<div></div>
<div>10101__001</div>
<div></div>
<div>10101010__</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>输入一个n</div>
<div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>第一行输出最少移动步数</div>
<div>
<div></div>
<div>接下来一行为移动方案，只要输出被移动的两个非空格格子左边那个的编号。换不换行无所谓。详见样例。</div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
1 4 8 6 9</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，2&lt;n&lt;=200000</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

