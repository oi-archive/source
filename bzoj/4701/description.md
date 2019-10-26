
# Description

<div class="content"><div>
<div>【题目背景】</div>
<div>“看着我的眼睛。”一一优祖列罕</div>
<div>【题意描述】</div>
<div>VOID抽取的基因呈环形，每个单元用A到Z的大写字母表示，换句话说一个基因就是一个环状字符串。设环状基因长</div>
<div>度为Li，从其中Li个断点分别断开，可以形成Li种链状基因（不一定两两不同）。以ABCAB为例，链状基因分别为A</div>
<div>BCAB，BCABA，CABAB，ABABC，BABCA，依次编号1--5现要抽取其中一种链状基因，不同种类基因参数不尽相同，每</div>
<div>个环状基因有两个参数Pi,ti首先执行打乱操作，每个位置x设定权重</div>
<div><img src="/source/bzoj/4701/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwOS8xMSgxKS5wbmc=.png" width="611" height="65" alt=""/></div>
<div>对于任意x，y，当F(x)&lt;f（y）且编号X的链状基因字典序小于编号y的链状基因字典序时，这两个链状基因会交换</div>
<div>编号。输入数据保证存在一种方案使得该操作不会执行超过f次便会停止。（易知执行顺序不影响最终结果）最终</div>
<div>，选取编号Pi的链状基因作为该环状基因的采样，记为Gi。现在有N个环状基因。a环状基因是b环状基因的亲和体</div>
<div>，当且仅当a环状基因的采样为b环状基因采样的前缀。求每个环状基因的亲和体数量。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个数n，表示环状基因的数量。</div>
<div>接下来n行，每行描述一个环状基因，由一个字符串，Pi，ti组成，之间用空格分隔。</div>
<div>1&lt;=Pi&lt;=Li,1&lt;=Ti&lt;=10000</div>
<p></p></div>

# Output

<div class="content"><div>输出n行，每行一个数，表示该环状基因的亲和体数量。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
CDEAB 3 2<br/>
ABC 2 4<br/>
D 1 6<br/>
EDEE 2 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
0<br/>
0<br/>
1</span></div>

# Hint

<div class="content"><p></p><p><img src="/source/bzoj/4701/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwOS8yMi5wbmc=.png" width="662" height="242" alt=""/></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

