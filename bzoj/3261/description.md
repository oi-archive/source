
# Description

<div class="content"><div>给定一个非负整数序列{a}，初始长度为N。</div>
<div>有M个操作，有以下两种操作类型：</div>
<div>1、Ax：添加操作，表示在序列末尾添加一个数x，序列的长度N+1。</div>
<div>2、Qlrx：询问操作，你需要找到一个位置p，满足l&lt;=p&lt;=r，使得：</div>
<div>a[p] xor a[p+1] xor ... xor a[N] xor x 最大，输出最大是多少。</div></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行包含两个整数 N  ，M，含义如问题描述所示。   <br/>
第二行包含 N个非负整数，表示初始的序列 A 。 <br/>
接下来 M行，每行描述一个操作，格式如题面所述。    </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">假设询问操作有 T个，则输出应该有 T行，每行一个整数表示询问的答案。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5  5<br/>
2  6 4 3 6<br/>
A 1 <br/>
Q 3 5 4 <br/>
A 4 <br/>
Q 5 7 0 <br/>
Q 3 6 6 <br/>
对于测试点 1-2，N,M&lt;=5   。<br/>
对于测试点 3-7，N,M&lt;=80000 。<br/>
对于测试点 8-10，N,M&lt;=300000    。<br/>
其中测试点 1, 3, 5, 7, 9保证没有修改操作。<br/>
0&lt;=a[i]&lt;=10^7。</span></div>

# Sample Output

<div class="content"><span class="sampledata">4 <br/>
5 <br/>
6 <br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

