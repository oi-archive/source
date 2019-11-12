# 题目描述


<p>
<br/>
</p>
<div>
USACO/starry
<hr/>
</div>
<p>
描述
</p>
<span style="font-family:&#39;Times New Roman&#39;;"></span> 
<p>
<br/>
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">高高的星空，簇簇闪耀的群星形态万千。一个星座(cluster)是一群连通的星组成的非空集合，所谓连通是指水平，垂直或者对角相邻。一个星座不能是另一个更大星座的一部分。<br/>
星座可以相似(similar)。如果两个星座有相同的形状，而且包括相同数目的星体，那么不管其方向性如何，就算相似。一般而言，星座可能的方向有八个，如图1所示。</span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;"><img alt="" src="/images/upload/image/20120711/20120711181106_61136.gif"/><br/>
图1 相似的八个星座</span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">夜空可以表示为一份天体图(sky map)，它是一个由字符0和1组成的二维矩阵，字符1表示所在的位置有一颗星；字符0表示该位置上没有星。<br/>
任务<br/>
给定一份天体图，用同一个小写英文标识(mark)相似的所有星座。相似的星座必须用相同的字母标识为不同的字母。<br/>
标识一个星座，就是将其中各星体对应的字符1替换为相应的小写字母。</span> 
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">PROGRAM NAME: starry</span> 
</h3>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">INPUT FORMAT(file starry.in)<br/>
</span> 
</h3>
<p>
<span style="font-family:&#39;Times New Roman&#39;;"><br/>
文件的前两行分别记录了天体图的宽度W、深度H。而天体图则是由接下来的H行表示，每行包括W个字符。</span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;"><b><span style="font-size:medium;">OUTPUT FORMAT(file starry.out)</span></b><br/>
输出文件记录了天体图与文件<b><span style="font-size:medium;">STARRY.IN</span></b>相似，不同之处在于，各个星座按照“任务”中的要求进行了标识(mark)。</span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;"><b><span style="font-size:medium;">SAMPLE INPUT (file starry.in)</span></b><br/>
23<br/>
15<br/>
10001000000000010000000<br/>
01111100011111000101101<br/>
01000000010001000111111<br/>
00000000010101000101111<br/>
00000111010001000000000<br/>
00001001011111000000000<br/>
10000001000000000000000<br/>
00101000000111110010000<br/>
00001000000100010011111<br/>
00000001110101010100010<br/>
00000100110100010000000<br/>
00010001110111110000000<br/>
00100001110000000100000<br/>
00001000100001000100101<br/>
00000001110001000111000</span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;"><img alt="" src="/images/upload/image/20120711/20120711181357_34511.gif"/><br/>
图2. 天空景象</span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;"><b><span style="font-size:medium;">SAMPLE OUTPUT (file starry.out)</span></b><br/>
a000a0000000000b0000000<br/>
0aaaaa000ccccc000d0dd0d<br/>
0a0000000c000c000dddddd<br/>
000000000c0b0c000d0dddd<br/>
00000eee0c000c000000000<br/>
0000e00e0ccccc000000000<br/>
b000000e000000000000000<br/>
00b0f000000ccccc00a0000<br/>
0000f000000c000c00aaaaa<br/>
0000000ddd0c0b0c0a000a0<br/>
00000b00dd0c000c0000000<br/>
000g000ddd0ccccc0000000<br/>
00g0000ddd0000000e00000<br/>
0000b000d0000f000e00e0b<br/>
0000000ddd000f000eee000<br/>
这是上述输入实例的一个可能的结果。请注意，该输出文件对应于下面的天空景象。</span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;"><img alt="" src="/images/upload/image/20120711/20120711181409_66434.gif"/><br/>
图 3. 星座标识后的天体图</span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;"><b><span style="font-size:medium;">Constraints</span></b><br/>
0 &lt;= W (天体图的宽度) &lt;= 100<br/>
0 &lt;= H (天体图的深度) &lt;= 100<br/>
0 &lt;= 星座的数目 &lt;= 500<br/>
0 &lt;= 不相似的星座数目 &lt;= 26 (a..z)<br/>
1 &lt;= 各星座包含的星体数目 &lt;= 160 <br/>
</span> 
</p>
<p>
 
</p>
