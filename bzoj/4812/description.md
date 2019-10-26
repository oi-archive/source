
# Description

<div class="content"><div>由乃不太会打扑克</div>
<div>所以她出了一个数据结构题 </div>
<div>给一个N个点树，第i个点的点权为Ai，M次操作， 每次求一些树链的并的贡献，强制在线</div>
<div>贡献定义：</div>
<div>定义权值集合为这些树链的并里面出现过的所有点权的集合</div>
<div>权值集合中每一段连续出现的数的贡献为这一段长度的k次方</div>
<div>例如出现了1,9,2,6,0,8,1,7这些数，k=3的时候贡献为3^3+4^3，因为0,1,2是连续一段，6,7,8,9为连续一段</div>
<div>每次询问给出x条树链，以及一个k，贡献对2^32取模</div>
<div><img src="/source/bzoj/4812/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwNC92djMucG5n.png" width="746" height="621" alt=""/></div>
<p></p></div>

# Input

<div class="content"><div>一行两个整数N,M</div>
<div>接下来一行N个整数， 第i个整数表示Ai</div>
<div>接下来N-1行每行两个数u,v， 用来描述树上的一条边, 1≤u,v≤N</div>
<div>接下来M行， 每行首先给出一个数x， 接下来2x个数， 读入的这2x个数需要异或上一次询问的答案解密得到，初</div>
<div>始答案为0， 得到的第2i+1以及2i+2个数表示第i条链的起点以及终点， 最后一个数k</div>
<div>0≤N,M≤10^5, 0≤∑x≤10^5, 0≤k≤30, 0≤Ai≤30000</div>
<p></p></div>

# Output

<div class="content"><div>对于每个询问输出一个数表示答案</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">8 2<br/>
1 9 2 6 0 8 1 7<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 5<br/>
5 6<br/>
6 7<br/>
7 8<br/>
2 1 4 5 8 3<br/>
1 90 90 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">91<br/>
1<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名提供">By 佚名提供</a></p></div>

