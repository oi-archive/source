<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">经历过大战之后的 tty,传说中的 Long'Aotian 职阶的骑士,开始研究数学。</p><p style="">他定义数列 f<sub>i</sub> ,这个数列的第 i 项,即 <span style="">f</span><sub style="">i</sub> 表示不大于 i 且与 i 的互质的数的个数。</p><p style="">例如 f<sub>1</sub> = 1 ,  f<sub>3</sub> = 2 , f<sub>6</sub> = 2 ,  f<sub>18</sub> = 6</p><p style="">他还定义了一种奇特的数学关系:</p><p style="">对于正整数 m, n,如果 2<sup>m</sup> -1 | 2<sup>n</sup> - 1,并且 m 能被至少一个大于 1 完全平方数整除,就称 m 是 n 的“可协调数”。</p><p style="">现在对于给定的 n,他希望你求出 sum (f<sub>m</sub>) (m 是 n 的“可协调数”)。 </p><p style="">注意有多组数据。</p><p style=""><span style="">sum (f</span><sub style="">m</sub><span style="">)为f<sub>m</sub>的和</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">第 1 行,一个正整数 T 表示数据组数。</p><p style=""><span style="">接下来 T 行,每行一组数据,只包含一个正整数 n.</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="TEXT-ALIGN: left; TEXT-INDENT: 2em">输出文件应包含&nbsp;T行。</p><p style="TEXT-ALIGN: left; TEXT-INDENT: 2em">对于每组数据,输出&nbsp;1行,表示你的答案。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p><p>7</p><p>8</p><p>9</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0 </p><p>6</p><p>6</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例解释】</p><p>7 没有“可协调数”,答案为 0。</p><p>8 的可协调数为 4,8,而 f<sub>4</sub> = 2,f<sub>8</sub> = 4,答案为 f<sub>4</sub>+f<sub>8</sub>= 6</p><p>9 的可协调数为 9,f<sub>9</sub> = 6,答案为 6。</p><p>【数据范围】</p><p>T=5  n&lt;=10<sup>18</sup></p><p><br></p>
</div>
</div>