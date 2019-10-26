
# Description

<div class="content"><div>你知道Just Odd Inventions社吗？这个公司的业务是“只不过是奇妙的发明(Just Odd Inventions)”。这里简称为JOI社。</div>
<div>JOI社的某个实验室中有着复杂的电路。电路由n个节点和m根细长的电阻组成。节点被标号为1~N</div>
<div>每个节点有一个可设定的状态【高电压】或者【低电压】。每个电阻连接两个节点，只有一端是高电压，另一端是低电压的电阻才会有电流流过。两端都是高电压或者低电压的电阻不会有电流流过。</div>
<div>某天，JOI社为了维护电路，选择了一根电阻，为了能让【只有这根电阻上的电流停止流动，其他M-1根电阻中都有电流流过】，需要调节各节点的电压。为了满足这个条件，能选择的电阻共有多少根？</div>
<div>对了，JOI社这个奇妙的电路是用在什么样的发明上的呢？这是公司内的最高机密，除了社长以外谁都不知道哦~</div>
<div>现在给出电路的信息，请你输出电路维护时可以选择使其不流的电阻的个数。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个空格分隔的正整数N和M，表示电路中有N个节点和M根电阻。</div>
<div>接下来M行，第i行有两个空格分隔的正整数Ai和Bi(1&lt;=Ai&lt;=N,1&lt;=Bi&lt;=N,Ai≠Bi)，表示第i个电阻连接节点Ai和节点Bi。</div>
<p></p></div>

# Output

<div class="content"><div>输出一行一个整数，代表电路维护时可选择的使其不流的电阻个数。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
1 2<br/>
2 3<br/>
3 2<br/>
4 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p><div>可以选择第一根电阻或第四根电阻。</div><br/>
<div> <img src="/source/bzoj/4238/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwOC9iYi5qcGc=.jpg" width="364" height="174" alt=""/></div><br/>
<div>2&lt;=N&lt;=10^5</div><br/>
<div>1&lt;=M&lt;=2*10^5</div><br/>
<div>不保证图是连通的，不保证没有重边</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=JOI 2013~2014 春季training合宿 竞技3 By PoPoQQQ">JOI 2013~2014 春季training合宿 竞技3 By PoPoQQQ</a></p></div>

