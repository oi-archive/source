
# Description

<div class="content"><div>万老板希望在新的智能音乐播放设备IPOOD中，实现对波文件音质性能的评定。离散的波文件被考虑为长度为 N 的</div>
<div>整数序列：Al,A2,...,AN。所谓的音质性能检测，可以评定任何的一个区间范围 [L,R] ，音质性能取决于下述评</div>
<div>分：</div>
<div></div>
<div><img src="/source/bzoj/4085/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNS_ml6DmoIfpopgoMikucG5n.png" width="445" height="88" alt=""/></div>
<div>其中 F 是可归纳定义的数列，满足 F[1]=1，F[2]=2 且 F[k+2]=F[k+l]+aF[k]+b 对于任何 k&gt;=l 成立。其中 a </div>
<div>和 b 为正整系数。为了可以为用户提供更好的服务体验，并希望对给定的波文件进行修正优化。这一款设备中，</div>
<div>还应该支持对波文件的修改。对于给定的区间范围 [L,R] ，允许用户将 A[L] 至 A[R] 同时增加一，或同时减少</div>
<div>一。</div>
<div></div>
<p style="font-size: 11.8181819915771px;"></p>
<p style="font-size: 11.8181819915771px;"></p></div>

# Input

<div class="content"><div>输入的第一行有两个正整数，波文件的总长度 N ，和总的修改与询问次数 Q 。</div>
<div>第二行有两个整数，分别表示系数 a 和 b 。</div>
<div>之后若干行，一共给出 N 个正整数 A1 到 AN ，满足 1≤A[i]≤2*109 。</div>
<div>之后 Q 行，每行是下述三种形式之一：</div>
<div>·plus L R：将波文件数列中下标在区间 [L,R] 内的元素每一个都加一。</div>
<div>·minus L R：将波文件数列中下标在区间 [L,R] 内的元素每一个都减一。</div>
<div>·query L R：询问区间 [L,R] 的音质性能评分。</div>
<div>修改和询问中，均保证 L≤R ，且保证 A[i] 严格大于总的修改次数加一(修改操作包括 plus 和 minus 两种)。</div>
<div>N≤300000，Q≤10000，0≤a,b≤10^9</div>
<div style="font-size: 11.8181819915771px;"></div></div>

# Output

<div class="content"><p> <span style="font-size: 11.8181819915771px;">输出若干行，每一行对应一次询问，输出一个整数。<br/>
</span></p>
<div style="font-size: 11.8181819915771px;"></div></div>

# Sample Input

<div class="content"><span class="sampledata">7 7 <br/>
1 0 <br/>
3 4 5 6 7 8 9 <br/>
query 2 4 <br/>
query 3 7 <br/>
plus 3 5 <br/>
query 2 4 <br/>
plus 4 7 <br/>
query 3 7 <br/>
query 1 7</span></div>

# Sample Output

<div class="content"><span class="sampledata">64 <br/>
1766 <br/>
104 <br/>
7479 <br/>
7687</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

