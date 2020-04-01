
# Description

<div class="content"><div>数字录音中，声音是用表示空气压力的数字序列描述的，序列中的每个值称为一个采样，每个采样之间间隔一定的</div>
<div>时间。 很多声音处理任务都需要将录到的声音分成由静音隔开的几段非静音段。为了避免分成过多或者过少的非</div>
<div>静音段，静音通常是这样定义的：m个采样的序列，该序列中采样的最大值和最小值之差不超过一个特定的阈值c。</div>
<div> 请你写一个程序，检测n个采样中的静音。</div></div>

# Input

<div class="content"><div>第一行有三个整数n，m，c，分别表示总的采样数、静音的长度和静音中允许的最大噪音程度。</div>
<div>第2行n个整数ai，表示声音的每个采样值，每两个整数之间用空格隔开。</div>
<div>1&lt;=n&lt;=1000000，1&lt;=m&lt;=10000，0&lt;=c&lt;=10000</div>
<div>0&lt;=ai&lt;=1,000,000</div></div>

# Output

<div class="content"><div>列出了所有静音的起始位置i</div>
<div>i满足max(a[i, . . . , i+m−1]) − min(a[i, . . . , i+m−1]) &lt;= c</div>
<div>每行表示一段静音的起始位置，按照出现的先后顺序输出。</div>
<div>如果没有静音则输出NONE。</div></div>

# Sample Input

<div class="content"><span class="sampledata">7 2 0<br/>
0 1 1 2 3 2 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
6</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

