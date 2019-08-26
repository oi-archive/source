
# Description

<div class="content"><div align="left"><span style="font-size: medium">在一个计算机网络中，连接两台计算机的电缆属于不同的公司。一项新的反垄断法规定，一家公司连接同一台计算机的电缆不能超过两条。为了避免资源浪费，另外一条法律规定，一家公司的电缆系统不能有冗余，即去掉任意一个电缆之后，至少一对之前连通的计算机要断开连接。由于这些公司不断的销售和购入电缆，要确定他们是否遵守这些规则十分的困难。你的任务是写一个程序完成这个任务</span></div></div>

# Input

<div class="content"><div align="left"><span style="font-size: medium">多组测试数据。第一行是4个整数N，M，C，T——计算机的数量1&lt;=N=8000，电缆的数量0&lt;=M&lt;=100000，公司的数量1&lt;=C&lt;=100，电缆销售/购入的数量0&lt;=T&lt;=100000。</span></div>
<div align="left"><span style="font-size: medium"> </span><span style="font-size: medium">接下来M行，每行三个整数Sj1,Sj2,Kj，代表这条电缆连接的两个服务器Sj1,Sj2以及电缆所属的公司Kj。初始状态是遵守规则的。</span></div>
<div align="left"><span style="font-size: medium"> </span><span style="font-size: medium">接下来行，每行3个整数Si1,Si2,Ki，表示公司购入了连接S1,S2的电缆。</span></div>
<div align="left"><span style="font-size: medium"> </span><span style="font-size: medium">4个0标志着测试文件的结束。</span></div></div>

# Output

<div class="content"><div align="left">
<div align="left" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23.3240013122559px;"><span style="font-size: medium;">对于每个测试数据，输出行：</span></div>
<div align="left" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23.3240013122559px; margin: 0cm 0cm 0pt 21pt; text-indent: -21pt;"><span style="font-size: medium;"><span style="font-stretch: normal; font-size: 7pt; line-height: normal; font-family: &#39;Times New Roman&#39;;">         </span>“No Such Cable.” 如果这对服务器之前没有被一对电缆相连</span></div>
<div align="left" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23.3240013122559px; margin: 0cm 0cm 0pt 21pt; text-indent: -21pt;"><span style="font-size: medium;"><span style="font-stretch: normal; font-size: 7pt; line-height: normal; font-family: &#39;Times New Roman&#39;;">         </span>“Already owned.” 如果这对电缆本来就属于这家公司</span></div>
<div align="left" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23.3240013122559px; margin: 0cm 0cm 0pt 21pt; text-indent: -21pt;"><span style="font-size: medium;"><span style="font-stretch: normal; font-size: 7pt; line-height: normal; font-family: &#39;Times New Roman&#39;;">         </span>“Forbidden: monopoly.” 如果公司Ki已经有2条电缆与S1或S2相连</span></div>
<div align="left" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23.3240013122559px; margin: 0cm 0cm 0pt 21pt; text-indent: -21pt;"><span style="font-size: medium;"><span style="font-stretch: normal; font-size: 7pt; line-height: normal; font-family: &#39;Times New Roman&#39;;">         </span>“Forbidden: redundant.” 如果公司Ki公司购入这条电缆后，会在其网络中形成环</span></div>
<div align="left" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23.3240013122559px; margin: 0cm 0cm 0pt 21pt; text-indent: -21pt;"><span style="font-size: medium;"><span style="font-stretch: normal; font-size: 7pt; line-height: normal; font-family: &#39;Times New Roman&#39;;">         </span>“Sold.” 操作成功</span></div>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 5 3 5<br/>
1 2 1<br/>
2 3 1<br/>
3 4 2<br/>
1 4 2<br/>
1 3 3<br/>
1 2 3<br/>
1 2 3<br/>
1 4 3<br/>
2 3 3<br/>
2 4 3<br/>
2 1 1 1<br/>
1 2 1<br/>
1 2 1<br/>
0 0 0 0<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Sold.<br/>
Already owned.<br/>
Forbidden: monopoly.<br/>
Forbidden: redundant.<br/>
No such cable.<br/>
 <br/>
Already owned.</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
        </p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

