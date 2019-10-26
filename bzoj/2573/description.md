
# Description

<div class="content"><p><span style="font-size: medium">Triangle War is a two-player game played on the following triangular grid: </span></p>
<p><span style="font-size: medium"><img height="179" width="192" alt="" src="/source/bzoj/2573/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTExMi8xKDkpLmpwZw==.jpg"/></span></p>
<p><span style="font-size: medium">Two players, A and B, take turns filling in any dotted line connecting two dots, with A starting first. Once a line is filled, it cannot be filled again. If the line filled by a player completes one or more triangles, she owns the completed triangles and she is awarded another turn (i.e. the opponent skips a turn). The game ends after all dotted lines are filled in, and the player with the most triangles wins the game. The difference in the number of triangles owned by the two players is not important. </span></p>
<p><span style="font-size: medium"><br/>
For example, if A fills in the line between 2 and 5 in the partial game on the left below: </span></p>
<p></p>
<p><span style="font-size: medium"><img height="180" width="460" alt="" src="/source/bzoj/2573/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTExMi8yKDUpLmpwZw==.jpg"/></span></p>
<p></p>
<p><span style="font-size: medium">Then, she owns the triangle labelled A and takes another turn to fill in the line between 3 and 5. B can now own 3 triangles (if he wishes) by filling in the line between 2 and 3, then the one between 5 and 6, and finally the one between 6 and 9. B would then make one more move before it is A&#39;s turn again. </span></p>
<p><span style="font-size: medium"><br/>
In this problem, you are given a number of moves that have already been made. From the partial game, you should determine which player will win assuming that each player plays a perfect game from that point on. That is, assume that each player always chooses the play that leads to the best possible outcome for himself/herself. </span></p>
<p><span style="font-size: medium"><br/>
This problem contains multiple test cases!</span></p>
<p><span style="font-size: medium">The first line of a multiple input is an integer N, then a blank line followed by N input blocks. Each input block is in the format indicated in the problem description. There is a blank line between input blocks.</span></p>
<p><span style="font-size: medium">The output format consists of N output blocks. There is a blank line between output blocks.</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">You will be given a number of games in the input. The first line of input is a positive integer 6 &lt;= m &lt;= 18 indicating the number of games to follow. Each game starts with an integer indicating the number of moves that have been made in the game. The next m lines indicate the moves made by the two players in order, each of the form i j (with i &lt; j) indicating that the line between i and j is filled in that move. You may assume that all given moves are legal.</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">For each game, print the game number and the result on one line as shown below. If A wins, print the sentence ``A wins.&#39;&#39; If B wins, print ``B wins.&#39;&#39; </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
<br/>
4<br/>
6<br/>
2 4<br/>
4 5<br/>
5 9<br/>
3 6<br/>
2 5<br/>
3 5<br/>
7<br/>
2 4<br/>
4 5<br/>
5 9<br/>
3 6<br/>
2 5<br/>
3 5<br/>
7 8<br/>
6<br/>
1 2<br/>
2 3<br/>
1 3<br/>
2 4<br/>
2 5<br/>
4 5<br/>
10<br/>
1 2<br/>
2 5<br/>
3 6<br/>
5 8<br/>
4 7<br/>
6 10<br/>
2 4<br/>
4 5<br/>
4 8<br/>
7 8<br/>
<br/>
<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Game 1: B wins.<br/>
Game 2: A wins.<br/>
Game 3: A wins.<br/>
Game 4: B wins.<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

