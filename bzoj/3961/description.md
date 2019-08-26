
# Description

<div class="content"><div>一位著名的微处理器公司邀请您帮忙在他们的电脑芯片上安排一些组件，每个芯片被设计成拥有N × N个插槽的正方形。一个插槽可以存放一个组件，你要尽可能多地在芯片上安装组件。</div>
<div>现代的处理器设计是相当复杂的。不幸地，你需要满足以下的限制。</div>
<div>* 一些插槽是不可用的</div>
<div>* 一些插槽已经被其他的组件所占据，无法用于固定额外的组件。</div>
<div>* 芯片水平和垂直边界上连接着着一些内存总线,他们的带宽负载需要匹配。也就是说，第一行和第一列的组件数目必须一样多，第二行和第二列的组件数目必须一样多，依此类推。这里的组件数要包括之前已经存在于芯片之上和后来加上去的。</div>
<div>* 类似地，每行每列都有能量供应系统。为了避免局部过热，对于给定的一组A，B，任何一行/一列的组件数都不能超过总组件数的A / B。</div>
<div>你希望计算出最多可以在芯片上再安装多少个组件。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div></div>
<div>对于每组数据，第一行包括三个正整数N，A，B。</div>
<div>接下来包含 N 行,每行包含 N 个字符，表示了描述芯片的矩阵。其中 &#39;.&#39; 表示可用插槽，&#39;/&#39; 表示不可用插槽，&#39;C&#39; </div>
<div>表示插槽已被一个部件占据。整个测试以&#34;0 0 0&#34;表示结束</div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>如果有解，输出一行包括一个正整数，表示最多能再安装多少个组件。</div>
<div>否则，输出&#34;impossible&#34;（不包含引号）。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 1 1<br/>
/.<br/>
//<br/>
2 50 100<br/>
/.<br/>
C/<br/>
0 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: 0<br/>
Case 2: 1</span></div>

# Hint

<div class="content"><p></p><p>1 ≤ N ≤ 40，1 ≤ B ≤ 1000， 0 ≤ A ≤ B。</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

