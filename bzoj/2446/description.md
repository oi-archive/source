
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: 12pt">A</span><span style="font-size: 12pt">和</span><span style="font-size: 12pt">B</span><span style="font-size: 12pt">进行石头剪刀布的游戏。</span></div>
<div style="text-indent: 21pt"> <span style="font-size: 12pt">游戏按照每轮进行，每轮进行</span><span style="font-size: 12pt">n</span><span style="font-size: 12pt">局，如果</span><span style="font-size: 12pt">A</span><span style="font-size: 12pt">先比</span><span style="font-size: 12pt">B</span><span style="font-size: 12pt">多获胜</span><span style="font-size: 12pt">m1</span><span style="font-size: 12pt">轮，</span><span style="font-size: 12pt">A</span><span style="font-size: 12pt">赢得游戏；如果</span><span style="font-size: 12pt">B</span><span style="font-size: 12pt">先比</span><span style="font-size: 12pt">A</span><span style="font-size: 12pt">多获胜</span><span style="font-size: 12pt">m2</span><span style="font-size: 12pt">轮，</span><span style="font-size: 12pt">B</span><span style="font-size: 12pt">赢得游戏。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">对于每轮，进行</span><span style="font-size: 12pt">n</span><span style="font-size: 12pt">局游戏，已知每局</span><span style="font-size: 12pt">B</span><span style="font-size: 12pt">出石头、剪刀和布的概率，每局如果</span><span style="font-size: 12pt">A</span><span style="font-size: 12pt">赢</span><span style="font-size: 12pt">A</span><span style="font-size: 12pt">得一分，如果</span><span style="font-size: 12pt">B</span><span style="font-size: 12pt">赢</span><span style="font-size: 12pt">B</span><span style="font-size: 12pt">得一分，平局没人得分。最后得分多的人此轮获胜，得分相同此轮无人获胜。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">求</span><span style="font-size: 12pt">A</span><span style="font-size: 12pt">获胜的最大概率。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">多组数据。</span></div></div>

# Input

<div class="content"><div> </div>
<div style="text-indent: 21pt"><span style="font-size: 10.5pt">读入包含多组数据。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 10.5pt">对于每组数据：</span></div>
<div style="text-indent: 21pt"><span style="font-size: 10.5pt">第一行包含三个数和</span><span style="font-size: 10.5pt">n</span><span style="font-size: 10.5pt">，</span><span style="font-size: 10.5pt">m1</span><span style="font-size: 10.5pt">，</span><span style="font-size: 10.5pt">m2</span><span style="font-size: 10.5pt">，如题目描述。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 10.5pt">接下来</span><span style="font-size: 10.5pt">n</span><span style="font-size: 10.5pt">行，每行</span><span style="font-size: 10.5pt">3</span><span style="font-size: 10.5pt">个数，分别表示</span><span style="font-size: 10.5pt">B</span><span style="font-size: 10.5pt">每局出<b>石头、布与剪刀</b>的百分率，保证三个数的和是</span><span style="font-size: 10.5pt">100.</span></div>
<div style="text-indent: 21pt"><span style="font-size: 10.5pt">整个输入以0 0 0结束</span></div></div>

# Output

<div class="content"><div style="text-indent: 21pt"> </div>
<p>对于每组数据输出一行，表示获胜的百分率，保留3位小数。<br/>
</p></div>

# Sample Input

