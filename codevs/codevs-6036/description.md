<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 'comic sans ms';">Hjw是鳝变的.经常喜欢泡妹纸,搞妹纸，在学校搞后宫。这是其中一位受害人(已成Hjw的正宫)的头像：</span></p><p><img src="/source/codevs/codevs-6036/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy02MDM2L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvYmxvYl8yMDE3MDQyNTEzMjM1Nl8yNTgucG5n.png" title=""></p><p><span style="font-family: 'comic sans ms';">Hjw并不满足只搞一个妹纸.他有时候可能会让妹纸们在他面前跳舞，顺便选出新的后宫(当然不会是上面这位受害者),上面这位只会唱歌...</span></p><p><span style="font-family: 'comic sans ms';">Hjw想通过他这位正宫的歌喉来考验妹纸们.因为这位正宫怕一些敌对势力威胁到他的地位，所以她会给己方势力放水，而给敌方势力放毒(可能会唱lost rivers)</span></p><p><span style="font-family: 'comic sans ms';">但Hjw并不知情，他只会按照程序来选出妹纸。</span></p><p><span style="font-family: 'comic sans ms';">这些妹纸需要在一台巨大的跳舞机上跳舞，跳舞机上有四块踩板<span style="font-family: 'comic sans ms';"><span style="font-family: 'comic sans ms';">游戏者必须按照或这个序列一次用某一只脚踩相应的踏板。在任何时候，两只脚都不能在同一踏板上，但可以同时待在中心位置0。</span><br style=""><span style="font-family: 'comic sans ms';">　　每一个时刻，它必须移动而且只能移动他的一只脚去踩相应的箭头，而另一只脚不许移动。跳完一首曲子之后，妹纸会计算他所消耗的体力。从中心移动到任何一个箭头耗费2单位体力，从任何一个箭头移动到相邻箭头耗费3单位体力，移动到相对的箭头（1和3相对，2和4相对）耗费4单位体力，而留在原地再踩一下只需要1单位。妹纸应该怎样移动她的双脚（即，对于每个箭头，选一只脚去踩它），才能用最少的体力完成一首给定的舞曲呢？</span></span></span></p><p><span style="font-family: 'comic sans ms';"><span style="font-family: 'comic sans ms';"><span style="font-family: 'comic sans ms';">    妹纸们所用的体力将是Hjw选择后宫的biu准。所以他们肯定会用最佳的方案来跳。<br></span></span></span></p><p><span style="font-family: 'comic sans ms';"><span style="font-family: 'comic sans ms';"><span style="font-family: 'comic sans ms';">    所用体力最小的将会成为Hjw的新后宫。妹纸们泥萌准备好了吗<br></span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一个整数n 表示一共有n个妹纸</p><p>for(int i=1;i&lt;=n;i++){</p><p style="">一个整数a[i] 表示这n个妹纸所需要跳的时间长度<br></p><p style="">下面1行a[i]个数 表示某个时刻她应该踩在第几块板上</p><p style="">(不知道什么意思的话看数据就懂了。。。</p><p>}</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>i行，每行一个整数表示妹纸所费体力多少</p><p>最后一行，一个整数表示新正宫的编号</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2//2个妹纸</p><p>2//歌曲长度</p><p>1 1//第几个时刻应该踩在哪块板上</p><p>2</p><p>1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3<br></p><p>3</p><p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>100%的数据 n&lt;=1000 a[i]&lt;=10000 </p><p>因为只有四块板，离开中心后就不会回去了</p><p>题很水，但是需要加上线段树维护一下。。。不然很容易超时</p>
</div>
</div>