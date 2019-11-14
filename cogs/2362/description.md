# 题目描述


<p class="NOI">
<span style="font-family:黑体;">猜测</span><span></span> 
</p>
<p class="NOI0">
<span style="font-family:黑体;">【问题描述】</span><span></span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;">有一块棋盘，棋盘的边长为</span><span>100000</span><span style="font-family:宋体;">，行和列的编号为</span><span>1</span><span style="font-family:宋体;">到</span><span>100000</span><span style="font-family:宋体;">。棋盘上有</span><span style="font-size:10.5pt;font-family:等线;"> </span><span style="font-family:宋体;">个特殊格子，任意两个格子的位置都不相同。</span><span></span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;">现在小</span><span>K</span><span style="font-family:宋体;">要猜哪些格子是特殊格子。她知道所有格子的横坐标和纵坐标，但并不知道对应关系。换言之，她只有两个数组，一个存下了所有格子的横坐标，另一个存下了所有格子的纵坐标，而且两个数组都打乱了顺序。当然，小</span><span>K</span><span style="font-family:宋体;">猜的</span><span style="font-size:10.5pt;font-family:等线;"> </span><span style="font-family:宋体;">个格子的位置也必须都不相同。</span><span></span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;">请求出一个最大的</span><span style="font-size:10.5pt;font-family:等线;"> </span><span style="font-family:宋体;">，使得无论小</span><span>K</span><span style="font-family:宋体;">怎么猜，都能猜对至少</span><span style="font-size:10.5pt;font-family:等线;"> </span><span style="font-family:宋体;">个格子的位置。</span><span></span> 
</p>
<p class="NOI0">
<span style="font-family:黑体;">【输入格式】</span><span></span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;">输入数据第一行包含一个整数</span><span style="font-size:10.5pt;font-family:等线;"> </span><span style="font-family:宋体;">。</span><span></span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;">接下来</span><span style="font-size:10.5pt;font-family:等线;"> </span><span style="font-family:宋体;">行，每行描述一个特殊格子的位置。第</span><span style="font-size:10.5pt;font-family:等线;"> </span><span style="font-family:宋体;">行含有两个整数</span><span style="font-size:10.5pt;font-family:等线;"> </span><span style="font-family:宋体;">和</span><span style="font-size:10.5pt;font-family:等线;"> </span><span style="font-family:宋体;">，代表第</span><span style="font-size:10.5pt;font-family:等线;"> </span><span style="font-family:宋体;">个格子的坐标。保证任意两个格子的坐标都不相同。</span><span></span> 
</p>
<p class="NOI0">
<span style="font-family:黑体;">【输出格式】</span><span></span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;">输出一行，包含一个整数，代表最大的</span><span style="font-size:10.5pt;font-family:等线;"> </span><span style="font-family:宋体;">。</span><span></span> 
</p>
<p class="NOI0">
<span style="font-family:黑体;">【样例输入</span><span>1</span><span style="font-family:黑体;">】</span><span></span> 
</p>
<p class="NOI2">
<span>2</span> 
</p>
<p class="NOI2">
<span>1 1</span> 
</p>
<p class="NOI2">
<span>2 2</span> 
</p>
<p class="NOI0">
<span style="font-family:黑体;">【样例输出</span><span>1</span><span style="font-family:黑体;">】</span><span></span> 
</p>
<p class="NOI2">
<span>0</span> 
</p>
<p class="NOI0">
<span style="font-family:黑体;">【样例解释</span><span>1</span><span style="font-family:黑体;">】</span><span></span> 
</p>
<p class="NOI1" style="margin-left:24.1pt;text-indent:0cm;">
<span style="font-family:宋体;">小</span><span>K</span><span style="font-family:宋体;">有可能会猜</span><span style="font-size:10.5pt;font-family:等线;"> </span><span style="font-family:宋体;">，此时一个都没对。</span><span></span> 
</p>
<p class="NOI0">
<span style="font-family:黑体;">【样例输入</span><span>2</span><span style="font-family:黑体;">】</span><span></span> 
</p>
<p class="NOI2">
<span>3</span> 
</p>
<p class="NOI2">
<span>1 1</span> 
</p>
<p class="NOI2">
<span>1 2</span> 
</p>
<p class="NOI2">
<span>2 1</span> 
</p>
<p class="NOI0">
<span style="font-family:黑体;">【样例输出</span><span>2</span><span style="font-family:黑体;">】</span><span></span> 
</p>
<p class="NOI2">
<span>3</span> 
</p>
<p class="NOI0">
<span style="font-family:黑体;">【样例解释</span><span>2</span><span style="font-family:黑体;">】</span><span></span> 
</p>
<p class="NOI1" style="margin-left:24.1pt;text-indent:0cm;">
<span style="font-family:宋体;">此时只有一种合法的猜测。注意</span><span style="font-size:10.5pt;font-family:等线;"> </span><span style="font-family:宋体;">不是一个合法的猜测。</span><span></span> 
</p>
<p class="NOI0">
<span style="font-family:黑体;">【数据规模和约定】</span><span></span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;">对于</span><span>30%</span><span style="font-family:宋体;">的数据，$n&lt;=8$</span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;">另外有</span><span>5%</span><span style="font-family:宋体;">的数据，所有横坐标和纵坐标均不相同。</span><span></span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;">另外有</span><span>15%</span><span style="font-family:宋体;">的数据，所有横坐标或者纵坐标均不相同。</span><span></span> 
</p>
<p class="NOI1">
<span style="font-family:宋体;">对于</span><span>100%</span><span style="font-family:宋体;">的数据，$n&lt;=50,1&lt;=x,y&lt;=100000$</span><span style="font-size:10.5pt;font-family:等线;"></span> 
</p>
<br/>
