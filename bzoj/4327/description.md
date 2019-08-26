
# Description

<div class="content"><div>在美丽的玄武湖畔，鸡鸣寺边，鸡笼山前，有一块富饶而秀美的土地，人们唤作进香河。相传一日，一缕紫气从天而至，只一瞬间便消失在了进香河中。老人们说，这是玄武神灵将天书藏匿在此。 </div>
<div>很多年后，人们终于在进香河地区发现了带有玄武密码的文字。更加神奇的是，这份带有玄武密码的文字，与玄武湖南岸台城的结构有微妙的关联。于是，漫长的破译工作开始了。 </div>
<div>经过分析，我们可以用东南西北四个方向来描述台城城砖的摆放，不妨用一个长度为N的序列来描述，序列中的元素分别是‘E’，‘S’，‘W’，‘N’，代表了东南西北四向，我们称之为母串。而神秘的玄武密码是由四象的图案描述而成的M段文字。这里的四象，分别是东之青龙，西之白虎，南之朱雀，北之玄武，对东南西北四向相对应。 </div>
<div>现在，考古工作者遇到了一个难题。对于每一段文字，其前缀在母串上的最大匹配长度是多少呢？ </div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行有两个整数，N和M，分别表示母串的长度和文字段的个数。 </div>
<div>
<div>第二行是一个长度为N的字符串，所有字符都满足是E,S,W和N中的一个。 </div>
<div>之后M行，每行有一个字符串，描述了一段带有玄武密码的文字。依然满足，所有字符都满足是E,S,W和N中的一个。 </div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>输出有M行，对应M段文字。 </div>
<div>每一行输出一个数，表示这一段文字的前缀与母串的最大匹配串长度。 </div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 3<br/>
SNNSSNS<br/>
NNSS<br/>
NNN<br/>
WSEE</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
2<br/>
0</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据，N&lt;=10^7，M&lt;=10^5，每一段文字的长度&lt;=100。</p><br/>
<p>应上传者要求，此题不公开，如有异议，请提出.</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

