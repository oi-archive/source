# 题目描述


<p>
<b>问题描述</b> 
</p>
<p>
一万两千年前，精灵还是在艾萨拉女王的统治下，辛德拉是女王手 下一名很有地位的法师。他受任建造了一座城市，来保存女王的法师们进行魔法研究的成果和法术物品。这个城市就是埃雷萨拉斯。永恒之井的爆炸，使这里的精灵 和总部联系中断，并失去了永恒之井的水做为能量的来源。辛德拉的后人为了满足魔法的欲望，捕猎了一个恶魔，伊莫塔尔，并以水晶塔建造了一个带有能量平衡系 统的结界监狱，水晶塔从恶魔身上吸取能量，一部分维持结界监狱，一部分可以让精灵狂热者吸收。近万年平安无事。但是现在，恶魔的能量被消耗得越来越多，最 终变得不稳定，已经难以维持结界监狱的消耗。统治这里的托尔塞林王子开始下令屠杀。只有少数狂热者之外的其他人都要死，以减少魔法能量的消耗。
</p>
<p>
<br/>
</p>
<p>
终于，强大的戈多克食人魔入侵了埃雷萨拉斯，并杀死了大量的精灵。他们把这里当作他们的领地，叫做厄运之槌。面临灭顶之灾的精灵们把他们祖先留下的宝藏用魔法结界藏了起来，以防戈多克食人魔抢走。
</p>
<p>
<br/>
</p>
<p>
作为一名勇敢的探险者，你悄悄来到了埃雷萨拉斯，来寻找传说中的宝藏。终于，你看到了宝藏，他就在你的前方不远处。但是你不能贸然前进，因为路上有着强大的魔法结界。这些结界根据能量的不同分为<span><span><span>P</span></span></span>种，踏入每种结界，你都会受到一定的伤害。为了拿到宝藏，这些伤害算不了什么。但是你要尽可能地减少伤害，请你设计一条路线，使你穿越结界获取宝藏受到的伤害最少。
</p>
<p>
<br/>
</p>
<p>
下面是一个魔法结界能量示意图，结界是一个正方形，内部有<span><span><span>P</span></span></span>种不同的能量，每种字母表示一种能量。你从最上端开始走，每次能走到与你所在的位置邻接的一个单元格，或者在同种能量结界中任意传送。重复进入同一种能量结界不会再次受到伤害。
</p>
<p>
<br/>
</p>
<p>
<span><span>|AAABBC|</span></span> 
</p>
<p>
<span><span>|ABCCCC|</span></span> 
</p>
<p>
<span><span>|AABBDD|</span></span> 
</p>
<p>
<span><span>|EEEEEF|</span></span> 
</p>
<p>
<span><span>|EGGEFF|</span></span> 
</p>
<p>
<span><span>|GGFFFF|</span></span> 
</p>
<p>
<br/>
</p>
<p>
你有<span><span><span>H</span></span></span>点生命值，请你在贸然行动之前先判断是否能够活着（生命值<b>大于</b><span><span><span>0</span></span></span>）穿越结界拿到宝藏，如果能够，请求出最大的生命值。
</p>
<p>
<br/>
</p>
<p>
<b>输入格式</b> 
</p>
<p>
第<span><span><span>1</span></span></span>行 三个非负整数 <span><span><span>N P H</span></span></span>。<span><span><span>N</span></span></span>为结界的边长，<span><span><span>P</span></span></span>为不同的能量结界的数量，<span><span><span>H</span></span></span>为你的生命值。
</p>
<p>
第<span><span><span>2-P+1</span></span></span>行 每行一个非负整数，表示走到该种能量结界受到的伤害值。
</p>
<p>
第<span><span><span>P+2</span></span></span>至第<span><span><span>P+2+N</span></span></span>行 每行<span><span><span>N</span></span></span>个正整数，为地图上该单元格的能量种类的编号，编号为<span><span><span>1..P</span></span></span>。
</p>
<p>
<br/>
</p>
<p>
<b>输出格式</b> 
</p>
<p>
如果你能够穿越结界到达对岸的宝藏，输出最多剩余的生命值。如果不能穿越，输出<span><span><span>NO</span></span></span>。
</p>
<p>
<br/>
</p>
<p>
<b>样例输入</b> 
</p>
<p>
<span><span>6 7 10</span></span> 
</p>
<p>
<span><span>3</span></span> 
</p>
<p>
<span><span>1</span></span> 
</p>
<p>
<span><span>2</span></span> 
</p>
<p>
<span><span>2</span></span> 
</p>
<p>
<span><span>1</span></span> 
</p>
<p>
<span><span>1</span></span> 
</p>
<p>
<span><span>3</span></span> 
</p>
<p>
<span><span>1 1 1 2 2 3</span></span> 
</p>
<p>
<span><span>1 2 3 3 3 3</span></span> 
</p>
<p>
<span><span>1 1 2 2 4 4</span></span> 
</p>
<p>
<span><span>5 5 5 5 5 6</span></span> 
</p>
<p>
<span><span>5 7 7 5 6 6</span></span> 
</p>
<p>
<span><span>7 7 6 6 6 6</span></span> 
</p>
<p>
<br/>
</p>
<p>
<b>样例输出</b> 
</p>
<p>
<span><span>7</span></span> 
</p>
<p>
<br/>
</p>
<p>
<b>样例说明</b> 
</p>
<p>
路线为
</p>
<p>
起始<span><span><span>-2-5-6-</span></span></span>目标
</p>
<p>
<span><span><span>1 1 1 </span><span><b>2</b></span><span> 2 3</span></span></span> 
</p>
<p>
<span><span>1 2 3 3 3 3</span></span> 
</p>
<p>
<span><span><span>1 1 2 </span><span><b>2</b></span><span> 4 4</span></span></span> 
</p>
<p>
<span><span><span>5 5 5 </span><span><b>5</b></span><span> 5 6</span></span></span> 
</p>
<p>
<span><span><span>5 7 7 </span><span><b>5</b></span><span> 6 6</span></span></span> 
</p>
<p>
<span><span><span>7 7 6 </span><span><b>6</b></span><span> 6 6</span></span></span> 
</p>
<p>
<br/>
</p>
<p>
<b>数据规模</b> 
</p>
<p>
对于<span><span><span>40%</span></span></span>数据
</p>
<p>
<span><span>4&lt;=N&lt;=10</span></span> 
</p>
<p>
<br/>
</p>
<p>
对于<span><span><span>100%</span></span></span>数据
</p>
<p>
<span><span>4&lt;=N&lt;=50</span></span> 
</p>
<p>
<span><span>1&lt;=P&lt;=N*N</span></span> 
</p>
<p>
<span><span>0&lt;=H&lt;=200000000</span></span> 
</p>
