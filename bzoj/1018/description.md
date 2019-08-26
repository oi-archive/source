
# Description

<div class="content"><p>　　有一天，由于某种穿越现象作用，你来到了传说中的小人国。小人国的布局非常奇特，整个国家的交通系统可<br/>
以被看成是一个2行C列的矩形网格，网格上的每个点代表一个城市，相邻的城市之间有一条道路，所以总共有2C个<br/>
城市和3C-2条道路。 小人国的交通状况非常槽糕。有的时候由于交通堵塞，两座城市之间的道路会变得不连通，<br/>
直到拥堵解决，道路才会恢复畅通。初来咋到的你决心毛遂自荐到交通部某份差事，部长听说你来自一个科技高度<br/>
发达的世界，喜出望外地要求你编写一个查询应答系统，以挽救已经病入膏肓的小人国交通系统。 小人国的交通<br/>
部将提供一些交通信息给你，你的任务是根据当前的交通情况回答查询的问题。交通信息可以分为以下几种格式：<br/>
Close r1 c1 r2 c2：相邻的两座城市(r1,c1)和(r2,c2)之间的道路被堵塞了；Open r1 c1 r2 c2：相邻的两座城<br/>
市(r1,c1)和(r2,c2)之间的道路被疏通了；Ask r1 c1 r2 c2：询问城市(r1,c1)和(r2,c2)是否连通。如果存在一<br/>
条路径使得这两条城市连通，则返回Y，否则返回N；</p></div>

# Input

<div class="content"><p>　　第一行只有一个整数C，表示网格的列数。接下来若干行，每行为一条交通信息，以单独的一行“Exit”作为<br/>
结束。我们假设在一开始所有的道路都是堵塞的。我们保证 C小于等于100000，信息条数小于等于100000。</p></div>

# Output

<div class="content"><p>　　对于每个查询，输出一个“Y”或“N”。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
Open 1 1 1 2<br/>
Open 1 2 2 2<br/>
Ask 1 1 2 2<br/>
Ask 2 1 2 2<br/>
Exit</span></div>

# Sample Output

<div class="content"><span class="sampledata">Y<br/>
N</span></div>

# Hint

<div class="content"><p></p><p> 题解：<a href="/JudgeOnline/upload/201604/sol(4).rar">JudgeOnline/upload/201604/sol(4).rar</a></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

