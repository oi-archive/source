<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    平时的练习和考试中，我们经常会碰上这样的题：命题人给出一个例句，要我们类比着写句子。这种往往被称为仿写的题，不单单出现在小学生的考试中，也有时会出现在中考中。许多同学都喜欢做这种题，因为较其它题显得有趣。仿写的句子往往具有“A__B__C”的形式，其中 A，B，C 是给定的由一个或多个单词组成的短句，空的部分需要学生填写。当然，考试的时候空在那里也是可以的。例如，“其实天不暗阴云终要散，其实_____，其实_____，其实路不远一切会如愿，艰难困苦的日子里我为你祈祷，请你保重每一天”。再比如，“见了大海的汹涌，没见过大山的巍峨，真是遗憾；见了大山的巍峨，没见过_____，还是遗憾。出发吧，永远出发。_____，人有不老的心情。”</p>
<p>    由于现在是网络时代，我们不再只能仿写命题人命的题，我们可以仿写网上各种句子和段落。2011 年 3 月 26 日，某人在博客上发布了的消息就惹来了很多人的仿写。 <br>很 难过 吧 。。。 考 得 完 爆 了 。。。 <br>。。。。。。 其 实 也没什 么 可以 说 的 。。。 都 是 蒟 蒻 的 借 口 罢 了 。。。 <br>。。。 自 己 果 然 还 只 是 半 吊 子 水 平 呢 。。。。 <br>。。。 祝 大 家 都 能 进 省 队 。。。 其 实 只要不要有 遗 憾 就 好 了 呢 。。。 <br>虽 然我很 遗 憾或 许 不 能 走 下 去 了 。。。。。 <br>886 <br>    在网络上广泛流传的仿写，因为在某些地方有独到之处，大都被命名为“某某体”。打开人人，刷新微博，你也能发现这样和那样的体，比如，对不起体，**说明他爱你体等等。金先生注意到了这一现象，他敏锐地认为这是一个很有价值的研究课题，于是就其展开研究，打算发一篇 paper。由于在网上发消息，人<span style="">们有了更大的灵活度，人们有时因为表达的需要，还往原本固定的 A, B, C 中添加一些修饰的词语。这就给辨别一个句子或段落是否是另一个句子或段落的仿写</span><span style="">增加了困难。</span></p>
<p>    金先生现在研究一种形如“A*B*C”的体作品，其中 A, B, C 分别是某个由若干单词组成的短句，*代表 0 个或多个单词。他在网上找了大量的体作品，不过很多体作品不太合乎原作者的格式，也就是相当于在正规的体作品中插入了 0个或多个单词。</p>
<p> </p>
<p>    由于数据量太大，金先生无法一个一个看过去，于是想请你帮忙，去掉尽量少的单词，使它成为指定的体。</p>
<p><span style=""><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>包含 4 行。第一行是某个也许不规范的体作品 T，接下来三行分别代表 A, B, C。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一行，包含一个数，即最少的去除单词数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>xiang yao yi zhi ai zhe mou wu de hua yi yao guai zhi si lai shuo tai chang le xiang yao shi xian yi qie meng xiang de hua yi ren lei zhi sheng lai shuo tai duan le <br>yao <br>tai chang le yao <br>tai duan le</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例提示：</p>
<p>在上述样例中，不规范的体作品为：“想要一直爱着某物的话，以妖怪之死来说<span style="">太长了；想要实现一切梦想的话，以人类之生来说太短了”。 </span><span style="">规范的体形如：“要*太长了要*太短了”。 </span><span style="">修改后的规范的体为：“要一直爱着某物的话，以妖怪之死来说太长了；要实现</span><span style="">一切梦想的话，以人类之生来说太短了”。</span></p>
<p><span style="">数据范围：</span></p>
<p>对于 20%的数据，1≤|T|, |A|, |B|, |C|≤10。 <br>对于 40%的数据，1≤|T|, |A|, |B|, |C|≤100。 <br>对于 70%的数据，1≤|T|, |A|, |B|, |C|≤1000。 <br>对于 100%的数据，1≤|T|, |A|, |B|, |C|≤50000；所有单词长度不超过 5，出现次数不超过 500；数据保证答案总存在。</p>
<p><span style=""><br></span></p>
<p><span style="text-decoration: underline;"><strong>C及C++选手注意：数据在Windows中生成，每行末尾是以"\r\n"结尾的，请小心处理。</strong></span></p>
</div>
</div>