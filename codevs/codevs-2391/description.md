<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>HURRICANE小组最近接到了一个搜索文本的任务，即从一个由数字构成的长文本中，匹配满足指定条件的子串。搜索的条件采用形如‘(0+10*1)*10*’这样的<span style="text-decoration: underline;">正则表达式</span>来描述。其中<span style="text-decoration: underline;">正则表达式</span>的归纳定义如下：</p>
<p> </p>
<ol>
<li>0, 1, …, 9，0*, 1*, …, 9*是<span style="text-decoration: underline;">正则表达式</span>；</li>
<li>如果A和B是<span style="text-decoration: underline;">正则表达式</span>，则(A)，A+B，AB，(A)*都是<span style="text-decoration: underline;">正则表达式</span>；</li>
<li>只有按以上方法构造出来的表达式才是<span style="text-decoration: underline;">正则表达式</span>。</li>
</ol>
<p> </p>
<p>其中，A+B表示“<span style="text-decoration: underline;">或者</span>”关系，AB表示“<span style="text-decoration: underline;">连接</span>”关系，(A)*表示A的内容“<span style="text-decoration: underline;">重复</span>”零次或者多次。比如正则表达式(12+3)(4+5)6*，就可以匹配以124，125，34，35之一开头，之后接零0个或任意多个6的字符串（例如字符串12566）。正则表达式(1+0)*可以匹配所有由0和1构成的字符串，或者是空串。如果一个正则表达式不能匹配空串，则称它是非空的。本题考虑的都是非空正则表达式。</p>
<p>如果在给定文本的某一个位置，存在一个以该位置结束的子串，能够被给定的非空<span style="text-decoration: underline;">正则表达式</span>匹配，则称该位置是<span style="text-decoration: underline;">可匹配的</span>。现在HURRICANE小组接到的任务就是找出所有<span style="text-decoration: underline;">可匹配的位置</span>。你能帮助他们完成这个任务么？</p>
<p>你的程序需要根据给定的输入，给出符合题意的输出：</p>
<p> </p>
<p>l  输入包括一个满足如上定义的<span style="text-decoration: underline;">正则表达式</span>，以及一长串文本；</p>
<p>l  你需要根据输入的<span style="text-decoration: underline;">正则表达式</span>及文本，找出文本中所有<span style="text-decoration: underline;">可匹配的位置</span>；</p>
<p>l  你给出的输出需要包括所有<span style="text-decoration: underline;">可匹配的位置</span>。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>的第一行描述一个<span style="text-decoration: underline;">正则表达式</span>，第二行为需要处理的文本：</p>
<p>l  第一行的<span style="text-decoration: underline;">正则表达式</span>包括由一个空格分开的两个部分：</p>
<p>n  一个非负整数<em>n</em>（1≤ <em>n</em>≤ 10），表示我们所要考虑的数字集（即在<span style="text-decoration: underline;">正则表达式</span>和文本中所出现的数字）是0, 1, …, <em>n</em>–1。</p>
<p>n  接下来是一个<span style="text-decoration: underline;">正则表达式</span>，它由{‘(‘, ’)’, ’+’, ’*’}中的4个符号和{0, …, <em>n</em>–1}中的数字构成，表达式的长度不超过500个字符。</p>
<p>l  第二行为一个由0到<em>n</em>-1之间数字构成的字符串，为需要处理的文本。该文本长度不超过10,000,000个字符。</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件只有一行，包括一些由空格分开的整数，按从小到大的顺序依次输出所需处理的文本中每一个<span style="text-decoration: underline;">可匹配的位置</span>。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 12333+33</p>
<p>312331</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>表达式的长度不超过500</p>
</div>
</div>