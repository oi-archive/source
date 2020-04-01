<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　你曾经品尝过火星食物吗？无论如何，你应该试一试。<br/>
<br/>
　　最具代表性的火星食物是这样的，它被放置在一个纯黑色的半径为R的圆形盘子上，就像煎饼那样。<br/>
<br/>
　　首先，他们把一份特别圆的Golden Honduras蛋糕放在盘子上。Golden Honduras蛋糕的半径等于r，并且放置的位置使得它恰好与盘子的边缘相切。这是因为火星人相信Golden Honduras蛋糕接近盘子边界的程度表明了他们洁净和纯粹的程度。<br/>
<br/>
　　接着，一份同样很圆的Pink Guadeloupe蛋糕被放置在盘子里。Guadeloupe蛋糕不能和Honduras蛋糕有任何重叠部分，也不能有任何部分超出盘子的边界外，但是它的半径要尽量大。（实际上，Pink Guadeloupe蛋糕会同时和盘子边缘和Golden Honduras蛋糕相切。）据说Rose Guadeloupe蛋糕的大小表现了火星人的慷慨和热情度。<br/>
<br/>
　　然后，第一份圆形的Green Bull Terrier蛋糕被放在盘子上。它会和Honduras蛋糕、Guadeloupe蛋糕分别相切，也不能超过盘子边缘，并且要让它的半径尽量大。<br/>
<br/>
　　接下来的每一步都会放置一个新的Green Bull Terrier蛋糕，它必须与Honduras蛋糕、上一个放置的Green Bull Terrier蛋糕和盘子边缘分别相切，但也不能超出盘子边界。<br/>
<br/>
　　为了判断一个陌生访客是否值得款待，火星人会告诉他盘子的半径R、和Golden Honduras蛋糕的半径r，然后询问他第k块放置的Green Bull Terrier蛋糕的半径是多少。那么，你是否值得款待呢？</div>
# 输入格式

<div class="pdcont">　　第一行包含一个整数t，表示测试数组组数。<br/>
　　接下来t行，每行包含3个正整数，依次是盘子的半径R、Golden Honduras蛋糕的半径r、以及序数k。</div>
# 输出格式

<div class="pdcont">　　输出t行，依次表示每组数据的答案，即第k个Green Bull Terrier蛋糕的半径。选手输出的答案与标准答案的相对误差或绝对误差应该不超过0.000001。</div>
# 样例输入

<div class="pddata">2<br/>
4 3 1<br/>
4 2 2</div>
# 样例输出

<div class="pddata">0.9230769231<br/>
0.6666666667</div>
# 数据规模和约定

<div class="pdcont">　　1  &lt;= t, k &lt;= 10000,<br/>
　　1 &lt;= r &lt; R &lt;= 10000.</div>

</div>