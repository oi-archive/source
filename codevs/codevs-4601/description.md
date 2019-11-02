<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>  为庆祝农民节日的到来，JF杂志决定将红人LXK的经典名言汇集成册，出版一本名为《LXK语录》的书。现在编辑部找到了一段文字材料T，现在你需要将其中LXK说的每一句话都找出来，并一条一条地列出来。<br></p><p>  文字资料是一种剧本一样的东西，每一行有两种可能：</p><p>  1.这一行以人名name开头，接下来是一个冒号，其左右都有空格；接下来是一段话S，表示名字为name的人说了S这段话。name只包含小写字母。一个人可以有多个名字，但不会有重名的人。</p><p>  2.这一行以一个‘（’开头，以一个‘）’结尾，括号内表示故事发生的背景，或人物的动作、表情。<br></p><p>  你对这段文字进行仔细研读后，发现LXK有k个外号。你希望求出LXK说过多少句话，并把每一句话都记录下来。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>  第一行为一个非负整数k，表示LXK的外号数。</p><p>  接下来k行，每行一个字符串name i，表示LXK的一个外号。可能有重复的外号。</p><p>  接下来一行为一个非负整数T，表示文本的行数。</p><p> 接下来T行，每行一个字符串，描述整个文本资料。<br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; 第一行输出一个整数k，表示LXK说的话的句数。</p><p>&nbsp; 接下来k行，每行一句话，按输入顺序输出（即先说的话先输出）。若这句话s为LXK说的第i句话，输出格式为：</p><p style="text-align: center;">i ：s</p><p>&nbsp;其中冒号前后各有一个空格。<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1<br></p><p>lxk</p><p>6<br></p><p>(In brackets,any character is allowed)</p><p>(such as,"lxk is a farmer")<br></p><p>lxk : yes,you are right.<br></p><p>(listen! lxk is nonging)</p><p>lxk : ni shi zhen nan ren bu?Kai kai kai!<br></p><p>yjy : da jia hao,wo shi nong ming.</p><p><br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2<br></p><p>1 : yes,you are right.</p><p>2 : ni shi zhen nan ren bu?Kai kai kai!</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>T&lt;=10^4,k&lt;=10^5,文件大小不超过5MB.<br></p>
</div>
</div>