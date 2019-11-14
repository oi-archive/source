
# Description

<div class="content"><div>Hzwer成功培育出神牛细胞，可最终培育出的生物体却让他大失所望......</div>
<div></div>
<div>后来，他从某同校女神 牛处知道，原来他培育的细胞发生了基因突变，原先决定神牛特征的基因序列都被破坏了，神牛hzwer很生气，但他知道基因突变的低频性，说不定还有以下优秀基因没有突变，那么他就可以用限制性核酸内切酶把它们切出来，然后再构建基因表达载体什么的，后面你懂的......</div>
<div></div>
<div>黄学长现在知道了N个细胞的DNA序列，它们是若干个由小写字母组成的字符串。一个优秀的基因是两个字符串s1和s2,当且仅当s1是某序列的前缀的同时，s2是这个序列的后缀时，hzwer认为这个序列拥有这个优秀基因。</div>
<div></div>
<div>现在黄学长知道了M个优秀基因s1和s2，它们想知道对于给定的优秀基因，有多少个细胞的DNA序列拥有它。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行：N，表示序列数</div>
<div>
<div>接下来N行，每行一个字符串，代表N个DNA序列，它们的总长为L1</div>
<div>接下来一个M，表示询问数</div>
<div>接下来M行，每行两个字符串s1和s2，由一个空格隔开，hzwer希望你能在线回答询问，所以s1等于“s1”的所有字符按字母表的顺序向后移动ans位（字母表是一个环），ans为上一个询问的答案，s2同理。例如ans=2  “s1”=qz</div>
<div>则s1=sb。对于第一个询问，ans=0</div>
<div>s1和s2的总长度为L2</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>输出M行，每行一个数，第i行的数表示有多少个序列拥有第i个优秀基因。</div>
<div>
<p></p>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
emikuqihgokuhsywlmqemihhpgijkxdukjfmlqlwrpzgwrwozkmlixyxniutssasrriafu<br/>
emikuqihgokuookbqaaoyiorpfdetaeduogebnolonaoehthfaypbeiutssasrriafu<br/>
emikuqihgokuorocifwwymkcyqevdtglszfzgycbgnpomvlzppwrigowekufjwiiaxniutssasrriafu<br/>
emikuqihgokuorociysgfkzpgnotajcfjctjqgjeeiheqrepbpakmlixyxniutssasrriafu<br/>
emikuqihgokuorociysgfrhulymdxsqirjrfbngwszuyibuixyxniutssasrriafu<br/>
emikuqihgokuorguowwiozcgjetmyokqdrqxzigohiutssasrriafu<br/>
emikuqihgokuorociysgsczejjmlbwhandxqwknutzgdmxtiutssasrriafu<br/>
emikuqihgokuorociysgvzfcdxdiwdztolopdnboxfvqzfzxtpecxcbrklvtyxniutssasrriafu<br/>
emikuqihgokuorocsbtlyuosppxuzkjafbhsayenxsdmkmlixyxniutssasrriafu<br/>
emikuqihgokuorociysgfjvaikktsixmhaasbvnsvmkntgmoygfxypktjxjdkliixyxniutssasrriafu<br/>
10<br/>
emikuqihgokuorociysg yxniutssasrriafu<br/>
aiegqmedckgqknky eqpoowonnewbq<br/>
xfbdnjbazhdnhkhvb qrqgbnmlltlkkbtyn<br/>
bjfhrnfedlhrlolzfv qppxpoofxcr<br/>
zhdfpldcbjf stsidponnvnmmdvap<br/>
zhdfpldcbjfpjmjxdt gdstsidponnvnmmdvap<br/>
dlhjtphgfnjtnqnbhxr wxwmhtsrrzrqqhzet<br/>
bjfhrnfedlhrlolzfv frqppxpoofxcr<br/>
zhdfpldcbjf dponnvnmmdvap<br/>
ucyakgyxweakehes nondykjiiqihhyqvk<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
7<br/>
3<br/>
5<br/>
5<br/>
1<br/>
3<br/>
5<br/>
10<br/>
4<br/>
</span></div>

# Hint

<div class="content"><p></p><div>N&lt;=2000</div><br/>
<div>L1&lt;=2000000</div><br/>
<div>M&lt;=100000</div><br/>
<div>L2&lt;=2000000</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

