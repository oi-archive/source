
# Description

<div class="content"><div>You’re designing  a game console with a special  board which can evaluate how balance people  are. </div>
<div>After the user stands on the board, it can record the movement of the user&#39;s &#34;center of gravity&#34;. </div>
<div>Technically,  the record is a sequence of  n  points  on  the  2D plane  (the user&#39;s &#34;center of gravity&#34; </div>
<div>projected to the game board), where the origin (0,0) is the center of the game board. Samples are taken </div>
<div>every 0.01 second, so if the user stands on it for one minute, your database gets 6000 sample points.  </div>
<div>In order to know better about his balancing status, the user can ask the game console some questions. </div>
<div>Each question (i,j) means: count how many pairs of sample points, chosen from the interval between </div>
<div>the i-th sample and the j-th sample (inclusive), whose Manhattan distance is no more than d, where d </div>
<div>is the preset balance threshold parameter in the system. </div>
<div>Your task is to write a program that can answer the questions. Note that you don&#39;t have to answer the </div>
<div>questions one by one. You can read all the questions first, and then answer them. </div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>There are no more than 3 test cases. The first line contains three integers n, d, q(1&lt;=n&lt;=200000, </div>
<div>1&lt;=d&lt;=10^8, 1&lt;=q&lt;=10000), the number of points, the balance threshold and the number of queries. </div>
<div>The next n lines contain the coordinates (x,y) (|x|,|y|&lt;=10^8) of the sample points, in order. The points </div>
<div>are numbered 1~n. The next q lines contain the questions (i,j) (1&lt;=i&lt;=j&lt;=n). </div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>For each test case, print the case number in the first line, then the answers of the questions, one on </div>
<div>each line. </div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 1 2 <br/>
0 0 <br/>
1 0 <br/>
3 0 <br/>
2 1 <br/>
2 0 <br/>
2 4 <br/>
1 5 <br/>
5 2 2 <br/>
0 0 <br/>
1 0 <br/>
3 0 <br/>
2 1 <br/>
2 0 <br/>
2 4 <br/>
1 5 </span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: <br/>
0 <br/>
4 <br/>
Case 2: <br/>
3 <br/>
8 </span></div>

# Hint

<div class="content"><p></p><p> 2015年湖南省大学生程序设计竞赛</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢刘汝佳先生授权使用">鸣谢刘汝佳先生授权使用</a></p></div>

