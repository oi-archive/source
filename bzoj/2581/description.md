
# Description

<div class="content"><div class="problem-text" align="left"><span style="font-size: medium"><span class="mono prewrap" id="probtext-text"> Farmer John and Bessie have devised a new exercise game for the cows. The cows are running on a circular track of length M (2 &lt;= M &lt;= 1,000,000,000) starting from the same position. The game proceeds in N (1 &lt;= N &lt;= 14) rounds using a deck of 8N cards each with a number X_i (0 &lt;= X_i &lt; M) written on it. Each round FJ moves the top 8 cards into a separate pile and selects either the top 4 or bottom 4 cards for Bessie to play with. Bessie then chooses either the top 2 cards or bottom 2 cards of the 4 cards FJ selected. After this FJ calls out the number on the top card, X_top, and the cows run a distance of R * X_top, where R is the total distance the cows have run so far. Bessie then calls out the number on the bottom card, X_bottom, and the cows run a distance of X_bottom. FJ is concerned that after the exercise the cows will be too tired to get back to the beginning of the track if they end up too far away. He believes if the cows end up more than a distance of K (0 &lt;= K &lt;= floor(M/2)) from their starting position they won&#39;t be able to get back home. It is guaranteed that if FJ plays correctly, he will always be able to ensure the cows can come home, irrespective of the moves made by Bessie! For each round, your task is to determine which half of the cards FJ should choose such that no matter what Bessie does from that point on, FJ can always get the cows home. Bessie will then make the move provided in the input and you can then continue onto the next round. Note that even though Bessie&#39;s moves are provided to you in the input, you are to specify moves for FJ that would have worked no matter what Bessie chooses (so it is effectively as if FJ does not really know what Bessie will do during her moves). </span></span></div>
<div class="problem-text" align="left"></div>
<div class="problem-text" align="left"><span class="Apple-style-span" style="font-family: simsun; font-size: 14px; color: rgb(70, 70, 70); line-height: 21px; ">FJ与Bessie进行n轮决策，每轮开始时FJ依次取出8张牌，选择前4张或后4张给bessie，bessie从中选前2张或后2张，最后得到2张牌a和b，然后其余的奶牛绕长为m的圈跑dis*a+b的距离(dis为累计已跑距离)，要求n轮过后奶牛离起点的距离不能超过k。要求求出FJ的必胜策略（虽已给出bessie的决策方案，但不可用）</span></div></div>

# Input

<div class="content"><p><font size="4"> * Line 1: Three space-separated integers N, M, K</font></p>
<p><font size="4"> * Line 2: A string N characters. If the ith character is &#39;T&#39; it means Bessie will select the top 2 cards in the ith round. Otherwise the ith character will be &#39;B&#39; to indicate Bessie will select the bottom 2 cards in the ith round. </font></p>
<p><font size="4">* Lines 3..2+N: Each line contains eight integers representing the 8 cards to be used that round from top to bottom. </font></p></div>

# Output

<div class="content"><p><span style="font-size: medium"> Line 1: A string of N characters where the ith character is &#39;T&#39; if FJ should choose the top 4 cards or &#39;B&#39; if FJ should choose the bottom 4 cards in the ith round. If there are multiple ways to get the cows home, choose the lexicographically first (that is, the string that is alphabetically smallest).</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 2 0<br/>
TT<br/>
1 0 0 0 0 0 0 1<br/>
0 1 1 1 0 0 1 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">TB<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

