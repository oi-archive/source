<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>帅气的作者将于今天下午作一次非常重要的演讲。不幸的是他不是一个非常爱整洁的人，他把自己演讲要用的幻灯片随便堆在了一起。因此，演讲之前他不得不去整理这些幻灯片。作为一个讲求效率的oier，他希望尽可能简单地完成它。帅气的作者这次演讲一共要用n张幻灯片（n&lt;=26），这n张幻灯片按照演讲要使用的顺序已经用数字1~n编了号。因为幻灯片是透明的，所以我们不能一下子看清每一个数字所对应的幻灯片。  　　现在我们用大写字母A,B,C……再次把幻灯片依次编号。你的任务是编写一个程序，把幻灯片的数字编号和字母编号对应起来，显然这种对应应该是唯一的；若出现多种对应的情况或是某些数字编号和字母编号对应不起来，我们称对应是无法实现的。   </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style=""><span style="">文件的第一行只有一个整数<strong>n</strong>，表示有</span><span style=""><strong>n</strong></span><span style="">张幻灯片，接下来的<strong>n</strong>行每行包括<strong>4</strong>个整数<strong>xmin,xmax,ymin,ymax</strong>（整数之间用空格分开）为幻灯片的坐标，这<strong>n</strong>张幻灯片按其在文件中出现的顺序从前到后依次编号为<strong>A,B,C……</strong>，再接下来的</span><span style=""><strong>n</strong></span><span style="">行依次为<strong>n</strong>个数字编号的坐标<strong>x,y</strong>，显然在幻灯片之外是不会有数</span></span><span style="">字的。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(0, 0, 0);">&nbsp;<span style="font-family: 黑体; font-size: 21px;">若是对应可以实现，输出文件应该包括</span><span style="font-size: 21px;"><strong>n</strong></span><span style="font-family: 黑体; font-size: 21px;">行，每一行为一个字母和一个数字，中间以一个空格隔开，并且每行以字母的升序排列，注意输出的字母要大写并且定格；反之，若是对应无法实现，在文件的第一行顶格输出<strong>None</strong>即可。首行末无多余的空格。 </span> &nbsp;</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style=""> <span style=""><strong>4 </strong></span></span></p><p><span style=""> <span style=""><strong>6 22 10 20 </strong></span></span></p><p><span style=""><span style=""></span> <span style=""><strong>4 18 6 16 </strong></span></span></p><p><span style=""><span style=""></span> <span style=""><strong>8 20 2 18 </strong></span></span></p><p><span style=""><span style=""></span> <span style=""><strong>10 24 4 8 </strong></span></span></p><p><span style=""><span style=""></span> <span style=""><strong>9 15 </strong></span></span></p><p><span style=""><span style=""></span> <span style=""><strong>19 17 </strong></span></span></p><p><span style=""><span style=""></span> <span style=""><strong>11 7 </strong></span></span></p><p><span style=""><span style=""></span> <span style=""><strong>21 11</strong></span><span style=""><strong> </strong></span>  </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style=""> <span style=""><strong>A 4</strong></span></span></p><p><span style=""><span style=""><strong> </strong></span> <span style=""><strong>B 1 </strong></span></span></p><p><span style=""><span style=""></span> <span style=""><strong>C 2</strong></span></span></p><p><span style=""><span style=""><strong> </strong></span> <span style=""><strong>D 3</strong></span><span style=""><strong> </strong></span>  </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>非常小，暴力吧</p>
</div>
</div>