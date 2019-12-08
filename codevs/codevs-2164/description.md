<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Farmer John為了让自己从无穷无尽的犁田工作中解放出来，於是买了个新机器人帮助他犁田。这个机器人可以完成犁田的任务，可惜有一个小小的缺点：这个犁田机器人一次只能犁一个边的长度是整数的长方形的田地。</p>
<p>因為FJ的田地有树和其他障碍物，所以FJ设定机器人去犁很多不同的长方形。这些长方形允许重叠。他给机器人下了P个指令，每个指令包含一个要犁长方形的地。这片田地由长方形的左下角和右上角坐标决定。他很好奇最后到底有多少个方格的地被犁过了。</p>
<p>一般来说，田地被分割為很多小方格。这些方格的边和x轴或y轴平行。田地的宽度為X个方格，高度為Y个方格 . FJ执行了I (1 &lt;= I &lt;= 200)个指令，每个指令包含4个整数：Xll, Yll, Xur, Yur (1 &lt;= Xll &lt;=Xur; Xll &lt;= Xur &lt;=X; 1 &lt;= Yll &lt;= Yur; Yll &lt;= Yur &lt;= Y), 分别是要犁的长方形的左下角坐标和右上角坐标。机器人会犁所有的横坐标在Xll..Xur并且纵坐标Yll..Yur范围内的所有方格的地。可能这个长方形会比你想像的多一行一列（就是说从第Xll列到第Xur列一共有Xur - Xll + 1列而不是Xur - Xll列）。</p>
<p>考虑一个6方格宽4方格高的田地。FJ进行了2个操作（如下），田地就被成"*"和"#"了。虽然一般被犁过的地看起来都是一样的。但是标成"#"可以更清晰地看出最近一次被犁的长方形。</p>
<p>    ......                  **....                  #####.</p>
<p>    ......  (1,1)(2,4) **....  (1,3)(5,4) #####.</p>
<p>    ......                  **....                  **....</p>
<p>    ......                  **....                  **....</p>
<p><br>一共14个方格的地被犁过了。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>* 第一行: 三个由空格隔开的整数： X, Y, I</p>
<p>* 第二行到第I+1行：第i+1行有四个整数Xll, Yll, Xur, Yur，表示第i个指令。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行: 一个单独的整数表示被犁过的方格数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 4 2<br>1 1 2 4<br>1 3 5 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>14</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1 &lt;= X &lt;= 240; 1 &lt;= Y &lt;= 240</p>
</div>
</div>