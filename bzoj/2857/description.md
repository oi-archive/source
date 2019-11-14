
# Description

<div class="content"><p>在接下来的N天内，你收到了M个生产请求，每天可能受到多个请求。原则上来说，第i天收到的生产请求只能在第i天完成，但是实际中，你可以最多推迟D天完成请求，即在第i天到i + D天内完成都可以。进行生产需要使用一种机器，一台机器一天内可以完成一个生产请求。你的任务是计算出最少需要的机器台数，使得所有生产都能按要求完成</p></div>

# Input

<div class="content"><div>第一行三个非负整数N, M, D (0 ≤ D &lt; N)。</div>
<div>第二行M个正整数，第i个正整数表示在第几天收到了第i个请求。生产请求用正整数1..M编号。数据保证第N－D天之后不会收到生产请求。</div></div>

# Output

<div class="content"><div><span style="font-size: 12pt">第一行一个正整数，表示最少需要的机器个数。</span><span style="font-size: 12pt">下面</span><i><span style="font-size: 12pt">N</span></i><span style="font-size: 12pt">行给出每天完成的请求编号。每一行以</span><span style="font-size: 12pt">0</span><span style="font-size: 12pt">结束。如果存在多种方案，随意输出一种即可。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">8 2 12<br/>
1 2 4 2 1 3 5 6 2 3 6 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
5 1 0<br/>
9 4 0<br/>
2 10 0<br/>
6 12 0<br/>
3 7 0<br/>
11 8 0<br/>
0<br/>
0<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据满足：1 ≤ N ≤ 100,000，1 ≤ M ≤ 1,000,000。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Oimaster，Spj程序by liutian">鸣谢Oimaster，Spj程序by liutian</a></p></div>

