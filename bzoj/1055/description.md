
# Description

<div class="content"><div>　　某人有一套玩具，并想法给玩具命名。首先他选择WING四个字母中的任意一个字母作为玩具的基本名字。然后</div>
<div>他会根据自己的喜好，将名字中任意一个字母用“WING”中任意两个字母代替，使得自己的名字能够扩充得很长。</div>
<div>现在，他想请你猜猜某一个很长的名字，最初可能是由哪几个字母变形过来的。</div></div>

# Input

<div class="content"><div>　　第一行四个整数W、I、N、G。表示每一个字母能由几种两个字母所替代。接下来W行，每行两个字母,表示W可</div>
<div>以用这两个字母替代。接下来I行，每行两个字母,表示I可以用这两个字母替代。接下来N行，每行两个字母,表示N</div>
<div>可以用这两个字母替代。接下来G行，每行两个字母,表示G可以用这两个字母替代。最后一行一个长度不超过Len的</div>
<div>字符串。表示这个玩具的名字。</div></div>

# Output

<div class="content"><div>　　一行字符串，该名字可能由哪些字母变形而得到。（按照WING的顺序输出）如果给的名字不能由任何一个字母</div>
<div>变形而得到则输出“The name is wrong!”</div></div>

# Sample Input

<div class="content"><span class="sampledata">1 1 1 1<br/>
II<br/>
WW<br/>
WW<br/>
IG<br/>
IIII</span></div>

# Sample Output

<div class="content"><span class="sampledata">IN</span></div>

# Hint

<div class="content"><p></p><div>W可以变成II所以IIII可以缩成WW IN均能变成WW所以WW又可以缩成I或者N 所以最终答案应该按照“WING”的顺序</div><br/>
<div>输出IN </div><br/>
<div>[数据范围]</div><br/>
<div>100%数据满足Len&lt;=200，W、I、N、G&lt;=16</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

