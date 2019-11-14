
# Description

<div class="content"><p>罗马皇帝很喜欢玩杀人游戏。  他的军队里面有n个人，每个人都是一个独立的团。最近举行了一次平面几何测试，每个人都得到了一个分数。  皇帝很喜欢平面几何，他对那些得分很低的人嗤之以鼻。他决定玩这样一个游戏。  它可以发两种命令：  1. Merger(i, j)。把i所在的团和j所在的团合并成一个团。如果i, j有一个人是死人，那么就忽略该命令。  2. Kill(i)。把i所在的团里面得分最低的人杀死。如果i这个人已经死了，这条命令就忽略。  皇帝希望他每发布一条kill命令，下面的将军就把被杀的人的分数报上来。（如果这条命令被忽略，那么就报0分）</p></div>

# Input

<div class="content"><div>第一行一个整数n（1&lt;=n&lt;=1000000）。n表示士兵数，m表示总命令数。 </div>
<div>第二行n个整数，其中第i个数表示编号为i的士兵的分数。</div>
<div>第三行一个整数m(1&lt;=m&lt;=100000) 第3+i行描述第i条命令。</div>
<div>命令为如下两种形式： </div>
<div>1. M i j </div>
<div>2. K i</div></div>

# Output

<div class="content"><p>如果命令是Kill，对应的请输出被杀人的分数。（如果这个人不存在，就输出0）</p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
100 90 66 99 10<br/>
7<br/>
M 1 5<br/>
K 1<br/>
K 1<br/>
M 2 3<br/>
M 3 4<br/>
K 5<br/>
K 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">10<br/>
100<br/>
0<br/>
66<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>部分数据如下 <a href="/JudgeOnline/upload/201607/aa.rar">JudgeOnline/upload/201607/aa.rar</a></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

