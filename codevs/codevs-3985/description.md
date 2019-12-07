<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">现在有一面很长的墙，墙被分成了 <span style="font-family: Times New Roman;">n </span><span style="">块，每个块都需要染上一种给定的颜色。</span></span></p><p><span style="">你需要使用一种特制的印章来对墙进行染色。假设印章长度为 <span style="font-family: Times New Roman;">m</span><span style="">，你可以设</span></span></p><p><span style="">定印章每一块的颜色，并将印章盖在墙的任意位置，但你需要保证：墙的每一块</span></p><p><span style="">都只能被它所应染上的颜色所盖到，最终墙的每一块都要被盖到相应的颜色；你</span></p><p><span style="">在使用印章时，不能将其翻转使用。</span></p><p><span style="">你需要求出：满足条件的印章的最小长度为多少？</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">我们使用一个字符串来表示墙需要被染成的颜色。相同的字符表示相同的颜</span></p><p><span style="">色。</span></p><p><span style="">第一行一个正整数 <span style="font-family: Times New Roman;">T</span><span style="">，表示有 </span><span style="font-family: Times New Roman;">T </span><span style="">组数据。</span></span></p><p><span style="">接下来 <span style="font-family: Times New Roman;">T </span><span style="">行，每行一个字符串，描述墙应该被染成的颜色。</span></span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style=";font-family:宋体;font-size:14px">输出<span style="font-family:Times New Roman">T</span><span style="font-family:宋体">行，第</span><span style="font-family:Times New Roman">i</span><span style="font-family:宋体">行表示第</span><span style="font-family:Times New Roman">T</span><span style="font-family:宋体">组数据的答案。</span></span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">seal.in</span></p><p><span style="">seal.out</span></p><p><span style="">1</span></p><p><span style="">ababbababbaba</span></p><p><br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">印章被设计为”<span style="font-family: Times New Roman;">ababbaba</span><span style="">”最优，盖在第 </span><span style="font-family: Times New Roman;">1 </span><span style="">和第 </span><span style="font-family: Times New Roman;">6 </span><span style="">个位置即可。</span></span></p><p><span style="">设每组数据中最长的字符串长度为 <span style="font-family: Times New Roman;">L</span></span></p><p><span style="">对于 <span style="font-family: Times New Roman;">30%</span><span style="">的数据，</span><span style="font-family: Times New Roman;">L&lt;=50</span></span></p><p><span style="">对于 <span style="font-family: Times New Roman;">60%</span><span style="">的数据，</span><span style="font-family: Times New Roman;">L&lt;=20000</span></span></p><p><span style="">对于 <span style="font-family: Times New Roman;">100%</span><span style="">的数据，</span><span style="font-family: Times New Roman;">L&lt;=500000</span><span style="">，</span><span style="font-family: Times New Roman;">T&lt;=20</span><span style="">。</span></span></p><p><span style="">多组数据？是的没错我就是要报复社会！</span></p><p><br></p>
</div>
</div>