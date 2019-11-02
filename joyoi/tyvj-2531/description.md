# 

 
 # 题目描述 
<p>
<br>A crime has been comitted: a load of grain has been taken from the barn by<br>one of FJ's cows.  FJ is trying to determine which of his C (1 <= C <=<br>100) cows is the culprit.  Fortunately, a passing satellite took an image<br>of his farm M (1 <= M <= 70000) seconds before the crime took place, giving<br>the location of all of the cows.  He wants to know which cows had time to<br>get to the barn to steal the grain.<br><br>Farmer John's farm comprises F (1 <= F <= 500) fields numbered 1..F<br>and connected by P (1 <= P <= 1,000) bidirectional paths whose<br>traversal time is in the range 1..70000 seconds (cows walk very<br>slowly).  Field 1 contains<br>the barn.  It takes no time to travel within a field (switch paths).<br><br>Given the layout of Farmer John's farm and the location of each cow<br>when the satellite flew over, determine set of cows who could be<br>guilty.<br><br>NOTE: Do not declare a variable named exactly 'time'. This will reference<br>the system call and never give you the results you really want.<br><br></p> 

 
 # 输入格式 
<p>
<br>* Line 1: Four space-separated integers: F, P, C, and M<br><br>* Lines 2..P+1: Three space-separated integers describing a path: F1,<br>        F2, and T. The path connects F1 and F2 and requires T seconds<br>        to traverse.<br><br>* Lines P+2..P+C+1: One integer per line, the location of a cow.  The<br>        first line gives the field number of cow 1, the second of cow<br>        2, etc.<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: A single integer N, the number of cows that could be guilty<br>        of the crime.<br><br>* Lines 2..N+1: A single cow number on each line that is one of the<br>        cows that could be guilty of the crime. The list must be in<br>        ascending order.<br><br></p> 
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
7 6 5 8
1 4 2
1 2 1
2 3 6
3 5 5
5 4 6
1 7 9
1
4
5
3
7

INPUT DETAILS:

Fields/distances like this:
          6
      4------5
      |      |
     2|      |
      |      |
7-----1      |5
   9  |      |
     1|      |
      |      |
      2------3
          6

</td><td>
4
1
2
3
4

OUTPUT DETAILS:

Any cow except cow 5 could have done it.  Cow 5 would take 9 seconds to get
to the barn.</td></tr></table>
