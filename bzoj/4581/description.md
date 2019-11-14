
# Description

<div class="content"><div>
<div>Farmer John&#39;s N cows (5≤N≤50,000) are all located at distinct positions in his two-dimensional fie</div>
<div>ld. FJ wants to enclose all of the cows with a rectangular fence whose sides are parallel to the x a</div>
<div>nd y axes, and he wants this fence to be as small as possible so that it contains every cow (cows on</div>
<div> the boundary are allowed).FJ is unfortunately on a tight budget due to low milk production last qua</div>
<div>rter. He would therefore like to build an even smaller fenced enclosure if possible, and he is willi</div>
<div>ng to sell up to three cows from his herd to make this possible.Please help FJ compute the smallest </div>
<div>possible area he can enclose with his fence after removing up to three cows from his herd (and there</div>
<div>after building the tightest enclosing fence for the remaining cows).For this problem, please treat c</div>
<div>ows as points and the fence as a collection of four line segments (i.e., don&#39;t think of the cows as </div>
<div>&#34;unit squares&#34;). Note that the answer can be zero, for example if all remaining cows end up standing</div>
<div> in a common vertical or horizontal line.</div>
<div>给定平面上N个点。现你可以删去至多3个点，接着你需要用一个矩形包含所有的点，点可以在矩形的边上，矩形的</div>
<div>边须与坐标轴平行。最小化矩形的面积并输出这个值。</div>
<div>5 ≤ N ≤ 50000, 1 ≤ X_i, Y_i ≤ 40000</div>
</div>
<div>
<div style="font-family: Arial; font-size: 14px; line-height: 15.8666658401489px;"></div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains N.</div>
<div>The next N lines each contain two integers specifying the locati</div>
<div>on of a cow. Cow locations are positive integers in the range 1…40,000.</div>
<p></p>
<p></p></div>

# Output

<div class="content"><p> Write a single integer specifying the minimum area FJ can enclose with his fence after removing up t</p>
<div>o three carefully-chosen cows from his herd.</div></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
1 1<br/>
7 8<br/>
10 9<br/>
8 12<br/>
4 100<br/>
50 7</span></div>

# Sample Output

<div class="content"><span class="sampledata">12</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver鸣谢frank_c1提供翻译">Silver鸣谢frank_c1提供翻译</a></p></div>

