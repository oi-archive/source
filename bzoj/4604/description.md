
# Description

<div class="content"><div>神犇Aleph在陪蒟蒻Bob玩一个游戏。神犇Aleph随手在地面上画了一个巨大无比的二维平面，然后在其上做一些微</div>
<div>小的贡献或教蒟蒻Bob做人。由于神犇Aleph是队爷，所以有时他会施用&#34;队爷光环&#34;这一魔法，在二维平面上的某坐</div>
<div>标整点处添加一个权值为v的贡献；又由于神犇Aleph是神犇，所以有时他会施用&#34;嘲讽&#34;这一技能，询问蒟蒻Bob在</div>
<div>矩形区域(x1, y1), (x2, y2)(x1≤x2且y1≤y2，包括边界)中，神犇Aleph所做的第k大的贡献是多少。由于神犇Al</div>
<div>eph是Au爷，所以他不会在同一个坐标整点处做两次或两次以上的贡献。现在神犇Aleph希望蒟蒻Bob回答他的每次</div>
<div>询问。然而蒟蒻Bob傻傻不会做，于是来求助您，宇宙第一神犇，请您来回答神犇Aleph的每次询问。</div>
<p></p></div>

# Input

<div class="content"><div>输入的第一行为两个正整数N, Q，表示横纵坐标的范围和神犇Aleph的操作次数（包括贡献次数和询问次数）。</div>
<div>接下来Q行，每行代表神犇Aleph的一个操作，操作格式如下：</div>
<div>首先第一个数字type，表示操作种类。type=1表示贡献，type=2表示询问。</div>
<div>若type=1，接下来会有三个正整数x, y, v，表示在坐标整点(x, y)添加一个贡献v。(1≤x, y≤N, 1≤v≤10^9)</div>
<div>若type=2，接下来会有五个正整数x1, y1, x2, y2, k，表示询问矩形区域(x1, y1), (x2, y2)中第k大的贡献。</div>
<div>(1≤x1≤x2≤N，1≤y1≤y2≤N，1≤k≤Q)</div>
<div>初始时平面上不存在贡献。</div>
<div>本题共有7组测试数据。对于所有的数据，N≤500,000。</div>
<div>Q的范围见下表：</div>
<div>测试点1-2<span class="Apple-tab-span" style="white-space: pre;">	</span>Q=1,000</div>
<div>测试点3-7<span class="Apple-tab-span" style="white-space: pre;">	</span>Q=50,000<span class="Apple-tab-span" style="white-space: pre;">	</span></div>
<p></p></div>

# Output

<div class="content"><div>对于每个询问(type=2的操作)，回答第k大的贡献。若不存在第k大的贡献，请输出&#34;NAIVE!ORZzyz.&#34;（输出不含双引号）。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
10 7<br/>
1 1 1 1<br/>
1 2 2 3<br/>
1 4 1 2<br/>
1 3 4 4<br/>
2 1 1 4 1 3<br/>
2 2 2 3 5 4<br/>
2 2 1 4 4 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">NAIVE!ORZzyz.<br/>
NAIVE!ORZzyz.<br/>
3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Idea By Aleph, Description &amp; Data cases By jinlifu1999.
">Idea By Aleph, Description &amp; Data cases By jinlifu1999.<br/>
</a></p></div>

