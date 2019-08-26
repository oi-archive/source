
# Description

<div class="content"><p><span style="font-size: medium">著名的电子产品品牌 SHOI 刚刚发布了引领世界潮流的下一代电子产品——概率充电器:<br/>
“采用全新纳米级加工技术,实现元件与导线能否通电完全由真随机数决定!SHOI 概率充电器,您生活不可或缺的必需品!能充上电吗?现在就试试看吧!<br/>
”<br/>
SHOI 概率充电器由 n-1 条导线连通了 n 个充电元件。进行充电时,每条导线是否可以导电以概率决定,每一个充电元件自身是否直接进行充电也由概率决定。<br/>
随后电能可以从直接充电的元件经过通电的导线使得其他充电元件进行间接充电。<br/>
作为 SHOI 公司的忠实客户,你无法抑制自己购买 SHOI 产品的冲动。在排了一个星期的长队之后终于入手了最新型号的 SHOI 概率充电器。<br/>
你迫不及待地将 SHOI 概率充电器插入电源——这时你突然想知道,进入充电状态的元件个数的期望是多少呢?</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行一个整数:n。概率充电器的充电元件个数。充电元件由 1-n 编号。<br/>
之后的 n-1 行每行三个整数 a, b, p,描述了一根导线连接了编号为 a 和 b 的<br/>
充电元件,通电概率为 p%。<br/>
第 n+2 行 n 个整数:qi。表示 i 号元件直接充电的概率为 qi%。<br/>
</span></p></div>

# Output

<div class="content"><p><span style="font-family: arial, verdana, helvetica, sans-serif; font-size: medium;">输出一行一个实数,为进入充电状态的元件个数的期望,四舍五入到六位小数</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 <br/>
1 2 50 <br/>
1 3 50 <br/>
50 0 0 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1.000000<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">对于 100%的数据,n≤500000,0≤p,qi≤100。<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名提供">By 佚名提供</a></p></div>

