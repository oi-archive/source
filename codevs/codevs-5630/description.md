<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小胖子许海涛由于体重超标，妈妈禁止他吃零食。</p><p><br></p><p>但是今天是朱昊生日，所以他妈妈破一次例，可以让他选一些零食购买。超市有减价的活动：每种零食都有编号，零食一律10000脑残币一包（你没有看错，钱以脑残币为单位），零食分成两种，A和B。有些A零食和B零食之间有减价关系，就可以减掉V[i]厘。一共有T种减价关系。</p><p><br></p><p>于是小胖子许海涛选了N包A零食和M包B零食。但他算不出最少要花多少钱了（可能是超市要考他的智商吧），他的智商不足，于是他只好向你求助，让你写个程序帮他算算他要买这些零食最少要花多少钱。</p><p><br></p><p>注：A零食和B零食可以任意选，只要满足A零食总量为N，B零食总量为M即可。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行为 T，表示测试数据的组数，对于每组测试数据的格式如下：</p><p>第 1 行包括 3 个整数， N， M 和 R；意义如题目描述，</p><p>接下来的 R 行 包括 Xi， Yi， Vi 表示如果买了编号为 Xi 的A零食，再买编号为 Yi 的B零食能省 Vi 脑残币。</p><p>（同样如果买了编号为 Yi 的A零食，再买编号为 Xi 的B零食也能省 Vi 脑残币）</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件共 T 行，每行一个整数，即每组数据的最少花费是多少；<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p><p>5 5 8</p><p>4 3 6831</p><p>1 3 4583</p><p>0 0 6592</p><p>0 1 3063</p><p>3 3 4975</p><p>1 3 2049</p><p>4 2 2104</p><p>2 2 781</p><p>5 5 10</p><p>2 4 9820</p><p>3 2 6236</p><p>3 1 8864</p><p>2 4 8326</p><p>2 0 5156</p><p>2 0 1463</p><p>4 1 2439</p><p>0 4 4373</p><p>3 4 8889</p><p>2 4 3133</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>71071<br></p><p>54223</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 20%的数据： 1≤T≤1； 1≤N,M≤10； 1≤R≤10；</p><p>对于 40%的数据： 1≤T≤2； 1≤N,M≤20； 1≤R≤100；</p><p>对于 100%的数据： 1≤T≤5； 1≤N,M≤10,000； 1≤R≤50,000； 0≤Xi&lt;N； 0≤Yi&lt;M； 0≤Vi≤10,000；</p><p><br></p>
</div>
</div>