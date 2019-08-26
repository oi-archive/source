
# Description

<div class="content"><div>给定一个 h*w 的矩阵,矩阵的行编号从上到下依次为 1..h，列编号从左到右依次1..w。在这个矩阵中你需要在每</div>
<div>个格子中填入 1..m 中的某个数。给这个矩阵填数的时候有一些限制，给定 n 个该矩阵的子矩阵,以及该子矩阵的</div>
<div>最大值 v,要求你所填的方案满足该子矩阵的最大值为 v。现在,你的任务是求出有多少种填数的方案满足 n 个限</div>
<div>制。两种方案是不一样的当且仅当两个方案至少存在一个格子上有不同的数。由于答案可能很大，你只需要输出答</div>
<div>案 对 1,000,000,007 的取模即可。</div>
<p></p></div>

# Input

<div class="content"><div>输入数据的第一行为一个数 T，表示数据组数。</div>
<div>对于每组数据，第一行为四个数 h,w,m,n。</div>
<div>接下来 n 行，每一行描述一个子矩阵的最大值 v。每行为五个整</div>
<div>数 x1,y1,x2,y2,v，表示一个左上角为(x1,y1),右下角为(x2,y2)的子矩阵的最大</div>
<div>值为 v ( 1≤x1≤x2≤h, 1≤y1≤y2≤w)</div>
<div>T≤5,1≤h,w,m≤10000,1≤v≤m,1≤n≤10</div>
<p></p></div>

# Output

<div class="content"><div>对于每组数据输出一行，表示填数方案 mod 1,000,000,007 后的值。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
3 3 2 2<br/>
1 1 2 2 2<br/>
2 2 3 3 1<br/>
4 4 4 4<br/>
1 1 2 3 3<br/>
2 3 4 4 2<br/>
2 1 4 3 2<br/>
1 2 3 4 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">28<br/>
76475</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

