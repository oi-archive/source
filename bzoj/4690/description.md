
# Description

<div class="content"><div>在实验室中，Nathan Wada作为助手的职责是测定两个样品的重量差异。当样品的差异很小时，使用天平能比使用</div>
<div>弹簧秤得到更精确的结果，所以他只使用天平来测得一些样品的重量差。他偶尔会被询问一些样品的重量差，而他</div>
<div>能否回答这些问题取决于在回答相应问题时他已经得到的测量结果。由于他所在处理的测量数据是巨大的，所以他</div>
<div>希望你能写个程序帮他处理数据和回答问题。</div>
<p></p></div>

# Input

<div class="content"><div>输入包含多组测试数据。每组数据第一行包含两个整数 N 和 M ，其中 N 表示样品的数量，</div>
<div>样品从 1 到 N 标号，满足 2≤N≤100000 。</div>
<div>接下来 M 行，每行包括一个测量结果或者询问，按时间顺序给出，满足 1≤M≤100000 。</div>
<div>一个测量结果被格式化为 ! a b w ，表示第 a 个样品比第 b 个样品轻 w 个单位重量</div>
<div>满足 a≠b,0≤w≤1000000 ，且任意的测试结果互不矛盾。</div>
<div>一个询问被格式化为 ? a b ，表示询问第 a 个样品比第 b 个样品轻多少个单位重量，满足 a≠b 。</div>
<div>输入以两个零作为结束。</div>
<p></p></div>

# Output

<div class="content"><div>对于每个询问输出一行，如果能回答问题，则输出问题的答案，你可以认为答案的绝对值不超过 1000000 </div>
<div>否则输出 UNKNOWN ，表示不能回答问题。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 2<br/>
! 1 2 1<br/>
? 1 2<br/>
2 2<br/>
! 1 2 1<br/>
? 2 1<br/>
4 7<br/>
! 1 2 100<br/>
? 2 3<br/>
! 2 3 100<br/>
? 2 3<br/>
? 1 3<br/>
! 4 3 150<br/>
? 4 1<br/>
0 0 </span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
-1<br/>
UNKNOWN<br/>
100<br/>
200<br/>
-50</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供试题">鸣谢Tangjz提供试题</a></p></div>

