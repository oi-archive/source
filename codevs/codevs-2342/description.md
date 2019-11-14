<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>很久很久以前，在遥远的大陆上有一个美丽的国家。统治着这个美丽国家的国王是一个园艺爱好者，在他的皇家花园里种植着各种奇花异草。有一天国王漫步在花园里，若有所思，他问一个园丁道：</p>
<p>“最近我在思索一个问题，如果我们把花坛摆成六个六角形，那么……”</p>
<p>“那么本质上它是一个深度优先搜索，陛下”，园丁深深地向国王鞠了一躬。</p>
<p>“嗯……我听说有一种怪物叫九头蛇，它非常贪吃苹果树……”</p>
<p>“是的，显然这是一道经典的动态规划题，早在N元4002年我们就已经发现了其中的奥秘了，陛下”。</p>
<p>“该死的，你究竟是什么来头？”</p>
<p>“陛下息怒，干我们的这行经常莫名其妙地被问到和OI有关的题目，我也是为了预防万一啊！”</p>
<p>王者的尊严受到了伤害，这是不可容忍的。看来一般的难题是难不倒这位园丁的，国王最后打算用车轮战来消耗他的实力：</p>
<p>“年轻人，在我的花园里的每一棵树可以用一个整数坐标来表示，一会儿，我的骑士们会来轮番询问你某一个矩阵内有多少树，如果你不能立即答对，你就准备走人吧！”说完，国王气呼呼地先走了。</p>
<p>这下轮到园丁傻眼了，他没有准备过这样的问题。所幸的是，作为“全国园丁保护联盟”的会长——你，可以成为他的最后一根救命稻草。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>文件的第一行有两个整数n，m（0≤n≤500000，1≤m≤500000）。n代表皇家花园的树木的总数，m代表骑士们询问的次数。</p>
<p>文件接下来的n行，每行都有两个整数xi，yi，代表第i棵树的坐标（0≤xi，yi≤10000000）。</p>
<p>文件的最后m行，每行都有四个整数aj，bj，cj，dj，表示第j次询问，其中所问的矩形以（aj，bj）为左下坐标，以（cj，dj）为右上坐标。</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共输出m行，每行一个整数，即回答国王以（aj，bj）和（cj，dj）为界的矩形里有多少棵树。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 1</p>
<p>0 0</p>
<p>0 1</p>
<p>1 0</p>
<p>0 0 1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>0≤n≤500000，1≤m≤500000</p>
</div>
</div>