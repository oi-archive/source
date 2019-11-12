# 题目描述


<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">【题目描述】</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">有一个N*M的白色矩形。有两种操作。</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="margin-left:18.0000pt;text-indent:-18.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">1. </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">用一块黑布盖住矩形的一部分</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="margin-left:18.0000pt;text-indent:-18.0000pt;">
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">2. </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">把之前放入的某块黑布拿走</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">对于每次操作，输出当前矩形上黑布的面积</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">【输入格式】</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">第一行三个整数N，M，K表示矩形的面积N*M和操作次数K</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">之后K行，每行五个整数a，X1，Y1，X2，Y2</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">a表示操作类型，1表示放入黑布，2表示拿走黑布</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">X1，Y1，X2，Y2表示黑布的左上角坐标和右下角坐标</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">【输出格式】</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">共K行，第i行表示第i次操作后矩形上黑布的面积</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">【输入样例】</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">3 4 4</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">1 1 2 2 4</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">1 2 2 3 3</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">2 1 2 2 4</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">1 2 1 3 4</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">【输出样例】</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">6</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">8</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">4</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">8</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">【数据规模】</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">对于40%的数据 1&lt;=N,M&lt;=100 , 1&lt;=K&lt;=100</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">对于70%的数据 1&lt;=N&lt;=2000 , 1&lt;=M&lt;=100 , 1&lt;=K&lt;=50000</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">对于100%的数据 1&lt;=N,M&lt;=2000 , 1&lt;=K&lt;=50000</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">1&lt;=X1&lt;=X2&lt;=N , 1&lt;=Y1&lt;=Y2&lt;=M </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
