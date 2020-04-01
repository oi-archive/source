<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一种奇怪的语言叫做“贰五语言”。它的每个单词都由A～Y这25个字母各一个组成。但是，并不是任何一种排列都是一个合法的贰五语言单词。贰五语言的单词必须满足这样一个条件：把它的25个字母排成一个5*5的矩阵，它的每一行和每一列都必须是递增的。比如单词ACEPTBDHQUFJMRWGKNSXILOVY，它排成的矩阵如下所示： <br>A C E P T<br>B D H Q U<br>F J M R W<br>G K N S X<br>I L O V Y<br><br>因为它的每行每列都是递增的，所以它是一个合法的单词。而单词YXWVUTSRQPONMLKJIHGFEDCBA则显然不合法。 由于单词太长存储不便，需要给每一个单词编一个码。编码方法如下：从左到右，再从上到下，可以由一个矩阵的得到一个单词，再把单词按照字典顺序排序。比如，单词ABCDEFGHIJKLMNOPQRSTUVWXY的编码为1，而单词ABCDEFGHIJKLMNOPQRSUTVWXY的编码为2。 <br><br>现在，你需要编一个程序，完成单词与编码间的转换。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>INPUT FORMAT 第一行为一个字母N或W。N表示把编码转换为单词，W表示把单词转换为编码。 若第一行为N，则第二行为一个整数，表示单词的编码。若第一行为W，则第二行为一个合法的单词。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>每行一个整数或单词。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>N<br>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>ABCDEFGHIJKLMNOPQRSUTVWXY</p>

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