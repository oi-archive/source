<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>潘塔纳尔沼泽地号称世界上最大的一块湿地，它地位于巴西中部马托格罗索州的南部地区。每当雨季来临，这里碧波荡漾、生机盎然，引来不少游客。</p>
<p>为了让游玩更有情趣，人们在池塘的中央建设了几座石墩和石桥，每座石桥连接着两座石墩，且每两座石墩之间至多只有一座石桥。这个景点造好之后一直没敢对外开放，原因是池塘里有不少危险的食人鱼。</p>
<p>豆豆先生酷爱冒险，他一听说这个消息，立马赶到了池塘，想做第一个在桥上旅游的人。虽说豆豆爱冒险，但也不敢拿自己的性命开玩笑，于是他开始了仔细的实地勘察，并得到了一些惊人的结论：食人鱼的行进路线有周期性，这个周期只可能是2，3或者4个单位时间。每个单位时间里，食人鱼可以从一个石墩游到另一个石墩。每到一个石墩，如果上面有人它就会实施攻击，否则继续它的周期运动。如果没有到石墩，它是不会攻击人的。</p>
<p>借助先进的仪器，豆豆很快就摸清了所有食人鱼的运动规律，他要开始设计自己的行动路线了。每个单位时间里，他只可以沿着石桥从一个石墩走到另一个石墩，而不可以停在某座石墩上不动，因为站着不动还会有其它危险。如果豆豆和某条食人鱼在同一时刻到达了某座石墩，就会遭到食人鱼的袭击，他当然不希望发生这样的事情。</p>
<p>现在豆豆已经选好了两座石墩Start和End，他想从Start出发，经过K个单位时间后恰好站在石墩End上。假设石墩可以重复经过（包括Start和End），他想请你帮忙算算，这样的路线共有多少种（当然不能遭到食人鱼的攻击</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件共M + 2 + NFish行。</p>
<p>第一行包含五个正整数N，M，Start，End和K，分别表示石墩数目、石桥数目、Start石墩和End石墩的编号和一条路线所需的单位时间。石墩用0到N–1的整数编号。</p>
<p>第2到M + 1行，给出石桥的相关信息。每行两个整数x和y，0 ≤ x, y ≤ N–1，表示这座石桥连接着编号为x和y的两座石墩。</p>
<p>第M + 2行是一个整数NFish，表示食人鱼的数目。</p>
<p>第M + 3到M + 2 + NFish行，每行给出一条食人鱼的相关信息。每行的第一个整数是T，T = 2，3或4，表示食人鱼的运动周期。接下来有T个数，表示一个周期内食人鱼的行进路线。</p>
<ul>
<li>如果T＝2，接下来有2个数P<sub>0</sub>和P<sub>1</sub>，食人鱼从P<sub>0</sub>到P<sub>1</sub>，从P<sub>1</sub>到P<sub>0</sub>，……；</li>
<li>如果T＝3，接下来有3个数P<sub>0</sub>，P<sub>1</sub>和P<sub>2</sub>，食人鱼从P<sub>0</sub>到P<sub>1</sub>，从P<sub>1</sub>到P<sub>2</sub>，从P<sub>2</sub>到P<sub>0</sub>，……；</li>
<li>如果T＝4，接下来有4个数P<sub>0</sub>，P<sub>1</sub>，P<sub>2</sub>和P<sub>3</sub>，食人鱼从P<sub>0</sub>到P<sub>1</sub>，从P<sub>1</sub>到P<sub>2</sub>，从P<sub>2</sub>到P<sub>3</sub>，从P<sub>3</sub>到P<sub>0</sub>，……。</li>
</ul>
<p>豆豆出发的时候所有食人鱼都在自己路线上的P<sub>0</sub>位置，请放心，这个位置不会是Start石墩。</p>
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

<p>输出路线的种数，因为这个数可能很大，你只要输出该数除以10000的余数就行了。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 8 1 5 3</p>
<p>0 2</p>
<p>2 1</p>
<p>1 0</p>
<p>0 5</p>
<p>5 1</p>
<p>1 4</p>
<p>4 3</p>
<p>3 5</p>
<p>1</p>
<p>3 0 5 1</p>

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

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<ul>
<li>1 ≤ N ≤ 50</li>
<li>1 ≤ K ≤ 2,000,000,000</li>
<li>1 ≤ NFish ≤ 20</li>
</ul>
</div>
</div>