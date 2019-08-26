
# Description

<div class="content"><div>给定一棵有n个节点的无根树和m个操作，操作有2类：</div>
<div>1、将节点a到节点b路径上所有点都染成颜色c；</div>
<div>2、询问节点a到节点b路径上的颜色段数量（连续相同颜色被认为是同一段），</div>
<div>如“112221”由3段组成：“11”、“222”和“1”。</div>
<div>请你写一个程序依次完成这m个操作。</div></div>

# Input

<div class="content"><div>第一行包含2个整数n和m，分别表示节点数和操作数；</div>
<div>第二行包含n个正整数表示n个节点的初始颜色</div>
<div>下面 行每行包含两个整数x和y，表示x和y之间有一条无向边。</div>
<div>下面 行每行描述一个操作：</div>
<div>“C a b c”表示这是一个染色操作，把节点a到节点b路径上所有点（包括a和b）都染成颜色c；</div>
<div>“Q a b”表示这是一个询问操作，询问节点a到节点b（包括a和b）路径上的颜色段数量。</div></div>

# Output

<div class="content"><p class="NOI1" style="margin: 0cm 0cm 0pt"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"><font size="3">对于每个询问操作，输出一行答案。</font></span></p>
<p class="NOI2" style="margin: 0cm 0cm 0pt"></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 5<br/>
2 2 1 2 1 1<br/>
1 2<br/>
1 3<br/>
2 4<br/>
2 5<br/>
2 6<br/>
Q 3 5<br/>
C 2 1 1<br/>
Q 3 5<br/>
C 5 1 2<br/>
Q 3 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
1<br/>
2</span></div>

# Hint

<div class="content"><p></p><p>数N&lt;=10^5，操作数M&lt;=10^5，所有的颜色C为整数且在[0, 10^9]之间。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=第一轮day1">第一轮day1</a></p></div>

