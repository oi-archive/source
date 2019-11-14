
# Description

<div class="content"><div>由乃正在做她的OJ。现在她在处理OJ上的用户排名问题。OJ上注册了n个用户，编号为1～&#34;，一开始他们按照编号</div>
<div>排名。由乃会按照心情对这些用户做以下四种操作，修改用户的排名和编号：然而由乃心情非常不好，因为Deus天</div>
<div>天问她题。。。因为Deus天天问由乃OI题，所以由乃去学习了一下OI，由于由乃智商挺高，所以OI学的特别熟练她</div>
<div>在RBOI2016中以第一名的成绩进入省队，参加了NOI2016获得了金牌保送</div>
<div>Deus：这个题怎么做呀？</div>
<div>yuno：这个不是NOI2014的水题吗。。。</div>
<div>Deus：那如果出到树上，多组链询问，带修改呢？</div>
<div>yuno：诶。。。？？？</div>
<div>Deus：这题叫做睡觉困难综合征哟~</div>
<div>虽然由乃OI很好，但是她基本上不会DS，线段树都只会口胡，比如她NOI2016的分数就是100+100+100+0+100+100。</div>
<div>。。NOIP2017的分数是100+0+100+100+0+100所以她还是只能找你帮她做了。。。</div>
<div>给你一个有n个点的树，每个点的包括一个位运算opt和一个权值x，位运算有&amp;,l,^三种，分别用1,2,3表示。</div>
<div>每次询问包含三个数x,y,z,初始选定一个数v。然后v依次经过从x到y的所有节点，每经过一个点i，v就变成v opti</div>
<div> xi，所以他想问你，最后到y时，希望得到的值尽可能大，求最大值？给定的初始值v必须是在[0,z]之间。每次修</div>
<div>改包含三个数x,y,z，意思是把x点的操作修改为y，数值改为z</div>
<div><img src="/source/bzoj/4811/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwNC92djIucG5n.png" width="822" height="515" alt=""/></div>
<p></p></div>

# Input

<div class="content"><div>第一行三个数n，m，k。k的意义是每个点上的数，以及询问中的数值z都 &lt;2^k。之后n行</div>
<div>每行两个数x,y表示该点的位运算编号以及数值</div>
<div>之后n - 1行，每行两个数x,y表示x和y之间有边相连</div>
<div>之后m行，每行四个数，Q,x,y,z表示这次操作为Q(1位询问，2为修改)，x，y，z意义如题所述</div>
<div>0 &lt;= n , m &lt;= 100000 , k &lt;= 64</div>
<p></p></div>

# Output

<div class="content"><div>对于每个操作1，输出到最后可以造成的最大刺激度v</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5 3<br/>
1 7<br/>
2 6<br/>
3 7<br/>
3 6<br/>
3 1<br/>
1 2<br/>
2 3<br/>
3 4<br/>
1 5<br/>
1 1 4 7<br/>
1 1 3 5<br/>
2 1 1 3<br/>
2 3 3 3<br/>
1 1 3 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
1<br/>
5<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名提供">By 佚名提供</a></p></div>

