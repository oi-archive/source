
# Description

<div class="content"><p><span style="font-size: medium"> 吉丽(JRY)的电脑里有一份时间表，表上有n个时间段，每个时间段吉丽都要和一个妹子约会。每个妹子都有一个属性a_i，表示吉丽和第i个妹子约会至少需要带的money。吉丽特意把a_i标在了第i行，以作备忘。<br/>
 你听说了吉丽的这张时间表，决定篡改一下数据，让吉丽花更多的money。当然，你对这n个妹子也有不同的好感度，所以你准备把第i行的数改为b_i。<br/>
 有一天你趁机接触到了吉丽的时间表，可是时间紧迫，你最多只能输入两个数据，其他只能通过复制得到了。<br/>
 定义“一次操作”为：修改第i行的数据，将a_i改为b_i，选中这个数向上或向下拖动到第j行，这样就使得第min(i,j)至第max(i,j)行的数都被覆盖成了b_i。<br/>
 注意：为了提高效率，你不会修改或覆盖同一行两次以上（包括两次）。<br/>
 你的时间只够你完成两次操作，你在这么短的时间内仍不忘让吉丽花的money越多越好。请你回答：在最多操作两次的情况下，吉丽最多要花多少money。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行n。第二行n个数，表示ai。第三行n个数，表示bi。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">一个数，表示吉丽最多要花的money。</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
1 3 4 7 6 1 2<br/>
1 1 3 1 5 1 1<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">31<br/>
<br/>
<br/>
【其他】<br/>
第一次操作：修改第3行，向上拖动到第1行。<br/>
第二次操作：修改第5行，向下拖动到第7行。<br/>
修改后的数列：3 3 3 7 5 5 5，money和为31，可以验证这是最大值。<br/>
<br/>
【数据范围】<br/>
1≤n≤500000,1≤ai,bi≤10^9<br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据已加强，By evil佂菡</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=XXY杯省选模拟题">XXY杯省选模拟题</a></p></div>

