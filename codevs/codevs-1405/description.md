<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>农民John的农场里有很多牧区。有的路径连接一些特定的牧区。一片所有连通的牧区称为一个牧场。但是就目前而言，你能看到至少有两个牧区通过任何路径都不连通。这样，农民John就有多个牧场了。 <br><br> John想在农场里添加一条路径(注意，恰好一条)。对这条路径有以下限制： <br><br> 一个牧场的直径就是牧场中最远的两个牧区的距离(本题中所提到的所有距离指的都是最短的距离)。考虑如下的有5个牧区的牧场，牧区用“*”表示，路径用直线表示。每一个牧区都有自己的坐标： <br><br> 　　　　　　 15,15 20,15<br> 　　　　　　　　 D　　 E<br> 　　　　　　　　 *-------*<br> 　　　　　　　　 |　　 _/|<br> 　　　　　　　　 | _/ |<br> 　　　　　　　　 | _/　　|<br> 　　　　　　　　 |/　　 |<br> 　　　　*--------*-------*<br> 　　　　A　　　　B　　 C<br> 　　　　10,10 15,10 20,10<br> 这个牧场的直径大约是12.07106, 最远的两个牧区是A和E，它们之间的最短路径是A-B-E。 <br><br> 这里是另一个牧场： <br><br> 　　　　　　　　　　　　 *F 30,15<br> 　　　　　　　　　　　　/ <br> 　　　　　　　　　　 _/ <br> 　　　　　　　　　　_/　　<br> 　　　　　　　　 /　　 <br> 　　　　　　　　 *------* <br> 　　　　　　　　 G　　 H<br> 　　　　　　　　 25,10 30,10<br> 这两个牧场都在John的农场上。John将会在两个牧场中各选一个牧区，然后用一条路径连起来，使得连通后这个新的更大的牧场有最小的直径。 <br><br> 注意，如果两条路径中途相交，我们不认为它们是连通的。只有两条路径在同一个牧区相交，我们才认为它们是连通的。 <br><br> 输入文件包括牧区、它们各自的坐标，还有一个如下的对称邻接矩阵： <br><br> 　 A B C D E F G H <br> A 0 1 0 0 0 0 0 0<br> B 1 0 1 1 1 0 0 0<br> C 0 1 0 0 1 0 0 0<br> D 0 1 0 0 1 0 0 0<br> E 0 1 1 1 0 0 0 0<br> F 0 0 0 0 0 0 1 0<br> G 0 0 0 0 0 1 0 1<br> H 0 0 0 0 0 0 1 0<br> 输入文件至少包括两个不连通的牧区。 <br><br> 请编程找出一条连接两个不同牧场的路径，使得连上这条路径后，这个更大的新牧场有最小的直径。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行: 一个整数N (1 &lt;= N &lt;= 150), 表示牧区数 <br><br> 第2到N+1行: 每行两个整数X,Y (0 &lt;= X ,Y&lt;= 100000), 表示N个牧区的坐标。注意每个 牧区的坐标都是不一样的。 <br><br> 第N+2行到第2*N+1行: 每行包括N个数字(0或1) 表示如上文描述的对称邻接矩阵。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>只有一行，包括一个实数，表示所求直径。数字保留六位小数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>8<br>10 10<br>15 10<br>20 10<br>15 15<br>20 15<br>30 15<br>25 10<br>30 10<br>01000000<br>10111000<br>01001000<br>01001000<br>01110000<br>00000010<br>00000101<br>00000010</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>22.071068</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1s</p>
</div>
</div>