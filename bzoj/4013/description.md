
# Description

<div class="content"><div><span style="font-family: 宋体;">小</span><span lang="EN-US">D </span><span style="font-family: 宋体;">被邀请到实验室，做一个跟图片质量评价相关的主观实验。实验用到的图片集一共有</span><span lang="EN-US"> N </span><span style="font-family: 宋体;">张图片，编号为</span><span lang="EN-US"> 1 </span><span style="font-family: 宋体;">到</span><span lang="EN-US"> N</span><span style="font-family: 宋体;">。实验分若干轮进行，在每轮实验中，小</span><span lang="EN-US"> D</span><span style="font-family: 宋体;">会被要求观看某两张随机选取的图片，</span> <span style="font-family: 宋体;">然后小</span><span lang="EN-US">D </span><span style="font-family: 宋体;">需要根据他自己主观上的判断确定这两张图片谁好谁坏，或者这两张图片质量差不多。</span> <span style="font-family: 宋体;">用符号“</span><span lang="EN-US">&lt;</span><span style="font-family: 宋体;">”、“</span><span lang="EN-US">&gt;</span><span style="font-family: 宋体;">”和“</span><span lang="EN-US">=</span><span style="font-family: 宋体;">”表示图片</span><span lang="EN-US"> x</span><span style="font-family: 宋体;">和</span><span lang="EN-US">y</span><span style="font-family: 宋体;">（</span><span lang="EN-US">x</span><span style="font-family: 宋体;">、</span><span lang="EN-US">y</span><span style="font-family: 宋体;">为图片编号）之间的比较：如果上下文中</span><span lang="EN-US"> x </span><span style="font-family: 宋体;">和</span><span lang="EN-US"> y </span><span style="font-family: 宋体;">是图片编号，则</span><span lang="EN-US"> x&lt;y </span><span style="font-family: 宋体;">表示图片</span><span lang="EN-US"> x</span><span style="font-family: 宋体;">“质量优于”</span><span lang="EN-US">y</span><span style="font-family: 宋体;">，</span><span lang="EN-US">x&gt;y </span><span style="font-family: 宋体;">表示图片</span><span lang="EN-US"> x</span><span style="font-family: 宋体;">“质量差于”</span><span lang="EN-US">y</span><span style="font-family: 宋体;">，</span><span lang="EN-US">x=y</span><span style="font-family: 宋体;">表示图片</span><span lang="EN-US"> x</span><span style="font-family: 宋体;">和</span><span lang="EN-US"> y</span><span style="font-family: 宋体;">“质量相同”；也就是说，这种上下文中，“</span><span lang="EN-US">&lt;</span><span style="font-family: 宋体;">”、“</span><span lang="EN-US">&gt;</span><span style="font-family: 宋体;">”、“</span><span lang="EN-US">=</span><span style="font-family: 宋体;">”分别是质量优于、质量差于、质量相同的意思；在其他上下文中，这三个符号分别是小于、大于、等于的含义。图片质量比较的推理规则（在</span><span lang="EN-US"> x</span><span style="font-family: 宋体;">和</span><span lang="EN-US">y</span><span style="font-family: 宋体;">是图片编号的上下文中）：（</span><span lang="EN-US">1</span><span style="font-family: 宋体;">）</span><span lang="EN-US">x &lt; y</span><span style="font-family: 宋体;">等价于</span><span lang="EN-US"> y &gt; x</span><span style="font-family: 宋体;">。（</span><span lang="EN-US">2</span><span style="font-family: 宋体;">）若</span><span lang="EN-US"> x &lt; y </span><span style="font-family: 宋体;">且</span><span lang="EN-US">y = z</span><span style="font-family: 宋体;">，则</span><span lang="EN-US">x &lt; z</span><span style="font-family: 宋体;">。（</span><span lang="EN-US">3</span><span style="font-family: 宋体;">）若</span><span lang="EN-US">x &lt; y</span><span style="font-family: 宋体;">且</span><span lang="EN-US"> x = z</span><span style="font-family: 宋体;">，则</span><span lang="EN-US"> z &lt; y</span><span style="font-family: 宋体;">。（</span><span lang="EN-US">4</span><span style="font-family: 宋体;">）</span><span lang="EN-US">x=y</span><span style="font-family: 宋体;">等价于</span><span lang="EN-US"> y=x</span><span style="font-family: 宋体;">。（</span><span lang="EN-US">5</span><span style="font-family: 宋体;">）若</span><span lang="EN-US">x=y</span><span style="font-family: 宋体;">且</span><span lang="EN-US"> y=z</span><span style="font-family: 宋体;">，则</span><span lang="EN-US">x=z</span><span style="font-family: 宋体;">。</span> <span style="font-family: 宋体;">实验中，小</span><span lang="EN-US"> D </span><span style="font-family: 宋体;">需要对一些图片对</span><span lang="EN-US">(x, y)</span><span style="font-family: 宋体;">，给出</span><span lang="EN-US"> x &lt; y </span><span style="font-family: 宋体;">或</span><span lang="EN-US"> x = y </span><span style="font-family: 宋体;">或</span><span lang="EN-US"> x &gt; y </span><span style="font-family: 宋体;">的主观判断。小</span><span lang="EN-US">D </span><span style="font-family: 宋体;">在做完实验后，</span> <span style="font-family: 宋体;">忽然对这个基于局部比较的实验的一些全局性质产生了兴趣。在主观实验数据给定的情形下，定义这</span><span lang="EN-US"> N </span><span style="font-family: 宋体;">张图片的一个合法质量序列为形如“</span><span lang="EN-US">x1 R1 x2 R2 x3 R3 </span><span style="font-family: 宋体;">…</span><span lang="EN-US">xN-1 RN-1 xN</span><span style="font-family: 宋体;">”的串，也可看作是集合</span><span lang="EN-US">{ xi Ri xi+1|1&lt;=i&lt;=N-1}</span><span style="font-family: 宋体;">，其中</span><span lang="EN-US"> xi</span><span style="font-family: 宋体;">为图片编号，</span><span lang="EN-US">x1,x2,</span><span style="font-family: 宋体;">…</span><span lang="EN-US">,xN</span><span style="font-family: 宋体;">两两互不相同（即不存在重复编号），</span><span lang="EN-US">Ri</span><span style="font-family: 宋体;">为</span><span lang="EN-US">&lt;</span><span style="font-family: 宋体;">或</span><span lang="EN-US">=</span><span style="font-family: 宋体;">，“合法”是指这个图片质量序列与任何一对主观实验给出的判断不冲突。</span> <span style="font-family: 宋体;">例如：</span> <span style="font-family: 宋体;">质量序列</span><span lang="EN-US">3 &lt; 1 = 2 </span><span style="font-family: 宋体;">与主观判断“</span><span lang="EN-US">3 &gt; 1</span><span style="font-family: 宋体;">，</span><span lang="EN-US">3 = <st1:chmetcnv unitname="”" sourcevalue="2" hasspace="False" negative="False" numbertype="1" tcsc="0" w:st="on">2<span lang="EN-US" style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;"><span lang="EN-US">”</span></span></st1:chmetcnv><span lang="EN-US" style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">冲突（因为质量序列中</span> 3&lt;1 </span><span style="font-family: 宋体;">且</span><span lang="EN-US">1=2</span><span style="font-family: 宋体;">，从而</span><span lang="EN-US">3&lt;2</span><span style="font-family: 宋体;">，这与主观判断中的</span><span lang="EN-US"> 3=2 </span><span style="font-family: 宋体;">冲突；同时质量序列中的</span><span lang="EN-US"> 3&lt;1 </span><span style="font-family: 宋体;">与主观判断中的</span><span lang="EN-US"> 3&gt;1 </span><span style="font-family: 宋体;">冲突）</span> <span style="font-family: 宋体;">，但与主观判断“</span><span lang="EN-US">2 = 1</span><span style="font-family: 宋体;">，</span><span lang="EN-US">3 &lt; <st1:chmetcnv unitname="”" sourcevalue="2" hasspace="False" negative="False" numbertype="1" tcsc="0" w:st="on">2<span lang="EN-US" style="font-family:宋体;mso-ascii-font-family:
&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;"><span lang="EN-US">”</span></span></st1:chmetcnv>  </span><span style="font-family: 宋体;">不冲突；因此给定主观判断“</span><span lang="EN-US">3&gt;1</span><span style="font-family: 宋体;">，</span><span lang="EN-US">3=<st1:chmetcnv unitname="”" sourcevalue="2" hasspace="False" negative="False" numbertype="1" tcsc="0" w:st="on">2<span lang="EN-US" style="font-family:宋体;mso-ascii-font-family:
&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;"><span lang="EN-US">”</span></span></st1:chmetcnv><span lang="EN-US" style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">时，</span>1&lt;3=2 </span><span style="font-family: 宋体;">和</span><span lang="EN-US">1&lt;2=3 </span><span style="font-family: 宋体;">都是合法的质量序列，</span><span lang="EN-US">3&lt;1=2 </span><span style="font-family: 宋体;">和</span><span lang="EN-US">1&lt;2&lt;3</span><span style="font-family: 宋体;">都是非法的质量序列。由于实验已经做完一段时间了，小</span><span lang="EN-US">D </span><span style="font-family: 宋体;">已经忘了一部分主观实验的数据。对每张图片</span><span lang="EN-US"> i</span><span style="font-family: 宋体;">，小</span><span lang="EN-US"> D </span><span style="font-family: 宋体;">都最多只记住了某一张质量不比</span><span lang="EN-US"> i </span><span style="font-family: 宋体;">差的另一张图片</span><span lang="EN-US"> Ki</span><span style="font-family: 宋体;">。这些小</span><span lang="EN-US"> D </span><span style="font-family: 宋体;">仍然记得的质量判断一共有</span><span lang="EN-US"> M </span><span style="font-family: 宋体;">条（</span><span lang="EN-US">0 &lt;= M &lt;= N</span><span style="font-family: 宋体;">），其中第</span><span lang="EN-US">i </span><span style="font-family: 宋体;">条涉及的图片对为</span><span lang="EN-US">(KXi, Xi)</span><span style="font-family: 宋体;">，判断要么是</span><span lang="EN-US">KXi   &lt; Xi  </span><span style="font-family: 宋体;">，要么是</span><span lang="EN-US">KXi = Xi</span><span style="font-family: 宋体;">，而且所有的</span><span lang="EN-US">Xi</span><span style="font-family: 宋体;">互不相同。小</span><span lang="EN-US">D </span><span style="font-family: 宋体;">打算就以这</span><span lang="EN-US">M </span><span style="font-family: 宋体;">条自己还记得的质量判断作为他的所有主观数据。现在，基于这些主观数据，我们希望你帮小</span><span lang="EN-US"> D </span><span style="font-family: 宋体;">求出这</span><span lang="EN-US"> N </span><span style="font-family: 宋体;">张图片一共有多少个不同的合法质量序列。我们规定：</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">如果质量序列中出现“</span><span lang="EN-US">x = y</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">”，那么序列中交换</span><span lang="EN-US"> x</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;">和</span><span lang="EN-US">y</span><span style="font-family:
宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;">的位置后仍是同一个序列。</span><span lang="EN-US"><o:p></o:p></span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">因此：</span><span lang="EN-US"> 1&lt;2=3=4&lt;5 </span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">和</span><span lang="EN-US">1&lt;4=2=3&lt;5 </span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">是同一个序列，</span><span lang="EN-US"> 1 &lt; 2 = 3 </span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">和</span><span lang="EN-US"> 1 &lt; 3 = 2 </span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">是同一个序列，而</span><span lang="EN-US">1 &lt; 2 &lt; 3 </span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;
mso-hansi-font-family:&#34;Times New Roman&#34;">与</span><span lang="EN-US">1 &lt; 2 = 3</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;">是不同的序列，</span><span lang="EN-US">1&lt;2&lt;3</span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;">和</span><span lang="EN-US">2&lt;1&lt;3 </span><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;">是不同的序列。</span><span style="font-family: 宋体;">由于合法的图片质量序列可能很多，</span> <span style="font-family: 宋体;">所以你需要输出答案对</span><span lang="EN-US">10^9 + 7 </span><span style="font-family: 宋体;">取模的结果</span></div>
<div></div>
<div></div></div>

# Input

<div class="content"><div>第一行两个正整数N,M，分别代表图片总数和小D仍然记得的判断的条数；</div>
<div>接下来M行，每行一条判断，每条判断形如”x &lt; y”或者”x = y”。 </div></div>

# Output

<div class="content"><p> 输出仅一行，包含一个正整数，表示合法质量序列的数目对 10^9+7取模的结果。</p></div>

# Sample Input

<div class="content"><span class="sampledata">5 4 <br/>
1 &lt; 2 <br/>
1 &lt; 3 <br/>
2 &lt; 4 <br/>
1 = 5 </span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
</span></div>

# Hint

<div class="content"><p></p><p> 不同的合法序列共5个，如下所示： </p><br/>
<div>1 = 5 &lt; 2 &lt; 3 &lt; 4 </div><br/>
<div>1 = 5 &lt; 2 &lt; 4 &lt; 3 </div><br/>
<div>1 = 5 &lt; 2 &lt; 3 = 4 </div><br/>
<div>1 = 5 &lt; 3 &lt; 2 &lt; 4 </div><br/>
<div>1 = 5 &lt; 2 = 3 &lt; 4 </div><br/>
<div>100%的数据满足N&lt;=100。  </div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

