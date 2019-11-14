<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>公元 2089年6 月4日，在经历了 17年零 3个月的漫长旅行后，“格纳格鲁一号”载人火箭返回舱终于安全着陆。此枚火箭由美国国家航空航天局（NASA）研制发射，行经火星、金星、土卫六、木卫二、谷神星、“张衡星”等 23颗太阳系星球，并最终在小行星“杰森星”探寻到了地外生命。宇航员在“杰森星”地表岩层下45.70米位置发现一批珍贵的活体生命样本，并将其带回检测。在带回的活体样本中，最吸引人的当属这些来自外星的千足虫了。这些虫子身躯纤长，身体分为若干节。受到触碰时，会将身体卷曲成圆环形，间隔一段时间后才会复原活动。</p>
<p><br>有趣的还不止如此。研究人员发现，这些虫子的足并不像地球千足虫成对出现、总共偶数条——它们每节身体下方都有着不定数量的足，但足的总数一定是奇数条！虽然从外观难以区分二者，但通过统计足的数目，科学家们就能根据奇偶性判断出千足虫所属的星球。</p>
<p>作为 J 国派去NASA 的秘密间谍，你希望参加这次研究活动以掌握进一步的情报，而NASA选拔的研究人员都是最优秀的科学家。于是 NASA 局长CharleBolden出了一道难题来检测你的实力： <br>现在你面前摆有 1…N 编号的N 只千足虫，你的任务是鉴定每只虫子所属的星球，但不允许亲自去数它们的足。Charles 每次会在这N 只千足虫中选定若干只放入“昆虫点足机”（the Insect Feet Counter, IFC）中，“点足机”会自动统计出其内所有昆虫足数之和。Charles 会将这个和数 mod 2 的结果反馈给你，同时告诉你一开始放入机器中的是哪几只虫子。他的这种统计操作总共进行M次，而你应当尽早得出鉴定结果。</p>
<p>假如在第 K 次统计结束后，现有数据就足以确定每只虫子的身份，你就还应将这个K 反馈给Charles，此时若K＜M，则表明那后 M－K 次统计并非必须的。</p>
<p>如果根据所有M次统计数据还是无法确定每只虫子身份，你也要跟Charles讲明：就目前数据会存在多个解。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>接下来 M行，按顺序给出 Charles 这M次使用“点足机”的统计结果。每行包含一个“01”串和一个数字，用一个空格隔开。“01”串按位依次表示每只虫子是否被放入机器：如果第 i 个字符是“0”则代表编号为 i 的虫子未被放入，“1”则代表已被放入。后面跟的数字是统计的昆虫足数 mod 2 的结果。 <br>由于 NASA的实验机器精确无误，保证前后数据不会自相矛盾。即给定数据一定有解。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件 insect.out 在给定数据存在唯一解时有 N＋1行，第一行输出一个不超过M的正整数K，表明在第K 次统计结束后就可以确定唯一解；接下来 N 行依次回答每只千足虫的身份，若是奇数条足则输出&ldquo;?y7M#&rdquo;（火星文），偶数条足输出&ldquo;Earth&rdquo;。如果输入数据存在多解，输出&ldquo;Cannot Determine&rdquo;。 所有输出均不含引号，输出时请注意大小写。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 5<br>011 1<br>110 1<br>101 0<br>111 1<br>010 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4<br>Earth<br>?y7M#<br>Earth</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 20%的数据，满足 N＝M≤20； <br>对于 40%的数据，满足 N＝M≤500； <br>对于 70%的数据，满足 N≤500，M≤1,000； <br>对于 100%的数据，满足 N≤1,000，M≤2,000。</p>
</div>
</div>