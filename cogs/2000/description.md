# 题目描述


<p>
【题目描述】
</p>
<p>
<br/>
</p>
<p>
Single dog
</p>
<p>
single dog
</p>
<p>
single all the day
</p>
<p>
See the AV
</p>
<p>
hit the plane
</p>
<p>
they&#39;re doing all the day     <img src="/upload/image/20151029/20151029081519_31067.jpg" alt="" height="429" width="645"/> 
</p>
<p>
Hey
</p>
<p>
Single dog
</p>
<p>
single dog
</p>
<p>
why not be a gay
</p>
<p>
No more wait
</p>
<p>
no more afraid
</p>
<p>
make him be a gay--刘晨晨
</p>
<p>
<br/>
</p>
<p>
很久很久以前，在遥远的南方的阿里木多大陆，一群单身狗无忧无虑的生活着，与世隔绝，怡然自得
</p>
<p>
可以是有一天，一群自称“情侣教会”的组织突然袭击了阿里木多大陆，科技无比落后的单身狗们迅速被击败。
</p>
<p>
情侣教会建立了殖民帝国，用独裁和高压手段统治单身狗们。
</p>
<p>
然而随着北方所谓“民主”、“科学”思想的传入，单身狗们似乎有了觉醒的姿态，一系列抗议、游行引起了社会骚乱。
</p>
<p>
此时帝国的皇帝为黄小明·阿卜杜拉二世，皇后为安杰拉·卑鄙
</p>
<p>
他们打算用残酷的手段来警示单身狗们造反的后果，为此，帝国的首相奉皇后之命要举办一场虐狗大赛。
</p>
<p>
他从巴士迪监狱里拖出来了N条被逮捕的反动的单身狗(4&lt;=n&lt;=100000),让他们站成一排。
</p>
<p>
许多情侣来参加这场大赛，他们以各种姿势、各种方法在单身狗面前秀恩爱，并且在情侣中央广播电视台现场直播。每对情侣对i号单身狗和j号单身狗为两端组成的子序列的单身狗造成k吨伤害。
</p>
<p>
每个单身狗都有两个参数：心理状态值H和心理承受能力D
</p>
<p>
单身狗受到的实际伤害为k-D(H-=(k-D)),若实际伤害小于0，则反而能参加H
</p>
<p>
在几段攻击之后首相要求实时更新每个单身狗的H，输出在大屏幕上。（更新次数很少）
</p>
<p>
【输入格式】
</p>
<p>
第一行一个正整数n
</p>
<p>
第二行为H1,H2,H3.....Hn
</p>
<p>
第三行为D1,D2,D3.....Dn
</p>
<p>
第四行一个正整数q,表示q次操作
</p>
<p>
5-q+6行，每行第一个数为0或1
</p>
<p>
若为0接下来三个数i,j,k
</p>
<p>
若为1表示更新
</p>
<p>
【输出格式】
</p>
<p>
每次更新输出所有单身狗的H，每次输出一行
</p>
<p>
【样例输入】
</p>
<p>
4
</p>
<p>
1 2 3 4
</p>
<p>
1 3 2 1
</p>
<p>
5
</p>
<p>
0 1 2 4
</p>
<p>
0 2 3 3
</p>
<p>
1
</p>
<p>
0 1 1 0
</p>
<p>
1
</p>
<p>
【样例输出】
</p>
<p>
-2 1 2 4
</p>
<p>
-1 1 2 4
</p>
<p>
【提示】
</p>
<p>
第一次攻击输出为4，对1号实际伤害为4-1=3，对2号实际伤害为4-3=1
</p>
<p>
第二次攻击输出为3，对2号实际伤害为0，对3号实际伤害为1
</p>
<p>
第三次攻击输出为0，对1号实际伤害为-1，使得H1增大1
</p>
<p>
对于20%的数据,n&lt;=1024,q&lt;=1024
</p>
<p>
对于另外20%的数据，Di=0;
</p>
<p>
对于另外10%的数据, 所有Di相同
</p>
<p>
对于100%的数据，n&lt;=100005,q&lt;=10050,更新次数&lt;=50
</p>
<p>
【来源】
</p>
<br/>
