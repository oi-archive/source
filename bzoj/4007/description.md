
# Description

<div class="content"><div> 脸哥最近来到了一个神奇的王国，王国里的公民每个公民有两个下属或者没有下属，这种</div>
<div>关系刚好组成一个 n 层的完全二叉树。公民 i 的下属是 2 * i 和 2 * i +1。最下层的公民即叶子</div>
<div>节点的公民是平民，平民没有下属，最上层的是国王，中间是各级贵族。现在这个王国爆发了</div>
<div>战争，国王需要决定每一个平民是去种地以供应粮食还是参加战争，每一个贵族（包括国王自</div>
<div>己）是去管理后勤还是领兵打仗。一个平民会对他的所有直系上司有贡献度，若一个平民 i 参</div>
<div>加战争，他的某个直系上司 j 领兵打仗，那么这个平民对上司的作战贡献度为 wij。若一个平民</div>
<div>i 种地，他的某个直系上司 j 管理后勤，那么这个平民对上司的后勤贡献度为 fij，若 i 和 j 所</div>
<div>参加的事务不同，则没有贡献度。为了战争需要保障后勤，国王还要求不多于 m 个平民参加</div>
<div>战争。国王想要使整个王国所有贵族得到的贡献度最大，并把这件事交给了脸哥。但不幸的是，</div>
<div>脸哥还有很多 deadline 没有完成，他只能把这件事又转交给你。你能帮他安排吗？</div>
<div></div></div>

# Input

<div class="content"><p>第一行两个数 n;m。接下来 2^(n-1) 行，每行n-1 个数，第 i 行表示编号为 2^(n-1)-1+ i 的平民对其n-1直系上司的作战贡献度，其中第一个数表示对第一级直系上司，即编号为 (2^(n-1)-1+ i)/2 的贵族的作战贡献度 wij，依次往上。接下来 2^(n-1)行，每行n-1个数，第i行表示编号为 2^(n-1)-1+ i的平民对其n-1个直系上司的后勤贡献度，其中第一个数表示对第一级直系上司，即编号为 (2^(n-1)-1+ i)/2 的贵族的后勤贡献度 fij ，依次往上。</p></div>

# Output

<div class="content"><p> 一行一个数表示满足条件的最大贡献值</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
503 1082<br/>
1271 369<br/>
303 1135<br/>
749 1289<br/>
100 54<br/>
837 826<br/>
947 699<br/>
216 389</span></div>

# Sample Output

<div class="content"><span class="sampledata">6701</span></div>

# Hint

<div class="content"><p></p><p> 对于 100% 的数据，2 &lt;= n &lt;= 10,m &lt;= 2n 1,0 &lt;= wij ;fij &lt;= 2000</p><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

