# 题目描述


<p>
<b>【问题描述】</b><br/>
  将一个８×８的棋盘进行如下分割：将原棋盘割下一块矩形棋盘并使剩下部分也是矩形，再将分割过的部分任选一块继续如此分割，这样割了n-1次后，连同最后剩下的矩形棋盘共有n块矩形棋盘。(每次切割都只能沿着棋盘格子的边进行)
</p>
<div align="left">
    原棋盘上每一格有一个分值，一块矩形棋盘的总分为其所含各格分值之和。现在需要把棋盘按上述规则分割成 n 块矩形棋盘，并使各矩形棋盘总分的均方差最小。
</div>
<div>
均方差<img alt="" src="/mw/images/9/96/Division-1.gif" height="53" width="124"/> ，其中平均值<img alt="" src="/mw/images/4/4e/Division-2.gif" height="48" width="74"/> x i 为第 i 块矩形棋盘的分。
</div>
<div>
请编程对给出的棋盘及 n ，求出 <img alt="" src="/mw/images/c/cb/Division-3.gif" height="15" width="13"/>的最小值。
</div>
<div align="center">
 
</div>
<div>
【输入格式】
</div>
<div>
第 1 行为一个整数 n(1<n<9) 。<="" div="">
<p>
第 2 行至第 9 行每行为 8 个小于 100 的非负整数，表示棋盘上相应格子的分值。每行相邻两数之间用一个空格分隔。
</p>
<div>
【输出格式】
</div>
<div>
<span>    </span> 
</div>
<div>
仅一个数，为 <img alt="" src="/mw/images/c/cb/Division-3.gif" height="15" width="13"/>（四舍五入精确到小数点后三位）。
</div>
<div>
【输入样例】
</div>
<div>
输入文件名：<span>division.in</span> 
</div>
<div>
3 <br/>
1 1 1 1 1 1 1 3 <br/>
1 1 1 1 1 1 1 1 <br/>
1 1 1 1 1 1 1 1 <br/>
1 1 1 1 1 1 1 1 <br/>
1 1 1 1 1 1 1 1 <br/>
1 1 1 1 1 1 1 1 <br/>
1 1 1 1 1 1 1 0 <br/>
1 1 1 1 1 1 0 3
</div>
<div>
<img alt="" src="/mw/images/7/74/Division-4.gif" height="149" width="149"/> 
</div>
<div>
输出文件名：<span>division.out</span> 
</div>
<div>
1.633
</div>
</n<9)>
</div>
