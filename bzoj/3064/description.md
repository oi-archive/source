
# Description

<div class="content"><p><span style="font-size: medium"><font face="Times New Roman">Bob需要一个程序来监视CPU使用率。这是一个很繁琐的过程，为了让问题更加简单，Bob会慢慢列出今天会在用计算机时做什么事。 <br/>
Bob会干很多事，除了跑暴力程序看视频之外，还会做出去玩玩和用鼠标乱点之类的事，甚至会一脚踢掉电源……这些事有的会让做这件事的这段时间内CPU使用率增加或减少一个值；有的事还会直接让CPU使用率变为一个值。 <br/>
当然Bob会询问：在之前给出的事件影响下，CPU在某段时间内，使用率最高是多少。有时候Bob还会好奇地询问，在某段时间内CPU曾经的最高使用率是多少。 <br/>
为了使计算精确，使用率不用百分比而用一个整数表示。 <br/>
不保证Bob的事件列表出了莫名的问题，使得使用率为负……………… <br/>
</font></span></p></div>

# Input

<div class="content"><p><font face="Times New Roman" size="4">第一行一个正整数T，表示Bob需要监视CPU的总时间。 <br/>
然后第二行给出T个数表示在你的监视程序执行之前，Bob干的事让CPU在这段时间内每个时刻的使用率达已经达到了多少。 <br/>
第三行给出一个数E，表示Bob需要做的事和询问的总数。 <br/>
接下来E行每行表示给出一个询问或者列出一条事件： <br/>
Q X Y:询问从X到Y这段时间内CPU最高使用率 <br/>
A X Y:询问从X到Y这段时间内之前列出的事件使CPU达到过的最高使用率 <br/>
P X Y Z:列出一个事件这个事件使得从X到Y这段时间内CPU使用率增加Z <br/>
C X Y Z:列出一个事件这个事件使得从X到Y这段时间内CPU使用率变为Z <br/>
时间的单位为秒，使用率没有单位。 <br/>
X和Y均为正整数（X&lt;=Y），Z为一个整数。 <br/>
从X到Y这段时间包含第X秒和第Y秒。 <br/>
保证必要运算在有符号32位整数以内。 <br/>
</font></p></div>

# Output

<div class="content"><p><font face="Times New Roman" size="4">对于每个询问，输出一行一个整数回答。 <br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
-62 -83 -9 -70 79 -78 -31 40 -18 -5 <br/>
20<br/>
A 2 7<br/>
A 4 4<br/>
Q 4 4<br/>
P 2 2 -74<br/>
P 7 9 -71<br/>
P 7 10 -8<br/>
A 10 10<br/>
A 5 9<br/>
C 1 8 10<br/>
Q 6 6<br/>
Q 8 10<br/>
A 1 7<br/>
P 9 9 96<br/>
A 5 5<br/>
P 8 10 -53<br/>
P 6 6 5<br/>
A 10 10<br/>
A 4 4<br/>
Q 1 5<br/>
P 4 9 -69<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">79<br/>
-70<br/>
-70<br/>
-5<br/>
79<br/>
10<br/>
10<br/>
79<br/>
79<br/>
-5<br/>
10<br/>
10<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"><font face="Times New Roman"> 数据分布如下： <br/><br/>
第1、2个数据保证T和E均小于等于1000 <br/><br/>
第3、4个数据保证只有Q类询问 <br/><br/>
第5、6个数据保证只有C类事件 <br/><br/>
第7、8个数据保证只有P类事件 <br/><br/>
全部数据保证T和E均小于等于100000 </font><br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

