
# Description

<div class="content"><div>懒得写背景了，给你一个字符串init，要求你支持两个操作</div>
<div>(1):在当前字符串的后面插入一个字符串</div>
<div>(2):询问字符串s在当前字符串中出现了几次？(作为连续子串)</div>
<div>你必须在线支持这些操作。</div></div>

# Input

<div class="content"><div>第一行一个数Q表示操作个数</div>
<div>第二行一个字符串表示初始字符串init</div>
<div>接下来Q行，每行2个字符串Type,Str</div>
<div>Type是ADD的话表示在后面插入字符串。</div>
<div>Type是QUERY的话表示询问某字符串在当前字符串中出现了几次。</div>
<div>为了体现在线操作，你需要维护一个变量mask，初始值为0 </div>
<p><img height="266" alt="" width="568" src="/source/bzoj/2555/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTExMi8xMS5KUEc=.JPG" style="font-size: large;"/><span style="font-size: large;">    </span></p>
<div>
<div>读入串Str之后，使用这个过程将之解码成真正询问的串TrueStr。</div>
<div>询问的时候，对TrueStr询问后输出一行答案Result</div>
<div>然后mask=maskxorResult</div>
<div>插入的时候，将TrueStr插到当前字符串后面即可。</div>
<div>HINT:ADD和QUERY操作的字符串都需要解压</div>
<div>长度 &lt;= 600000，询问次数&lt;= 10000,询问总长度&lt;= 3000000</div>
<div>新加数据一组--2015.05.20</div>
</div></div>

# Output

<div class="content"></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
A<br/>
QUERY B<br/>
ADD BBABBBBAAB</span></div>

# Sample Output

<div class="content"><span class="sampledata">0</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Ctsc模拟赛By 洁妹">Ctsc模拟赛By 洁妹</a></p></div>

