<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">小哈最近感冒了，十分不高兴。但是塞翁失马，焉知非福呢？小哈因此习得了一种技能。但是刚学会技能的他，需要你的帮助，验证他技能的稳定性。</span></p><p><span style="">小哈的技能是这样的，对于一个一维字符数组，小哈可以固定一个起点</span>pos<span style="">，然后选出他喜欢的一个字符串，覆盖上去这个一维数组上。当然了，两次的覆盖可能有重叠，但是因为小哈刚刚习得这个技能，已经被覆盖了的地方，就只好跳过了。现在小哈心中浮现出了</span>m<span style="">个他喜欢的字符串，然后进行了</span>Q<span style="">次操作后，他整个人都乱了，但是小哈又想知道这个一维字符数组最终的样子是什么。聪明的你能帮帮他吗？</span></p><p><br></p><p>数据有错误，请大家跳过，不好意思</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">题目是单</span>case<span style="">的</span></p><p><span style="">第一行三个正整数</span>lenstr<span style="">（</span>lenstr &lt;= 1e6<span style="">），</span>m<span style="">（</span>m &lt;= 10<span style="">）和</span>Q<span style="">（</span>Q &lt;= 1e5<span style="">），</span></p><p><span style="">表示一维字符数组的长度、小哈喜欢的字符串的个数和他执行了</span>Q<span style="">次操作。</span></p><p><span style="">第</span>2 – m + 1<span style="">行，包括</span>m<span style="">个字符串，保证每个字符串的长度不超过</span>1000</p><p><span style="">接下来</span>Q<span style="">行，每行的格式如下：</span></p><p><span style="">两个正整数</span> pos<span style="">（</span>1 &lt;= pos &lt;= lenstr<span style="">）</span> <span style="">和</span> which<span style="">。表示从</span>pos<span style="">点开始，覆盖上第</span>which<span style="">个字符串。</span></p><p><span style="">保证覆盖过去的字符串不会越界，也就是不会覆盖到</span>lenstr<span style="">之后。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 宋体">输出仅一行，表示最终的一维字符数组的是什么。</span></p><p><span style="font-family: 宋体">注意，开始的时候，整个一维字符数组都是字符</span>’$’<span style="font-family:宋体">。并且它不应该被当作已经被覆盖。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>12 3 3</p><p>SCAU</p><p>ACM</p><p>daydayup</p><p>3 1</p><p>1 3</p><p>10 2</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>daSCAUup$ACM</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: Arial, sans-serif;"><span style="">如题所示</span></span></p>
</div>
</div>