<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　没头脑和不高兴是一对形影不离的好朋友，他们一起上学也一起玩耍。<br/>
　　这天，这对好朋友聚在一起玩纸牌游戏。他们所玩的纸牌总共有N张，每一张上面都有一个1~N的数字，任意两张纸牌上的数字都不相同。根据他们制定的游戏规则，在每局游戏的开始，所有的牌需要按照从1~N的顺序排好。在开心地玩完了一局牌之后，他们发现牌的顺序被弄得乱七八糟，将它们排好序是一件挺麻烦的事情。<br/>
　　他们将凌乱的纸牌在桌面上排成一排，然后开始了排序工作。不高兴由于在上一局游戏中输了牌，非常不高兴。他只将其中<b><i>奇数位置</i></b>的牌排成了升序，然后把剩下的任务推给了没头脑。没头脑非常没头脑，他采取了一个有些笨的排序方式。每次，他找到两张相邻并且顺序不对的牌交换它们，直到整个序列被排好序为止。<br/>
　　乐于探究的你，想要研究在初始排列随机的情况下没头脑花在交换纸牌上的时间。假设没头脑每交换一对纸牌花费的时间为1，你希望求出他排序时间的期望。此外，为了更好地分析这个问题，你还希望能够计算出所花时间的方差。更进一步地，如果<b><i>被不高兴排好序的位置发生了变化</i></b>，你是否还能求出没头脑用来排序时间的期望呢？</div>
# 输入格式

<div class="pdcont">　　输入文件共M+1行。<br/>
　　第一行包含两个正整数N,M。<br/>
　　接下来M行，每行包含三个整数l,r,v。其中1&lt;=l&lt;=r&lt;=n，v∈{0,1}。若v=0则表示不高兴不再对l到r之间的位置排序；反之若v=1则表示被不高兴排序的位置将涵盖l到r。</div>
# 输出格式

<div class="pdcont">　　输出文件共M+2行。每行输出一个形如p/q的有理数，其中(p,q)=1，q&gt;=1，p,q∈Z。<br/>
　　第一行输出在初始条件下没头脑排序时间的期望。<br/>
　　第二行输出在初始条件下没头脑排序时间的方差。<br/>
　　接下来M行，每行分别输出在对不高兴排序的位置进行了前若干次修改之后没头脑排序时间的期望。</div>
# 样例输入

<div class="pddata">3 3<br/>
2 3 0<br/>
2 2 1<br/>
1 3 1</div>
# 样例输出

<div class="pddata">2/3<br/>
2/9<br/>
3/2<br/>
1/1<br/>
0/1</div>
# 样例说明

<div class="pdcont">　　在初始条件下，不高兴会将位置1和3的纸牌排好顺序。对于排列(1,2,3)和(3,2,1)，他将排列成(1,2,3)，没头脑不需要操作；对于排列(1,3,2)和(2,3,1)，他将排列成(1,3,2) ，没头脑需要交换一次；对于排列(2,1,3)和(3,1,2)，他将排列成(2,1,3)，没头脑需要交换一次。因此没头脑所花的时间期望为(0*2+1*2+1*2)/6=2/3；方差为( (0-2/3)^2*2+(1-2/3)^2*2+(1-2/3)^2*2 )/6=2/9。<br/>
　　在进行了第一次修改之后，不高兴会只对位置1排序，这和没有排序的效果一样；第二次修改之后，他会对位置1,2排序；最后一次修改之后，他会对位置1,2,3排序，这样没头脑完全不用参与排序工作。可据此求出对应情况下没头脑排序时间的期望。</div>
# 评分标准

<div class="pdcont">　　如果选手的前两行正确，其余行出现错误，可以得到40%的分数。<br/>
　　如果选手的前两行出现错误，其余行正确，可以得到50%的分数。<br/>
　　如果选手的所有行输出完全正确，可以得到100%的分数。<br/>
　　其余情况选手不得分。</div>
# 数据规模和约定

<div class="pdcont"><table cellspacing="0" cellpadding="2px" style="border-collapse:collapse;" class="table table-striped table-horver"><tbody><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">测试点编号<br/>
</td><td style="border:solid 1.0pt"><i>N</i><br/>
</td><td style="border:solid 1.0pt">M<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">1<br/>
</td><td style="border:solid 1.0pt"><i>N</i> = 4<br/>
</td><td style="border:solid 1.0pt"><i>M </i>= 10<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">2<br/>
</td><td style="border:solid 1.0pt"><i>N</i> = 11<br/>
</td><td style="border:solid 1.0pt"><i>M </i>= 100<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">3<br/>
</td><td style="border:solid 1.0pt"><i>N</i> = 100<br/>
</td><td style="border:solid 1.0pt"><i>M </i>=10^3<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">4<br/>
</td><td style="border:solid 1.0pt"><i>N</i> = 1001<br/>
</td><td style="border:solid 1.0pt"><i>M </i>=10^4<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">5<br/>
</td><td style="border:solid 1.0pt"><i>N</i> = 78590<br/>
</td><td rowspan="6" style="border:solid 1.0pt"><i>M </i>=10^5<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">6<br/>
</td><td style="border:solid 1.0pt"><i>N</i> = 87933<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">7<br/>
</td><td style="border:solid 1.0pt"><i>N</i> = 95000<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">8<br/>
</td><td style="border:solid 1.0pt"><i>N</i> = 99445<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">9<br/>
</td><td style="border:solid 1.0pt"><i>N</i> = 99999<br/>
</td></tr><tr style="border:solid 1.0pt"><td style="border:solid 1.0pt">10<br/>
</td><td style="border:solid 1.0pt"><i>N</i> = 100000<br/>
</td></tr></tbody></table></div>

</div>