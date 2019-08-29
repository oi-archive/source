<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　在星历2012年，星灵英雄Zeratul预测到他所在的Aiur行星在M天后会发生持续性暴雨灾害，尤其是他们的首都。而Zeratul作为星灵族的英雄，当然是要尽自己最大的努力帮助星灵族渡过这场自然灾害。<br/>
　　要渡过这场自然灾害，Zeratul自然要安排很多很多事情，其中一件就是将雨水疏导到大海里去。星灵族在重建家园的时候建造了N条河流，这些河流连接了共N+1个城市，当然其中包括了星灵首都。城市的编号为0…N，星灵首都的编号为0。<br/>
　　当然水流是有方向的，除了星灵首都以外，其余的城市都有且仅有一条河流流入。如果一个城市没有流出去的河流，那么这个城市就是一个沿海城市，可以认为流入这个城市的河流是直接流入大海的。<br/>
　　聪明的星灵族在建造河流的时候是不会让其出现环状结构的，也就是说所有的河流都是能够流入大海的。<br/>
　　每一条河流都是有一个最大流量的，一旦超过这个最大流量，就会发生洪水灾害。因此从星灵首都流入大海的总水流量是有一个最大值的。<br/>
　　例如有3条河流：第一条是从城市0流向城市1，最大流量为4；第二条是从城市1流向城市2，最大流量为2；第三条是从城市1流向城市3，最大流量为3。此时从星灵首都(城市0)流入大海的总水流量最大为4，方案有两种：<br/>
　　A. 第一条河流的流量为4，第二条河流的流量为2，第三条河流的流量为2。<br/>
　　B. 第一条河流的流量为4，第二条河流的流量为1，第三条河流的流量为3。<br/>
　　由于离暴雨到来还有时间，因此Zeratul可以扩大某些河流的最大流量来使得从星灵首都流入大海的总水流量增大。比如将上面这个例子的第一条河流的最大流量增大1，那么从星灵首都流入大海的总流水量也可以增大1，变成了5。<br/>
　　当然将河流的最大流量扩大是需要时间的，将一条河流的最大流量扩大1所需要的时间为1天。离暴雨到来还有M天，因此Zeratul也有M天的时间来扩大河流的最大流量。<br/>
　　不过由于河流周围的地形限制，每条河流并不是能够无限扩大的，因此每条河流的可以扩大到的最大流量也是有限制的。<br/>
　　而此时Zeratul正忙着安排别的工作，因此他将这个艰巨的任务交给了你。你需要安排一种方案，使得从星灵首都流入大海的总水流量最大。不过现在你只需要告诉Zeratul这个最大值即可。</div>
# 输入格式

<div class="pdcont">　　输入文件的第一行包含一个正整数N和一个非负整数M。其中N表示河流的个数，M表示离暴雨到来还剩下的天数。<br/>
　　接下来N行，每行四个正整数U、V、A、B。其中U和V为该河流所连接的两个城市，且河流的水流方向为从城市U流向城市V，A和B表示该河流当前的最大流量和可以扩大到的最大流量的上限。<br/>
　　输入数据保证合法。</div>
# 输出格式

<div class="pdcont">　　输出仅包含一个整数，表示从星灵首都流入大海的最大总水流量。</div>
# 样例输入

<div class="pddata">5 7<br/>
0 1 4 8<br/>
0 4 1 6<br/>
1 2 2 10<br/>
1 3 3 5<br/>
4 5 6 6</div>
# 样例输出

<div class="pddata">11</div>
# 数据规模和约定

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">数据编号<br/>
</td><td valign="top" style="border:solid 1.0pt"><i>N</i><br/>
</td><td valign="top" style="border:solid 1.0pt"><i>M</i><br/>
</td><td valign="top" style="border:solid 1.0pt">数据编号<br/>
</td><td valign="top" style="border:solid 1.0pt"><i>N</i><br/>
</td><td valign="top" style="border:solid 1.0pt"><i>M</i><br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">≤100<br/>
</td><td valign="top" style="border:solid 1.0pt">0<br/>
</td><td valign="top" style="border:solid 1.0pt">6<br/>
</td><td valign="top" style="border:solid 1.0pt">≤1000<br/>
</td><td valign="top" style="border:solid 1.0pt">≤100<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">2<br/>
</td><td valign="top" style="border:solid 1.0pt">≤100<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">7<br/>
</td><td valign="top" style="border:solid 1.0pt">≤1000<br/>
</td><td valign="top" style="border:solid 1.0pt">≤1000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">3<br/>
</td><td valign="top" style="border:solid 1.0pt">≤1000<br/>
</td><td valign="top" style="border:solid 1.0pt">1<br/>
</td><td valign="top" style="border:solid 1.0pt">8<br/>
</td><td valign="top" style="border:solid 1.0pt">≤10000<br/>
</td><td valign="top" style="border:solid 1.0pt">≤10000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">4<br/>
</td><td valign="top" style="border:solid 1.0pt">≤100<br/>
</td><td valign="top" style="border:solid 1.0pt">≤100<br/>
</td><td valign="top" style="border:solid 1.0pt">9<br/>
</td><td valign="top" style="border:solid 1.0pt">≤10000<br/>
</td><td valign="top" style="border:solid 1.0pt">≤1000000<br/>
</td></tr><tr style="border:solid 1.0pt"><td valign="top" style="border:solid 1.0pt">5<br/>
</td><td valign="top" style="border:solid 1.0pt">≤1000<br/>
</td><td valign="top" style="border:solid 1.0pt">≤100<br/>
</td><td valign="top" style="border:solid 1.0pt">10<br/>
</td><td valign="top" style="border:solid 1.0pt">≤10000<br/>
</td><td valign="top" style="border:solid 1.0pt">≤1000000<br/>
</td></tr></tbody></table><br/>
　　所有测试点均满足1≤A≤B≤100000。</div>

</div>