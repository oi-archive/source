<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　清华里面有很多超市，但是有的商品在这个超市里便宜些，有的商品在另一个超市里便宜些。周末大购物的时候，超超想从1号超市逛到n号超市，然后把该买的东西(从1到m编号)都用最便宜的价格买到，你的任务是帮帮他决定在哪个超市应该买什么商品。</div>
# 输入格式

<div class="pdcont">　　输入数据第一行是两个数n m，表示有n个超市和m个该买的商品。<br/>
　　接下来是nXm的矩阵A<sub>ij</sub>，其中第i行第j列表示i号超市中j商品的价格（小于100的非负整数），A<sub>ij</sub>=0则表示j商品无法在i超市找到。输入数据不能保证能买到所有商品。</div>
# 输出格式

<div class="pdcont">　　输出仅一行，包括m个数B1,B2, ..., Bm，依次表示第i号商品该在Bi号超市中购买。如果买不到的话Bi为0。<br/>
　　当然啦，如果一个商品在i号超市与j号超市购买一样便宜，超超更乐意大号超市了。嘻嘻，有兴趣的话猜猜为什么。</div>
# 样例输入

<div class="pddata">3 6<br/>
5 3 0 2 3 5<br/>
8 9 0 2 0 2<br/>
3 4 0 2 1 3</div>
# 样例输出

<div class="pddata">3 1 0 3 3 2</div>
# 数据规模和约定

<div class="pdcont">　　1&lt;=n&lt;=50<br/>
　　1&lt;=m&lt;=100</div>

</div>