
# Description

<div class="content"><div>在一个二维平面上有一个图形，如下图所示：</div>
<div>###############</div>
<div>#.............#</div>
<div>#.###########.#</div>
<div>#.#.........#.#</div>
<div>#.#.#######.#.#</div>
<div>#.#.#.....#.#.#</div>
<div>#.#.#.###.#.#.#</div>
<div>#.#.#.#.#.#.#.#</div>
<div>#.#.#.###.#.#.#</div>
<div>#.#.#.....#.#.#</div>
<div>#.#.#######.#.#</div>
<div>#.#.........#.#</div>
<div>#.###########.#</div>
<div>#.............#</div>
<div>###############</div>
<div>它是一个中心为一个字符&#39;.&#39;，之后按照一层&#39;#&#39;一层&#39;.&#39;的顺序围起来的无限大的图形。</div>
<div>现在给定若干个位置上的字符，请你确定出这个图形中心位置的坐标，若有多个合法中心位置，</div>
<div>则输出离原点曼哈顿距离最近的一个。若仍有多个，则输出横坐标最大的一个，</div>
<div>若还有多个，输出纵坐标最大的一个；若没有合法中心点，输出&#34;Too damaged&#34;.</div></div>

# Input

<div class="content"><div>第一行一个正整数T表示数据组数。</div>
<div>对于每组数据，第一行一个正整数n表示已知位置数。</div>
<div>接下来n行，每行两个整数x,y和一个字符c，表示该位置的坐标以及该位置上的字符。</div>
<div>n ≤ 1000, |x|, |y| ≤ 10^15, T ≤ 50 , c ∈ {., #}</div></div>

# Output

<div class="content"><div>对于每组数据输出一行表示答案。</div>
<div>格式为：&#34;Case #x: ans&#34;,其中x为当前数据的组编号，ans表示答案，#之前有一个空格，:之后有一个空格，</div>
<div>除此之外不允许有任何多余字符。</div></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
1<br/>
0 0 .<br/>
1<br/>
0 0 #<br/>
3<br/>
0 0 #<br/>
0 1 #<br/>
1 0 #<br/>
5<br/>
50 30 #<br/>
49 30 #<br/>
49 31 #<br/>
49 32 #<br/>
50 32 #<br/>
2<br/>
-98 0 #<br/>
99 50 .<br/>
4<br/>
88 88 .<br/>
88 89 .<br/>
89 88 .<br/>
89 89 .</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1: 0 0<br/>
Case #2: 1 0<br/>
Case #3: 1 1<br/>
Case #4: 50 31<br/>
Case #5: 1 0<br/>
Case #6: Too damaged<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By ExfJoe">By ExfJoe</a></p></div>

