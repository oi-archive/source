# 

 
 # 题目描述 
<p>
<br>Farmer John has set up a puzzle for his cows to solve.  At the<br>entrance to the barn, he has laid out an H x W (1 <= H <= 30, 1 <=<br>W <= 30) grid of letters.  Before a cow can enter the barn, she<br>must spell out a valid English word by jumping from square to square,<br>creating a sequence of letters.  She can start at any square but<br>may only jump to a subsequent square that is located to the right<br>and/or above the current square (i.e., neither to the left nor<br>lower).  The next square can be any distance from the current one<br>since the cows are world-class jumpers!<br><br>No two cows may traverse the exact same path, although two cows are<br>allowed to spell the same word via different paths.<br><br>As an example, consider this grid (presuming 'TO' and 'OX' are<br>words):<br><br>  T X X O<br>  T X Q T<br>  X T X Q<br><br>Four paths are valid, all spelling 'TO' (one spelling requires a<br>'T' from the bottom row and an 'O' from the top row).  'OX' is a<br>valid word, but would require jumping to an 'X' square left of the<br>'O', which is not allowed.<br><br>Given the grid and a list of valid words, compute the number of<br>cows that can enter the barn without any cow repeating a path.  The<br>file `dict.txt' will be available and will contain the list of valid<br>words, one per line. See a copy of it at<br>http://ace.delos.com/usaco/dict-twalk.txt .<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: Two integers: H and W<br><br>* Lines 2..H+1: Each line contains W characters, without spaces,<br>        representing a row in the grid.  The first row is the top row.<br>         The first character in each row is the left-most character.<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: The number of cows that can enter the barn without repeating<br>        a path.<br><br></p> 
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
<tr><td>3 4
TXXO
TXQT
XTXQ
</td><td>4

OUTPUT DETAILS:

4 cows can enter the barn, each one spelling out one of the 'TO's.</td></tr></table>
