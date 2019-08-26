
# Description

<div class="content"><div>Alice和Bob在玩一个游戏， 在平面上有n个域标号为a,b,c...，在游戏前Alice和Bob各自独立地选择一个域, 并把</div>
<div>刀片放在Bob的域然后游戏开始，每轮执行如下操作：</div>
<div>1.Alice在当前位置的可选的集合中选择一个集合S </div>
<div>2.Bob在S中选择一个不为当前位置的位置，把刀片移动到上面 </div>
<div>若在某时刻刀片被放到了Alice的域上，游戏结束</div>
<div>由于Alice是一个抖M，她希望尽快迫使Bob把刀片放在Alice的域，而Bob则希望尽量晚.</div>
<div></div>
<p></p>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 25.55555534362793px;"></div></div>

# Input

<div class="content"><div style="font-size: 11.8181819915771px;">第一行一个整数n(n&lt;=25)表示域的个数</div>
<div style="font-size: 11.8181819915771px;">接下来n行，每行有一个整数m(m&lt;2^n,Σ m&lt;=10^6)，后跟m不同的字符串，以字典序给出，描述位置i的可选的集合</div>
<div style="font-size: 11.8181819915771px;"></div>
<p></p>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 25.55555534362793px;"></div></div>

# Output

<div class="content"><p> <span style="font-size: 11.8181819915771px;">输出一个n*n的矩阵</span></p>
<div style="font-size: 11.8181819915771px;">第i行第j个数表示，Bob初始选择第i个域，Alice初始选择第j个域，游戏最少要进行多少轮，如果无法给Alice寄</div>
<div style="font-size: 11.8181819915771px;">刀片则输出-1</div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
2 ab b<br/>
1 b<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 1 <br/>
-1 0<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

