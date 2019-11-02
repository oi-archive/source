<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">      雄心勃勃的企业家达伦·克劳斯发现了皮姆博士有关缩小原子间距离的公式并研发出新一代微型“黄蜂战士”，皮姆博士担忧武器会引发不可挽回的后果，于是找到斯科特并使他成为了新一代“蚁人”。正逢克劳斯与外商交易黄蜂战衣的那天，斯科特受命前往摧毁黄蜂战衣并销毁数据，然而一个人的力量是渺小的，斯科特需要走入一个巨大的蚁穴去召唤蚂蚁与他共同作战。</span></p><p><span style="">      蚁穴是一个巨大复杂的地带，由n行m列组成，每个偶数行存在至少一个蚂蚁聚集地，同一行的不同蚂蚁聚集地以一堵墙隔开，每个蚂蚁聚集地的大小为Si；每个奇数行存在连接相邻偶数行中蚂蚁聚集地的路径，一个蚂蚁聚集地可能有多条路径可以到达。</span></p><p><span style="">      蚁人可从蚁穴的第一行任何一路口出发，由于时间紧迫，<strong>蚁人只能向下一行走</strong>，在这种情况下，蚁人希望你能告诉他如何使经过的蚂蚁聚集地大小之和最大，从而召唤最多的蚂蚁。</span></p><p><span style=""><br></span><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行包含两个用空格隔开的整数n，m，意义见描述。</span></p><p style=""><span style="">第2到n+1行，每行m个字符（无间隔）且仅存在0和1：同一偶数行中连续x个0组成一个大小为x的蚂蚁聚集地，1为墙体；奇数行中0表示蚁人可以从此处通过。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-align:left"><span style="font-family: 宋体; font-size: 14px; ">对于每组数据输出一个整数，表示经过路径中最大聚集地之和（不包含聚集地之间的路径）。若蚁人无法到达最后一行则请输出“-1”。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">10 10</span></p><p style=""><span style="">1111101111</span></p><p style=""><span style="">1100001011</span></p><p style=""><span style="">1101111111</span></p><p style=""><span style="">1100000101</span></p><p style=""><span style="">1110110111</span></p><p style=""><span style="">1000110001</span></p><p style=""><span style="">1101111011</span></p><p style=""><span style="">1101000011</span></p><p style=""><span style="">1101011111</span></p><p style=""><span style="">1101010001</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">17<span style=""></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">对于20%的数据，</span><span style="font-family: Arial;">n≤20,m≤20</span></p><p style=""><span style="font-family: Arial;"> </span></p><p style=""><span style="">对于50%的数据，</span><span style="font-family: Arial;">n≤20,m≤100</span></p><p style=""><span style=""> </span></p><p style=""><span style="">对于100%的数据，</span><span style="font-family: Arial;">n≤5000,m≤2000</span><span style="">，保证n是一个偶数，路径的数量不多于</span><span style="font-family: Arial;">1×10</span><span style=""><sup><span style="font-family: Arial;">6</span></sup></span></p><p><br></p>
</div>
</div>