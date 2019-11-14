<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>彭先生任职于证券公司，是一位股票分析师。公司经理认为目前的股票分析软件仍可再改进，希望彭先生再设计一套更准确的软件。近日來，彭先生埋头钻研，他发现过去的研究结果，有人提到，如果能在历史资料中，找到与近期股票走势相近的样型，即可使用此历史样型的交易策略，做为近期的买卖策略。为了验证这样的讲法是否正确，彭先生从股票历史资料抽出一些特征资料，并以大写英文字母A~Z 代表特征资料，因此股票资料变成一串的英文字母序列。判断近期股票资料与某一段历史资料是否相近，就变成判断二串字母序列( 长度不一定相等) 的相似度，亦即找出兩者的最长共同子序列(LCS，longest common subsequence) 。</p>
<p>在计算二串股票资料序列的相似度时，还有一个限制，兩个相似点( 相同字母) 的前后间距不能太远，否则相似度会被扭曲。发现了这个特性后，彭先生将此问题正式定义为「有间距限制的最长共同子序列」(GLCS, gapped longest common subsequence)问题。</p>
<p>假设第一个序列称为α，第二个序列称为β。例如，α =“ACBDCAA”，β=“ADDBCDBAC” 。兩者在无间距限制的情形下，其 LCS 可为“ADCA” ， “ABCA” ，或“ACBC” ，长度为4。假设间距限制如下： </p>
<p>A 2, B 0, C 3, D 0</p>
<p> 上述间距之意义为，如果字母A 被选入LCS 中，则与其前一个被选入的字母之间，在α序列最多只能有2 个未被选入的字母，在β序列亦同。α与β在上述间距限制的情形，GLCS 可为“ACA” 或“ACC” ，长度为3。</p>
<p>对于无间距限制的情形，可将每个字母的间距视为无限大。本题的答案只要输出GLCS 的长度即可。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>共分成二部分。第一部分，第一行为α序列，第二行为β序列，兩者都是大写英文字母A~Z 的序列，每个序列长度至少为 1，最长为 800。第二部分自第三行起，第三行有一个数值 k，代表以下有 k 组测试资料(1 ≤ k≤ 5) ，每一组测试资料为一行，每一行有多个( 可能零个) 字母间距限制，每个限制的第一个为英文字母，第二个为间距数值( 数值介于0 与400 之间)；英文字母不一定按照顺序，也不一定每个字母都会出现，未出现的字母间距可视为无限大。每一行字母间距限制的最后一个符号为$ ，代表该行( 该组) 的资料结束。每一行的字母间距限制情形，相邻兩项资料之间均有一个空白隔开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每一组测试资料，输出它的 GLCS 长度。输出这 k 个值于一行，且相邻兩个整数之间以一个空白隔开。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1：</p>
<p>ACBDCAA</p>
<p>ADDBCDBAC</p>
<p>2</p>
<p>$</p>
<p>A 2 B 0 C 3 D 0 $</p>
<p>  </p>
<p>样例2：</p>
<p>ACBDCAA</p>
<p>ADDBCDBAC</p>
<p>1</p>
<p>C 4 A 6 $</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1：</p>
<p>4 3</p>
<p> </p>
<p>样例2：</p>
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>TW一百学年度全国高级中学咨询学科能力竞赛决赛5</p>
</div>
</div>