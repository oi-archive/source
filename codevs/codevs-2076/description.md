<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>       佳佳是个贪玩的孩子。一天，他正在跟凡凡玩“数石子”的游戏。佳佳在地上摆了Ｎ堆石子，其中第Ｉ堆石子有Ａi个石头。佳佳每次都会问凡凡：“凡凡，请问从第Ｉ堆到第Ｊ堆，总共有多少个石子？”聪明的凡凡每次都能快速而准确地回答对。凡凡老是被问问题，心里有些不服，就对佳佳说：“佳佳，你还记得你问了什么问题，我回答了什么答案吗？”佳佳说当然记得。于是凡凡说：“好，我把石子拿走，再问你一些相似的问题，你能答得出来吗？”佳佳张圆了嘴巴，望着凡凡，一脸疑问和惊讶的表情。你现在知道了游戏规则和过程，但没看见原来的石子。请你写一个程序来帮助佳佳。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>       输入文件的第一行有３个数Ｎ(1&lt;=n&lt;=5000)，Ｍ，Ｋ(0&lt;=m,k&lt;=10000)，表示Ｎ堆石子，佳佳问了Ｍ个问题，凡凡要问Ｋ个问题。接下来Ｍ行每行３个整数Ｌ，Ｒ（1&lt;=l&lt;=r&lt;=n），Ｘ(-10<sup>8</sup>&lt;=X&lt;=10<sup>8</sup>)，表示佳佳问从Ｌ堆到Ｒ堆的石子共有多少个，而凡凡回答Ｘ个。接下来Ｋ行每行２个整数Ａ，Ｂ(1&lt;=a&lt;=b&lt;=n)，每行表示凡凡问从Ａ到Ｂ这些堆里的石子有多少个。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; &nbsp; &nbsp;输出文件需要对于凡凡提出每一个提问，你若可以回答，则输出答案，若无法回答，输出UNKNOWN。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 5 5<br> 1 5 4<br> 2 5 4<br> 3 6 5<br> 1 9 9<br> 6 6 2<br> 1 9<br> 2 6<br> 1 2<br> 3 5<br> 1 7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>9</p>
<p>6</p>
<p>1</p>
<p>3</p>
<p>UNKNOWN</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>10%的数据满足1&lt;=n&lt;=10,0&lt;=m,k&lt;=10</p>
<p>30%的数据满足1&lt;=n&lt;=500,0&lt;=m,k&lt;=500</p>
<p>100%的数据满足1&lt;=n&lt;=5000,0&lt;=m,k&lt;=10000</p>
</div>
</div>