<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">大神Mz有一块很大很大的区域，可以看作无限大，这块区域被分割成无数行、无数列的方格，每个方格都对应着一个整数坐标x,y（类似于平面直角坐标系，因而坐标也不一定是正数）。</span></p><p style=""><span style="">HR妹子是大神Mz的忠实粉丝，会有很多很多HR妹子来拜访大神Mz的区域，大神Mz当然会很excited。有时也会有一些HR妹子离开。对于Mz来说，在某时某个方格的愉悦度是这样定义的：如果该处没有HR妹子，那么愉悦度为周围八个方格中，有HR妹子的方格的数量（大神Mz当然希望周围有很多HR妹子，这样大神Mz就能为所欲为了）；<span style="">如果该处有HR妹子，那么愉悦度为0（方格实在太小，待不下两个人）</span>。</span></p><p style=""><span style="">对于某方格的周围八个方格是这样定义的：如果该方格坐标为x,y，则其周围八个方格的坐标分别为</span><span style="">x-1,y-1；x-1,y；x-1,y+1；x,y-1；x,y+1；x+1,y-1；x+1,y；x+1,y+1。</span><span style=""></span></p><p style=""><span style="">大神Mz在某时刻的总愉悦度就是该时刻所有方格的愉悦度之和。开始的时候，没有一个HR妹子在大神Mz的区域里，显然此时的总愉悦度会是0。接下来会有若干次修改与询问，每次修改提供一对坐标x,</span><span style="">y，如果该坐标方格里还没有HR妹子，那么有一个HR妹子会来到这里；否则即已经有了HR妹子，那么这个HR妹子会离开。询问操作则以两个0代替之，你需要输出此时大神Mz的总愉悦度。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行，一个正整数n，表示修改和询问的总次数。</span></p><p style=""><span style="">接下来n行，每行两个非负整数x和y：如果x和y的值均为</span><span style="">0</span><span style="">，则表示询问；否则x和y一定均为正整数，表示对坐标为x,y的方格进行修改。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(88, 102, 110); font-family: 宋体; font-size: 14px; line-height: 20px; background-color: rgb(255, 255, 255);">若干行，行数应该等于输入文件中询问的次数，每行仅有一个非负整数，代表你的回答。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">5</span></p><p style=""><span style="">1 1</span></p><p style=""><span style="">1 2</span></p><p style=""><span style="">0 0</span></p><p style=""><span style="">1 2</span></p><p style=""><span style="">0 0</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">14</span></p><p style=""><span style="">8</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一次询问时，各个方格的愉悦度如下：</span></p><p style=""><span style="">（以下描述包含坐标中的x或y为0的方格）</span></p><p style=""><span style="">1221</span></p><p style=""><span style="">1001</span></p><p style=""><span style="">1221</span></p><p><span style="">对于20%的数据，n&lt;=100。对于20%的数据，x,y&lt;=1000。</span></p><p><span style="">对于100%的数据，n&lt;=20,000，x,y&lt;=1,000,000,000。</span></p><p><br></p>
</div>
</div>