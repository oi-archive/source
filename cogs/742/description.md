# 题目描述


<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">深海机器人问题</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«问题描述：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">深海资源考察探险队的潜艇将到达深海的海底进行科学考察。潜艇内有多个深海机器</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">人。潜艇到达深海海底后，深海机器人将离开潜艇向预定目标移动。深海机器人在移动中还</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">必须沿途采集海底生物标本。沿途生物标本由最先遇到它的深海机器人完成采集。每条预定</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">路径上的生物标本的价值是已知的，而且生物标本只能被采集一次。本题限定深海机器人只</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">能从其出发位置沿着向北或向东的方向移动，而且多个深海机器人可以在同一时间占据同一</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">位置。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«编程任务：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">用一个P´Q 网格表示深海机器人的可移动位置。西南角的坐标为（0,0），东北角的坐</span><br/>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">标为 (Q,P)。</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><img src="/cogs/images/upload/image/20120405/20120405173054_94736.png" alt=""/><br/>
</span> 
</p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">给定每个深海机器人的出发位置和目标位置，以及每条网格边上生物标本的价值。计算</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">深海机器人的最优移动方案，使深海机器人到达目的地后，采集到的生物标本的总价值最高。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«数据输入：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">由文件<span>shinkai.in</span>提供输入数据。文件的第1 行为深海机器人的出发位置数a，和目的地</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">数b，第2 行为P和Q 的值。接下来的P+1 行，每行有Q 个正整数，表示向东移动路径上</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">生物标本的价值，行数据依从南到北方向排列。再接下来的Q+1 行，每行有P 个正整数，</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">表示向北移动路径上生物标本的价值，行数据依从西到东方向排列。接下来的a行，每行有</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3 个正整数k,x,y，表示有k个深海机器人从(x,y)位置坐标出发。再接下来的b行，每行有3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">个正整数r,x,y，表示有r个深海机器人可选择(x,y)位置坐标作为目的地。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«结果输出:</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">程序运行结束时，将采集到的生物标本的最高总价值输出到文件<span>shinkai.out</span>中。</span><br/>
<span style="font-family:&#39;&#39;Microsoft YaHei&#39;&#39;;"><span style="font-size:16px;line-height:24px;"><br/>
</span></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span>shinkai.in</span></span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3 4</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5 6</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">7 2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">8 10</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">9 3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 0 0</span><br/>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 2 2</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span>shinkai.out</span><br/>
</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">42</span>
</p>
<p>
1&lt;=P,Q&lt;=15 1&lt;=a,b&lt;=10<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"></span>
</p>
