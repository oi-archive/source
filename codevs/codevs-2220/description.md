<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>吉儿是一家古董店的老板娘，由于她经营有道，小店开得红红火火。昨天，吉儿无意之中得到了散落民间几百年的珍宝—月亮之眼。吉儿深知“月亮之眼”价值连城：它是由许多珍珠相连而成的，工匠们用金线连接珍珠，每根金线连接两个珍珠；同时又对每根金线染上两种颜色，一半染成银白色，一半染成黛黑色。由于吉儿自小熟读古籍，所以还晓得“月亮之眼”的神秘传说：“月亮之眼”原是一个古代寺庙的宝物，原本是挂在佛堂的一根顶梁柱上的，整个宝物垂直悬挂，所有珍珠排成一线，且都镶嵌在柱子里，而每一根金线又都是绷紧的，并且金线的银白色一端始终在黛黑色一端的上方；然而，在一个月圆之夜，“月亮之眼”突然从柱里飞出，掉落下来，宝物本身完好无损，只是僧侣们再也无法以原样把“月亮之眼”嵌入柱子中了。吉儿望着这个神秘的宝物，回忆着童年读到的传说，顿时萌发出恢复“月亮之眼”的冲动，但是摆弄了几天依旧没有成功。</p>
<p>现在，要麻烦您来帮助吉儿完成这项使命。</p>
<p>您要设计一个程序，对于给定的“月亮之眼”进行周密分析，然后给出这串宝物几百年前嵌在佛堂顶梁柱上的排列模样。给定的“月亮之眼”有N个珍珠和P根金线，所有珍珠按一定顺序有了一个序号：1、2…、N。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入数据包含一个“月亮之眼”的特征描述：</p>
<p>文件第一行有两个整数N和P，其中N表示宝物中的珍珠个数，P表示宝物中的金线根数；</p>
<p>以下P行描述珍珠连接情况：</p>
<p>文件第I+1行有三个整数，Ri1,Ri2,Li。其中Ri1表示第I根金线的银白色一端连接的珍珠序号；Ri2表示第I根金线的黛黑色一端连接的珍珠序号；Li表示第I根金线的长度。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>由于珍珠尺寸很小，所以几个珍珠可以同时镶嵌在一个位置上。</p>
<p>您的输出数据描述的是&ldquo;月亮之眼&rdquo;各个珍珠在顶梁柱上的位置，输出文件共N行：</p>
<p>第I行，一个整数S，它表示标号为I的珍珠在顶梁柱上距离最高位置珍珠的距离。</p>
<p>注意：若无解则输出仅一行，包含一个整数&ldquo;-1&rdquo;。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>9 9</p>
<p>1 2 3</p>
<p>2 3 5</p>
<p>2 7 1</p>
<p>4 5 4</p>
<p>5 6 1</p>
<p>5 9 1</p>
<p>6 7 1</p>
<p>7 8 3</p>
<p>9 8 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>5</p>
<p>10</p>
<p>0</p>
<p>4</p>
<p>5</p>
<p>6</p>
<p>9</p>
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=N&lt;=255</p>
</div>
</div>