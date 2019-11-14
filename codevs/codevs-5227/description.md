<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>   丛林中共有n 棵果树，每一棵果树上都有数量不等的果实。果树之间有单向边连接。你提着一个篮子从编号为1的果树出发，选择一条路径走到编号为n
的果树。每当你走到一棵果树的时候，你都会将这棵果树的所有果实采摘下来，放入篮子中，假设这个过程是不花费任何时间的。而当你在路上行走的时候，每走1分钟，你都会从篮子中拿出一个果实吃掉（如果篮子里还有果实的话）。<br><br>　　你的任务是求出你所携带的篮子至少要能够承担多少个果实的重量，才能够顺利地选择一条路径完成旅途，并且在途中不扔掉任何果实。（当到达第i棵果树时，还是要将这棵果树的全部果实放入篮子中）。  </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>   第一行为两个整数n和m，分别表示果树的个数与单向边的条数。所有的果树从1到n 编号。<br>　　接下来一行， n个用空格隔开的整数，分别表示编号1~n
的果树上果实的个数。<br>　　接下来m ，每行三个用空格隔开的整数 x,y,c，表示从x 到y 有一条单向边相连，这条边通过所需的时间为c （分钟）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>有且仅有一行，一个整数，表示篮子最少需要承担多少个果实的重量。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 4<br>5 7 6 4<br>1 2 3<br>1 3 3<br>2 4 100<br>3 4 1<br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>两颗不同树之间可能有多条边直接相连，但是没有一条边连接两颗相同的树。一定存在至少一条从树1到达树
的路径。每棵树上果实的数量，通过一条边所需的时间都是1~10000之间的整数。<br><br>　　对于30%的数据，n&lt;=10，m&lt;=20
。<br>　　对于60%的数据，n&lt;=100，m&lt;=300。<br>　　对于100%的数据，n&lt;=1000，m&lt;=5000。<br></p>
</div>
</div>