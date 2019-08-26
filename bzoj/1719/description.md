
# Description

<div class="content"><p><span style="font-size: medium">Farmer John is quite the nature artist: he often constructs large works of art on his farm. Today, FJ wants to construct a giant &#34;field web&#34;. FJ&#39;s field is large convex polygon with fences along the boundary and fence posts at each of the N corners (1 &lt;= N &lt;= 150). To construct his field web, FJ wants to run as many ropes as possible in straight lines between pairs of non-adjacent fence posts such that no two ropes cross. There is one complication: FJ&#39;s field is not completely usable. Some evil aliens have created a total of G (0 &lt;= G &lt;= 100) grain circles in the field, all of radius R (1 &lt;= R &lt;= 100,000). FJ is afraid to upset the aliens, and therefore doesn&#39;t want the ropes to pass through, or even touch the very edge of a grain circle. Note that although the centers of all the circles are contained within the field, a wide radius may make it extend outside of the field, and both fences and fence posts may be within a grain circle. Given the locations of the fence posts and the centers of the circles, determine the maximum number of ropes that FJ can use to create his field web. FJ&#39;s fence posts and the circle centers all have integer coordinates X and Y each of which is in the range 0..1,000,000. </span></p>
<div><span style="font-size: medium">    约翰真是一个自然派艺术大师，他常常在他的田地上创作一些巨大的艺术杰作．今天，他想在麦田上创作一幅由绳索构成的巨画．他的麦田是一个多边形，由N(1≤N≤150)个篱笆桩和之间的篱笆围成．为了创作他的巨画，他打算用尽量多的数量的绳索，笔直地连接两个不相邻的篱笆桩．但是为了画作的优美，任意两根绳索不得交叉．</span></div>
<div><span style="font-size: medium">    约翰有一个难处：一些邪恶的外星人在他的麦田上整出了G(O≤G≤100)个怪圈．这些怪圈都有一定的半径R(1≤R≤100000)．他不敢惹外星人，所以不想有任何绳索通过这些怪圈，即使碰到怪圈的边际也不行．这些怪圈的圆心都在麦田之内，但一些怪圈可能有部分在麦田之外．一些篱笆或者篱笆桩都有可能在某一个怪圈里．</span></div>
<div><span style="font-size: medium">    给出篱笆桩和怪圈的坐标，计算最多的绳索数．所有的坐标都是[0，10^61内的整数．</span></div></div>

# Input

<div class="content"><p>* Line 1: Three space-separated integers: N, G, and R * Lines 2..N+1: Each line contains two space-separated integers that are the X,Y position of a fence post on the boundary of FJ&#39;s field. * Lines N+2..N+G+1: Each line contains two space-separated integers that are the X,Y position of a circle&#39;s center inside FJ&#39;s field.</p>
<div><span style="font-size: medium">    第1行输入三个整数N，G，R.接下来N行每行输入两个整数表示篱笆桩的坐标．接下来G行每</span><span style="font-size: medium">行输入两个整数表示一个怪圈的圆心坐标．</span></div></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer that is the largest number of ropes FJ can use for his artistic creation. </span></p>
<div><span style="font-size: medium">    最多的线索数．</span></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3 1<br/>
6 10<br/>
10 7<br/>
9 1<br/>
2 0<br/>
0 3<br/>
2 2<br/>
5 6<br/>
8 3<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
A pentagonal field, in which all possible ropes are blocked by three<br/>
grain circles, except for the rope between fenceposts 2 and 4.<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">除了篱笆桩</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">2</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">和</span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">4</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">之间可以连接绳索，其余均会经过怪圈</span></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

