
# Description

<div class="content"><div>小强和阿米巴是好朋友。</div>
<div>阿米巴告诉小强，变形虫（又叫阿米巴虫）和绝大多数生物一样，也是有 DNA 的。并且，变形虫可以通过分裂的方式进行无性繁殖。</div>
<div>我们把一个变形虫的基因组抽象成一个大小为 L 的基因集合。每个基因都是一个 4 位长的字符串（字符包括大小写字母、数字、符号“~!@#$%^&amp;()[]`:;&#34;&#39;&lt;&gt;,.?/|\=-{}”）。现在，有 N 个变形虫凑到了一起。由于他们是从天南海北过来的，我们可以认为，他们的基因组都是从一个大小为 M 的“变形虫基因库“中独立的随机的选取L个基因得到的。目前人类并不了解这个基因库里都有什么基因，但是我们知道它的大小是 M。</div>
<div>这时，环境突然发生巨变。这 N 个变形虫在外界的刺激下同时进行了一次分裂。每个变形虫分裂成了两个。分裂的过程中，原来的变形虫的基因组（基因的集合）被原样的复制成了两份，分别进入两个新的变形虫。两个新变形虫中的一只的基因组中有一半发生了突变，被替换为“变形虫基因库”中随机的其他的基因。如果两个变形虫是由原来的一个变形虫产生的，我们叫它们“同源”的。</div>
<div>给出 2N 个变形虫的基因组，请你找出每个变形虫同源的另一只虫是谁。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行三个整数 N、M、L。</div>
<div>接下来一行 2NL×4个字符，依次表示每个集合中的元素。集合内的元素之间的顺序是无关紧要的。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出 2N 行，每行一个整数表示第 i 个变形虫（从 1 开始标号）同源的另一只变形虫是谁。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 100 6<br/>
H[P,86(^,<n&7x_sg"ly67m2h$n+5'!vhp5ia.@gm:4-njsqsig!h[p,7x_s86(^>aNQ22&#39;B5&#39;!V<fd!f!6xnjsq>!]dHp5I</fd!f!6xnjsq></n&7x_sg"ly67m2h$n+5'!vhp5ia.@gm:4-njsqsig!h[p,7x_s86(^></span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
4<br/>
1<br/>
2<br/>
<br/>
explanation<br/>
<br/>
输入文件一共有两行。四个基因组分别是<br/>
<br/>
“H[P,”，“86(^”，“,<n&”，“7x_s”，“g"ly”， “67m2”<br="">
<br/>
“H$n+”，“5&#39;!V”，“Hp5I”，“A.@G”，“M:4-”，“NJsq”<br/>
<br/>
“siG!”，“H[P,”，“7X_S”，“86(^”，“&gt;aNQ”，“22&#39;B”<br/>
<br/>
“5&#39;!V”，“<fd!”，“f!6x”，“njsq”，“>!]d”，“Hp5I”<br/>
<br/>
明显，1、3是同源的，2、4是同源的。<br/>
<br/>
</fd!”，“f!6x”，“njsq”，“></n&”，“7x_s”，“g"ly”，></span></div>

# Hint

<div class="content"><p></p><div>一共有 10 个测试点。数据均为按照题目中描述的方法随机生成的。对于非同源的两个变形虫，他们的基因组的交的大小均小于 L/2。对于同源的两个变形虫，他们的基因组的交的大小刚好是 L/2</div><br/>
<div>最大的一个测试数据的大小是 17MB 左右（2NL×4=17576000）。在测评系统上，由于磁盘缓存的存在，使用 scanf 将数据读入需要的时间小于 0.1 秒。请不要使用 cin。</div><br/>
<div>N&lt;=16900,M&lt;=16900,L&lt;=130</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2015年国家集训队测试">2015年国家集训队测试</a></p></div>

