
# Description

<div class="content"><div>  1：在人物集合 S 中加入一个新的程序员，其代号为 X,保证 X 在当前集合中不存在。 </div>
<div>  2：在当前的人物集合中询问程序员的mod Y 最小的值。 （为什么统计这个？因为拯救</div>
<div>过世界的人太多了，只能取模） </div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行为用空格隔开的一个个正整数 N。 </div>
<div>接下来有 N 行，若该行第一个字符为“A” ，则表示操作 1；若为“B”，表示操作 2； </div>
<div>其中 对于 100%的数据：N≤100000， 1≤X,Y≤300000，保证第二行为操作 1。 </div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于操作 2，每行输出一个合法答案。 </div>
<div></div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5            <br/>
A 3             <br/>
A 5 <br/>
B 6 <br/>
A 9 <br/>
B 4 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
1<br/>
</span></div>

# Hint

<div class="content"><p></p><div>【样例说明】 </div><br/>
<div>  在第三行的操作前，集合里有 3、5 两个代号，此时 mod 6 最小的值是 3 mod 6 = 3； </div><br/>
<div>  在第五行的操作前，集合里有 3、5、9，此时 mod 4 最小的值是 5 mod 4 = 1； </div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

