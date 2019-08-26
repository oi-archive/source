
# Description

<div class="content"><div>利用空闲时间，BX希望外出工作，工作开始之前，公司就会给BX一个评估值X0，之后每天BX的评估值都是根据上一</div>
<div>天的评估值和当天公司的运行状况得出，即Xi=Xi-1+Di,但是每天的评估值有一个上限，也就是说完整的评估公式</div>
<div>因该是Xi=min{Xi-1+Di,Li}。现在BX已经知道了该公司对自己的初始评估值X0、公司每天的运行状况Di、每天的评</div>
<div>估上限Li，他的空闲时间是从第A天到第B天，他希望找到一段时间i，j (A≤i≤j≤B)，使得从第i天开始工作，到</div>
<div>第j天结束后的评估值最大。当然如果任意一段时间的工作得到评估值都&lt;初始评估值X0，BX可以选择不工作，从而</div>
<div>得到最大的评估值。</div></div>

# Input

<div class="content"><div>输入的第一行包含两个整数N、M，分别表示总共工作天数和询问数。</div>
<div>第二行N个数，表示Di。第三行N个数，表示Li。</div>
<div>以下M行，每行3个数A、B、X0，表示一次询问。</div></div>

# Output

<div class="content"><p>M行，每行输出一个整数，表示评估的最大值</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 3<br/>
-6 5 3 2 -3 4<br/>
8 10 8 1 9 9<br/>
1 3 9<br/>
2 6 3<br/>
3 4 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">10<br/>
8<br/>
3<br/>
【数据规模】<br/>
对于100%数据,满足N,M&lt;50001,|Di|&lt;10001,0≤Li&lt;1000000001</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

