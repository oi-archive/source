<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>　　阿米巴是小强的好朋友。</span><br><span>　　在小强眼中，阿米巴是一个作文成绩很高的文艺青年。为了获取考试作文的真谛，小强向阿米巴求教。阿米巴给小强展示了几篇作文，小强觉得这些文章怎么看怎么觉得熟悉，仿佛是某些范文拼拼凑凑而成的。小强不禁向阿米巴投去了疑惑的眼光，却发现阿米巴露出了一个狡黠的微笑。</span><br><span>　　为了有说服力地向阿米巴展示阿米巴的作文是多么让人觉得“眼熟”，小强想出了一个评定作文 “熟悉程度”的量化指标：L</span><sub>0</sub><span>.</span><br><span>　　小强首先将作文转化成一个01串。</span><br><span>　　之后，小强搜集了各路名家的文章，同样分别转化成01串后，整理出一个包含了M个01串的“<span style="text-decoration: underline;"><em><strong>标准作文库</strong></em></span>”。</span><br><span>　　小强认为：如果一个01串长度不少于L且在<span style="text-decoration: underline;"><em><strong>标准作文库</strong></em></span>中的某个串里出现过（即，它是<strong><em><span style="text-decoration: underline;">标准作文库</span></em></strong>的<strong><em><span style="text-decoration: underline;">某个串</span></em></strong>的一个<span style="text-decoration: underline;"><em><strong>连续子串</strong></em></span>），那么它是<strong><span style="text-decoration: underline;"><em>“熟悉”</em></span></strong>的。对于一篇作文（一个01串）A，如果能够把A分割成若干段子串，其中<em><span style="text-decoration: underline;"><strong>“熟悉”的子串的长度总和不少于A总长度的90%</strong></span></em>，那么称A是<span style="text-decoration: underline;"><em><strong>“熟悉的文章”</strong></em></span>。 L</span><sub>0</sub><span>是<span style="text-decoration: underline;"><em><strong>能够让A成为“熟悉的文章”的所有L的最大值</strong></em></span>（如果不存在这样的L，那么规定L</span><sub>0 </sub><span>= 0）。</span><br><span>　　举个例子：</span><br><span>　　小强的作文库里包含了如下2个字符串：</span><br><span>　　10110</span><br><span>　　000001110</span><br><span>　　有一篇待考察的作文是：</span><br><span>　　1011001100</span><br><span>　　小强计算出这篇作文L的最大值是4，因为待考察的作文可以视作'10110'+'0110'+'0'，其中'10110'和'0110'被判定为<span style="text-decoration: underline;"><em><strong>“熟悉”</strong></em></span>的。而当L = 5或是更大的时候，不存在符合题意的分割方法。所以，这篇作文的L</span><sub>0</sub><span> = 4。</span><br><span>　　小强认为阿米巴作文的L</span><sub>0</sub><span>值比其他同学的明显要大。请你帮他验证一下。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　输入第一行是两个整数 N, M，表示待检查的作文数量，和小强的标准作文库的行数。</span><br><span>　　接下来是M行的01串，表示标准作文库。</span><br><span>　　接下来是N行的01串，表示N篇作文。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　输出N行，每一行包含一个整数，表示该篇作文的L</span><sub>0</sub><span>值。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>1 2</span><br><span>10110</span><br><span>000001110</span><br><span>1011001100</span></p>
<p><span><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<div>
<div><span>4</span></div>
<div><span><br></span></div>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>【样例说明】</span></p>
<p><span>　　这就是题目描述里的例子。</span></p>
<p><span><br></span></p>
<p><span>【数据规模】</span></p>
<p><span><span>　　对于30%的测试数据，输入文件的长度不超过1000字节。</span><br><span>　　对于50%的测试数据，输入文件的长度不超过61000字节。</span><br><span>　　对于80%的测试数据，输入文件的长度不超过250000字节。</span><br><span>　　对于100%的测试数据，输入文件的长度不超过1100000字节。</span></span></p>
</div>
</div>