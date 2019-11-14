<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>中国的沿海城市的网速是比较快的，但是到了内陆就很慢了。KFC来到了内陆城市飞机场，虽然已经是大牛了，但是舍不得花钱买samsung和iPhone,还用着诺基亚的神机，自然手机不支持NFC，不过后来大神自己改装，让手机拥有了无线充电的功能，在飞机场遇到飞机延误，要等T个单位时间，周围也没有手机充电站，幸好在宾馆充好了电，可以玩一会儿。但是突然KFC的教父突然打电话说让他用手机下载一个东西，文件有一定大小M(kB),已经知道了现在的网速，但是事情没有那么简单。<br>他看到了飞机场的告示牌，有free-wifi，但是每个wifi是有一定时间的。他得知有N个wifi，每个wifi 有一个开始时间Si和终止时间Ti，只有在这一段时间之内才能使用此wifi。当然除了使用wifi之外，还可以使用3g，无流量限制，也没有时间限制，但是弊端就是，无法支持无线充电，有一个耗电量D(每个单位时间)，而wifi的耗电量由于无线充电的存在可以忽略不计，KFC在宾馆就已经充满了电，拥有电量R，现在可以知道，单位时间以1来计算，3g的网速为G(kB/单位时间),wifi的网速分别为Gi(kB/单位时间)。free-wifi当然是免费的，3g可就不是了，不过走之前神父已经给他冲了无限的元宝，足够用了，不必考虑。可以保证的是网络不会受到干扰，网速是恒定不变的，不会出现中途断网的情况。但是机场有个bt的要求，连接上某一个wifi之后不可以自行断掉，只会因为wifi自行的信号结束而断开，3g网络则可以随时选择连接上，也可以随时选择断开。<br>请问在飞机来临之前，大神KFC能不能下载完文件？<br>如果可以输出Yes(注意：Y要大写，后面没有多余的内容)<br>不可以则输出No和最大的文件下载大小(注意：N同样要大写)</p>
<p>注意：只有在电量不为0的时候，才可以下载文件；使用前一个网络的结束时间必须严格小于后一个网络的开始时间。不使用wifi和3g的时候耗电量忽略不计。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行6个整数，N,M,T,G,R,D，分别表示wifi个数，需要下载文件的大小，离开飞机场的时间，3g网络的网速，手机当前的电量以及使用wifi时每个单位时间内消耗的电量。<br>接下来N行，每行3个整数，Si Ti Gi，分别表示可以扫描到信号的开始时间，结束时间以及这个wifi在单位时间内可以下载的文件大小</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行，表示可以在T个单位时间之内，完成任务吗？如果不可以请再输出最大的下载大小为多少。(No和最大下载大小之间有1个空格，后面被不需要加kB之类的单位；如果答案为Yes,就不需要输出其他内容)</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 1 1 1 1 1</p>
<p>1 1 100</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Yes</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N&lt;=100,M&lt;=2<sup>31</sup>,T&lt;=100,R&lt;=100,G&lt;=M,Gi&lt;=M,1&lt;=Si&lt;Ti&lt;=M</p>
</div>
</div>