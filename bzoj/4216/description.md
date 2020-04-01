
# Description

<div class="content"><div>红学姐和黄学长是好朋友。</div>
<div>有一天，黄学长想吃猪肉丸，于是他去找红学姐买猪。红学姐到她的猪圈中赶猪的</div>
<div>时候发现有许多猪逃离了她的猪圈。同时红学姐发现，一个名叫wwf的魔法猪藏在某</div>
<div>个猪圈中施法。然而wwf实在太巨了，红学姐并没有办法捉住它，只好向方老师求救。</div>
<div>为了确定wwf的位置，方老师向红学姐提出了m组询问，每次询问标号在区间[l,r]内</div>
<div>的猪圈剩余的猪的数量和，但红学姐不屑于做这些简单的问题，就把它们交给了你，同</div>
<div>时给了你一台内存较小的电脑。</div>
<div>由于wwf施展了一些奇怪的魔法，所以猪圈中猪的数量可能是负数。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个正整数n,m,t。n表示猪圈数，m表示询问数，t=0表示方老师没有对询问进行加密，t=1表示方老师对询问进行了加密，解密方法如下：</div>
<div><img src="/source/bzoj/4216/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNy9jY2MuanBn.jpg" width="246" height="117" alt=""/> </div>
<div>其中^表示异或操作，last_ans表示上一次询问的答案，对于第一次询问，last_ans=0。</div>
<div>第二行n个整数，第i个整数x[i]表示标号为i的猪圈中剩余猪的数量。</div>
<div>接下来m行每行两个正整数l,r表示一组询问。</div>
<p></p></div>

# Output

<div class="content"><div>输出m行，第i行表示第i个询问的答案</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5 1<br/>
1 3 -4 5 -3<br/>
3 4<br/>
1 1<br/>
2 3<br/>
2 4<br/>
3 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
5<br/>
-1<br/>
5<br/>
4<br/>
</span></div>

# Hint

<div class="content"><p></p><p>N,M&lt;=500000,|x[i]|&lt;=8000000</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

