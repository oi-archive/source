
# Description

<div class="content"><div>CTY神犇成为了著名品牌的一个经销商，由于经营有方，他创造了商品销售上的奇迹——就是进多少卖多少。为了</div>
<div>可以获得更多的利润，他决定从其他经销商那里进货。进货的要遵循以下规则：</div>
<div>1.有一个顶级经销商，他有无限的库存，他的出货价总是恒定的。</div>
<div>2.其他的经销商只能间接或直接从顶级经销商进货，而且一个经销商向其他经销商进货的量应等于向其他经销商出货</div>
<div>的量（即假设经销商都只会把商品卖给别的经销商）（顶级经销商和CTY神犇例外）。</div>
<div>3.经销商之间有单向的买卖关系，一个经销商v会向u要求进货，当且仅当存在u-&gt;v的单向买卖关系，同理，u会向v出</div>
<div>货也是要求当且仅当存在u-&gt;v的单向买卖关系。</div>
<div>4.代理一个产品最主要的就是获利，一个经销商将商品卖个另一个经销商时会以成本价上浮x%的价格卖给购买方（例</div>
<div>外的是顶级经销商有着固定的出货价，他的出货价不会随着进货价而变动，或者说因为他就是厂家，他的成本价是</div>
<div>一定的，而且他会不加价的买给其他经销商）。由于经销商之间亲密程度不同，所以每一条单向买卖关系的加价幅</div>
<div>度（即x%）不一定相同，而且对于一个单向买卖关系&lt;ui, vi&gt;而言，经销商ui最多愿意卖给vi的商品数为ci。</div>
<div>根据以上规则，CTY神犇想知道他最多可以拿到多少的商品，而由于售价是一定的，CTY神犇想要以尽量低的总成本</div>
<div>购进尽量多的商品。他发现经销商的关系有点小复杂，编程解决又太水了，所以他决定把这个简单的任务交给你。</div></div>

# Input

<div class="content"><div>第一行n,m,s表示共有n个经销商，m条单向买卖关系，顶级经销商的出货价格为s</div>
<div>（其中顶级经销商的编号为1，CTY神犇的编号为n）</div>
<div>接下来m行，每行4个正整数；u, v, c,x表示经销商u和v之间存在最多销售c和加价x%的单向买卖关系。</div>
<div>根据题意，输入数据保证顶级经销商卖给其他经销商的价格总是恒定的，即xi=0。</div>
<div>数据保证没有重边。</div>
<div>n&lt;=1800,m&lt;=n * (n - 1) / 2,0&lt;=x&lt;=100</div></div>

# Output

<div class="content"><div>第一行一个数sum，表示最多的进货量。</div>
<div>第二行一个数cost，表示获得最多进货量的最小成本。</div>
<div>进货成本精确到一位小数。</div>
<div>无法进货时输出:</div>
<div>0</div>
<div>0.0</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 3 5<br/>
1 2 4 0<br/>
2 3 3 100<br/>
1 3 3 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
45.0</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

