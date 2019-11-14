
# Description

<div class="content"><div>在一片美丽的大陆上有100000个国家，记为1到100000。这里经济发达，有数不尽的账房，并且每个国家有一个银行。某大公司的领袖在这100000个银行开户时都存了3大洋，他惜财如命，因此会不时地派小弟GFS清点一些银行的存款或者让GFS改变某个银行的存款。该村子在财产上的求和运算等同于我们的乘法运算，也就是说领袖开户时的存款总和为3100000。这里发行的软妹面额是最小的60个素数（p1=2,p2=3,…,p60=281），任何人的财产都只能由这60个基本面额表示，即设某个人的财产为fortune（正整数），则fortune=p1^k1*p2^k2*......p60^K60。</div>
<div></div>
<div>领袖习惯将一段编号连续的银行里的存款拿到一个账房去清点，为了避免GFS串通账房叛变，所以他不会每次都选择同一个账房。GFS跟随领袖多年已经摸清了门路,知道领袖选择账房的方式。如果领袖选择清点编号在[a,b]内的银行财产，他会先对[a,b]的财产求和（计为product），然后在编号属于[1,product]的账房中选择一个去清点存款，检验自己计算是否正确同时也检验账房与GFS是否有勾结。GFS发现如果某个账房的编号number与product相冲，领袖绝对不会选择这个账房。怎样才算与product不相冲呢？若存在整数x,y使得number*x+product*y=1，那么我们称number与product不相冲，即该账房有可能被领袖相中。当领袖又赚大钱了的时候，他会在某个银行改变存款，这样一来相同区间的银行在不同的时候算出来的product可能是不一样的，而且领袖不会在某个银行的存款总数超过1000000。</div>
<div></div>
<div>现在GFS预先知道了领袖的清点存款与变动存款的计划，想请你告诉他，每次清点存款时领袖有多少个账房可以供他选择，当然这个值可能非常大，GFS只想知道对19961993取模后的答案。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行一个整数x表示领袖清点和变动存款的总次数。</div>
<div>接下来x行，每行3个整数ai,bi,ci。ai为0时表示该条记录是清点计划，领袖会清点bi到ci的银行存款，你需要对该条记录计算出GFS想要的答案。ai为1时表示该条记录是存款变动，你要把银行bi的存款改为ci，不需要对该记录进行计算。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出若干行，每行一个数，表示那些年的答案。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
013<br/>
115<br/>
013<br/>
117<br/>
013<br/>
023</span></div>

# Sample Output

<div class="content"><span class="sampledata">18<br/>
24<br/>
36<br/>
6<br/>
<br/>
explanation<br/>
<br/>
初始化每个国家存款都为3;<br/>
<br/>
1到3的product为27，[1,27]与27不相冲的有18个数;<br/>
1的存款变为5;<br/>
1到3的product为45，[1,45]与45不相冲的有24个数;<br/>
1的存款变为7;<br/>
1到3的product为63，[1,63]与63不相冲的有36个数;<br/>
2到3的product为9，[1,9]与9不相冲的有6个数。<br/>
</span></div>

# Hint

<div class="content"><p></p><p>x≤100000，当ai=0时0≤ci−bi≤100000</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2015年国家集训队测试">2015年国家集训队测试</a></p></div>

