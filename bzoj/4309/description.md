
# Description

<div class="content"><div>Maishroom有一个蘑菇，我们不妨称它为蘑菇1。蘑菇上有n个room，这些room按1..n编号，并组成了一棵树，其中room 1是根。由于Maishroom长期没有修剪，蘑菇1的每个room 里都长满了杂草。</div>
<div>众所周知Maishroom非常喜欢蘑菇，于是它对这个蘑菇进行了一系列操作，包括复制、合并、修剪和询问。这些操作的具体说明如下：</div>
<div>操作<span class="Apple-tab-span" style="white-space:pre">	</span>格式<span class="Apple-tab-span" style="white-space:pre">	</span>说明</div>
<div>复制<span class="Apple-tab-span" style="white-space:pre">	</span>1 u<span class="Apple-tab-span" style="white-space:pre">	</span>Maishroom复制了蘑菇u，新的蘑菇编号为cnt+1。</div>
<div>合并<span class="Apple-tab-span" style="white-space:pre">	</span>2 u v<span class="Apple-tab-span" style="white-space:pre">	</span>Maishroom将蘑菇v合并到了蘑菇u上。当然，如果某个旧蘑菇的某个room有杂草，新的蘑菇u的对应room中也会有杂草。合并完后蘑菇v不会消失。</div>
<div>修剪1<span class="Apple-tab-span" style="white-space:pre">	</span>3 u v<span class="Apple-tab-span" style="white-space:pre">	</span>Maishroom除去了蘑菇u上以room x为根的子树上的杂草。</div>
<div>修剪2<span class="Apple-tab-span" style="white-space:pre">	</span>4 u v<span class="Apple-tab-span" style="white-space:pre">	</span>Maishroom几乎除去了蘑菇u上所有的杂草，除了以room x为根的子树上的那些。</div>
<div>修剪3<span class="Apple-tab-span" style="white-space:pre">	</span>5 u x y<span class="Apple-tab-span" style="white-space:pre">	</span>Maishroom除去了蘑菇u上room x到room y 路径上的杂草。</div>
<div>修剪4<span class="Apple-tab-span" style="white-space:pre">	</span>6 u x y<span class="Apple-tab-span" style="white-space:pre">	</span>Maishroom几乎除去了蘑菇u上所有的杂草，除了room x到room y路径上的那些。</div>
<div>修剪5<span class="Apple-tab-span" style="white-space:pre">	</span>7 u l r<span class="Apple-tab-span" style="white-space:pre">	</span>Maishroom除去了蘑菇u上编号在L到r之间（包括L,R）的room中的杂草。</div>
<div>修剪6<span class="Apple-tab-span" style="white-space:pre">	</span>8 u l r<span class="Apple-tab-span" style="white-space:pre">	</span>Maishroom几乎除去了蘑菇u上所有的杂草，除了编号在L到r之间（包括L,r）的room 中的那些。</div>
<div>询问<span class="Apple-tab-span" style="white-space:pre">	</span>9 u w<span class="Apple-tab-span" style="white-space:pre">	</span>Maishroom想知道清除蘑菇u上所有杂草所需的时间。Maishroom有一种工具来清除蘑菇上的杂草，每使用一次Maishroom可以选定一个蘑菇上编号的极差不超过w的一些room并清除它们中的杂草，使用一次消耗一个单位的时间。</div>
<div>注：表中的cnt表示该操作进行之前Maishroom拥有的蘑菇数。</div>
<div>现在有一份Maishroom的操作记录，你的任务是回答Maishroom的每个询问。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行一个整数n，表示蘑菇上room的个数。</div>
<div>接下来n-1行，每行两个整数x,y，表示room x,y之间有一条边。</div>
<div>接下来一行一个整数q，表示Maishroom的操作次数。</div>
<div>接下来q行，每行表示Maishroom的一个操作。</div>
<p></p></div>

# Output

<div class="content"><div>对于每个询问输出一行表示该询问的答案。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 3<br/>
3 5<br/>
1 2<br/>
2 4<br/>
9<br/>
1 1<br/>
1 2<br/>
5 3 4 5<br/>
9 3 0<br/>
2 3 2<br/>
6 3 4 5<br/>
9 3 1<br/>
4 2 2<br/>
9 2 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
3<br/>
2<br/>
</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="text-align:justify;text-justify:inter-ideograph"><span lang="EN-US" style="font-size:10.5pt;line-height:115%;font-family:微软雅黑;&lt;br /&gt;
mso-bidi-font-family:微软雅黑">N&lt;=50000,Q&lt;=100000,W</span><span style="font-size:10.5pt;line-height:115%;font-family:微软雅黑;mso-bidi-font-family:&lt;br /&gt;
微软雅黑">在<span lang="EN-US">[0,200]</span>中随机<span lang="EN-US"><o:p></o:p></span></span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

