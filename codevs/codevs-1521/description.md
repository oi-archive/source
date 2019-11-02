<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    著名的Microhardware公司即将迎来其创业50周年庆典，为了使这次庆典能够体面而又隆重，以显出公司在国际硬件的龙头地位，总裁决定举办一次交谊舞会，届时将有社会各界名流前来捧场，希望以此来提高本公司的名望。他将布置场地的任务交给了JYY，而JYY遇到了一个小小的问题——吊灯。<br><span style="">    在当前的经济环境下，JYY为了省钱，从一个不知名的小吊灯商那里购来一批吊灯，但是他发现并不能直接把这吊灯挂起来：只有一个吊灯能挂在天花板上，而其他所有的灯只能固定的挂在某一个别的吊灯上（可恶的奸商～…好在没有什么吊灯A只能挂在吊灯B上，而吊灯B却也只能挂在吊灯A上）。众所周知，每个吊灯都有其本身的重量，也有一定的承受能力（如果某一个下面吊的东西太多的话，那么Microhardware公司就得给舞者准备保险金和医疗金了），并且，不是所有的吊灯亮度都一样的。JYY希望能够选出其中的一些吊灯吊起来，每个灯下面所吊的都在其重力承受范围之内，且使所有灯的亮度之和最大，JYY要求你帮他解决这个问题（我不保证他会给你工钱，但是如果你不做的就会被公司解雇）。</span></p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入共包含n+1行：<br><span style="">第一行一个整数n（n≤400）。 以后的n行每行四个整数t、w、p、l，第i+1行的t（t&lt;i）表示第i盏灯只能吊在第t盏灯下面，w(0≤w≤200)表示第i盏灯的重量，p(p&lt;=200)表示第i盏灯所能吊起的最大重力,l(l≤10000)表示第i盏灯的亮度。<br></span><span style="">注意：第1盏灯的t=0。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出共包含2行：<br /><span style="font-size: 10px;">第一行两个整数m、maxl，m为所选中的吊灯的数量，maxl为最大的亮度。<br /></span><span style="font-size: 10px;">第二行共包含m个整数，分别为被选中的吊灯的编号，按升序输出，且每两个之间用空格隔开（末尾无多余空格）；如果问题有多解，只需输出其中的一种即可。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5<br><span style="">0 100 100 100<br></span><span style="">1 50 50 50<br></span><span style="">1 50 50 50<br></span><span style="">2 30 50 60<br></span><span style="">2 25 50 50</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3 210<br><span style="">1 2 4</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>