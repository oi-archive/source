
# Description

<div class="content"><div style="background: white" align="left"><span style="font-size: medium"><span style="color: #200000">　《海猫鸣泣之时》</span><span style="color: #200000">EP8</span><span style="color: #200000">终于在今年暑假的末尾出了汉化，作为整个作品中高人气人物古户绘梨花，自然也是在剧中大活跃。在攻占黄金乡的战役中担任了指挥官一职，而整个战役过程也都被记录在了图书之都中，方便后来人的复盘。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　当时的战况如下，黄金乡可以看做是一个长方体空间，我们用</span><span style="color: #200000">(0,0,0)~(n-1,m-1,k-1)</span><span style="color: #200000">表示里面的每一个单位区域，绘梨花指挥了</span><span style="color: #200000">t</span><span style="color: #200000">艘不同等级的战舰依靠魔法突然出现在了黄金乡的</span><span style="color: #200000">t</span><span style="color: #200000">个不同的区域，之后从战舰上便源源不断的涌出山羊们。每一个单位时刻，山羊们会从自己所在的区域向四周</span><span style="color: #200000">6</span><span style="color: #200000">个方向扩展一个区域（如果那个相邻的区域已经被占领了，就不扩展），如果两队山羊在同一时刻想占领同一区域，那么等级高的山羊优先占领。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　没过多久，黄金乡就变成了一片山羊海，但是作为指挥官的绘梨花却因茫茫多的山羊而找不到战舰所在的位置了，于是她将问题交给了身边的你</span><span style="color: #200000">——</span><span style="color: #200000">山羊君，作为一个急于立下战功然后回故乡找山羊子的青年将领，你自然不会放弃这个机会，于是很快就找到了战舰所在的位置，你的这份功绩自然也会被记录到图书之都的文书之中。</span></span></div></div>

# Input

<div class="content"><div style="background: white" align="left"><span style="font-size: medium"><span style="color: #200000">　　第一行一个数</span><span style="color: #200000">test</span><span style="color: #200000">，表示数据组数，以下</span><span style="color: #200000">test</span><span style="color: #200000">部分。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　每部分第一行</span><span style="color: #200000">3</span><span style="color: #200000">个数</span><span style="color: #200000">n,m,k,</span><span style="color: #200000">以下</span><span style="color: #200000">n</span><span style="color: #200000">部分，每部分为</span><span style="color: #200000">m</span><span style="color: #200000">行</span><span style="color: #200000">k</span><span style="color: #200000">列的字符矩阵。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　第</span><span style="color: #200000">i</span><span style="color: #200000">部分表示区域</span><span style="color: #200000">(i,0,0)~(i,m-1,k-1)</span><span style="color: #200000">中的战况。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　不同等级的山羊我们用不同的小写英文字母表示，字典序越小的字母表示山羊等级越高。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　相邻部分之间用空行隔开。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　注意下面的样例输入输出中的</span><span style="color: #200000">&lt;</span><span style="color: #200000">空行</span><span style="color: #200000">&gt;</span><span style="color: #200000">表示该行没有任何内容。</span></span></div>
<div style="background: white" align="left"><span style="font-size: medium"><span style="color: #200000">　</span></span></div></div>

# Output

<div class="content"><p><font color="#200000"><font size="4">　输出<span style="color: #200000">test</span></font></font><span style="color: #200000"><font size="4">部分，每部分用空行隔开。</font></span><span style="color: #200000"><br/>
</span><font size="4"><span style="color: #200000">　　每部分有</span><span style="color: #200000">t</span><span style="color: #200000">行，</span><span style="color: #200000">t</span><span style="color: #200000">为该组数据中战舰的数目，每行格式为</span></font><span style="color: #200000"><br/>
</span><span style="color: #200000"><font size="4">　　</font></span><font size="4"><span style="color: #200000">ch x y z<br/>
</span><span style="color: #200000">　　表示编号为</span><span style="color: #200000">ch</span><span style="color: #200000">的战舰的位置为</span><span style="color: #200000">(x,y,z)</span><span style="color: #200000">。</span></font><span style="color: #200000"><br/>
</span><span style="color: #200000"><font size="4">　　战舰输出顺序无关，如果有多解，输出任意解即可。</font></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
1 2 2<br/>
dd<br/>
gg<br/>
&lt;空行&gt;<br/>
3 3 3<br/>
aaa<br/>
aaa<br/>
baa<br/>
&lt;空行&gt;<br/>
aaa<br/>
aaa<br/>
baa<br/>
&lt;空行&gt;<br/>
aaa<br/>
aaa<br/>
bcc<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">d 0 0 0<br/>
g 0 1 0<br/>
&lt;空行&gt; <br/>
a 1 1 1<br/>
b 1 2 0<br/>
c 2 2 1<br/>
数据规模和约定<br/>
　　测试点1~3： n=1,n*m*k&lt;=10<br/>
　　测试点4~6： n=1,n*m*k&lt;=100<br/>
　　测试点7~10： n=1,n*m*k&lt;=500<br/>
　　测试点11~20： n*m*k&lt;=1500<br/>
　　所有所有数据 test&lt;=10，t&lt;=26<br/>
　　时间限制：5秒<br/>
 </span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: large">请不要提交！</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2012国家集训队Round 1 day1">2012国家集训队Round 1 day1</a></p></div>

