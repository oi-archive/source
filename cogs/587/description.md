# 题目描述


<p>
【问题描述】 <br/>
金明今天很开心，因为今天是他的生日，妈妈给了N元钱。今天一早，金明就开始做预算了，他从因特网上查到了M件物品的价格(每件物品的价格都不相同)。他希望从中购买一些物品能恰好将N元钱花完。请你帮助计算一下共有多少种不同的购物方案。
</p>
<div>
【输入文件】<br/>
输入文件shopping.in的第1行，为两个正整数N，M。接下来一行M个互不相同的正整数，表示M种物品的价格，它们之间用一个空格隔开。<br/>
(其中M&lt;=20)
</div>
<div>
【输出文件】<br/>
输出文件shopping.out只有一个正整数，为不同的购物方案数(所有数据都不超出整形范围)。
</div>
<div>
<br/>
【输入输出样例】<br/>
输入文件：shopping.in<br/>
5 6<br/>
1 2 3 4 5 6<br/>
输出文件：shopping.out<br/>
3
</div>
<div>
样例说明：共有3种方案：<br/>
(1)a(1)+a(4)=1+4=5<br/>
(2) a(2)+a(3)=2+3=5<br/>
(3) a(5)=5
</div>