# 

 
 # 题目描述 
<p>
<br>The pasture contains a small, contiguous grove of trees that has<br>no 'holes' in the middle of the it.  Bessie wonders: how far is it<br>to walk around that grove and get back to my starting position?<br>She's just sure there is a way to do it by going from her start<br>location to successive locations by walking horizontally, vertically,<br>or diagonally and counting each move as a single step. Just looking<br>at it, she doesn't think you could pass 'through' the grove on a<br>tricky diagonal. Your job is to calculate the minimum number of<br>steps she must take.<br><br>Happily, Bessie lives on a simple world where the pasture is<br>represented by a grid with R rows and C columns (1 <= R <= 50, 1<br><= C <= 50). Here's a typical example where '.' is pasture (which<br>Bessie may traverse), 'X' is the grove of trees, '*' represents<br>Bessie's start and end position, and '+' marks one shortest path<br>she can walk to circumnavigate the grove (i.e., the answer):<br><br>...+...<br>..+X+..<br>.+XXX+.<br>..+XXX+<br>..+X..+<br>...+++*<br><br>The path shown is not the only possible shortest path; Bessie might<br>have taken a diagonal step from her start position and achieved a<br>similar length solution. Bessie is happy that she's starting 'outside'<br>the grove instead of in a sort of 'harbor' that could complicate<br>finding the best path.<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: R and C<br><br>* Lines 2..R+1: Line i+1 describes row i with C characters (with no<br>        spaces between them).<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: The single line contains a single integer which is the<br>        smallest number of steps required to circumnavigate the grove.<br></p> 
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
<tr><td>
6 7
.......
...X...
..XXX..
...XXX.
...X...
......*
</td><td>
13</td></tr></table>
