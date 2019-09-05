# 题目描述


<div>
Bessie结束了国外长途旅游回来。为了迎接她的归来，Farmer John准备在牧场给她挂起一个&#34;Welcome Home&#34;的横幅。横幅会挂在两个柱子间的长度介于L1..L2的金属丝上。(1 &lt;= L1 &lt;= L2; L1 &lt;= L2 &lt;= 1,500)。
</div>
<div>
牧场是一个W×H 的矩阵 (1 &lt;= W &lt;= 1,000; 1 &lt;= H &lt;= 1,000)并且FJ在每个坐标点上都树立起了柱子，在这 (W + 1) * (H + 1)个柱子上，FJ要选两个连上金属丝以挂上横幅。
</div>
<div>
FJ不希望在横幅之间有任何杂物，就是说在这条金属丝下面没有别的柱子。
</div>
<div>
FJ需要你编程帮他算出有多少种挂横幅的可能。但是这个数据很大，也许32位整数都放不下。
</div>
<div>
例如如下的牧场地图：
</div>
<div>
W = 2 H = 1
</div>
<div>
***
</div>
<div>
***
</div>
<div>
而横幅长度为2和3之间。
</div>
<div>
这个牧场共有 (2+1) * (1+1) = 6个点以及有(6 take 5) = (6*5)/(2*1) = 15 种配对方法
</div>
<div>
<span>    (0,0)-(0,1)   (0,0)-(2,1)   (0,1)-(2,1)   (1,1)-(2,0)</span> 
</div>
<div>
<span>    (0,0)-(1,0)   (0,1)-(1,0)   (1,0)-(1,1)   (1,1)-(2,1)</span> 
</div>
<div>
   (0,0)-(1,1)<span>   (0,1)-(1,1)   (1,0)-(2,0)   (2,0)-(2,1)</span> 
</div>
<div>
 <span>  (0,0)-(2,0)   (0,1)-(2,0)   (1,0)-(2,1)</span> 
</div>
<div>
在这之中，只有四种是可以配对的
</div>
<div>
 
</div>
<div>
<span>         </span>始位 末位 长度<span>          </span>始位 末位 长度
</div>
<div>
<span>        (0,0)-(2,0) 2.00          (0,1)-(2,0) 2.24</span> 
</div>
<div>
<span>        (0,0)-(2,1) 2.24          (0,1)-(2,1) 2.00</span> 
</div>
<div>
但在这四种之中，(0,0)-(2,0)和(0,1)-(2,1)都不符合“没有杂物”的要求，所以这个样例中只有2种结果。
</div>
<div>
输入格式
</div>
<div>
一行，4个整数W, H, L1, 和 L2
</div>
<div>
样例输入 banner.in
</div>
<div>
2 1 2 3
</div>
<div>
输出格式
</div>
<div>
一行。可能的方案数。
</div>
<div>
样例输出 banner.out
</div>
<div>
2
</div>
<div>
 
</div>
<div>
 
</div>
<div>
【数据范围】
</div>
<div>
50%数据 0&lt;w,h,L1,L2&lt;=100
</div>