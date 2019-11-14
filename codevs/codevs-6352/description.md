<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">Io</span><span style="">和Ao在玩一个单词游戏。</span></p><p><span style="">  </span><span style="">他们轮流说出一个仅包含元音字母的单词，并且后一个单词的第一个字母必须与前一单词的最后一个字母一致。</span></p><p><span style="">  </span><span style="">游戏可以从任何一个单词开始。</span></p><p><span style="">  </span><span style="">任何单词禁止说两遍，游戏中只能使用给定词典中含有的单词。</span></p><p><span style="">  </span><span style="">游戏的复杂度定义为游戏中所使用的单词长度总和。</span></p><p><span style="">编写程序，求出使用一本给定的词典来玩这个游戏所能达到的游戏最大可能复杂度。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输入文件的第一行，表示一个自然数N，N表示一本字典中包含的单词数量以下的每一行包含字典中的一个单词，每一个单词是由字母A、E、I、O和U组成的一个字符串。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-left: 28px;text-indent: 4px"><span style="font-family: 宋体">输出文件仅有一行，表示该游戏的最大可能复杂度。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">5</span></p><p><span style="">  IOO</span></p><p><span style="">  IUUO</span></p><p><span style="">  AI</span></p><p><span style="">  OIOOI</span></p><p><span style="">  AOOI</span></p><div><span style=""><br></span></div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">16</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">对于40%的数据,1&lt;=N&lt;=10</span></p><p style=""><span style="">对于100%的数据，1&lt;=N&lt;=16,1&lt;=单词长度&lt;=100</span></p><p><span style="">    样例解释</span></p><p><span style="">    </span><span style="">按如下顺序连接：AOOI </span><span style="font-family: Wingdings;">à</span><span style=""> IOO </span><span style="font-family: Wingdings;">à</span><span style=""> OIOOI </span><span style="font-family: Wingdings;">à</span><span style=""> IUUO</span><span style="">，所以总长度为4+3+5+4=16</span></p><p>       ps:数据灰常大，爆搜+卡时肯定过不了。</p>
</div>
</div>