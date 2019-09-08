# 题目描述


<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«问题描述：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">给定一个由n 行数字组成的数字梯形如下图所示。梯形的第一行有m 个数字。从梯形</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">的顶部的m 个数字开始，在每个数字处可以沿左下或右下方向移动，形成一条从梯形的顶</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">至底的路径。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">规则1：从梯形的顶至底的m条路径互不相交。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">规则2：从梯形的顶至底的m条路径仅在数字结点处相交。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">规则3：从梯形的顶至底的m条路径允许在数字结点相交或边相交。</span><br/>
<span><img alt="" src="/cogs/images/upload/image/20120405/20120405172117_38925.png"/><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"></span><br/>
</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«编程任务：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于给定的数字梯形，分别按照规则1，规则2，和规则3 计算出从梯形的顶至底的m</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">条路径，使这m条路径经过的数字总和最大。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«数据输入：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">由文件<span>digit.in</span>提供输入数据。文件的第1 行中有2个正整数m和n（m,n&lt;=20），分别</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">表示数字梯形的第一行有m个数字，共有n 行。接下来的n 行是数字梯形中各行的数字。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第1 行有m个数字，第2 行有m+1 个数字，…。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«结果输出:</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">程序运行结束时，将按照规则1，规则2，和规则3 计算出的最大数字总和输出到文件</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span>digit.out</span>中。每行一个最大总和。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入文件示例 输出文件示例</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span>digit.in</span></span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 5</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3 4 5</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">9 10 9 1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 1 10 1 1</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 1 10 12 1 1</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span>digit.out</span><br/>
</span> 
</p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">66</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">75</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">77</span><br/>
