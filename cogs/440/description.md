# 题目描述


<div style="text-indent: 24pt;">
<p>【问题描述】</p>
<p>在XOI总部，有一只由C.H养的耗子，这一只耗子拥有超过一般耗子的智商，而且很听话，所有XOI的人都叫它“WM”意思为聪明的耗子。而XOI总部有另一名成员X.J.H养的一只大猫，这只猫是一个捕鼠能手，名字叫“UC”。有一天C.H．和X.J.H打赌，C.H认为W.M可以逃脱U.C的追捕，X.J.H很不服气，他认为W.M是逃不过U.C的追捕。</p>
<p>他们就在XOI总部做了一个实验来判断，XOI总部的地形有点奇怪，如下图所示，</p>
<p><img width="188" height="187" alt="" src="http://192.168.1.252/os/sj/gdoi/gdoisearch/mouse/image001.gif"/></p>
<p>每一间工作室只有三条通路，而且某一些路是非常不好走的，通过的时间较长，因为那里放满了杂物，通过其余通路的用时是一样的，U.C可以以最快的速度从第一间工作室，通过所有的工作室再回到第一间工作室，而且每一间工作室只能进一次。如果W.M也可以在最短的时间内通过则U.C就算输了。事实上W.M办到了。</p>
<p>请问它是如何办到的?</p>
<p>【输入格式】<br/>
 </p>
<p>输入文件的第一行为数字3&lt;n≤80。n为工作室的个数，接下的3n/2行为a,b,c表示为从a工作室到b工作室有通道。c为0时通道为好走的通道，为1时是难走的通道。<br/>
 </p>
<p>【输出格式】</p>
<p>输出文件为耗子依次通过工作室的编号。</p>
<p><br/>
【输入输出样例】</p>
<p>样例输入:（mouse.in）</p>
<p>8<br/>
1 3 0<br/>
3 2 0<br/>
7 3 1<br/>
7 2 0<br/>
8 7 0<br/>
1 8 0<br/>
6 8 0<br/>
6 4 0<br/>
6 5 1<br/>
5 4 0<br/>
<br/>
样例输出（mouse.out）：</p>
<p>1 5 4 6 8 7 2 3</p>
<p><br/>
 </p>
</div>
