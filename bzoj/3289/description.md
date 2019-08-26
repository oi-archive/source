
# Description

<div class="content"><div>
<div>Mato同学从各路神犇以各种方式（你们懂的）收集了许多资料，这些资料一共有n份，每份有一个大小和一个编号</div>
<div>。为了防止他人偷拷，这些资料都是加密过的，只能用Mato自己写的程序才能访问。Mato每天随机选一个区间[l,r</div>
<div>]，他今天就看编号在此区间内的这些资料。Mato有一个习惯，他总是从文件大小从小到大看资料。他先把要看的</div>
<div>文件按编号顺序依次拷贝出来，再用他写的排序程序给文件大小排序。排序程序可以在1单位时间内交换2个相邻的</div>
<div>文件（因为加密需要，不能随机访问）。Mato想要使文件交换次数最小，你能告诉他每天需要交换多少次吗？</div>
</div></div>

# Input

<div class="content"><div>第一行一个正整数n，表示Mato的资料份数。</div>
<div>第二行由空格隔开的n个正整数，第i个表示编号为i的资料的大小。</div>
<div>第三行一个正整数q，表示Mato会看几天资料。</div>
<div>之后q行每行两个正整数l、r，表示Mato这天看[l,r]区间的文件。</div>
<div>n,q &lt;= 50000</div></div>

# Output

<div class="content"><p>q行，每行一个正整数，表示Mato这天需要交换的次数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 4 2 3<br/>
2<br/>
1 2<br/>
2 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
2<br/>
//样例解释：第一天，Mato不需要交换<br/>
第二天，Mato可以把2号交换2次移到最后。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By taorunz">By taorunz</a></p></div>

