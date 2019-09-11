# 题目描述


<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">柠檬的坦克游戏</span><br/>
<span style="font-size:16px;"></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目背景】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">『Citric杯』NOIP模拟赛 I 第二题</span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目描述】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Lemon最近迷上了一款坦克对战游戏。在这款游戏中，Lemon需要驾驶一辆坦克与敌军对战。坦克有很多不同的武器，每种武器有各自的特点，而Lemon所要做的就是合适地发射这些武器，对敌军造成最大的伤害。具体来说，每个武器都有两个参数：攻击力D和攻击半径R。为了简化题意，我们保证所有武器的攻击力D均不相同，所有武器的攻击半径R也均不相同。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Lemon决定对这些武器的性能进行评价。当然，评价不能只看攻击力D，也不能只看攻击半径R。Lemon觉得一件武器A优于另一件武器B，当且仅当A的攻击力大于B的攻击力且A的攻击半径大于B的攻击半径。</span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">接下来，Lemon想要对武器进行分组，Lemon按照以下方式分组：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">首先，我们定义f(A,S)为真当且仅当在武器集合S中的任何武器都不比武器A性能更优秀。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1.令i=0</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2.令i=i+1 令S=还没被分组的武器集合</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3.对于每一件S中的武器A，如果f(A,S)为真，则将武器A标记为第i组（注意S在这个过程中始终保持不变）</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">4.如果所有武器均被分组则结束，否则转2</span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">给定N个武器的D和R，你的任务是按照Lemon的规则对这些武器进行分组。</span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入文件第一行包含一个正整数N，表示武器的个数。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">接下来N行，每行两个正整数D，R，描述一件武器的攻击力和攻击半径。保证所有的D两两不同，所有的R两两不同。</span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出文件包含N行，每行一个正整数，第i行的数表示第i件武器被分在了哪一组。</span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入样例】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 4</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3 3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">4 1</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5 5</span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出样例】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1</span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例解释】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">首先我们发现武器5比武器1性能更优，所以武器1不在第1组。同理武器2、3、4也不在第1组。但没有武器比武器5性能更优，因此武器5在第1组。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">接下来还剩武器1、2、3、4没被分组。我们发现这些武器中没有武器比武器1更优，于是武器1在第2组，同理武器3、4也在第2组。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">接下来只剩武器2了，武器2在第3组。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">此时所有武器均被分组，过程结束。</span><br/>
<br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【数据规模约定】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">时间限制为1s</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于20%的数据，N&lt;=100.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于40%的数据，N&lt;=3000.</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于100%的数据，N&lt;=100000，1&lt;=R,D&lt;=10^9.</span><br/>
