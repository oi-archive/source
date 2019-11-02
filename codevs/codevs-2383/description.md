<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在歌唱王国，所有人的名字都是一个非空的仅包含整数1~n 的字符串。 <br>王国里生活着一大群咕噜兵，他们靠不停的歌唱首领——牛人酋长们的名字<br>来获取力量。咕噜兵每一次歌唱过程是这样的： <br>首先，他从整数生成器那儿获得一个数字，然后花一个时间单位将此数字唱<br>出来，如果他发现某个牛人酋长的名字已经被歌唱出来（即此名字是歌唱序列的<br>一个连续子串） ，那么这次歌唱过程就立即结束。 <br>相关名词定义 <br>歌唱序列：如果某人歌唱了 x 个数字，第 i 次歌唱的数字为 ai，那么歌<br>唱序列=(a1,a2,…,ax)。 <br>整数生成器：歌唱王国的神物，它有一个按钮，如果你按一下按钮，将<br>从 1~n 数字中等概率的随机返回一个整数。 <br>歌唱时间：在一次歌唱过程中花费的时间。 <br> <br>歌唱时间是随机的，无法预料；不过歌唱时间的期望值是固定的，此期望值<br>即平均来说歌唱时间有多长，亦可称作平均歌唱时间。 <br> <br>王国里的人非常喜欢歌唱，他们希望歌唱的时间越长越好，所以他们决定罢<br>免一些牛人酋长， 使得平均歌唱时间变长。 但是他们不能罢免掉所有的牛人酋长，<br>否则他们每次歌唱都无法停止，无法获取力量；于是他们决定只保留一个牛人酋<br>长而罢免其余的牛人酋长。 <br> <br>你的任务是：对于给定的n、牛人酋长的个数 t 以及每一个牛人酋长的名字，<br>告诉王国里的人们，对于 1≤i≤t，如果保留第 i 个牛人酋长，罢免掉其余的，那<br>么平均歌唱时间将是多少。 <br>提示：此数为一个非负整数！ <br>输出要求：由于这个数字太大，所以你只需输出这个数的末4 位数字。如果<br>不足 4 位，则前面补 0(见样例)。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，两个整数 n、t；以下 t 行描述 t 个牛人酋长名字。 <br>文件第 i+1(1≤i≤t)行格式如下 <br>第一个数为 mi表示第 i 个牛人酋长的名字的长度，在一个空格之后，接<br>下来有 mi 个数，用来描述这个牛人酋长的名字，相邻两个整数之间用一个空<br>格分开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第 2 页 共 7 页 <br /> 共 t 行，第 i 行为一个整数，表示若保留第 i 个牛人酋长而罢免其余的，则平均歌唱时间最长的末四位数字是多少。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1≤n≤105<br>，t≤50，1≤mi≤105<br>。 <br> 有 30%的数据满足 n≤103<br>，mi≤103 <br> <br>有 50%的数据满足 n≤104<br>，mi≤10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 2 <br> 1 1 <br> 3 1 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>0002 <br>0010</p>
</div>
</div>