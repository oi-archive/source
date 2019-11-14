
# Description

<div class="content"><div>曾经发明了自动刷题机的发明家SHTSC又公开了他的新发明：脑洞治疗仪--一种可以治疗他因为发明而日益增大的脑洞的神秘装置。</div>
<div>为了简单起见，我们将大脑视作一个01序列。1代表这个位置的脑组织正常工作，0代表这是一块脑洞。</div>
<div>1<span class="Apple-tab-span" style="white-space:pre">	</span>0<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">	</span>0<span class="Apple-tab-span" style="white-space:pre">	</span>0<span class="Apple-tab-span" style="white-space:pre">	</span>0<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">	</span>0</div>
<div>脑洞治疗仪修补某一块脑洞的基本工作原理就是将另一块连续区域挖出，将其中正常工作的脑组织填补在这块脑洞中。</div>
<div>（所以脑洞治疗仪是脑洞的治疗仪？）</div>
<div>例如，用上面第8号位置到第10号位置去修补第1号位置到第4号位置的脑洞。我们就会得到：</div>
<div>1<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">	</span>0<span class="Apple-tab-span" style="white-space:pre">	</span>0<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">	</span>0<span class="Apple-tab-span" style="white-space:pre">	</span>0<span class="Apple-tab-span" style="white-space:pre">	</span>0</div>
<div>如果再用第1号位置到第4号位置去修补第8号位置到第10号位置：</div>
<div>0<span class="Apple-tab-span" style="white-space:pre">	</span>0<span class="Apple-tab-span" style="white-space:pre">	</span>0<span class="Apple-tab-span" style="white-space:pre">	</span>0<span class="Apple-tab-span" style="white-space:pre">	</span>0<span class="Apple-tab-span" style="white-space:pre">	</span>0<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">	</span>1</div>
<div>这是因为脑洞治疗仪会把多余出来的脑组织直接扔掉。</div>
<div>如果再用第7号位置到第10号位置去填补第1号位置到第6号位置：</div>
<div>1<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">	</span>1<span class="Apple-tab-span" style="white-space:pre">	</span>0<span class="Apple-tab-span" style="white-space:pre">	</span>0<span class="Apple-tab-span" style="white-space:pre">	</span>0<span class="Apple-tab-span" style="white-space:pre">	</span>0<span class="Apple-tab-span" style="white-space:pre">	</span>0<span class="Apple-tab-span" style="white-space:pre">	</span>0</div>
<div>这是因为如果新脑洞挖出来的脑组织不够多，脑洞治疗仪仅会尽量填补位置比较靠前的脑洞。</div>
<div>假定初始时SHTSC并没有脑洞，给出一些挖脑洞和脑洞治疗的操作序列，你需要即时回答SHTSC的问题：</div>
<div>在大脑某个区间中最大的连续脑洞区域有多大。</div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行两个整数n，m。表示SHTSC的大脑可分为从1到n编号的n个连续区域。有m个操作。</div>
<div>以下m行每行是下列三种格式之一。</div>
<div>0 l r ：SHTSC挖了一个从l到r的脑洞。</div>
<div>1 l0 r0 l1 r2 ：SHTSC进行了一次脑洞治疗，用从l0到r0的脑组织修补l1到r1的脑洞。</div>
<div>2 l r ：SHTSC询问l到r这段区间最大的脑洞有多大。</div>
<div>n,m &lt;=200000，1&lt;=l&lt;=r&lt;=n</div>
</div>
<p></p></div>

# Output

<div class="content"><div>对于每个询问，输出一行一个整数，表示询问区间内最大连续脑洞区域有多大。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10 10<br/>
0 2 2<br/>
0 4 6<br/>
0 10 10<br/>
2 1 10<br/>
1 8 10 1 4<br/>
2 1 10<br/>
1 1 4 8 10<br/>
2 1 10<br/>
1 7 10 1 6<br/>
2 1 10<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
3<br/>
6<br/>
6<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

