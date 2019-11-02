# 

 
 # 题目描述 
<p>
Bessie and the rest of Farmer John's cows are taking a trip this<br>winter to go skiing.  One day Bessie finds herself at the top left<br>corner of an R (1 <= R <= 100) by C (1 <= C <= 100) grid of elevations<br>E (-25 <= E <= 25). In order to join FJ and the other cows at a<br>discow party, she must get down to the bottom right corner as quickly<br>as she can by travelling only north, south, east, and west.<br><br>Bessie starts out travelling at a initial speed V (1 <= V <=<br>1,000,000).  She has discovered a remarkable relationship between<br>her speed and her elevation change.  When Bessie moves from a<br>location of height A to an adjacent location of height B, her speed<br>is multiplied by the number 2^(A-B).  The time it takes Bessie to<br>travel from a location to an adjacent location is the reciprocal<br>of her speed when she is at the first location.<br><br>Find the both smallest amount of time it will take Bessie to join<br>her cow friends and the number of moves required by the path (a<br>move is a transition from one location to another adjacent location).<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Three space-separated integers: V, R, and C, which<br>        respectively represent Bessie's initial velocity and the<br>        number of rows and columns in the grid.<br><br>* Lines 2..R+1: C integers representing the elevation E of the<br>        corresponding location on the grid.<br><br></p> 

 
 # 输出格式 
<p>
A single number value, printed to two exactly decimal places: the<br>minimum amount of time that Bessie can take to reach the bottom right<br>corner of the grid.<br><br></p> 
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
<tr><td>1 3 3  //奶牛开始在左上角，速度为1,它可以移动到别的格子上，速度会发生变化
1 5 3 //这个3*3的数矩阵代表每个格子的参数，当从一个格子A到B时，速度变成V*2^(A-B)
6 3 5
2 4 3
</td><td>29.00

OUTPUT DETAILS:

Bessie's best route is:
	Start at 1,1 time  0 speed 1
	East  to 1,2 time  1 speed 1/16
	South to 2,2 time 17 speed 1/4
	South to 3,2 time 21 speed 1/8
	East  to 3,3 time 29 speed 1/4</td></tr></table>
