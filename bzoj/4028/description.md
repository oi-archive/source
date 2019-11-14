
# Description

<div class="content"><p>设计一个数据结构. 给定一个正整数数列 a_0, a_1, ..., a_{n - 1}，你需要支持以下两种操作：</p>
<div>1. MODIFY id x: 将 a_{id} 修改为 x.</div>
<div>2. QUERY x: 求最小的整数 p (0 &lt;= p &lt; n)，使得 gcd(a_0, a_1, ..., a_p) * XOR(a_0, a_1, ..., a_p) = x. 其中 XOR(a_0, a_1, ..., a_p) 代表 a_0, a_1, ..., a_p 的异或和，gcd表示最大公约数。</div></div>

# Input

<div class="content"><p> 输入数据的第一行包含一个正整数 n.</p>
<div>接下来一行包含 n 个正整数 a_0, a_1, ..., a_{n - 1}.</div>
<div>之后一行包含一个正整数 q，表示询问的个数。</div>
<div>之后 q 行，每行包含一个询问。格式如题目中所述。</div></div>

# Output

<div class="content"><p>对于每个 QUERY 询问，在单独的一行中输出结果。如果不存在这样的 p，输出 no.</p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
1353600 5821200 10752000 1670400 3729600 6844320 12544000 117600 59400 640<br/>
10<br/>
MODIFY 7 20321280<br/>
QUERY 162343680<br/>
QUERY 1832232960000<br/>
MODIFY 0 92160<br/>
QUERY 1234567<br/>
QUERY 3989856000<br/>
QUERY 833018560<br/>
MODIFY 3 8600<br/>
MODIFY 5 5306112<br/>
QUERY 148900352</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
0<br/>
no<br/>
2<br/>
8<br/>
8</span></div>

# Hint

<div class="content"><p></p><p> 对于 100% 的数据，n &lt;= 100000，q &lt;= 10000，a_i &lt;= 10^9 (0 &lt;= i &lt; n)，QUERY x 中的 x &lt;= 10^18，MODIFY id x 中的 0 &lt;= id &lt; n，1 &lt;= x &lt;= 10^9.</p><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

