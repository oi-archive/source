# 

 
 # 题目描述 
<p>
<br>Farmer John's cows thoroughly enjoy throwing pebbles into the lake<br>next to their grazing field. When a pebble hits the surface of the<br>lake, it generates a wave that propagates across the surface of the<br>lake.<br><br>The surface of the lake is represented by a large grid of squares.<br>The water at each square is at some depth, which is determined by<br>the interaction of the waves.  Before any pebbles are dropped, every<br>square (except those on the original river banks) has a depth of<br>0.  When displayed, each square will be represented as follows:<br><br>     o Square has a depth < 0<br>     - Square has a depth = 0<br>     * Square has a depth > 0<br>     X Square is part of the original river bank<br><br>When a pebble in dropped into the lake it causes a wave of raised<br>water to spread out in a diamond pattern that grows every second.<br>The depth of each square in the diamond is increased by 1 for just<br>one single second. This wave is followed two seconds later by a<br>wave of lowered water (depth decreased by 1) which also spreads out<br>as a diamond.  Each pebble causes only two waves, the raised wave<br>followed by the lowered wave.<br><br>For example, the diagram below shows the effect of a pebble dropped<br>in the middle of the lake at time intervals of 0, 1, 2 and 3 seconds:<br>after it is dropped:<br><br>0 seconds   1 second    2 seconds   3 seconds<br> -------     -------     -------     ---*---<br> -------     -------     ---*---     --*-*--<br> -------     ---*---     --*-*--     -*-o-*-<br> ---*---     --*-*--     -*-o-*-     *-o-o-*<br> -------     ---*---     --*-*--     -*-o-*-<br> -------     -------     ---*---     --*-*--<br> -------     -------     -------     ---*---<br><br>The river banks have fixed x co-ordinates and run for the entire<br>length (top to bottom) of the lake with a width of a single square.<br>When a wave reaches a river bank, rather than carrying on, it<br>continues to grow but the part that hits the bank is reflected.<br><br>The early seconds of a wave hitting one of the river banks are shown<br>below. To make the picture clearer, the second wave of lowered water<br>is not shown:<br><br>1 second    2 seconds   3 seconds   4 seconds   5 seconds<br> X------     X------     X--*---     X-*-*--     X*---*-<br> X------     X--*---     X-*-*--     X*---*-     X*----*<br> X--*---     X-*-*--     X*---*-     X*----*     X-*----<br> X-*-*--     X*---*-     X*----*     X-*----     X--*---<br> X--*---     X-*-*--     X*---*-     X*----*     X-*----<br> X------     X--*---     X-*-*--     X*---*-     X*----*<br> X------     X------     X--*---     X-*-*--     X*---*-<br><br>When sections of waves meet they have no effect on the way each<br>other propagates. In other words, at the next clock tick the waves<br>will grow as though there was no encounter. Note however that their<br>effects are combined on the lake.  For example:<br><br> 1 second      2 seconds     3 seconds     4 seconds<br> ---------     ---------     ---------     ---*-----<br> ---------     ---------     ---*-----     --*-*-*--<br> ---------     ---*-----     --*-*-*--     -*-o-*-*-<br> ---*-----     --*-*-*--     -*-o-*-*-     *-o-----*<br> --*-*-*--     -*-o-*-*-     *-o-----*     -o-*-o---<br> ---*-----     --*-*-*--     -*-o-*-*-     *-o-----*<br> ---------     ---*-----     --*-*-*--     -*-o-*-*-<br> ---------     ---------     ---*-----     --*-*-*--<br> ---------     ---------     ---------     ---*-----<br><br>Write a program to help the cows figure out how the waves will<br>spread out over time.<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Four space-separated integers: P, B1, B2, and R:<br><br>      * P (1 <= P <= 5) indicates the number of pebbles,<br><br><br>      * B1 (-500,000 <= B1 <= 500,000) and B2 (-500,000 <= B2 <= 500,000)<br>        are the x co-ordinates of two river banks, and<br><br><br>      * R (1 <= R <= 500,000) the time at which you are to display the lake.<br><br><br>      No two pebbles will be dropped at the same position at the<br>      same time.  The two banks will have different x co-ordinates,<br>      and no pebble will be dropped on a bank.<br><br>* Lines 2..P+1: Each line contains three space-separated integers that<br>        describe a pebble: X (-500,000 <= X <= 500,000), Y (-500,000<br>        <= Y <= 500,000), and and T (1 <= T <= 500,000)<br><br>      * X and Y are the coordinates where a pebble is dropped<br><br>      * T is the time at which the pebble is dropped<br><br></p> 

 
 # 输出格式 
<p>
* Lines 1..9: The output contains a 9 x 9 grid, centered on 0,0. The<br>        bottom left of the grid represents (-4, -4) and the top right<br>        represents (4,4). The grid should represent the state of the<br>        lake at time R.<br><br></p> 
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
<tr><td>2 4 100 4
-3 0 1
0 0 2
</td><td>
--------X
-*------X
*-*-*---X
-o-*-*--X
o-----*-X
-o-*-*--X
*-*-*---X
-*------X
--------X</td></tr></table>
