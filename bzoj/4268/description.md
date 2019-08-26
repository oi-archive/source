
# Description

<div class="content"><div>小强有很多书，它想制作一个书架。</div>
<div>对于每本书，它有一个高度、一个厚度。书架的一层能够放置的书的厚度总和不能超过一个</div>
<div>常数W。小强想让每层书架里的书都用一种雅观的方式进行摆放，它经过思考之后认为，</div>
<div>一层书架的高度应该由下式给出：</div>
<div>First+Second+(W-s)/10</div>
<div>其中，First和Second分别是这层书架中高度前两高的书的高度（如果这层只有一本书，</div>
<div>那么令First、Second等于这唯一一本书的高度；如果这层有超过一本高度相同的书都是</div>
<div>最高的，那么First、Second都等于这个最高高度），s表示这层书架的厚度的总和。注</div>
<div>意，每层书架的高度可以不一样。</div>
<div>小强把书从1到N编号，它规定，书架的一层中放置的书的编号必须是连续的。小强想知</div>
<div>道，把所有的书都放进去，它的书架至少要多高呢？</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行两个正整数N和W，表示书的数目和一层书架里的书的厚度总和</div>
<div>的上限。N行，每行两个正整数，按编号顺序依次描述了每本书的高度和厚度。输入数据保证每本书</div>
<div>的厚度都不超过W，高度不超过100000000。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>一行一个数，精确到小数点后一位，表示书架的最小高度。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 10<br/>
3 5<br/>
7 2<br/>
1 3<br/>
5 2<br/>
6 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">19.5</span></div>

# Hint

<div class="content"><p></p><div>【样例解释】</div><br/>
<div>第一本书自己一层，高度3+3+5/10=6.5，剩下4本书一层，高度7+6+0/10=13。总</div><br/>
<div>共19.5的高度。</div><br/>
<div>【数据规模】</div><br/>
<div>对于100%的测试数据，N&lt;=300000，W&lt;=1000000000</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

