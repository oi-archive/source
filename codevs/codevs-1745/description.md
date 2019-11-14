<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>P城是M国的著名旅游城市。在市长G先生的治理下，人民安居乐业，城市欣欣向荣。然而，G市长并没有被自己的政绩冲昏头脑，他清醒地意识到城市的治理还存在着一些问题，其中之一就是交通问题。</p>
<p>P城有<em>m</em>条横向街道和<em>n</em>条纵向街道，横向街道横贯东西，纵向街道纵穿南北，构成了P城整齐的交通网络（如图1所示）。</p>
<p>由于街道狭窄，每条街道都只允许单向行驶，单向行驶的方向是事先设定好了的。一条横向街道的行驶方向只能是向东或者向西，一条纵向街道的行驶方向只能是向南或者向北，逆向行驶是绝对禁止的。</p>
<p>这项限制给交通带来了巨大的不便。如图1，很多游人希望从宾馆前往购物中心，但限于街道的行驶方向，他们不得不绕一个大圈才能够到达。</p>
<p>这个问题一直困扰着G市长，每天他都会收到不少游人的来信，抱怨P城不合理的交通设计。但由于街道数目过多，他和他的部下始终不能解决这个问题……</p>
<p>令人高兴的是这个问题不久就可能得以解决。因为最近他们以重金聘请了著名的交通规划大师B先生，请他对P城的交通进行有效合理的改造。</p>
<p>B先生知道不能通过拓宽街道的方法解决问题，因为这样势必影响到街道两旁的旅游景点，这是大家都不希望看到的。于是他准备重新设计街道的行驶方向（整条街道的行驶方向），使之尽可能满足大家的要求。</p>
<p>B先生先把P城的街道编号，横向街道由北向南编号为1，2，……，<em>m</em>，纵向街道由西向东编号为1，2，……，<em>n</em>。这样任何一个十字路口的位置都可以用一对正整数来表示，第一个数是该路口所在的横向街道的编号，第二个数是它所在的纵向街道的编号，这对整数被称为该十字路口的坐标。比如图1中宾馆所在的十字路口的坐标是(2,3)。</p>
<p>经过长期调查，他整理出了游人们提得相对集中的一些要求。每条要求都可以写成如下的形式：从一个十字路口到另一个十字路口的最短路</p>
<p>径的长度必须等于它们之间的曼哈顿距离。所谓曼哈顿距离是指两个十字路口在东西方向上的距离加上在南北方向上的距离，坐标分别为(<em>x</em>1,<em>y</em>1)和(<em>x</em>2,<em>y</em>2)的两个十字路口之间的曼哈顿距离为|<em>x</em>1-<em>x</em>2|+|<em>y</em>1-<em>y</em>2|。</p>
<p>好了，B先生已经知道了P城目前所有街道的行驶方向和游人们提得相对集中的要求，他能不能重新设计街道的行驶方向，使之满足所有要求呢？</p>
<p>另外，改变每条街道的行驶方向都有一定的工作量，工作量的大小因道路而异。B先生不仅想找到一个可行的改造计划，而且还希望这个计划的总工作量尽可能小。你能帮帮他吗？</p>

<img src="/source/codevs/codevs-1745/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNzQ1L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTc0NS5wbmc=.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行有两个正整数<em>m</em>和<em>n</em>，分别表示横向街道和纵向街道的数目。</p>
<p>第二行是一个长度为<em>m</em>的字符串，由北向南列出了<em>m</em>条横向街道改造前的行驶方向。E表示向东，W表示向西。</p>
<p>第三行是一个长度为<em>n</em>的字符串，由西向东列出了<em>n</em>条纵向街道改造前的行驶方向。S表示向南，N表示向北。</p>
<p>第四行有<em>m</em>个非负整数，由北向南列出了改变每条横向街道的行驶方向的工作量。</p>
<p>第五行有<em>n</em>个非负整数，由西向东列出了改变每条纵向街道的行驶方向的工作量。</p>
<p>第六行是一个正整数<em>k</em>，表示游人们提得相对集中的要求的数目。</p>
<p>接下来的<em>k</em>行，每行有四个正整数<em>x</em>1，<em>y</em>1，<em>x</em>2，<em>y</em>2，表示一条要求。这条要求的内容是希望从坐标为(<em>x</em>1,<em>y</em>1)的十字路口到坐标为(<em>x</em>2,<em>y</em>2)的十字路口的最短路径的长度等于这两个路口之间的曼哈顿距离。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行是一个字符串，&ldquo;possible&rdquo;或者&ldquo;impossible&rdquo;（引号不输出）。输出&ldquo;possible&rdquo;表示可以通过改变街道的行驶方向满足输入数据中的所有要求，输出&ldquo;impossible&rdquo;表示无论怎么设计都不可能满足输入数据中的所有要求。</p>
<p>如果在第一行输出的是&ldquo;possible&rdquo;的话，在第二行输出一个整数，表示最小的总工作量，在第三行输出一个长度为<em>m</em>的字符串，由北向南列出改造后的<em>m</em>条横向街道的行驶方向，E表示向东，W表示向西，在第四行输出一个长度为<em>n</em>的字符串，由西向东列出改造后的<em>n</em>条纵向街道的行驶方向， S表示向南，N表示向北。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 3</p>
<p>WE</p>
<p>NNS</p>
<p>3 9</p>
<p>1 4 2</p>
<p>2</p>
<p>1 3 2 1</p>
<p>2 3 2 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>possible</p>
<p>9</p>
<p>WW</p>
<p>NNS</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>m≤10</p>
<p>n，k≤100</p>
<p>改变一条街道的行驶方向的工作量不超过10000</p>
</div>
</div>