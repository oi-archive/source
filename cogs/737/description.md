# 题目描述


<span style="font-family:&#39;&#39;Microsoft YaHei&#39;&#39;;"><span style="font-size:16px;line-height:24px;"><span>«问题描述：</span><br/>
<span>给定一个N*N 的方形网格，设其左上角为起点◎，坐标为（1，1），X 轴向右为正，Y</span><br/>
<span>轴向下为正，每个方格边长为1，如图所示。一辆汽车从起点◎出发驶向右下角终点▲，其</span><br/>
<span>坐标为（N，N）。在若干个网格交叉点处，设置了油库，可供汽车在行驶途中加油。汽车在</span><br/>
<span>行驶过程中应遵守如下规则：</span><br/>
<span>(1)汽车只能沿网格边行驶，装满油后能行驶K 条网格边。出发时汽车已装满油，在起</span><br/>
<span>点与终点处不设油库。</span><br/>
<span>(2)汽车经过一条网格边时，若其X 坐标或Y 坐标减小，则应付费用B，否则免付费用。</span><br/>
<span>(3)汽车在行驶过程中遇油库则应加满油并付加油费用A。</span><br/>
<span>(4)在需要时可在网格点处增设油库，并付增设油库费用C（不含加油费用A）。</span><br/>
<span>(5)(1)～(4)中的各数N、K、A、B、C均为正整数，且满足约束：2 &lt;= N &lt;= 100，2 &lt;= K &lt;= 10。</span><br/>
</span></span> 
<p>
<span style="font-family:&#39;&#39;Microsoft YaHei&#39;&#39;;"><span style="font-size:16px;line-height:24px;"><span>设计一个算法，求出汽车从起点出发到达终点的一条所付费用最少的行驶路线。</span></span></span> 
</p>
<p>
<span style="font-family:&#39;&#39;Microsoft YaHei&#39;&#39;;"><span style="font-size:16px;line-height:24px;"><br/>
</span></span> 
</p>
<p>
<br/>
</p>
<span style="font-family:&#39;&#39;Microsoft YaHei&#39;&#39;;"><span style="font-size:16px;line-height:24px;"><span>«编程任务：<img src="/cogs/images/upload/image/20120405/20120405171852_40636.png" alt=""/></span><br/>
<span>对于给定的交通网格，计算汽车从起点出发到达终点的一条所付费用最少的行驶路线。</span><br/>
<span>«数据输入：</span><br/>
<span>由文件<span>trav.in</span>提供输入数据。文件的第一行是N，K，A，B，C的值。第二行起是一</span><br/>
<span>个N*N 的0-1 方阵，每行N 个值，至N+1 行结束。方阵的第i 行第j 列处的值为1 表示在</span><br/>
<span>网格交叉点（i，j）处设置了一个油库，为0 时表示未设油库。各行相邻两个数以空格分隔。</span><br/>
<span>«结果输出:</span><br/>
<span>程序运行结束时，将最小费用输出到文件<span>trav.out</span>中。</span><br/>
<span>输入文件示例 输出文件示例</span><br/>
<span><span>trav.in</span></span><br/>
<span>9 3 2 3 6</span><br/>
<span>0 0 0 0 1 0 0 0 0</span><br/>
<span>0 0 0 1 0 1 1 0 0</span><br/>
<span>1 0 1 0 0 0 0 1 0</span><br/>
<span>0 0 0 0 0 1 0 0 1</span><br/>
<span>1 0 0 1 0 0 1 0 0</span><br/>
<span>0 1 0 0 0 0 0 1 0</span><br/>
<span>0 0 0 0 1 0 0 0 1</span><br/>
<span>1 0 0 1 0 0 0 1 0</span><br/>
</span></span> 
<p>
<span style="font-family:&#39;&#39;Microsoft YaHei&#39;&#39;;"><span style="font-size:16px;line-height:24px;"><span>0 1 0 0 0 0 0 0 0</span></span></span> 
</p>
<p>
<span style="font-family:&#39;&#39;Microsoft YaHei&#39;&#39;;"><span style="font-size:16px;line-height:24px;"><span><span>trav.out</span><br/>
</span></span></span> 
</p>
<span style="font-family:&#39;&#39;Microsoft YaHei&#39;&#39;;"><span style="font-size:16px;line-height:24px;"> <span>12</span><br/>
<br/>
</span></span>
