
# Description

<div class="content"><div style="margin: 7.5pt 0cm; line-height: 15pt">
<div>背景</div>
<div>花神是神，一大癖好就是嘲讽大J，举例如下：</div>
<div>“哎你傻不傻的！【hqz：大笨J】”</div>
<div>“这道题又被J屎过了！！”</div>
<div>“J这程序怎么跑这么快！J要逆袭了！”</div>
<div>……</div>
<div>描述</div>
<div>这一天DJ在给吾等众蒟蒻讲题，花神在一边做题无聊，就跑到了一边跟吾等众蒟蒻一起听。以下是部分摘录：</div>
<div>1.</div>
<div>“J你在讲什么！”</div>
<div>“我在讲XXX！”</div>
<div>“哎你傻不傻的！这么麻烦，直接XXX再XXX就好了！”</div>
<div>“……”</div>
<div>2.</div>
<div>“J你XXX讲过了没？”</div>
<div>“……”</div>
<div>“那个都不讲你就讲这个了？哎你傻不傻的！”</div>
<div>“……”</div>
<div>DJ对这种情景表示非常无语，每每出现这种情况，DJ都是非常尴尬的。</div>
<div>经过众蒟蒻研究，DJ在讲课之前会有一个长度为N方案，我们可以把它看作一个数列；</div>
<div>同样，花神在听课之前也会有一个嘲讽方案，有M个，每次会在x到y的这段时间开始嘲讽，为了减少题目难度，每次嘲讽方案的长度是一定的，为K。</div>
<div>花神嘲讽DJ让DJ尴尬需要的条件：</div>
<div>在x~y的时间内DJ没有讲到花神的嘲讽方案，即J的讲课方案中的x~y没有花神的嘲讽方案【这样花神会嘲讽J不会所以不讲】。</div>
<div>经过众蒟蒻努力，在一次讲课之前得到了花神嘲讽的各次方案，DJ得知了这个消息以后欣喜不已，DJ想知道花神的每次嘲讽是否会让DJ尴尬【说不出话来】。</div>
<div></div>
</div></div>

# Input

<div class="content"><div style="margin: 0cm 0cm 7.5pt; line-height: 15pt">
<div>第1行3个数N，M，K；</div>
<div>第2行N个数，意义如上；</div>
<div>第3行到第3+M-1行，每行K+2个数，前两个数为x,y,然后K个数，意义如上；</div>
</div></div>

# Output

<div class="content"><div style="margin: 7.5pt 0cm; line-height: 15pt"><span style="font-size: medium"><span style="color: #333333">对于每一个嘲讽做出一个回答会尴尬输出‘Yes’，否则输出‘No’</span></span></div></div>

# Sample Input

<div class="content"><span class="sampledata">8 5 3<br/>
1 2 3 4 5 6 7 8<br/>
2 5 2 3 4<br/>
1 8 3 2 1<br/>
5 7 4 5 6<br/>
2 5 1 2 3<br/>
1 7 3 4 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">No<br/>
Yes<br/>
Yes<br/>
Yes<br/>
No<br/>
</span></div>

# Hint

<div class="content"><p></p><div>题中所有数据不超过2*10^9;保证方案序列的每个数字&lt;=N</div><br/>
<div>2~5中有2 3 4的方案，输出No，表示DJ不会尴尬</div><br/>
<div>1~8中没有3 2 1的方案，输出Yes，表示DJ会尴尬</div><br/>
<div>5~7中没有4 5 6的方案，输出Yes，表示DJ会尴尬</div><br/>
<div>2~5中没有1 2 3的方案，输出Yes，表示DJ会尴尬</div><br/>
<div>1~7中有3 4 5的方案，输出No，表示DJ不会尴尬</div><br/>
<div>//2018.7.6新加数据一组.未重测.</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=原创 Memphis
">原创 Memphis<br/>
</a></p></div>

