<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">南方神秘的长沙州长郡山庄庄主、伟大的tya在设计了谭氏矩形、拯救了世界之后，本以为世界就此会安宁。但是，总是有一些隐藏在黑暗之中的势力会破坏着tya辛辛苦苦维护的稳定与秩序。tya无可奈何，有心扼杀这些势力却无法把他们从黑暗之中彻底的消除。</span></p><p><span style="">tya在翻阅了未来科技高手tbh和sz所留下的、未来关于现在的历史的记录,tya发现了维护世界的和平的<em><strong>唯一办法——召唤Lulu</strong></em>。</span></p><p><span style="">但是和平岂是那么容易实现?要想<strong><em>召唤Lulu必须收集足够多的JR之力</em></strong>。但是JR是一种很奇怪的生物，只有了解JR的生长规律才能够收集JR之力。</span></p><p><span style="">tya把若干JR放在一根长度无限的数轴的n个位置上。</span></p><p><span style="">每经过一天，JR就会一分为二。若某JR的坐标为x，则新的JR分别产生在x-1和x+1的位置上，然后x位置的JR消失。 </span></p><p><span style="">然而，tya的法力也并非无穷，只能够在每一个位置上维护一定数量的JR生长，<em><strong>若一个位置上有≥P JR，将立刻消失P JR</strong></em>。经过测定，<strong><em>P = 10^9 + 7</em></strong>。 </span></p><p><span style="">tya不可能随时随地守护着JR，但是为了能够召唤出Lulu，他必须随时了解JR的情况。于是，tya在南方神秘的长沙州长郡山庄——他自己的山庄，找到了闭关的东方隐士cjj，希望cjj能够出山给予他帮助。</span></p><p><span style="">然而cjj沉迷于学习无法自拔，成为了Study Father，这种简单的工作自然不屑于做。<em><strong>cjj没有恼怒，但是他离开了。</strong></em>cjj自己做，但是希望你能够帮助他——帮助cjj完成伟大的救世主——tya的任务，告诉他在第T天的位置w上有多少JR。(最初是第0天)。</span></p><p><span style="">当然，cjj自然会鼓励你<strong><em>“这个任务一点也不难，只比周末卷难一点点”</em></strong></span></p><p><br></p><p>PS：别管是谁出的，反正不是Anger</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行三个正整数n、T、w。 </span></p><p><span style="">接下来n行，每行两个数Xi、Ci，表示位置Xi上最初有Ci JR。<em> <strong>(</strong><strong>若Xi有重复出现，则该位置上的JR初始化要累计)</strong></em></span></p><p><br></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: 16px;">第一行一个数Ans，表示第T天位置w上有多少只JR。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">2 2 2<br></span></p><p><span style="">0 3</span></p><p><span style="">1 2</span></p>

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
<p><span style="">样例解释 </span></p><p><span style="">(坐标) -1 -2 0 1 2 3 </span></p><p><span style="">第0天：0 0 3 2 0 0 </span></p><p><span style="">第1天：0 3 2 3 2 0 </span></p><p><span style="">第2天：3 2 6 4 3 2</span></p><p><br></p><p><span style=""><em><strong>数据范围 </strong></em></span></p><p><span style=""><em><strong>对于40%的数据，n、T、|w|≤10^3。 </strong></em></span></p><p><span style=""><em><strong>对于100%的数据，n、T、|w|≤10^5，|Xi|≤T，0＜Ci≤10^5。</strong></em></span></p><p><br></p>
</div>
</div>