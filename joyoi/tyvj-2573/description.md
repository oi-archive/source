# 

 
 # 题目描述 
<p>
Like everyone else, cows like to stand close to their friends when<br>queuing for feed.  FJ has N (2 <= N <= 1,000) cows numbered 1..N<br>standing along a straight line waiting for feed. The cows are<br>standing in the same order as they are numbered, and since they can<br>be rather pushy, it is possible that two or more cows can line up<br>at exactly the same location (that is, if we think of each cow as <br>being located at some coordinate on a number line, then it is <br>possible for two or more cows to share the same coordinate).<br><br>Some cows like each other and want to be within a certain distance<br>of each other in line. Some really dislike each other and want to<br>be separated by at least a certain distance. A list of ML (1 <= ML<br><= 10,000) constraints describes which cows like each other and the<br>maximum distance by which they may be separated; a subsequent list<br>of MD constraints (1 <= MD <= 10,000) tells which cows dislike each<br>other and the minimum distance by which they must be separated.<br><br>Your job is to compute, if possible, the maximum possible distance<br>between cow 1 and cow N that satisfies the distance constraints.<br><br>当排队等候喂食时，奶牛喜欢和它们的朋友站得靠近些。FJ有N（2<=N<=1000）头奶牛，编号从1到N，沿一条直线站着等候喂食。奶牛排在队伍中的顺序和它们的编号是相同的。因为奶牛相当苗条，所以可能有两头或者更多奶牛站在同一位置上。即使说，如果我们想象奶牛是站在一条数轴上的话，允许有两头或更多奶牛拥有相同的横坐标。<br>一些奶牛相互间存有好感，它们希望两者之间的距离不超过一个给定的数L。另一方面，一些奶牛相互间非常反感，它们希望两者间的距离不小于一个给定的数D。给出ML条关于两头奶牛间有好感的描述，再给出MD条关于两头奶牛间存有反感的描述。（1<=ML,MD<=10000，1<=L,D<=1000000）<br>你的工作是：如果不存在满足要求的方案，输出-1；如果1号奶牛和N号<br>奶牛间的距离可以任意大，输出-2；否则，计算出在满足所有要求的情况下，1号奶牛和N号奶牛间可能的最大距离。<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Three space-separated integers: N, ML, and MD.<br><br>* Lines 2..ML+1: Each line contains three space-separated positive<br>        integers: A, B, and D, with 1 <= A < B <= N. Cows A and B must<br>        be at most D (1 <= D <= 1,000,000) apart.<br><br>* Lines ML+2..ML+MD+1: Each line contains three space-separated<br>        positive integers: A, B, and D, with 1 <= A < B <= N. Cows A<br>        and B must be at least D (1 <= D <= 1,000,000) apart.<br><br>第一行：三个空间分隔的整数：N，ML，和MD<br>第二行至第ML+1行：每行包含三个空间分隔的正整数：A，B和D，其中1<= A <B <= N。表示牛A和牛B必须在距离D（1 <= D <= 1,000,000）之内。<br>第ML+2至第ML+MD+1行：每行包含三个空间分隔的正整数：A，B和D，其中1 <= A <B <= N。表示牛A和牛B必须在距离D（1 <= D <= 1,000,000）之外。<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: A single integer. If no line-up is possible, output -1.  If<br>        cows 1 and N can be arbitrarily far apart, output -2. <br>        Otherwise output the greatest possible distance between cows 1<br>        and N.<br><br>输出一个整数。<br>如果不可能安排奶牛的布局，输出-1。<br>如果奶牛1和奶牛N可以相距任意距离，输出-2。<br>否则输出奶牛1和奶牛N之间的最大距离。<br></p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>4 2 1
1 3 10
2 4 20
2 3 3

INPUT DETAILS:

There are 4 cows.  Cows #1 and #3 must be no more than 10 units
apart, cows #2 and #4 must be no more than 20 units apart, and cows
#2 and #3 dislike each other and must be no fewer than 3 units apart.

有4头奶牛。奶牛1和奶牛3必须在10个单位之内，奶牛2和奶牛4必须在20个单位之内，奶牛2和奶牛3不喜欢对方，必须在3个单位之外。

</td><td>27

OUTPUT DETAILS:

The best layout, in terms of coordinates on a number line, is to put cow #1
at 0, cow #2 at 7, cow #3 at 10, and cow #4 at 27.

最好的布局是，在同一条坐标上，把奶牛1放在0处，把奶牛2放在7处，把奶牛3放在10处，把奶牛4放在27处。</td></tr></table>
