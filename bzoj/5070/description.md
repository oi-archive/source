
# Description

<div class="content"><p><a href="/JudgeOnline/upload/201710/55.doc">JudgeOnline/upload/201710/55.doc</a></p>
<p></p></div>

# Input

<div class="content"><div>第一行是两个整数A与B(1≤A,B≤10)，中间用空格分隔，表示该迷宫是A行B列的。</div>
<div>第2行至第A+1行，每行有B个1至100以内的整数，表示该迷宫每一格的危险程度。</div>
<div>以下一行是一个整数K。接着K行每行有四个整数X0,Y0,X1,Y1,</div>
<div>(1 ≤X0,X1≤A, 1≤Y0,Y1≤B) ，(X0,Y0),(X1,Y1)为相邻的两格，这两格相通。</div>
<div>接着一行是一个整数N（0≤N≤A*B/2），表示有N个出口与入口。</div>
<div>以下N行，每行有两个整数X0,Y0，表示每个入口的行列位置。</div>
<div>以下还有N行，每行有两个整数X1,Y1，表示每个出口的行列位置。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出仅一个数，若队员们不能全部到达指定目标位置，则输出-1；</div>
<div>否则输出所有队员所经过的所有单元格的危险程度之和。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
20 30 40 30<br/>
30 60 20 20<br/>
20 15 20 20<br/>
13<br/>
1 1 2 1<br/>
1 2 1 3<br/>
1 2 2 2<br/>
1 3 1 4<br/>
1 4 2 4<br/>
2 1 2 2<br/>
2 1 3 1<br/>
2 2 2 3<br/>
2 3 2 4<br/>
2 4 3 4<br/>
3 1 3 2<br/>
3 2 3 3<br/>
3 3 3 4<br/>
2<br/>
1 1<br/>
1 2<br/>
2 3<br/>
3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">235</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

