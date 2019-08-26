
# Description

<div class="content"><div style="text-indent: 21pt">小<span>N小A小T是三个好朋友，他们经常在一起玩游戏，这些游戏有比如SC2这种最先进的即时战略游戏，也有斗地主这种古老经典，具有阶级性的游戏！</span></div>
<div style="text-indent: 21pt">今天，受到“<span>8023”的启发，三个人决定在玩斗地主的时候融入一些新的理念。</span></div>
<div style="text-indent: 21pt">小<span>N决定，不再使用原来的牌，而是运用三国杀的设计，采用2种牌的方式。简单来说，一张牌只有两种可能，有用的牌，和没用的牌。</span></div>
<div style="text-indent: 21pt">小<span>A想到了一种新的方式来打牌，当然打牌之前要摸牌，由于三国杀中有一个技能叫做制衡，所以说，他将采取以下的操作来决定手牌。首先他将从小N那里得到M+N张牌，其中有M张有用的牌，N张没用的牌，小A会随机打乱这些牌，接下来他会把牌叠成一叠，每次从上至下依次摸every_time张牌，如果这every_time张牌中有大于等于limit张有用的牌，小A称这<b>牌组</b>是有用的。每次摸完牌，判定后，小A会扔掉这些牌，从那叠牌继续拿every_time张牌，继续接下来的判定。这样子，如果说叠的牌是一定，并且小A可以透视所有的牌叠放的顺序，小A可以算出确定的一个值（他所拿到的有用的牌组数量），也就是他所拿到的所有有用的牌组数量是一定的。当然，小A希望自己可以得到更多的有用的牌组，于是他将采用如下的策略。</span></div>
<div style="text-indent: 21pt">小<span>A每次摸牌之后，也就是在判定的时候（此时小A已经知道自己手上的牌了），他可以选择把手上的牌放回那一叠牌，重新随机打乱，之后，再次摸evert_time张判定，（可以连续打乱），当然，打乱这个操作次数最大值也是有的，random_time。</span></div>
<div style="text-indent: 21pt">小<span>A是怎么样判断自己要不要打乱牌呢？他会想，对于手上和那一叠牌，数学期望的有用牌组数量是多少，当然这个值需要考虑还能随机的次数，如果这个值会比当前手上的牌和那一叠牌，先混在一起，之后再次随机打乱后的数学期望小，他就会选择打乱，这里小A也需要考虑剩余随机的次数对数学期望的影响。</span></div>
<div style="text-indent: 21pt">我们可以打一个比方，如果一叠牌为<span>1100（1为有用，0为无用），有1张或以上则为有用的牌组，小A摸到了11，此时他会选择打乱，为什么呢？因为他知道自己不打乱的数学期望是1，打乱之后就是5/3了。因为打乱后你会摸到1100,1010,1001,0110,0101,0011,（1+2+2+2+2+1）/6 = 5/3了。</span></div>
<div style="text-indent: 21pt">小<span>T没有小A那么聪明，但是由于小N很喜欢小T，于是小N决定让小T在最初的洗牌后，可以看到牌堆放的顺序，这个时候，如果小T想要洗牌的话，小N就会打乱牌，再给小T选择。最多打乱random_time次。</span></div>
<div style="text-indent: 21pt">小<span>T选择是否打乱的方法也很简单，如果当前的答案小于数学期望的话，就打乱吧。这个数学期望是只考虑打乱一次的。</span></div>
<div style="text-indent: 21pt">再次说明，小<span>T的选择方式，简单来说就是开始随机一副牌，然后摊开让小T看到，小T可以算出有多少有用的牌组，如果这个值比期望小，小T就盖上牌，再次随机打乱，之后再摊开进行判定。和小A 的区别在于，他不能每回合的取出看牌，而是一次性决定是否选择当前的牌局。</span></div>
<div style="text-indent: 21pt">同样是<span>1100的例子，小T会打乱，原因和小A类似。</span></div>
<div style="text-indent: 21pt">于是乎，小<span>A，小T想要知道自己有用牌组的数学期望值是多少。</span></div>
<div style="text-indent: 21pt"> </div>
<div><b><span style="font-size: 15pt">输入方式</span></b></div>
<div style="text-indent: 21pt">本题目有多组数据，每个点数据组数不超过<span>1000。</span></div>
<div style="text-indent: 21pt">第一行有一个正整数<span>tot，表示有几组数据。</span></div>
<div style="text-indent: 21pt">接下来每一行有六个正整数<span>M，N，every_time，random_time,limit，case。如果case = 1，则你是小A，否则case = 2，你是小T。数据保证(M + N) mod every_time = 0。</span></div>
<div>输出方式</div>
<div style="text-indent: 21pt">对于每一个询问输出一行，数学期望，保留<span>6位小数。</span></div>
<div><b><span style="font-size: 16pt">样例</span></b></div>
<div style="text-indent: 21pt">输入</div>
<div style="text-indent: 21pt">2</div>
<div style="text-indent: 21pt">2 2 2 1 1 1</div>
<div style="text-indent: 21pt">5 4 3 4 9 4</div>
<div style="text-indent: 21pt">输出</div>
<div style="text-indent: 21pt">1.888889</div>
<div style="text-indent: 21pt">1.994791</div>
<div style="text-indent: 21pt">解释：第一个数据，如果是<span>0011或者1100则选择打乱。</span></div>
<div><b><span style="font-size: 15pt">规模</span></b></div>
<div style="text-indent: 21pt">40%的数据<span>case = 1，此时</span></div>
<div style="text-indent: 21pt">10%的数据<span> M &lt;= 5,N &lt;= 5,random_time &lt;= 10</span></div>
<div style="text-indent: 21pt">30%的数据<span> M &lt;= 12 N &lt;= 12 random_time &lt;= 20</span></div>
<div style="text-indent: 21pt">对于<span>40%的数据case = 2 此时</span></div>
<div style="text-indent: 21pt">10%的数据<span> M &lt;= 12,N &lt;= 12,random_time &lt;= 10</span></div>
<div style="text-indent: 21pt">30%的数据<span> M &lt;= 12,N &lt;= 12,random_time &lt;= 1000000000</span></div>
<div style="text-indent: 21pt">接下来的<span>40%数据包含了case = 1 和 case = 2，且数据规模为各自较大者。</span></div>
<div><b><span style="font-size: 15pt">hint</span></b></div>
<div style="text-indent: 21pt">这道题希望大家做的开心！</div>
<div style="text-indent: 21pt">如果第二个样例挂了希望大家仔细再次读题思考。</div></div>

# Input

<div class="content"></div>

# Output

<div class="content"></div>

# Sample Input

<div class="content"><span class="sampledata"></span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p><p> 此题题面存在严重问题，建议不要做！</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

