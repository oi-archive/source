
# Description

<div class="content"><div>有一个长度为 n 的 01 串，你可以每次将相邻的 k 个字符合并，得到一个新的字符并获得一定分数。得到的新字</div>
<div>符和分数由这 k 个字符确定。你需要求出你能获得的最大分数。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数n，k。接下来一行长度为n的01串，表示初始串。接下来2k行，每行一个字符ci和一个整数wi，ci</div>
<div>表示长度为k的01串连成二进制后按从小到大顺序得到的第i种合并方案得到的新字符,wi表示对应的第i种方案对应</div>
<div>获得的分数。1&lt;=n&lt;=300,0&lt;=ci&lt;=1,wi&gt;=1,<a href="http://www.lydsy.com/JudgeOnline/wttl/thread.php?tid=2970">k&lt;=8</a></div>
<p></p></div>

# Output

<div class="content"><p>输出一个整数表示答案</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2<br/>
101<br/>
1 10<br/>
1 10<br/>
0 20<br/>
1 30</span></div>

# Sample Output

<div class="content"><span class="sampledata">40<br/>
//第3行到第6行表示长度为2的4种01串合并方案。00-&gt;1,得10分，01-&gt;1得10分，10-&gt;0得20分，11-&gt;1得30分。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

