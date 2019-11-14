
# Description

<div class="content"><div>请写一个程序，要求维护一个数列，支持以下 6 种操作：</div>
<div>请注意，格式栏 中的下划线‘ _ ’表示实际输入文件中的空格</div>
<div><img src="/source/bzoj/1500/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMi8xMTEoMikucG5n.png" width="594" height="299" alt=""/></div></div>

# Input

<div class="content"><p>输入的第1 行包含两个数N 和M(M ≤20 000)，N 表示初始时数列中数的个数，M表示要进行的操作数目。<br/>
第2行包含N个数字，描述初始时的数列。<br/>
以下M行，每行一条命令，格式参见问题描述中的表格。<br/>
任何时刻数列中最多含有500 000个数，数列中任何一个数字均在[-1 000, 1 000]内。<br/>
插入的数字总数不超过4 000 000个，输入文件大小不超过20MBytes。</p></div>

# Output

<div class="content"><p>对于输入数据中的GET-SUM和MAX-SUM操作，向输出文件依次打印结果，每个答案（数字）占一行。</p></div>

# Sample Input

<div class="content"><span class="sampledata">9 8<br/>
2 -6 3 5 1 -5 -3 6 3<br/>
GET-SUM 5 4<br/>
MAX-SUM<br/>
INSERT 8 3 -5 7 2<br/>
DELETE 12 1<br/>
MAKE-SAME 3 3 2<br/>
REVERSE 3 6<br/>
GET-SUM 5 4<br/>
MAX-SUM</span></div>

# Sample Output

<div class="content"><span class="sampledata">-1<br/>
10<br/>
1<br/>
10</span></div>

# Hint

<div class="content"><p></p><p><img src="/source/bzoj/1500/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMi8yMigxKS5wbmc=.png" width="569" height="861" alt=""/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

