
# Description

<div class="content"><div>一个原力网络可以看成是一个可能存在重边但没有自环的无向图。每条边有一种属性和一个权值。属性可能是R、G</div>
<div>、B三种当中的一种，代表这条边上原力的类型。权值是一个正整数，代表这条边上的原力强度。原力技术的核心</div>
<div>在于将R、G、B三种不同的原力融合在一起产生单一的、便于利用的原力。为了评估一个能源网络，JYY需要找到所</div>
<div>有满足要求的三元环（首尾相接的三条边），其中R、G、B三种边各一条。一个三元环产生的能量是其中三条边的</div>
<div>权值之积。</div>
<div>现在对于给出的原力网络，JYY想知道这个网络的总能量是多少。网络的总能量是所有满足要求三元环的能量之和。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行包含两个正整数N、M。表示原力网络的总顶点个数和总边数。</div>
<div>接下来M行，每行包含三个正整数ui，vi，wi和一个字符ci。</div>
<div>表示编号ui和vi的顶点之间存在属性为ci权值为wi的一条边。</div>
<div>N≤50,000,M≤100,000,1≤?Wi≤10^6</div>
<p></p></div>

# Output

<div class="content"><p>输出一行一个整数，表示这个原力网络的总能量模10^9+7的值</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 6<br/>
1 2 2 R<br/>
2 4 3 G<br/>
4 3 5 R<br/>
3 1 7 G<br/>
1 4 11 B<br/>
2 3 13 B</span></div>

# Sample Output

<div class="content"><span class="sampledata">828</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

