# 题目描述


<p>
<span style="font-family:宋体;"><span style="font-size:18px;">问题描述</span><br/>
</span><span style="font-family:黑体;font-size:18px;">如图</span><span style="font-size:18px;">,A</span><span style="font-family:黑体;font-size:18px;">点有一过河卒，需要走到目标</span><span style="font-size:18px;">B</span><span style="font-family:黑体;font-size:18px;">点。卒行走的规则：可以向下，或者向右。</span> 
</p>
<p align="center">
<span><img alt="" src="/cogs/images/upload/image/20120416/20120416215703_46786.gif" width="600" height="373"/></span> 
</p>
<p>
<span style="font-family:宋体;font-size:18px;">同时在棋盘上的任一点有一个对方的马（如图中</span><span style="font-size:18px;">C</span><span style="font-family:宋体;font-size:18px;">点），该马所在的点和所有跳跃一步可达的点称为对方马的控制点。</span> 
</p>
<p style="text-indent:21pt;">
<span style="font-family:宋体;font-size:18px;">例如上图</span><span style="font-size:18px;">C</span><span style="font-family:宋体;font-size:18px;">点的马可控制</span><span style="font-size:18px;">9</span><span style="font-family:宋体;font-size:18px;">个点（</span><span style="font-size:18px;">P1...P8</span><span style="font-family:宋体;font-size:18px;">，</span><span style="font-size:18px;">C</span><span style="font-family:宋体;font-size:18px;">）。卒不能通过对方马的控制点。棋盘用坐标表示，</span><span style="font-size:18px;">A</span><span style="font-family:宋体;font-size:18px;">点（</span><span style="font-size:18px;">0</span><span style="font-family:宋体;font-size:18px;">，</span><span style="font-size:18px;">0</span><span style="font-family:宋体;font-size:18px;">），</span><span style="font-size:18px;">B</span><span style="font-family:宋体;font-size:18px;">点（</span><span style="font-size:18px;">n</span><span style="font-family:宋体;font-size:18px;">，</span><span style="font-size:18px;">m</span><span style="font-family:宋体;font-size:18px;">）（</span><span style="font-size:18px;"><strong>n</strong></span><span style="font-family:宋体;font-size:18px;"><strong>，</strong></span><span style="font-size:18px;"><strong>m</strong></span><span style="font-family:宋体;font-size:18px;"><strong>为不超过</strong></span><span style="font-size:18px;"><strong>20</strong></span><span style="font-family:宋体;font-size:18px;"><strong>的整数</strong>），同样，马的位置坐标是需要给出的（约定：</span><span style="font-size:18px;">C</span><span style="font-family:宋体;font-size:18px;">≠</span><span style="font-size:18px;">A</span><span style="font-family:宋体;font-size:18px;">同时</span><span style="font-size:18px;">C</span><span style="font-family:宋体;font-size:18px;">≠</span><span style="font-size:18px;">B</span><span style="font-family:宋体;font-size:18px;">）。</span> 
</p>
<p style="text-indent:21pt;">
<span style="font-family:宋体;font-size:18px;">现在要你计算出</span> <span style="font-family:宋体;font-size:18px;">卒从</span><span style="font-size:18px;">A</span><span style="font-family:宋体;font-size:18px;">点出发能够到达</span><span style="font-size:18px;">B</span><span style="font-family:宋体;font-size:18px;">点的路径的条数。</span> 
</p>
<p>
<span style="font-size:18px;">【输入格式】</span> 
</p>
<p style="text-indent:21pt;">
<span style="font-family:宋体;font-size:18px;">输入</span> 
</p>
<p style="text-indent:21pt;">
<span style="font-size:18px;">一行四个整数n</span><span style="font-family:宋体;font-size:18px;">,</span><span style="font-size:18px;">m</span><span style="font-family:宋体;font-size:18px;">,</span><span style="font-size:18px;">x</span><span style="font-family:宋体;font-size:18px;">,</span><span style="font-size:18px;">y</span> 
</p>
<p style="text-indent:21pt;">
<span style="font-family:宋体;font-size:18px;">B点坐标（n,m）以及对马的坐标（x,y）{不用判错}</span> 
</p>
<p>
<span></span><span style="font-size:18px;">【输出格式】</span> 
</p>
<p style="text-indent:21pt;">
<span style="font-family:宋体;font-size:18px;">输出</span> 
</p>
<p style="text-indent:21pt;">
<span style="font-family:宋体;"><span style="font-size:18px;">一个整数</span><span style="font-size:18px;">(路径的条数)</span></span> 
</p>
<p>
<span style="font-size:18px;">【输入样例】</span> 
</p>
<p>
<span style="font-size:18px;">输入文件</span> 
</p>
<p>
<span style="font-size:18px;">6 6 3 2</span> 
</p>
<p>
<span style="font-size:18px;">输出文件</span> 
</p>
<p>
<span style="font-size:18px;">17</span> 
</p>
