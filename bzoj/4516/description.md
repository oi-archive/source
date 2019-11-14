
# Description

<div class="content"><div>魔咒串由许多魔咒字符组成，魔咒字符可以用数字表示。例如可以将魔咒字符 1、2 拼凑起来形成一个魔咒串 [1,2]。</div>
<div>一个魔咒串 S 的非空字串被称为魔咒串 S 的生成魔咒。</div>
<div>例如 S=[1,2,1] 时，它的生成魔咒有 [1]、[2]、[1,2]、[2,1]、[1,2,1] 五种。S=[1,1,1] 时，它的生成魔咒有 [1]、</div>
<div>[1,1]、[1,1,1] 三种。最初 S 为空串。共进行 n 次操作，每次操作是在 S 的结尾加入一个魔咒字符。每次操作后都</div>
<div>需要求出，当前的魔咒串 S 共有多少种生成魔咒。</div>
<div></div></div>

# Input

<div class="content"><p></p>
<div>第一行一个整数 n。</div>
<div>第二行 n 个数，第 i 个数表示第 i 次操作加入的魔咒字符。</div>
<div>1≤n≤100000。,用来表示魔咒字符的数字 x 满足 1≤x≤10^9</div></div>

# Output

<div class="content"><p>输出 n 行，每行一个数。第 i 行的数表示第 i 次操作后 S 的生成魔咒数量</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
1 2 3 3 3 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
3<br/>
6<br/>
9<br/>
12<br/>
17<br/>
22</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Menci上传">鸣谢Menci上传</a></p></div>