<div class="content"><span class="sampledata">2 1 1<br/>
50 50 0<br/>
0 0 100<br/>
1 2 1<br/>
20 20 60<br/>
5 3 1<br/>
32 47 21<br/>
25 37 38<br/>
34 40 26<br/>
49 20 31<br/>
25 60 15<br/>
5 3 1<br/>
41 13 46<br/>
13 27 60<br/>
50 24 26<br/>
14 32 54<br/>
25 56 19<br/>
10 3 1<br/>
21 33 46<br/>
31 25 44<br/>
24 32 44<br/>
39 39 22<br/>
21 39 40<br/>
30 25 45<br/>
49 21 30<br/>
30 24 46<br/>
20 33 47<br/>
43 28 29<br/>
10 3 1<br/>
30 20 50<br/>
44 23 33<br/>
31 28 41<br/>
28 48 24<br/>
35 26 39<br/>
29 34 37<br/>
47 31 22<br/>
32 43 25<br/>
25 29 46<br/>
30 42 28<br/>
362 91 3<br/>
34 35 31<br/>
33 33 34<br/>
33 33 34<br/>
33 34 33<br/>
33 32 35<br/>
33 35 32<br/>
34 33 33<br/>
31 35 34<br/>
32 35 33<br/>
35 34 31<br/>
33 34 33<br/>
34 31 35<br/>
33 34 33<br/>
33 35 32<br/>
32 34 34<br/>
34 34 32<br/>
32 35 33<br/>
32 34 34<br/>
32 35 33<br/>
34 32 34<br/>
35 32 33<br/>
34 35 31<br/>
35 34 31<br/>
34 31 35<br/>
35 34 31<br/>
33 34 33<br/>
32 35 33<br/>
33 33 34<br/>
32 33 35<br/>
34 32 34<br/>
35 34 31<br/>
35 33 32<br/>
34 33 33<br/>
34 34 32<br/>
34 32 34<br/>
33 32 35<br/>
32 33 35<br/>
35 34 31<br/>
32 35 33<br/>
35 34 31<br/>
35 33 32<br/>
35 31 34<br/>
33 34 33<br/>
32 33 35<br/>
35 32 33<br/>
32 34 34<br/>
32 35 33<br/>
32 34 34<br/>
33 35 32<br/>
34 34 32<br/>
33 34 33<br/>
35 34 31<br/>
32 34 34<br/>
34 32 34<br/>
35 33 32<br/>
33 34 33<br/>
34 35 31<br/>
33 33 34<br/>
35 32 33<br/>
35 34 31<br/>
33 33 34<br/>
31 35 34<br/>
33 33 34<br/>
34 35 31<br/>
33 34 33<br/>
32 35 33<br/>
32 34 34<br/>
33 33 34<br/>
31 35 34<br/>
34 31 35<br/>
34 34 32<br/>
35 32 33<br/>
33 32 35<br/>
34 32 34<br/>
35 34 31<br/>
35 31 34<br/>
34 33 33<br/>
34 32 34<br/>
31 35 34<br/>
35 32 33<br/>
34 33 33<br/>
32 35 33<br/>
33 35 32<br/>
33 35 32<br/>
33 34 33<br/>
32 33 35<br/>
32 33 35<br/>
31 34 35<br/>
33 33 34<br/>
35 31 34<br/>
31 35 34<br/>
34 31 35<br/>
35 31 34<br/>
32 34 34<br/>
34 35 31<br/>
35 33 32<br/>
34 31 35<br/>
34 31 35<br/>
34 31 35<br/>
34 33 33<br/>
33 33 34<br/>
34 31 35<br/>
33 34 33<br/>
35 33 32<br/>
32 35 33<br/>
32 33 35<br/>
31 34 35<br/>
33 35 32<br/>
34 32 34<br/>
34 34 32<br/>
33 32 35<br/>
35 34 31<br/>
34 35 31<br/>
32 33 35<br/>
32 35 33<br/>
34 31 35<br/>
35 32 33<br/>
34 31 35<br/>
34 35 31<br/>
31 34 35<br/>
35 33 32<br/>
31 35 34<br/>
34 35 31<br/>
34 31 35<br/>
35 33 32<br/>
34 33 33<br/>
34 31 35<br/>
34 31 35<br/>
34 34 32<br/>
33 34 33<br/>
34 32 34<br/>
34 35 31<br/>
34 34 32<br/>
32 35 33<br/>
35 32 33<br/>
35 32 33<br/>
35 31 34<br/>
35 32 33<br/>
33 33 34<br/>
31 35 34<br/>
32 33 35<br/>
31 34 35<br/>
34 33 33<br/>
34 32 34<br/>
32 33 35<br/>
33 34 33<br/>
34 33 33<br/>
35 32 33<br/>
32 33 35<br/>
32 34 34<br/>
32 35 33<br/>
33 35 32<br/>
35 33 32<br/>
34 31 35<br/>
32 33 35<br/>
33 35 32<br/>
31 35 34<br/>
34 31 35<br/>
33 34 33<br/>
34 35 31<br/>
33 32 35<br/>
34 32 34<br/>
33 35 32<br/>
34 35 31<br/>
31 35 34<br/>
33 33 34<br/>
32 34 34<br/>
34 33 33<br/>
35 33 32<br/>
34 34 32<br/>
33 33 34<br/>
32 34 34<br/>
33 32 35<br/>
34 31 35<br/>
34 32 34<br/>
33 32 35<br/>
32 34 34<br/>
35 32 33<br/>
34 31 35<br/>
34 32 34<br/>
33 32 35<br/>
34 32 34<br/>
35 31 34<br/>
34 33 33<br/>
31 35 34<br/>
33 35 32<br/>
32 34 34<br/>
31 34 35<br/>
33 34 33<br/>
34 34 32<br/>
34 32 34<br/>
35 31 34<br/>
32 33 35<br/>
34 31 35<br/>
34 34 32<br/>
32 34 34<br/>
32 34 34<br/>
32 33 35<br/>
31 34 35<br/>
32 34 34<br/>
33 35 32<br/>
33 33 34<br/>
35 33 32<br/>
31 35 34<br/>
35 32 33<br/>
31 34 35<br/>
32 34 34<br/>
33 32 35<br/>
35 32 33<br/>
35 31 34<br/>
34 32 34<br/>
32 34 34<br/>
31 34 35<br/>
34 35 31<br/>
34 34 32<br/>
35 31 34<br/>
31 35 34<br/>
33 34 33<br/>
34 34 32<br/>
33 33 34<br/>
35 33 32<br/>
34 33 33<br/>
34 33 33<br/>
34 33 33<br/>
33 35 32<br/>
35 34 31<br/>
33 33 34<br/>
34 35 31<br/>
31 35 34<br/>
32 35 33<br/>
32 33 35<br/>
35 34 31<br/>
33 33 34<br/>
35 32 33<br/>
32 33 35<br/>
34 31 35<br/>
35 34 31<br/>
34 32 34<br/>
31 34 35<br/>
35 34 31<br/>
35 31 34<br/>
32 33 35<br/>
33 33 34<br/>
32 33 35<br/>
34 31 35<br/>
31 35 34<br/>
35 32 33<br/>
34 35 31<br/>
33 32 35<br/>
34 32 34<br/>
33 32 35<br/>
34 33 33<br/>
33 33 34<br/>
31 35 34<br/>
35 34 31<br/>
35 32 33<br/>
34 31 35<br/>
32 35 33<br/>
34 34 32<br/>
35 33 32<br/>
33 35 32<br/>
34 31 35<br/>
33 34 33<br/>
34 33 33<br/>
34 35 31<br/>
34 32 34<br/>
32 35 33<br/>
32 33 35<br/>
35 32 33<br/>
34 32 34<br/>
33 33 34<br/>
33 33 34<br/>
35 31 34<br/>
34 35 31<br/>
34 35 31<br/>
35 31 34<br/>
34 32 34<br/>
31 34 35<br/>
33 33 34<br/>
32 34 34<br/>
34 32 34<br/>
32 35 33<br/>
33 32 35<br/>
33 32 35<br/>
33 33 34<br/>
35 33 32<br/>
31 34 35<br/>
35 31 34<br/>
33 34 33<br/>
31 34 35<br/>
34 35 31<br/>
31 34 35<br/>
32 35 33<br/>
33 35 32<br/>
34 35 31<br/>
32 35 33<br/>
34 32 34<br/>
32 33 35<br/>
32 34 34<br/>
35 33 32<br/>
32 35 33<br/>
33 32 35<br/>
35 34 31<br/>
34 35 31<br/>
33 33 34<br/>
33 32 35<br/>
32 33 35<br/>
33 34 33<br/>
35 32 33<br/>
31 35 34<br/>
31 34 35<br/>
32 35 33<br/>
33 34 33<br/>
31 35 34<br/>
33 34 33<br/>
34 33 33<br/>
33 33 34<br/>
32 34 34<br/>
32 35 33<br/>
33 35 32<br/>
34 31 35<br/>
34 35 31<br/>
31 34 35<br/>
35 33 32<br/>
35 34 31<br/>
31 34 35<br/>
34 31 35<br/>
32 35 33<br/>
34 31 35<br/>
33 35 32<br/>
34 35 31<br/>
34 33 33<br/>
34 34 32<br/>
34 33 33<br/>
32 33 35<br/>
32 34 34<br/>
35 33 32<br/>
35 32 33<br/>
34 34 32<br/>
32 35 33<br/>
34 33 33<br/>
33 35 32<br/>
33 35 32<br/>
33 35 32<br/>
35 31 34<br/>
34 33 33<br/>
33 33 34<br/>
34 31 35<br/>
34 35 31<br/>
34 31 35<br/>
32 34 34<br/>
35 33 32<br/>
35 32 33<br/>
35 34 31<br/>
34 32 34<br/>
32 34 34<br/>
35 32 33<br/>
33 34 33<br/>
32 33 35<br/>
35 31 34<br/>
34 35 31<br/>
33 35 32<br/>
0 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">100.000%<br/>
69.231%<br/>
64.981%<br/>
80.864%<br/>
72.400%<br/>
69.287%<br/>
94.322%<br/>
</span></div>

# Hint

<div class="content"><p></p><p>Data Limit<br/><br/>
对于40%的测试点，n&lt;=500 <br/><br/>
对于100%的测试点，n&lt;=1000,m1,m2&lt;=100。<br/><br/>
 <br/><br/>
每个测试点中，数据组数都不超过10<br/><br/>
 </p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2011福建集训">2011福建集训</a></p></div>

