
# Description

<div class="content"><p><img src="/source/bzoj/4119/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNi8xMS5QTkc=.PNG" width="816" height="1292" alt=""/> </p></div>

# Input

<div class="content"><p>The first line of input contains one integer Q(1&lt;=Q&lt;=25), specifying the number of test cases to consider. The following 3Q  lines of input contain descriptions of test cases. Each test case is described by three lines of input.</p>
<div>The first line of a test case description contains one integer N(2&lt;=N&lt;=10), specifying the number of frames. The second line contains a sequence of 2N+1 characters which denotes the game description from Byteasar&#39;s notes. Blurry characters are replaced by &#34;?&#34; characters. The third line contains n integers, the total number of points after each frame, separated by spaces. In each number either all digits are readable, or all digits are blurry. Numbers in which all digits are blurry are replaced by &#34;-1&#34;.</div></div>

# Output

<div class="content"><p>Your program should output q lines, one line per each test case in the same order as in the input.</p>
<div>For each test case your program should write one integer: the number of possible distinct games corresponding to the test case. Two games are considered different if and only if they differ in at least one shot, that is, their 2N+1 -character game descriptions are different. You can assume that there is at least one game consistent with each test case in the input. You can assume that the result fits into 64-bit signed integer type.</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
10<br/>
08x-7/2/x?x-23??1/???<br/>
8 -1 40 60 82 97 102 110 120 140<br/>
5<br/>
x-x-23?/00-<br/>
22 37 42 52 52<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">9<br/>
10<br/>
</span></div>

# Hint

<div class="content"><p></p><p> Explanation to the example: In the first case, in frame 5 after the character &#34;x&#34; the only possible character is &#34;-&#34;. In frame 8 the player got 8 points in total. Thus there are 9 possibilities how this sum could have been obtained:0+8,1+7,….8+0. There were no bonus points in frame 9. Therefore, there were no points on the first shot of the final frame. To obtain 20 points in the last two shots, the only possibility is a spare with a following strike in the last shot of the frame. Therefore there are 9 different valid games which correspond to this input data.</p><br/>
<div>In the second case, any character from 0 to 9 is consistent with the input data.</div><br/>
<div>求译文!请发至lydsy2012@163.com</div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

