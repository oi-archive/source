<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>[HAOI2008] 排名系统 &amp; [ZJOI2006] GameZ游戏排名系统：</span></p>
<p><span>　　GameZ为他们最新推出的游戏开通了一个网站。世界各地的玩家都可以将自己的游戏得分上传到网站上。这样就可以看到自己在世界上的排名。得分越高，排名就越靠前。当两个玩家的名次相同时，先上传记录者优先。由于新游戏的火爆，网站服务器已经难堪重负。为此GameZ雇用了你来帮他们重新开发一套新的核心。 排名系统通常要应付三种请求：上传一条新的得分记录、查询某个玩家的当前排名以及返回某个区段内的排名记录。当某个玩家上传自己最新的得分记录时，他原有的得分记录会被删除。为了减轻服务器负担，在返回某个区段内的排名记录时，最多返回10条记录。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　第一行是一个整数n（n&gt;=10）表示请求总数目。<br>　　接下来n行每行包含了一个请求。请求的具体格式如下：<br>　　　　<strong>+Name Score</strong> 上传最新得分记录。Name表示玩家名字，由大写英文字母组成，不超过10个字符。Score为<span style="text-decoration: underline;">不超过无符号32位整型</span>表示范围的<span style="text-decoration: underline;">非负</span>整数。<br>　　　　<strong>?Name</strong> 查询玩家排名。该玩家的得分记录必定已经在前面上传。<br>　　　　<strong>?Index</strong> 返回自第Index名开始的最多10名玩家名字。Index必定合法，即不小于1，也不大于当前有记录的玩家总数。<br>　　输入数据大小不超过2M。<br>　　NOTE：用C++的fstream读大规模数据的效率较低。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　对于每条查询请求，输出相应结果。对于?Name格式的请求，应输出一个整数表示该玩家当前的排名。对于?Index格式的请求，应在一行中依次输出从第Index名开始的最多10名玩家姓名，用一个空格分隔。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>20<br>+ADAM 1000000<br>+BOB 1000000<br>+TOM 2000000<br>+CATHY 10000000<br>?TOM<br>?1<br>+DAM 100000<br>+BOB 1200000<br>+ADAM 900000<br>+FRANK 12340000<br>+LEO 9000000<br>+KAINE 9000000<br>+GRACE 8000000<br>+WALT 9000000<br>+SANDY 8000000<br>+MICK 9000000<br>+JACK 7320000<br>?2<br>?5<br>?KAINE</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>2</span><br><span> CATHY TOM ADAM BOB</span><br><span> CATHY LEO KAINE WALT MICK GRACE SANDY JACK TOM BOB</span><br><span> WALT MICK GRACE SANDY JACK TOM BOB ADAM DAM</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例解释】<br>20<br>+ADAM 1000000 加入ADAM的得分记录<br>+BOB 1000000 加入BOB的得分记录<br>+TOM 2000000 加入TOM的得分记录<br>+CATHY 10000000 加入CATHY的得分记录<br>?TOM 输出TOM目前排名<br>?1 目前有记录的玩家总数为4，因此应输出第1名到第4名。<br>+DAM 100000 加入DAM的得分记录<br>+BOB 1200000 更新BOB的得分记录<br>+ADAM 900000 更新ADAM的得分记录（即使比原来的差）<br>+FRANK 12340000 加入FRANK的得分记录<br>+LEO 9000000 加入LEO的得分记录<br>+KAINE 9000000 加入KAINE的得分记录<br>+GRACE 8000000 加入GRACE的得分记录<br>+WALT 9000000 加入WALT的得分记录<br>+SANDY 8000000 加入SANDY的得分记录<br>+MICK 9000000 加入MICK的得分记录<br>+JACK 7320000 加入JACK的得分记录<br>?2 目前有记录的玩家总数为12，因此应输出第2名到第11名。<br>?5 输出第5名到第13名。<br>?KAINE 输出KAINE的排名</p>
<p><br>【数据范围】<br>　　20%数据满足N&lt;=100<br>　　100%数据满足N&lt;=250000</p>
</div>
</div>