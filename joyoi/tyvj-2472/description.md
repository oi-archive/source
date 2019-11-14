# 

 
 # 题目描述 
<p>
The cows have taken up alphabetical jigsaw puzzles. In these puzzles<br>with R (1 <= R <= 10) rows and C (1 <= C <= 10) columns, the edges<br>are not funny-shaped cardboard shapes but rather are letters.<br><br>Each piece has a serial number and 4 letters (or borders) that must<br>be aligned as in a regular jigsaw puzzle. The pseudo-letter '0'<br>(the digit 0) will represent a border (and a piece can have several<br>borders if it is a corner piece or even the top of column in a,<br>e.g., 4x1 puzzle).  Below is a set of six pieces (the borders are<br>marked with lines instead of '0's) assembled in one way (of many)<br>that completes the puzzle:<br><br>              +---+  +---+  +---+<br>              | 1 c  c 3 d  d 5 |<br>              +-d-+  + a +  +-e-+<br><br>              +-d-+  +-a-+  +-e-+<br>              | 2 b  b 4 b  b 6 |<br>              +---+  +---+  +---+<br><br>Note that each edge letter of each piece matches the border letter<br>of the piece adjacent to it; the borders appear properly on the top,<br>bottom, and sides.<br><br>Pieces are represented by a serial number and a clockwise list of<br>their four edges (where edges are the letters a..z and 0). Pieces<br>might require rotation when placed in the puzzle.<br><br>Given a set of pieces, find at least one way to assemble them into<br>a puzzle. Test data for puzzles with larger R and C are easier to<br>solve because they have a more varied set of edge letters.<br><br>奶牛们玩字母拼图游戏，拼图有R(1<=R<=10)行C(1<=C<=10)列，每个格子有上下左右4条边，<br>边可以是abcd四种字母或边界（用'0' 表示），如图是一种拼法。<br>注意到两个相邻格子所对的边上的字母互相匹配，边界出现在拼图的上下左右边缘上。<br>每个格子用序号表示，按顺时针方向给出它们的四条边，可以旋转。要求找出一组可行解。<br>输入 ： 第一行R,C。接下来2..R*C+1行，每行描述一个格子，第一个数是它的序号，接下来四个数为它的四条边。<br>输出 ： 共R*C行，第(i-1)*C+j行5个数，第一个数为放在（i，j)处的格子序号，接下来按上右下左的顺序为它的四条边。</p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: R and C<br><br>* Lines 2..R*C+1: Each line contains five space-separated entities: an<br>        integer serial number and four edge identifiers<br><br></p> 

 
 # 输出格式 
<p>
* Lines 1..R*C: Line R*(i-1)+j describes the puzzle piece placed a row<br>        i, column j with an integer and five space-separated entities:<br>        the serial number of the puzzle piece and the four piece edge<br>        identifiers in the order top, right, bottom, left.<br><br></p> 
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
<tr><td>2 3
1 c d 0 0
2 0 d b 0
3 c 0 d a
4 b a b 0
5 d 0 0 e
6 0 0 b e

INPUT DETAILS:

Describes the input puzzle although with some of the pieces rotated
compared to the sample solution.


</td><td>1 0 c d 0
3 0 d a c
5 0 0 e d
2 d b 0 0
4 a b 0 b
6 e 0 0 b

OUTPUT DETAILS:

As shown in the diagram in the task text. Other solutions (like
reflections) are possible; a grading program will check your answer.
</td></tr></table>
