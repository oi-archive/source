# 

 
 # 题目描述 
<p>
Those Who Know About Cows are aware of the way cows group into "Cow <br>Neighborhoods". They have observed Farmer John's N (1 <= N <= <br>100,000) cows (conveniently numbered 1..N) as they graze, each at <br>her own unique integer rectilinear coordinate, on a pasture whose <br>X and Y coordinates are in the range 1..1,000,000,000. <br><br>Two cows are neighbors if at least one of two criteria is met: <br><br>1) If the cows are no further than some integer Manhattan distance <br>C (1 <= C <= 1,000,000,000) apart, they are neighbors. [Manhattan <br>distance is calculated as d = |x1-x2| + |y1-y2|.] <br><br>2) If cow A is a neighbor of cow Z and cow B is a neighbor of cow <br>Z, then cow A is a neighbor of cow B (the "transitive closure <br>of neighbors"). <br><br>Given the locations of the cows and the distance C, determine the <br>the number of neighborhoods and the number of cows in the largest <br>neighborhood. <br><br>By way of example, consider the pasture below. When C = 4, this <br>pasture has four neighborhoods: a big one on the left, two neighborhoods <br>of size 1 (the lonesome cows), and a huge neighborhood on the right <br>with 60 different cows. <br><br>.....................................*................. <br>....*...*..*.......................***................. <br>......*...........................****................. <br>..*....*..*.......................*...*.******.*.*..... <br>........................*.............***...***...*.... <br>*..*..*...*..........................*..*...*..*...*... <br>.....................................*..*...*..*....... <br>.....................................*..*...*..*....... <br>...*................*.................................. <br>.*..*............................*.*.*.*.*.*.*.*.*.*.*. <br>.*.....*..........................*.*.*.*.*.*.*.*.*.*.* <br>....*.................................................. <br><br>The input file describes cow locations by integer X,Y coordinates, <br>where the lower left corner is (1,1) and cows close to that corner <br>appear at both (2,2) and (5,1) in the example above. <br><br>For a given pasture, determine both the number of cow neighborhoods <br>and the number of cows resident in the largest cow neighborhood. <br><br>The above picture is sample test case 2, which will be evaluated <br>for you upon submission. <br><br>Partial feedback for some test cases will be provided on the first <br>10 submissions. <br><br>给出N头牛的坐标，以及一个常数C <br>两头牛A和B满足下面两个条件中至少一个，便是邻居 <br>1：两者之间的距离小于C,距离为计算为两者横纵坐标差的绝对差 <br>2：存在奶牛C，便奶牛A和C是邻居，奶牛B和C也是邻居， <br><br>请找出有多少个奶牛群，以及最大的群中有多少头牛.<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: N and C <br>* Lines 2..N+1: Line i+1 describes cow i's location with two <br>space-separated integers: X_i and Y_i <br></p> 

 
 # 输出格式 
<p>
* Line 1: A single line with a two space-separated integers: the <br>number of cow neighborhoods and the size of the largest cow <br>neighborhood. <br><br></p> 
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
<tr><td>4 2
1 1
3 3
2 2
10 10

* Line 1: A single line with a two space-separated integers: the
        number of cow neighborhoods and the size of the largest cow
        neighborhood.



</td><td>2 3

OUTPUT DETAILS:
There are 2 neighborhoods, one formed by the first three cows and
the other being the last cow. The largest neighborhood therefore
has size 3.
</td></tr></table>
