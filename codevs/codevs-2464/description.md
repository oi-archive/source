<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>很多人都知道玩麻将，当然也有人不知道，呵呵，不要紧，我在这里简要地介绍一下麻将规则： <br> 普通麻将有砣、索、万三种类型的牌，每种牌有 1~9个数字，其中相同的牌<br>每个有四张，例如 1 砣~9 砣，1索~9 索，1 万~9 万各有 4 张，所以共 36*3=108张牌。胡牌时每人有 14 张牌，其中只要某人手里有若干句话（就是同种类型的牌连续三张或同种牌三张） ，另外再加上一对，即可胡牌。当然如果全是对，叫七小对，也可以胡牌。下图是连三张示例。</p>
<p>四万 五万 六万</p>
<p>四万 四万 四万</p>
<p> </p>
<p>要判断某人是否胡牌，显然一个弱智的算法就行了，某中学信息学小组超级麻将迷想了想，决定将普通麻将改造成超级麻将。 <br>所谓超级麻将没有了砣、索、万的区分，每种牌上的数字可以是 1~100，而每种数字的牌各有100 张。另外特别自由的是，玩牌的人手里想拿多少张牌都可以，好刺激哦！ <br> 刺激归刺激，但是拿多了怎么胡牌呢？ <br> 超级麻将规定只要一个人手里拿的牌是若干句话（三个连续数字的牌各一张组成一句话，三张或者四张同样数字的牌也算一句话） ，再加上一对相同的牌，就算胡了。 <br>作为信息学竞赛选手的你，麻烦你给这位超级麻将迷编个程序，判断能否胡牌。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行一个整数 N（N&lt;=100），表示玩了 N次超级麻将。 接下来N行，每行 100个数a1..a100，描述每次玩牌手中各种牌的数量。ai表示数字为i的牌有ai张。（0&lt;=ai&lt;=100）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp;输出 N行，若胡了则输出 Yes，否则输出No，注意区分 Yes，No 的大小写！</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 <br>2 4 0 0 0 0 0 …… 0（一共 98 个 0） <br>2 4 2 0 0 0 0 …… 0（一共 97 个 0） <br>2 3 2 0 0 0 0 …… 0（一共 97 个 0）</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Yes <br>Yes <br>No</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见题面</p>
</div>
</div>