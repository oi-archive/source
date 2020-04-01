
# Description

<div class="content"><div>
<div>Byteburg is a beautiful town by a river. There are N houses along the river, numbered downstream wit</div>
<div>h successive integers from   to  . Byteburg used to be a nice quiet town in which everyone was happy</div>
<div>. Alas, this changed recently, as two dangerous criminals - Bitie and Bytie set up shop in it. They </div>
<div>did so many robberies already that the citizens are afraid to leave their houses.Bitie and Bytie do </div>
<div>no mere burglaries but rather whole raids: each time they leave their houses and walk towards each o</div>
<div>ther, never turning back. Bitie walks downstream (towards larger numbers) while Bytie walks upstream</div>
<div> (towards smaller numbers). Along the way, before they meet, each chooses several houses to break in</div>
<div>to and steal precious items (and vital data). After the robberies they meet in a house and divide th</div>
<div>eir loot. Byteburgers are sick of this already - they would all rather have their tranquility restor</div>
<div>ed. So they asked the detective Bythony for help.The detective established that the bandits live in </div>
<div>houses of the same color but he does not know which one. Just a moment ago, an anonymous tip claimed</div>
<div> that the robbers are on a raid. Fearing for their own safety, the source did not say which houses w</div>
<div>ill be broken into. They did however specify their colors. As it turns out, the bandits are quite su</div>
<div>perstitious - each of them will rob a house of each color at most once.Bythony can wait no longer. H</div>
<div>e intends to ambush the criminals at their meeting place. Aid Bythony in his undertaking by writing </div>
<div>a program to find all possible meeting places of the robbers.</div>
<div>给 你一个颜色序列，有两个人会分别从左往右和从右往左走，并在途中任意取走几个格子里面的颜色，直到两个</div>
<div>人相遇。已知两个人所取走的颜色序列，并且保证这两 个颜色序列的最后一个元素都是同一种颜色，代表两个人</div>
<div>相遇的点。还知道两个人出发点的颜色都是相同的，并且他们不会取出发点的颜色。（即在两个人的序列中 都不</div>
<div>会出现）同时还发现不存在任意一个颜色在这两个序列中出现两次。我们需要找到他们相遇的点。请求出可能的相</div>
<div>遇点有多少个，并输出。</div>
<div></div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>There are two integers in the first line of the standard input, N and K(3&lt;=N&lt;=1000 000,1&lt;=K&lt;=1000 00</div>
<div>0 ,K&lt;=N), separated by a single space, that specify the number of houses and the number of house col</div>
<div>ors in Byteburg respectively. The colors are number with successive integers from   to K. In the sec</div>
<div>ond line of input, there is a sequence of N integers, C1，C2….Cn(1&lt;=Ci&lt;=K) , separated by single sp</div>
<div>aces. These are the colors of successive houses in Byteburg.In the third line of input, there are tw</div>
<div>o integers M and L(1&lt;=M,L&lt;=N,M+L&lt;=N-1), separated by a single space, specifying the numbers of house</div>
<div>s (to be) broken into by Bitie and Bytie respectively. In the fourth line of input, there are   pair</div>
<div>wise different integers X1,X2…Xm(1&lt;=Xi&lt;=K), separated by single spaces. These are the colors of hou</div>
<div>ses robbed by Bitie in the order of being broken into (i.e., excluding Bitie&#39;s house). In the fifth,</div>
<div> which is the last, line of input, there are   pairwise different integers Y1,Y2…YL(1&lt;=Yi&lt;=K), sepa</div>
<div>rated by single spaces. These are the colors of houses robbed by Bytie in the order of being broken </div>
<div>into (again, these do not include Bytie&#39;s house). Moreover, Xm=Yi  is the color of the house in whic</div>
<div>h the robbers will divide the plunder. (Clearly, they have to break into that one as well!)</div>
<div>第一行两个正整数N和K（K&lt;=N&lt;=1000000）分别代表序列长度和颜色总数。第二行给出n个正整数Ci（1&lt;=Ci&lt;=K）。</div>
<div>第三行给出了两个正整数M和L（1&lt;=M,L&lt;=N，M+L&lt;=N-1）分别代表两个人所取走的颜色序列长度。第四行M个数是第</div>
<div>一个人的颜色序列（从左往右）。第五行L个数是第二个人的颜色序列（从右往左）,注意颜色序列里没有重复数字.</div>
<div><span style="color: rgb(255, 0, 0);"><span style="font-family: arial, verdana, helvetica, sans-serif;">注意：两个人的出发点的颜色必须相同，他们不能在出发点上面取颜色（不是说出发点上的颜色不能取）</span></span></div></div>

# Output

<div class="content"><div>Your program it to print exactly two lines to the standard output. The first of those should give th</div>
<div>e number of houses in which the criminals can meet while respecting aforementioned constraints. The </div>
<div>second line should contain the increasing sequence of the numbers of those houses, separated by sing</div>
<div>le spaces. If the robbers cannot meet at all, the first line should contain the number 0 while the s</div>
<div>econd one should be empty.</div>
<div>第一行一个整数s代表可能的相遇点个数。第二行s个数分别是可能相遇点的下标。</div></div>

# Sample Input

<div class="content"><span class="sampledata">15 7<br/>
2 5 6 2 4 7 3 3 2 3 7 5 3 6 2<br/>
3 2<br/>
4 7 3<br/>
5 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
7 8 10<br/>
<br/>
HINT<br/>
可能的两个人取走的颜色位置是第一个人：5、6、7（或8或10）。第二个人12、7（或8或10）。两个人可能的出发<br/>
</span></div>

# Hint

<div class="content"><p></p><p style="line-height: 23.8px;" class="MsoNormal"><font face="宋体">新加数据一组 by </font><span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.549334526062px;">Rcapor--2016.9.27</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

