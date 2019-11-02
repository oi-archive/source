<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    HR大神的Mz数量众多，所以有时他不能很好地辨别出与他约会的是哪个Mz。所以每见到一名Mz，他就会先在大脑中寻找这名Mz的信息，如果找得到， HR就能愉快的玩耍；如果大脑中没有，HR大神便会询问这位Mz的信息，并将其信息记在大脑中，以备后续的愉悦。不幸的是，由于HR大神Mz数量太多，而且忙于在机房刷题(玩codevs的Flappy Bird)，他的大脑无法同时记住所有Mz的信息。 假设HR的大脑中有M个单元，每单元能存放一个Mz的所有信息。每将一个新Mz存入大脑前，如果当前大脑中已存入的Mz数不超过M，HR会将新Mz存入一个未使用的记忆单元；若大脑中已存入M个Mz，HR只好忍痛割爱，清空最早进入大脑的那个Mz的信息，腾出单元来， 存放新Mz（喜新厌旧）。假设HR大神要与N个Mz约会（Mz有可能重复）。给定所有Mz，HR大神需要询问几次Mz的信息？假设在约会(papapa)前，他的大脑中没有任何Mz的信息。<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入共2行。</p><p>    第一行为两个正整数n和m，代表Mz的个数以及HR大脑中用来储存Mz信息的单元个数。</p><p>    第二行为N个非负整数，按照把妹的顺序，每个字符串（长度≤250，字符串只包含大小写英文字母 ）代表一个Mz。数列中两个Mz是同一个Mz，当且仅当它们对应的字符串相同。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; 输出共1行，包含一个整数，为HR需要询问Mz信息的次数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   对于100%的数据有n≤20000，m≤15000。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7 3</p><p>Mz</p><p>abc</p><p>hpw</p><p>mZ</p><p>Mz</p><p>hpw</p><p>app</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>6</p>
</div>
</div>