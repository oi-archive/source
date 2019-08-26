
# Description

<div class="content"><div>
<div>对于一个字符串S，我们定义|S|表示S的长度。</div>
<div>接着，我们定义Si表示S中第i个字符，S<sub>L,R</sub>表示由S中从左往右数，第L个字符到第R个字符依次连接形成的字符串。</div>
<div>特别的，如果L&gt;R，或者L不属于[1,∣S∣],或者R不属于[1,∣S∣]我们可以认为S<sub>L,R</sub>为空串。</div>
<div>给定一个长度为n的仅由数字构成的字符串S，</div>
<div>现在有q次询问，第k次询问会给出S的一个字符串S<sub>l,r,</sub>请你求出有多少对(i,j)，满足1&lt;=i&lt;j&lt;=n，i+1&lt;j，</div>
<div>且S<sub>l,r</sub>出现在S<sub>i+1,J-1</sub>或S<sub>j,n</sub>中</div>
</div></div>

# Input

<div class="content"><div>输入的第一行包含两个整数n,q。</div>
<div>第二行包含一个长度为n的仅由数字构成的字符串S。</div>
<div>接下来q行，每行两个正整数l和r，表示此次询问的子串是Sl,r</div>
<div>1&lt;=N&lt;=10%5,1&lt;=Q&lt;=3*10^5,1&lt;=L&lt;=R&lt;=N</div></div>

# Output

<div class="content"><div>对于每个询问，输出一个整数表示合法的数对个数。</div></div>

# Sample Input

<div class="content"><span class="sampledata">5 2<br/>
00100<br/>
1 2<br/>
1 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
1</span></div>

# Hint

<div class="content"><p></p><p> 原题面:<a href="http://www.lydsy.com/JudgeOnline/upload/201804/day2(3).pdf">www.lydsy.com/JudgeOnline/upload/201804/day2(3).pdf</a></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

