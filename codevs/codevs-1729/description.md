<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在进行文法分析的时候，通常需要检测一个单词是否在我们的单词列表里。为了提高查找和定位的速度，通常都要画出与单词列表所对应的单词查找树，其特点如下：</p>
<p>l  根节点不包含字母，除根节点外每一个节点都仅包含一个大写英文字母；</p>
<p>l  从根节点到某一节点，路径上经过的字母依次连起来所构成的字母序列，称为该节点对应的单词。单词列表中的每个词，都是该单词查找树某个节点所对应的单词；</p>
<p>l  在满足上述条件下，该单词查找树的节点数最少。</p>
<p>对一个确定的单词列表，请统计对应的单词查找树的节点数（包括根节点）</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>该文件为一个单词列表，每一行仅包含一个单词和一个换行/回车符。每个单词仅由大写的英文字符组成，长度不超过63个字符。文件总长度不超过32K，至少有一行数据。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>该文件中仅包含一个整数和一个换行/回车符。该整数为单词列表对应的单词查找树的节点数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<div>
<p>A</p>
<p>AN</p>
<p>ASP</p>
<p>AS</p>
<p>ASC</p>
<p>ASCII</p>
<p>BAS</p>
<p>BASIC</p>
</div>

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
<p>13</p>
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

</div>
</div>