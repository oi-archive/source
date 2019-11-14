
# Description

<div class="content"><p></p>
<div><span style="font-size: medium">       小Y盯上了最近发行的即时战略游戏——ResourceTransport。但在前往通关之路的道路上，一个小游戏挡住了小Y的步伐。“国家的本质是生产与收集资源”是整款游戏的核心理念，这个小游戏也不例外。简单的说，用户需要管理一个国家，使其繁荣富强。</span></div>
<div><span style="font-size: medium">       一个国家含有N个城市，游戏开始时城市间没有任何道路。城市可以通过高速公路连接。为了减少建设费用，每对城市间最多存在一条路径。</span></div>
<div><span style="font-size: medium">       小Y拥有极强的游戏天赋，很快就把所有城市的生产能力提到了满级，把高速公路的建设费用修改成了0。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">悲剧的是，对于每个连通的城市群，都要把该城市群中的某个城市设立成资源集合处，小Y把这件事忘了；更悲剧的是，建造高速公路这件事，小Y也忘了。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">可小Y是个完美主义者，他请来了你帮他设立资源集合处，自己负责建造高速公路。<b>假设连通城市群中的某个城市</b><b>i</b><b>到该城市群的资源集合处最少需要经过Di</b><b>条高速公路，那么总运输费用为Sigma(Di)</b>。<b>你需要在每个连通城市群中设立一个资源集合处，使得总费用最小。小</b><b>Y</b><b>有时会向你询问此时最小的总费用</b>。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">问题很简单，麻烦的是小Y会在你好不容易算出最小总费用时建造一条新的高速公路。由于每个连通的城市群只能有一个资源集合处，所以最小总费用又得重新计算，这可真是个苦差事……</span></div></div>

# Input

<div class="content"><div> </div>
<div style="text-indent: 21pt"><span style="font-size: medium">第一行两个整数N，M分别表示国家中的城市数与小Y的操作数。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">接下来M行，每行可能为：</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">       1.A x y：表示在城市x和城市y间建造一条高速公路，保证此操作出现N-1次；</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">       2.Q：表示小Y询问此时的最小总费用。</span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">       对于每个Q操作，单独输出一行一个整数Ans，表示所求的答案。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
8 10<br/>
Q<br/>
A 1 2<br/>
A 4 5<br/>
A 6 7<br/>
A 3 4<br/>
Q<br/>
A 2 5<br/>
A 6 8<br/>
A 4 6<br/>
Q<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
0<br/>
4<br/>
12<br/>
【样例解释】<br/>
       1.开始所有城市互不联通，每个城市都是资源集合处，费用为0；<br/>
2.后来分别把城市1、城市4、城市7、城市8设立为资源集合处，费用为4；<br/>
3.最后把城市4设立为资源集合处，费用为12。</span></div>

# Hint

<div class="content"><p></p><p>N<span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">&lt;=40000,M<span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">&lt;=80000</span></span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

