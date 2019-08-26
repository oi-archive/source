
# Description

<div class="content"><div>给你N颗宝石，每颗宝石都有重量和价值。要你从这些宝石中选取一些宝石，保证总重量不超过W，且总价值最大为</div>
<div>，并输出最大的总价值。</div>
<div>数据范围：N&lt;=100;W&lt;=2^30,并且保证每颗宝石的重量符合a*2^b（a&lt;=10;b&lt;=30）</div></div>

# Input

<div class="content"><div>输入文件中包含多组数据。</div>
<div>每组数据的格式如下：</div>
<div>第一行是两个正整数n和W，1≤n≤100,1≤W≤2^30，分别表示宝石的数目和最多能带走的宝石重量。</div>
<div>接下来的n行，每行有两个正整数weighti和valuei，1≤weighti≤2^30, 0≤valuei≤2^30，</div>
<div>分别表示第i颗宝石的重量和价值，且保证weighti能写成a*2^b(1≤a≤10,0≤b≤30)的形式。</div>
<div>同一行的两个正整数之间用空格隔开。</div>
<div>最后一组数据的后面有两个-1，表示文件的结束。这两个-1并不代表一组数据，</div>
<div>你不需对这组数据输出结果。并且输入文件中数据的组数不超过20。</div></div>

# Output

<div class="content"><div>对于输入的每组数据，输出一个整数C，表示小P最多能带走的宝石的总价值。</div>
<div>每个结果整数C单独占一行，且保证C不会超过2^30。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 10<br/>
8 9<br/>
5 8<br/>
4 6<br/>
2 5<br/>
4 13<br/>
8 9<br/>
5 8<br/>
4 6<br/>
2 5<br/>
16 75594681<br/>
393216 5533<br/>
2 77<br/>
32768 467<br/>
29360128 407840<br/>
112 68<br/>
24576 372<br/>
768 60<br/>
33554432 466099<br/>
16384 318<br/>
33554432 466090<br/>
2048 111<br/>
24576 350<br/>
9216 216<br/>
12582912 174768<br/>
16384 295<br/>
1024 76<br/>
-1 -1</span></div>

# Sample Output

<div class="content"><span class="sampledata">14<br/>
19<br/>
1050650</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

