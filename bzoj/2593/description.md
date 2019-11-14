
# Description

<div class="content"><div class="ptx" lang="en-US"><span style="font-size: medium">Kid is a famous thief and he is known for his unique habit. Before his attempt, he will always inform the person who he is going to rob beforehand. Though the people have paid much attention to him, he has never failed. This time Kid informed a billionaire, Jack, that he is going to enter Jack&#39;s home to take away his expensive treasure. Jack is very afraid and he asked a brilliant boy, Conan, to help him. Conan designed a special lock for Jack’s home. However, Kid is very tricky and he stole the structure map and the password of the lock. <br/>
</span><center><span style="font-size: medium"><img alt="" src="/source/bzoj/2593/img/aHR0cDovL3Bvai5vcmcvaW1hZ2VzLzIwNTVfMS5qcGc=.jpg"/></span></center><span style="font-size: medium"><br/>
From the structure map (see Figure-1), Kid knows that the lock contains K dial plates and K gears, and every dial plate controls several gears. There are N teeth on each gear, which is numbered counter-clockwise from 1 to N. When a certain dial plate is dialed, the gears that refer to the plate will rotate counter-clockwise by several teeth (different gears may rotate different numbers of teeth). A dial plate can be dialed more than once. At the beginning, the numbers of the top teeth of the gears are all &#34;1&#34;. To open the lock, the number of the top tooth of every gear must be a certain number. These K numbers form the password. Take Figure-1 for an example where N=8, K=4; if the password is 1-2-8-1, the lock will open. <br/>
<br/>
With the password in hand, Kid wants to know whether he can open the lock; and if he can, he wants to know the least number of dials he has to use to open the lock. You may assume that the lock is always locked at the beginning, which means that the password cannot be K &#34;1&#34;s. <br/>
</span></div>
<p><span style="font-size: medium">题目是说有k个旋钮，k个齿轮，每个旋钮控制若干个齿轮，问能否使齿轮到给定的值，若能给出一个最小总步数</span></p></div>

# Input

<div class="content"><div class="ptx" lang="en-US"><span style="font-size: medium">There are several test cases. In the first line of each case there are two integers K (1 &lt;= K &lt;= 20) and N (2 &lt;= N &lt;= 10). Then follows a line with K integers expressing the password. Each number in the password is between 1 and N. Then come K lines, the i-th of which describes how the i-th dial plate controls the referred gears. These K lines have the following format: <br/>
<br/>
p a1 b1 a2 b2 ... ap bp <br/>
<br/>
Integer p (0 &lt;= p &lt;= K) expresses the number of gears that are referred to the dial plate. ai (1 &lt;= i &lt;= p) is an integer between 1 and K which tells that the ai-th gear is under the control of this dial plate. bi is an integer between 1 and N-1 which tells that when the dial plate is dialed once, the ai-th gear will rotate across by bi gears. <br/>
<br/>
A test case of K = 0 and N = 0 indicates the end of input, and should not be processed. <br/>
</span></div></div>

# Output

<div class="content"><div class="ptx" lang="en-US"><span style="font-size: medium">For each test case, there is a single line. If the lock can be opened, the line contains the least number of times Kid should dial the dial plates; otherwise, output &#34;No solution&#34;.</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">1 4<br/>
2<br/>
1 1 2<br/>
4 8<br/>
8 8 8 8<br/>
4 1 1 2 2 4 1 3 1<br/>
2 4 7 3 2<br/>
2 1 5 3 5<br/>
1 2 7<br/>
0 0<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">No solution<br/>
2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Acm BeiJing 2004">Acm BeiJing 2004</a></p></div>

