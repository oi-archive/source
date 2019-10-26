
# Description

<div class="content"><div>wxh太强了，他觉得你们太菜了，所以懒得写背景了，给你一个字符串init，要求你支持三个操作</div>
<div>(1):在当前字符串的后面插入若干个字符</div>
<div>(2):在当前字符串的后面删除若干个字符</div>
<div>(3):询问字符串s在当前字符串中出现了几次？(作为连续子串)</div>
<div>你必须在线支持这些操作。</div>
<div><img src="/source/bzoj/4768/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwMy8xLnBuZw==.png" width="730" height="336" alt=""/></div>
<p></p></div>

# Input

<div class="content"><div>第一行一个数Q表示操作个数</div>
<div>第二行一个字符串表示初始字符串init</div>
<div>接下来Q行，每行2个字符串Type,Str </div>
<div>Type是ADD的话表示在后面插入。</div>
<div>Type是DEL的话表示在后面删除。</div>
<div>Type是QUERY的话表示询问某字符串在当前字符串中出现了几次。</div>
<div>为了体现在线操作，你需要维护一个变量mask，初始值为0</div>
<div>读入串Str之后，使用这个过程将之解码成真正询问的串TrueStr。</div>
<div>询问的时候，对TrueStr询问后输出一行答案Result</div>
<div>然后mask = mask xor Result  </div>
<div>插入的时候，将TrueStr插到当前字符串后面即可。</div>
<div>HINT:ADD和QUERY操作的字符串都需要解压</div>
<div>字符集大写字母</div>
<div><span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.549334526062px;">数据字符串变化长度以及初始长度和 &lt;= 800000，询问次数 &lt;= 100000,询问总长度 &lt;= 3000000</span></div>
<p></p></div>

# Output

<div class="content"><div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
A<br/>
QUERY B<br/>
ADD BBABBBBAAB<br/>
DEL 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">0</span></div>

# Hint

<div class="content"><p></p><p> 应出题人要求放出数据如下：http://www.lydsy.com/JudgeOnline/upload/wxh.zip</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By nzhtl1477">By nzhtl1477</a></p></div>

