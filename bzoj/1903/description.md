
# Description

<div class="content"><p>YY国的人们喜欢将油、盐、酱油、醋掺在一起作为他们最喜欢的“饮品”。作为YY国的一位科学家，你也不例外。 油、盐、酱油、醋的价格分别为c1、c2、c3、c4，如果用量分别为a1、a2、a3、a4，总的价格自然就是a1 c1+a2 c2+a3 c3+a4 c4。 一天，你的一位科学家同事来你家做客，你为他调制了一杯饮品。谁知这种饮品味道极佳，你的同事无论如何都要将其买下。你假惺惺地做了一番规劝后，开始考虑你最多能卖得多少钱。 不幸的是，你们都是科学家，不是家庭主妇，因此对于油盐酱醋的具体价格并不清楚。但是为了让大家都不吃太大的亏，因此饮品的定价取决于唯一的线索：你在一家饮品店的外卖记录：总共有n次，每次都记录了你要求的a1、a3、a4和付的钱v。由于近一段时间盐价波动的非常厉害，因此每次的盐价不尽相同，但是已知所有的（包括这次的） a2 c2都在的区间[L，R]内。同时你们还知道0≤c1≤c3≤c4。 由于你的同事愿望迫切，他希望支付满足条件的情况下最贵的价格。</p></div>

# Input

<div class="content"><p>第一行一个整数T，表示这个故事发生的次数。 对于每组数据，第一行是三个整数n、L、R。 接下来n行，每行四个整数a1、a3、a4、v。 最后一行有三个整数a1、a3、a4表示你所调制的饮品所用的成分。  对于每组数据，输出一行，如果没有合法的价格，则输出“Inconsistent data”；如果解可能为无穷大，则输出“Too expensive!”；否则输出最贵的价格，精确到小数点后4位。</p></div>

# Output

<div class="content"><p>1 3 5 <br/>
1 2 3 10 <br/>
2 4 6 <br/>
1 2 4 <br/>
1 1 1 1 <br/>
1 1 1 <br/>
1 3 8 <br/>
0 1 0 17 <br/>
0 0 1 <br/>
3 1 2 <br/>
2 1 3 14 <br/>
1 5 1 15 <br/>
7 3 2 21 <br/>
4 1 6 <br/>
2 0 2 <br/>
45 31 53 4087 <br/>
30 16 1 1251 <br/>
11 51 34 <br/>
0</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">Case 1: 19.0000<br/>
Case 2: Inconsistent data<br/>
Case 3: Too expensive!<br/>
Case 4: 26.2338<br/>
Case 5: 3440.3088<br/>
<br/>
【数据约定】<br/>
编号	1	2	3	4	5	6	7<br/>
T	7	1000	9	1000	2007	100	4<br/>
n≤	3	5	100	100	100	10	1000<br/>
分数	10	10	20	10	10	10	30<br/>
0≤L≤R≤max{v}≤10000。<br/>
0≤a1、a3、a4≤100。<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p><p>国家队2007GY论文,Acm BeiJing 2007</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢刘汝佳先生授权使用">鸣谢刘汝佳先生授权使用</a></p></div>

