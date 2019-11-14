
# Description

<div class="content"><p><img alt="" src="/source/bzoj/2595/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIwMi8xKDEpLmpwZw==.jpg"/></p>
<p><img alt="" src="/source/bzoj/2595/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIwMi8yLmpwZw==.jpg"/></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行有两个整数，N和 M，描述方块的数目。 <br/>
接下来 N行， 每行有 M 个非负整数， 如果该整数为 0， 则该方块为一个景点；<br/>
否则表示控制该方块至少需要的志愿者数目。 相邻的整数用 （若干个） 空格隔开，<br/>
行首行末也可能有多余的空格。 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><br/>
由 N + 1行组成。第一行为一个整数，表示你所给出的方案<br/>
中安排的志愿者总数目。 <br/>
接下来 N行，每行M 个字符，描述方案中相应方块的情况： <br/>
z  ‘_’（下划线）表示该方块没有安排志愿者； <br/>
z  ‘o’（小写英文字母o）表示该方块安排了志愿者； <br/>
z  ‘x’（小写英文字母x）表示该方块是一个景点； <br/>
注：请注意输出格式要求，如果缺少某一行或者某一行的字符数目和要求不<br/>
一致（任何一行中，多余的空格都不允许出现） ，都可能导致该测试点不得分。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4 <br/>
0 1 1 0 <br/>
2 5 5 1 <br/>
1 5 5 1 <br/>
0 1 1 0<br/>
<br/>
<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6 <br/>
xoox <br/>
___o <br/>
___o <br/>
xoox<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p> <span style="font-family: arial, verdana, helvetica, sans-serif">对于100%的数据，N,M,K≤10，其中K为景点的数目。输入的所有整数均在[0,2^16]的范围内</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Ljcc930提供SPJ">Ljcc930提供SPJ</a></p></div>

