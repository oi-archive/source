<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 'times new roman';">    下列等式中缺少运算符，请你在“?”处添加“+”或“-”符号，使得等式成立。</span><br></p><p style=""><span style="font-family: 'times new roman';">? 1 ? 2 ? 3 ... ? <em>n</em> = <em>k</em><br></span></p><p><span style="font-family: 'times new roman';">    这实在是太简单了，所以你不必求出每个“?”处要填什么符号，你需要考虑的是下述问题：<br></span></p><p><span style="font-family: 'times new roman';">    给出<em>k</em>，求出最小的<em>n</em>，使得等式<span style="font-family: 'times new roman';">添加“+”或“-”符号后能够成立，注意<em>n</em>&gt;=1。</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'times new roman';">    输入为标准输入。</span><br></p><p style=""><span style="font-family: 'times new roman';">    输入的第一行为一个正整数<em>T</em>，表示该测试点下共有<em>T</em>组子测试点。<br></span></p><p style=""><span style="font-family: 'times new roman';">    接下来<em>T</em>行，每行描述一组子测试点，每一组子测试点为一行一个整数<em>k</em>，表示等式等号右边的数字。<br></span></p><p style=""><span style="font-family: 'times new roman';">    输入不含多余的空格和回车符。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="white-space: normal;"><span style="font-family: &#39;times new roman&#39;;">&nbsp; &nbsp; 输出为标准输出。<br/></span></p><p style="white-space: normal;"><span style="font-family: &#39;times new roman&#39;;">&nbsp;&nbsp;&nbsp;&nbsp;输出共<em>T</em>行，每行为一个子测试点的答案，表示能使等式成立的最小正整数<em>n</em>。</span><br/></p><p style="white-space: normal;"><span style="font-family: &#39;times new roman&#39;;">&nbsp;&nbsp;&nbsp;&nbsp;输出不要包含多余的空格与回车符。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p><p>12</p><p>3646397</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7</p><p>2701</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'times new roman';">    对于30%的数据，|<em>k</em>|&lt;=100；<br></span></p><p style=""><span style="font-family: 'times new roman';">    对于50%的数据，<span style="font-family: 'times new roman';">|<em>k</em>|&lt;=100,000，1&lt;=<em>T</em>&lt;=100；</span></span></p><p style=""><span style="font-family: 'times new roman';">    对于80%的数据，1&lt;=<em>T</em>&lt;=1,000；<br></span></p><p style=""><span style="font-family: 'times new roman';">    对于95%的数据。1&lt;=<em>T</em>&lt;=100,000；<br></span></p><p style=""><span style="font-family: 'times new roman';">    对于100%的数据，|<em>k</em>|&lt;=10<sup>9</sup>,1&lt;=<em>T</em>&lt;=1,500,000；</span></p><p style=""><span style="font-family: 'times new roman';">    其中有30%的数据，<em>k</em>&gt;0。<br></span></p><p style=""><span style="font-family: 'times new roman';">【评分方式】</span></p><p style=""><span style="font-family: 'times new roman';">    如果你的输出与标准输出完全一致，则得到该测试点的全部分数，任意一组子测试点的答案错误都会导致该测试点不得分。<br></span></p><p style=""><span style="font-family: 'times new roman';"><br></span></p><p style=""><span style="font-family: 'times new roman';">【提示】</span></p><p style=""><span style="font-family: 'times new roman';">    注意最后一组数据测试点数目<em>T</em>极大，请使用高效的求解方式，必要时请采取读写优化。<br></span></p><p style=""><span style="font-family: 'times new roman';"><br></span></p><p style=""><span style="font-family: 'times new roman';">【限制】</span></p><p style=""><span style="font-family: 'times new roman';">    时间限制为1s，空间限制为256MB。<br></span></p><p style=""><br></p><p style=""><span style="font-family: 'times new roman';">【Source】</span></p><p style=""><span style="font-family: 'times new roman';">    UVa Online Judge（加强版）</span></p><p><br></p>
</div>
</div>