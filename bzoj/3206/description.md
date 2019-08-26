
# Description

<div class="content"><p><img height="630" width="688" alt="" src="source/bzoj/3206/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwNS8xKDE1KS5qcGc=.jpg"/></p>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行包含三个由空格隔开的整数N，M和K。</div>
<div>接下来的 M行描述最开始的M 条道路</div>
<div>这M行中的第i行包含由空格隔开的整数ai，bi和c i，表示有一条在a i和b i之间，费用为c i的双向道路。</div>
<div>接下来的K行描述新建的K条道路。</div>
<div>这 K行中的第i行包含由空格隔开的整数 xi和yi，表示有一条连接城镇xi和yi新道路</div>
<div>最后一行包含N个由空格隔开的整数，其中的第j个为pj，表示从城镇j 前往城镇 1的人数。</div>
<div>输入也满足以下约束条件。</div>
<div>1 ≤ N ≤ 100000；1 ≤ K ≤ 20；1 ≤ M ≤ 300000；对每个i和j，1 ≤ ci, pj ≤ 10^6；</div>
<div>注意：边权值可能相同</div>
</div></div>

# Output

<div class="content"><p><span style="font-size: 12pt; color: black; font-family: 宋体; mso-ascii-font-family: &#39;Arial Unicode MS&#39;; mso-hansi-font-family: &#39;Arial Unicode MS&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">你的程序必须输出恰好一个整数到标准输出，表示能获得的最大的收入。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5  5 1<br/>
3  5 2<br/>
1  2 3<br/>
2  3 5<br/>
2  4 4<br/>
4  3 6<br/>
1  3<br/>
10 20 30 40 50 </span></div>

# Sample Output

<div class="content"><span class="sampledata">400</span></div>

# Hint

<div class="content"><p></p><div><br/>
<div>在样例中， Mr. Greedy应该将新道路(1,3)的费用设置为 5分钱。</div><br/>
<div>在这个费用下，他可以选择道路(3,5)，(1,2)，(2,4)和(1,3)来最小化总费用，这个费用为14。</div><br/>
<div>从城镇 3出发的 30个人和从城镇 5出发的 50个人将经过新道路前往城镇 1，因此他可以获得为(30+50)_5=400 分钱的最好收入。</div><br/>
<div>如果我们这样做，将新道路(1,3)的费用设置为 10分钱。</div><br/>
<div>根据传统的限制，Mr. Greedy必须选择(3,5)，(1,2)，(2,4)和(2,3)，因为这是唯一费用最小的集合</div><br/>
<div>。因此，在嘉年华的过程中道路(1,3)将没有任何收入。</div><br/>
</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

