# 题目描述


<span>【问题描述】 </span><br/>
<span>苦无(Kunai)是一种忍者使用的形状像刀的武器，忍者通过投掷苦无攻击对</span><br/>
<span>手。 </span><br/>
<span>现在有N名忍者聚集在一块H行W列的棋盘式的广场上。每个忍者都站在</span><br/>
<span>其所在方块的中心处，任何两个忍者都不在同一个方块上。每个忍者都拿着一个</span><br/>
<span>苦无，面朝上、下、左、右四个方向中的一个方向站着。在时刻0，所有忍者同</span><br/>
<span>时向其所朝向的方向投掷苦无。 </span><br/>
<span>每个苦无将会一直保持其初始的方向，并以单位速度飞行。如果某个时刻一</span><br/>
<span>个位置上多于一个的苦无，它们将会相撞并且消失。苦无特别小，可以看成质点。</span><br/>
<span>同时，由于忍者的移动速度特别快，他们不会被苦无击中。 </span><br/>
<span>在下面的例子中，我们用箭头来表示苦无，而箭头的方向即为苦无的方向。</span><br/>
<span>在这些图中，所有的苦无都会相撞后消失。 </span><br/>
<span> </span><br/>
<span>在下面的图中，两个粗线箭头表示的苦无不会相撞。其中在第二个和第三个</span><br/>
<span>图中，其中一个粗线表示的苦无会与细线表示的苦无相撞后消失，因此不会撞上</span><br/>
<span>另一个粗线表示的苦无。 </span><br/>
<span> </span><br/>
<span>你的任务是计算经过足够长的时间之后，在这个W × H的广场中有多少格</span><br/>
<span>子被苦无经过。 </span><br/>
<span>【数据范围】 </span><br/>
<span>1 ≤ N ≤ 100,000  忍者数； </span><br/>
<span>1 ≤ W ≤ 1,000,000,000  列数； </span><br/>
<span>1 ≤ H ≤ 1,000,000,000  行数； </span><br/>
<span>1 ≤ Xi</span><span> ≤ W，1 ≤ Yi</span><span> ≤ H  坐标范围。 </span><br/>
<span> </span><br/>
<span>在10%的数据中，N ≤ 1000, W ≤ 1000, H ≤ 1000。 </span><br/>
<p>
<span>在40%的数据中，N ≤ 1000。</span> 
</p>
<p>
<span><span>【输入格式】 </span><br/>
<span>从标准输入读入数据。 </span><br/>
<span>第一行包含两个被空格隔开的整数W, H，表示广场的尺寸为W列H行。 </span><br/>
<span>第二行包含一个整数N，表示忍者的数量。 </span><br/>
<span>接下来N行中，第i行有三个以空格分隔的整数Xi</span><span>, Yi</span><span>, Di</span><br/>
<span>, 表示第i个忍者</span><br/>
<span>处在从左往右的Xi 列、从上往下的第Yi 行，任何两个忍者不在同一个位置。第</span><br/>
<span>i个忍者面向的方向由Di 表示，分别为： </span><br/>
<span>  Di</span><span> = 0，表示忍者向右； </span><br/>
<span>  Di</span><span> = 1，表示忍者向上； </span><br/>
<span>  Di</span><span> = 2，表示忍者向左； </span><br/>
<span>  Di</span><span> = 3，表示忍者向下。 </span><br/>
<span>【输出格式】 </span><br/>
<span>输出到标准输出。 </span><br/>
<span>输出一个整数，表示经过足够长的时间之后，在这个W × H的广场中被苦</span><br/>
<span>无经过被苦无经过的格子数量。 </span><br/>
<span>【样例输入1】 </span><br/>
<span>5 4 </span><br/>
<span>5 </span><br/>
<span>3 3 2 </span><br/>
<span>3 2 0 </span><br/>
<span>4 2 2 </span><br/>
<span>5 4 1 </span><br/>
<span>1 1 3 </span><br/>
<span>【样例输出1】 </span><br/>
<span>11 </span><br/>
<span>【样例说明】 </span><br/>
<span>在时刻0，苦无的情况如下图所示 </span><br/>
<span> </span><br/>
<span>在下面的描述中，忍者i投掷的苦无将用苦无i表示。 </span><br/>
<span>在时刻0.5，苦无2和苦无3相撞后消失。 </span><br/>
<span>下图为时刻1的情况，加深的格子表示已经被苦无经过。</span><br/>
<br/>
</span> 
</p>
<p>
<span><span>在时刻2，苦无1和苦无5相撞后消失，此时的广场如下图所示。 </span><br/>
<span> </span><br/>
<span>之后没有苦无相撞。再经过足够时间后的广场如下图所示。 </span><br/>
<span> </span><br/>
<span>共有11个格子被苦无经过，因此输出11。 </span><br/>
<span>【样例输入2】 </span><br/>
<span>7 6 </span><br/>
<span>12 </span><br/>
<span>3 2 3 </span><br/>
<span>6 3 2 </span><br/>
<span>7 1 3 </span><br/>
<span>1 5 0 </span><br/>
<span>3 6 1 </span><br/>
<span>6 6 1 </span><br/>
<span>4 5 2 </span><br/>
<span>1 3 0 </span><br/>
<span>6 5 2 </span><br/>
<span>5 1 2 </span><br/>
<span>6 4 3 </span><br/>
<span>4 1 3 </span><br/>
<span>【样例输出2】 </span><br/>
<span>29</span><br/>
<br/>
</span> 
</p>
