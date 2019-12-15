<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">Jam</span></span></span></span><span style="">是个喜欢标新立异的科学怪人。他不使用阿拉伯数字计数，而是使用小写英文字母计数，他觉得这样做，会使世界更加丰富多彩。在他的计数法中，每个数字的位数都是相同的（使用相同个数的字母），英文字母按原先的顺序，排在前面的字母小于排在它后面的字母。我们把这样的“数字”称为</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">Jam</span></span></span></span><span style="">数字。在</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">Jam</span></span></span></span><span style="">数字中，每个字母互不相同，而且从左到右是严格递增的。每次，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">Jam</span></span></span></span><span style="">还指定使用字母的范围，例如，从</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">2</span></span></span></span><span style="">到</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">10</span></span></span></span><span style="">，表示只能使用</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">{b,c,d,e,f,g,h,i,j}</span></span></span></span><span style="">这些字母。如果再规定位数为</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">5</span></span></span></span><span style="">，那么，紧接在</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">Jam</span></span></span></span><span style="">数字“</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">bdfij</span><span style="">”</span></span></span></span><span style="">之后的数字应该是“</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">bdghi</span><span style="">”</span></span></span></span><span style="">。（如果我们用</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">U</span></span></span></span><span style="">、</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">V</span></span></span></span><span style="">依次表示</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">Jam</span></span></span></span><span style="">数字“</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">bdfij</span><span style="">”</span></span></span></span><span style="">与“</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">bdghi</span><span style="">”</span></span></span></span><span style="">，则</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">U&lt;V&lt; span&gt;</span></span></span></span><span style="">，且不存在</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">Jam</span></span></span></span><span style="">数字</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">P</span></span></span></span><span style="">，使</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">U&lt;P&lt;V&lt; span&gt;</span></span></span></span><span style="">）。你的任务是：对于从文件读入的一个</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">Jam</span></span></span></span><span style="">数字，按顺序输出紧接在后面的</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">5</span></span></span></span><span style="">个</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">Jam</span></span></span></span><span style="">数字，如果后面没有那么多</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">Jam</span></span></span></span><span style="">数字，那么有几个就输出几个。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">有</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">2</span></span></span></span><span style="">行，第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span></span></span></span><span style="">行为</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">3</span></span></span></span><span style="">个正整数，用一个空格隔开：</span></p>
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>s t w</span></span></span></p>
<p style=""><span style="">（其中</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">s</span></span></span></span><span style="">为所使用的最小的字母的序号，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">t</span></span></span></span><span style="">为所使用的最大的字母的序号。</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">w</span></span></span></span><span style="">为数字的位数，这</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">3</span></span></span></span><span style="">个数满足：</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span><span style="">≤</span><span style="font-family: Courier New,monospace;">s&lt;T&lt; span&gt;</span><span style="">≤</span><span style="font-family: Courier New,monospace;">26, 2</span><span style="">≤</span><span style="font-family: Courier New,monospace;">w</span><span style="">≤</span><span style="font-family: Courier New,monospace;">t-s </span></span></span></span><span style="">）</span></p>
<p style=""><span style="">第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">2</span></span></span></span><span style="">行为具有</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">w</span></span></span></span><span style="">个小写字母的字符串，为一个符合要求的</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">Jam</span></span></span></span><span style="">数字。</span></p>
<p style=""><span style="">所给的数据都是正确的，不必验证。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="cjk" style="text-indent: 0.74cm; margin-top: 0.49cm; margin-bottom: 0.49cm; line-height: 0.64cm; widows: 2; orphans: 2;" align="LEFT"><span style="font-size: small;">最多为</span><span style="font-family: Times New Roman,serif;"><span style="font-size: small;"><span lang="en-US"><span style="font-family: Courier New,monospace;">5</span></span></span></span><span style="font-size: small;">行，为紧接在输入的</span><span style="font-family: Times New Roman,serif;"><span style="font-size: small;"><span lang="en-US"><span style="font-family: Courier New,monospace;">Jam</span></span></span></span><span style="font-size: small;">数字后面的</span><span style="font-family: Times New Roman,serif;"><span style="font-size: small;"><span lang="en-US"><span style="font-family: Courier New,monospace;">5</span></span></span></span><span style="font-size: small;">个</span><span style="font-family: Times New Roman,serif;"><span style="font-size: small;"><span lang="en-US"><span style="font-family: Courier New,monospace;">Jam</span></span></span></span><span style="font-size: small;">数字，如果后面没有那么多</span><span style="font-family: Times New Roman,serif;"><span style="font-size: small;"><span lang="en-US"><span style="font-family: Courier New,monospace;">Jam</span></span></span></span><span style="font-size: small;">数字，那么有几个就输出几个。每行只输出一个</span><span style="font-family: Times New Roman,serif;"><span style="font-size: small;"><span lang="en-US"><span style="font-family: Courier New,monospace;">Jam</span></span></span></span><span style="font-size: small;">数字，是由</span><span style="font-family: Times New Roman,serif;"><span style="font-size: small;"><span lang="en-US"><span style="font-family: Courier New,monospace;">w</span></span></span></span><span style="font-size: small;">个小写字母组成的字符串，不要有多余的空格</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>2 10 5</span></span></span></p>
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>bdfij</span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>bdghi</span></span></span></p>
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>bdghj</span></span></span></p>
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>bdgij</span></span></span></p>
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>bdhij</span></span></span></p>
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>befgh</span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>