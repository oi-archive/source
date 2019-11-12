# 题目描述


<span style="font-family:Microsoft YaHei;">【题目描述】</span><br/>
<br/>
<span style="font-family:Microsoft YaHei;"> 经过11 年的韬光养晦，帝国研发出了一种新的导弹拦截系统，凡是与它的距离不超过其工作半径的导弹都能够被它成功拦截。当工作半径为0 时，则能够拦截与它位置恰好相同的导弹。但该导弹拦截系统也存在这样的缺陷：每套系统每天只能设定一次工作半径。而当天的使用代价，就是所有系统工作半径的平方和。</span><br/>
<span style="font-family:Microsoft YaHei;"> 某天，雷达捕捉到敌国的导弹来袭。由于该系统尚处于试验阶段，所以只有两套系统投入工作。如果现在的要求是拦截所有的导弹，请计算这一天的最小使用代价。</span><br/>
<br/>
<span style="font-family:Microsoft YaHei;"> 【输入格式】</span><br/>
<br/>
<span style="font-family:Microsoft YaHei;"> 第一行包含4 个整数x1、y1、x2、y2，每两个整数之间用一个空格隔开，表示这两套导弹拦截系统的坐标分别为(x1, y1)、(x2, y2)。</span><br/>
<span style="font-family:Microsoft YaHei;"> 第二行包含1 个整数N，表示有N 颗导弹。接下来N 行，每行两个整数x、y，中间用一个空格隔开，表示一颗导弹的坐标(x, y)。不同导弹的坐标可能相同。</span><br/>
<br/>
<span style="font-family:Microsoft YaHei;"> 【输出格式】</span><br/>
<br/>
<span style="font-family:Microsoft YaHei;"> 输出只有一行，包含一个整数，即当天的最小使用代价。</span><br/>
<br/>
<span style="font-family:Microsoft YaHei;"> 【输入样例1】</span><br/>
<span style="font-family:Microsoft YaHei;"> 0 0 10 0</span><br/>
<span style="font-family:Microsoft YaHei;"> 2</span><br/>
<span style="font-family:Microsoft YaHei;"> -3 3</span><br/>
<span style="font-family:Microsoft YaHei;"> 10 0</span><br/>
<br/>
<span style="font-family:Microsoft YaHei;">  【输出样例1】</span><br/>
<span style="font-family:Microsoft YaHei;"> 18</span><br/>
<br/>
<span style="font-family:Microsoft YaHei;">  【样例 1 说明】</span><br/>
<span style="font-family:Microsoft YaHei;"> 样例1 中要拦截所有导弹，在满足最小使用代价的前提下，两套系统工作半径的平方分别为18 和0。</span><br/>
<br/>
<span style="font-family:Microsoft YaHei;"> 【输入样例2】</span><br/>
<span style="font-family:Microsoft YaHei;"> 0 0 6 0</span><br/>
<span style="font-family:Microsoft YaHei;"> 5</span><br/>
<span style="font-family:Microsoft YaHei;"> -4 -2</span><br/>
<span style="font-family:Microsoft YaHei;"> -2 3</span><br/>
<span style="font-family:Microsoft YaHei;"> 4 0</span><br/>
<span style="font-family:Microsoft YaHei;"> 6 -2</span><br/>
<span style="font-family:Microsoft YaHei;"> 9 1</span><br/>
<br/>
<span style="font-family:Microsoft YaHei;"> 【输出样例2】</span><br/>
<span style="font-family:Microsoft YaHei;"> 30</span><br/>
<span style="font-family:Microsoft YaHei;"></span><br/>
<span style="font-family:Microsoft YaHei;"> 【样例2 说明】</span><br/>
<p>
<span style="font-family:Microsoft YaHei;">样例中的导弹拦截系统和导弹所在的位置如下图所示。要拦截所有导弹，在满足最小使用代价的前提下，两套系统工作半径的平方分别为20 和10。</span> 
</p>
<p>
<img width="422" height="264" alt="" src="https://dn-vijos-org-static.qbox.me/static/ProblemImg/P1810.png"/> 
</p>
<br/>
<span style="font-family:Microsoft YaHei;"> 【提示】</span><br/>
<span style="font-family:Microsoft YaHei;"> 两个点(x1, y1)、(x2, y2)之间距离的平方是(x1-x2)^2+(y1-y2)^2。</span><br/>
<span style="font-family:Microsoft YaHei;"> 两套系统工作半径r1、r2 的平方和，是指r1、r2 分别取平方后再求和，即r1^2+r2^2。</span><br/>
<br/>
<span style="font-family:Microsoft YaHei;"> 【数据范围】</span><br/>
<span style="font-family:Microsoft YaHei;"> 对于10%的数据，N = 1</span><br/>
<span style="font-family:Microsoft YaHei;"> 对于20%的数据，1 ≤ N ≤ 2</span><br/>
<span style="font-family:Microsoft YaHei;"> 对于40%的数据，1 ≤ N ≤ 100</span><br/>
<span style="font-family:Microsoft YaHei;"> 对于70%的数据，1 ≤ N ≤ 1000</span><br/>
<span style="font-family:Microsoft YaHei;"> 对于100%的数据，1 ≤ N ≤ 100000，且所有坐标分量的绝对值都不超过1000。</span><br/>
<div>
<br/>
</div>
